Most popular PCI devices in Tablets
===================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Tablets ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Digitizer pen ](#digitizer-pen-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Iommu ](#iommu-pci)
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
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Unclassified device ](#unclassified-device-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d18 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 113   | pcieport   | 0E1D0B8D70 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 111   | lpc_ich    | 3317BA664D |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 99    | iosf_mb... | 3317BA664D |
| 8086:9d14 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 74    | pcieport   | 0E1D0B8D70 |
| 8086:1904 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 59    | skl_uncore | 0E1D0B8D70 |
| 8086:9d48 | 8086:7270 | Intel      | Sunrise Point-LP LPC Cont... | 59    |            | 0E1D0B8D70 |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 50    | pcieport   | 85D49B081C |
| 8086:0a04 | 1414:0a04 | Intel      | Haswell-ULT DRAM Controller  | 45    | hsw_uncore | BA2B6488C2 |
| 8086:9c43 | 1414:9c43 | Intel      | 8 Series LPC Controller      | 45    | lpc_ich    | BA2B6488C2 |
| 8086:9d4e | 8086:7270 | Intel      | Sunrise Point LPC Control... | 42    |            | 7A294509DE |
| 8086:9c14 | 1414:9c14 | Intel      | 8 Series PCI Express Root... | 32    | pcieport   | AC7F0D85A6 |
| 8086:2280 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 31    | iosf_mb... | F21B55E1F7 |
| 8086:229c | 17aa:380d | Intel      | Atom/Celeron/Pentium Proc... | 31    | lpc_ich    | F21B55E1F7 |
| 8086:2280 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 29    | iosf_mb... | 4AC35C901A |
| 8086:229c | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 29    | lpc_ich    | 4AC35C901A |
| 8086:9d13 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 27    | pcieport   | 7A294509DE |
| 8086:9d1b | 8086:7270 | Intel      | Skylake-U/Y PCIe Port #12    | 24    | pcieport   | 0E1D0B8D70 |
| 8086:0f1c | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 23    | lpc_ich    | 9B7A2A3D3B |
| 8086:5914 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 23    | skl_uncore | 8C4E9C3488 |
| 8086:5904 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 21    | skl_uncore | 7A294509DE |
| 8086:2280 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | iosf_mb... | E5A8BA60CF |
| 8086:2280 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | iosf_mb... | 83AE87648C |
| 8086:229c | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | lpc_ich    | E5A8BA60CF |
| 8086:229c | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | lpc_ich    | 83AE87648C |
| 8086:22c8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | pcieport   | 83AE87648C |
| 8086:22c8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 16    | pcieport   | E5A8BA60CF |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 14    |            | 1785E9C758 |
| 8086:3482 | 8086:7270 | Intel      | Ice Lake-LP LPC Controller   | 14    |            | D34ECF1B95 |
| 8086:34b0 | 8086:7270 | Intel      | Ice Lake-LP PCI Express R... | 14    | pcieport   | D34ECF1B95 |
| 1002:439d | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 13    |            | 560E2E570B |
| 1022:1510 | 1022:1510 | AMD        | Family 14h Processor Root... | 13    |            | 560E2E570B |
| 1022:1700 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1701 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1702 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1703 |           | AMD        | Family 12h/14h Processor ... | 13    | k10temp    | 560E2E570B |
| 1022:1704 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1716 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1718 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 1022:1719 |           | AMD        | Family 12h/14h Processor ... | 13    |            | 560E2E570B |
| 8086:8a12 | 8086:7270 | Intel      | Ice Lake-LP Processor Hos... | 13    | icl_uncore | D34ECF1B95 |
| 8086:2280 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | iosf_mb... | 0542145A63 |
| 8086:229c | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | lpc_ich    | 0542145A63 |
| 8086:22c8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | pcieport   | 0542145A63 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    |            | 902AD35DB3 |
| 8086:0f00 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 11    | iosf_mb... | 314AA4D200 |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 11    | pcieport   | 902AD35DB3 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | lpc_ich    | 902AD35DB3 |
| 8086:9d10 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 11    | pcieport   | 14A3F2D111 |
| 8086:9d16 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 11    | pcieport   | DBD06D839B |
| 1022:1513 | 1022:1234 | AMD        | Family 14h Processor Root... | 10    | shpchp     | 560E2E570B |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    |            | 1A6758A371 |
| 8086:31f0 | 8086:7270 | Intel      | Gemini Lake Host Bridge      | 10    |            | 1A6758A371 |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 9     | pcieport   | 1A8EF422E7 |
| 8086:31d9 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 9     | pcieport   | 1A8EF422E7 |
| 8086:31da | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 9     | pcieport   | 1A8EF422E7 |
| 8086:590c | 152d:1182 | Intel      | Xeon E3-1200 v6/7th Gen C... | 9     | skl_uncore | 3EB69E8095 |
| 8086:9d12 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 9     | pcieport   | 3EB69E8095 |
| 8086:9d13 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 9     | pcieport   | 3EB69E8095 |
| 8086:9d18 | 8086:9d18 | Intel      | Sunrise Point-LP PCI Expr... | 9     | pcieport   | 5FE3179524 |
| 8086:9d4b | 152d:1182 | Intel      | Skylake-U/Y LPC/eSPI Cont... | 9     |            | 3EB69E8095 |
| 8086:2280 | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 8     | iosf_mb... | 85D49B081C |
| 8086:0f00 | 17aa:221b | Intel      | Atom Processor Z36xxx/Z37... | 7     | iosf_mb... | 9B7A2A3D3B |
| 8086:5904 | 103c:82ca | Intel      | Xeon E3-1200 v6/7th Gen C... | 7     | skl_uncore | D6AB5352B8 |
| 8086:590c | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 7     | skl_uncore | DBD940A4F3 |
| 8086:9d10 | 103c:82ca | Intel      | Sunrise Point-LP PCI Expr... | 7     | pcieport   | D6AB5352B8 |
| 8086:9d14 | 103c:82ca | Intel      | Sunrise Point-LP PCI Expr... | 7     | pcieport   | D6AB5352B8 |
| 8086:9d15 | 103c:82ca | Intel      | Sunrise Point-LP PCI Expr... | 7     | pcieport   | D6AB5352B8 |
| 8086:9d16 | 152d:1182 | Intel      | Sunrise Point-LP PCI Expr... | 7     | pcieport   | FD20A2C976 |
| 8086:9d18 | 103c:82ca | Intel      | Sunrise Point-LP PCI Expr... | 7     | pcieport   | D6AB5352B8 |
| 8086:9d4b | 8086:7270 | Intel      | Skylake-U/Y LPC/eSPI Cont... | 7     |            | DBD940A4F3 |
| 8086:9d4e | 103c:82ca | Intel      | Sunrise Point LPC Control... | 7     |            | D6AB5352B8 |
| 8086:0f00 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 6     | iosf_mb... | 2C99AF7703 |
| 8086:0f00 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 6     | iosf_mb... | BE55ABE40D |
| 8086:0f00 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 6     | iosf_mb... | 92D4603EA8 |
| 8086:0f1c | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 6     | lpc_ich    | 2C99AF7703 |
| 8086:0f1c | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 6     | lpc_ich    | BE55ABE40D |
| 8086:0f1c | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 6     | lpc_ich    | 92D4603EA8 |
| 8086:0154 | 1414:0154 | Intel      | 3rd Gen Core processor DR... | 5     | ivb_uncore | 4E005ED117 |
| 8086:0f00 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 5     | iosf_mb... | 2548D4154B |
| 8086:0f00 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 5     | iosf_mb... | 36E2AE6F17 |
| 8086:0f1c | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 5     | lpc_ich    | 2548D4154B |
| 8086:0f1c | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 5     | lpc_ich    | 36E2AE6F17 |
| 8086:0f48 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 5     | pcieport   | 2548D4154B |
| 8086:0f48 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 5     | pcieport   | 36E2AE6F17 |
| 8086:0f4a | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 5     | pcieport   | 36E2AE6F17 |
| 8086:15d3 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 Bri... | 5     | pcieport   | 234767F4BA |
| 8086:1e57 | 1414:1e57 | Intel      | HM77 Express Chipset LPC ... | 5     | lpc_ich    | 4E005ED117 |
| 8086:2280 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | iosf_mb... | 1C188B150F |
| 8086:229c | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | lpc_ich    | 1C188B150F |
| 8086:22c8 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | pcieport   | 1C188B150F |
| 8086:31d8 | 17aa:380c | Intel      | Gemini Lake PCI Express R... | 5     | pcieport   | 9118598BC9 |
| 8086:31da | 17aa:3811 | Intel      | Gemini Lake PCI Express R... | 5     | pcieport   | 9118598BC9 |
| 8086:31e8 | 17aa:3820 | Intel      | Celeron/Pentium Silver Pr... | 5     |            | 9118598BC9 |
| 8086:31f0 | 17aa:3806 | Intel      | Gemini Lake Host Bridge      | 5     |            | 9118598BC9 |
| 8086:5904 | 1028:07a4 | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | 45B102BEAF |
| 8086:5904 | 144d:c14f | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | C9D869A6A8 |
| 8086:590c | 103c:828b | Intel      | Xeon E3-1200 v6/7th Gen C... | 5     | skl_uncore | 3196DC7C2A |
| 8086:9d10 | 103c:828b | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 3196DC7C2A |
| 8086:9d11 | 103c:828b | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | 3196DC7C2A |
| 8086:9d12 | 144d:c14f | Intel      | Sunrise Point-LP PCI Expr... | 5     | pcieport   | C9D869A6A8 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:522a | 152d:1182 | Realtek... | RTS522A PCI Express Card ... | 9     | rtsx_pci   | 3EB69E8095 |
| 10ec:522a | 103c:82ca | Realtek... | RTS522A PCI Express Card ... | 7     | rtsx_pci   | D6AB5352B8 |
| 10ec:5229 | 17aa:3833 | Realtek... | RTS5229 PCI Express Card ... | 5     | rtsx_pci   | 9118598BC9 |
| 10ec:522a | 103c:828b | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx_pci   | 3196DC7C2A |
| 10ec:525a | 1028:07a4 | Realtek... | RTS525A PCI Express Card ... | 5     | rtsx_pci   | 45B102BEAF |
| 10ec:522a | 152d:1237 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 2618117BB7 |
| 10ec:522a | 17aa:2244 | Realtek... | RTS522A PCI Express Card ... | 4     | rtsx_pci   | 234767F4BA |
| 10ec:525a | 1028:06e6 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 36CE9AD0C9 |
| 10ec:525a | 1028:081d | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx_pci   | 1ABEA9314A |
| 10ec:5229 | 10ec:5229 | Realtek... | RTS5229 PCI Express Card ... | 3     | rtsx_pci   | 8484A178B3 |
| 10ec:522a | 17aa:2241 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx_pci   | 1C271464F4 |
| 10ec:525a | 1028:06d6 | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx_pci   | 7A9C92F242 |
| 10ec:5229 | 17aa:382e | Realtek... | RTS5229 PCI Express Card ... | 2     | rtsx_pci   | 1DD80D33E5 |
| 10ec:522a | 103c:82cb | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx_pci   | 009ABCD381 |
| 10ec:522a | 103c:824c | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | A557059CBA |
| 10ec:522a | 17aa:2243 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | AA3F633BF5 |
| 10ec:522a | 17aa:3823 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx_pci   | FD98FD839E |
| 10ec:525a | 1028:0702 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx_pci   | 229409A8DC |
| 10ec:5286 | 1558:5470 | Realtek... | RTL8402 Integrated 1-LUN ... | 1     | rtsx_pci   | DD65C5ABF7 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:11a0 |           | Intel      | Merrifield SCU IPC           | 1     | intel_s... | D1F5E15D8C |
| 8086:11a1 |           | Intel      | Merrifield Power Manageme... | 1     | intel_p... | D1F5E15D8C |
| 8086:11a3 |           | Intel      | Co-processor                 | 1     | intel_p... | D1F5E15D8C |
| 8086:11a4 |           | Intel      | Co-processor                 | 1     | intel_mcu  | D1F5E15D8C |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 112   | mei_me     | 0E1D0B8D70 |
| 8086:9d3e |           | Intel      | Skylake-U/Y CSME: HECI #3    | 112   | mei_me     | 0E1D0B8D70 |
| 8086:9c3a | 1414:9c3a | Intel      | 8 Series HECI #0             | 32    | mei_me     | AC7F0D85A6 |
| 8086:34a8 | 8086:7270 | Intel      | Ice Lake-LP Serial IO UAR... | 14    | intel_l... | D34ECF1B95 |
| 8086:34e0 | 8086:7270 | Intel      | Ice Lake-LP Management En... | 14    | mei_me     | D34ECF1B95 |
| 8086:9c3a | 8086:9c3a | Intel      | 8 Series HECI #0             | 13    | mei_me     | BA2B6488C2 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | mei_me     | 902AD35DB3 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | mei_me     | 1A6758A371 |
| 8086:34e4 | 1414:0039 | Intel      | Communication controller     | 9     | mei_me     | 4265905516 |
| 8086:9d3a | 152d:1182 | Intel      | Sunrise Point-LP CSME HEC... | 9     | mei_me     | 3EB69E8095 |
| 8086:9d3a | 103c:82ca | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | D6AB5352B8 |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 6     | mei_me     | 5FE3179524 |
| 8086:1e3a | 1414:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 5     | mei_me     | 4E005ED117 |
| 8086:319a | 17aa:3824 | Intel      | Celeron/Pentium Silver Pr... | 5     | mei_me     | 9118598BC9 |
| 8086:9d3a | 1028:07a4 | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | 45B102BEAF |
| 8086:9d3a | 144d:c14f | Intel      | Sunrise Point-LP CSME HEC... | 5     | mei_me     | C9D869A6A8 |
| 8086:9d3a | 1028:06e6 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 36CE9AD0C9 |
| 8086:9d3a | 1028:081d | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 1ABEA9314A |
| 8086:9d3a | 103c:828b | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 3196DC7C2A |
| 8086:9d3a | 144d:c135 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 4E4EF907A0 |
| 8086:9d3a | 152d:1237 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 2618117BB7 |
| 8086:9d3a | 17aa:2244 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | 234767F4BA |
| 8086:9d3a | 17aa:3850 | Intel      | Sunrise Point-LP CSME HEC... | 4     | mei_me     | F78D607B1F |
| 8086:9cba | 17aa:222b | Intel      | Wildcat Point-LP MEI Cont... | 3     | mei_me     | 5BADA8B921 |
| 8086:9d3a | 1025:111e | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 1A171E7553 |
| 8086:9d3a | 1028:06d6 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 7A9C92F242 |
| 8086:9d3a | 1028:07a5 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 0325FE3F75 |
| 8086:9d3a | 17aa:2241 | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | 1C271464F4 |
| 8086:9d3a | 17aa:382b | Intel      | Sunrise Point-LP CSME HEC... | 3     | mei_me     | F590550713 |
| 8086:34e4 | 1414:0041 | Intel      | Communication controller     | 2     |            | 79D77CFE11 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 2     | mei_me     | 6CBD38B3E5 |
| 8086:9d3a | 1025:1171 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 4B0ED624FA |
| 8086:9d3a | 103c:82cb | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 009ABCD381 |
| 8086:9d3a | 1043:13c0 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | 4363CA1BD6 |
| 8086:9d3a | 1043:1410 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | C66E4999F0 |
| 8086:9d3a | 1043:16c0 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | D33E67BDF4 |
| 8086:9d3a | 19e5:3e00 | Intel      | Sunrise Point-LP CSME HEC... | 2     | mei_me     | D4C3DCBC61 |
| 8086:9d3e | 103c:82cb | Intel      | Skylake-U/Y CSME: HECI #3    | 2     | mei_me     | 009ABCD381 |
| 8086:02e0 | 17aa:3811 | Intel      | Comet Lake Management Eng... | 1     | mei_me     | 6F0E0FCC43 |
| 8086:1195 |           | Intel      | Merrifield Serial IO I2C ... | 1     | i2c_des... | D1F5E15D8C |
| 8086:1196 |           | Intel      | Merrifield Serial IO I2C ... | 1     | i2c_des... | D1F5E15D8C |
| 8086:1197 |           | Intel      | Communication controller     | 1     |            | D1F5E15D8C |
| 8086:1a9a |           | Intel      | ME OEM Extension             | 1     | mei_me     | 555A26F0D1 |
| 8086:1c3a | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | mei_me     | 95C27C9FC7 |
| 8086:1e3a | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 68ECFC5409 |
| 8086:1e3a | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | mei_me     | 5A97B2A1A7 |
| 8086:319a | 17aa:381f | Intel      | Celeron/Pentium Silver Pr... | 1     | mei_me     | FD98FD839E |
| 8086:34e4 | 1414:0040 | Intel      | Communication controller     | 1     | mei_me     | BAA04FAF58 |
| 8086:5a9a | 8086:5a9a | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | D461E042A0 |
| 8086:9d3a | 1028:0702 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 229409A8DC |
| 8086:9d3a | 103c:824c | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | A557059CBA |
| 8086:9d3a | 103c:8414 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 4937A2C0A8 |
| 8086:9d3a | 17aa:2243 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | AA3F633BF5 |
| 8086:9d3a | 17aa:3834 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | 14DC838F85 |
| 8086:9d3a | 1b0a:01d3 | Intel      | Sunrise Point-LP CSME HEC... | 1     | mei_me     | C2D333A420 |
| 8086:9de0 | 1028:0895 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | FF9B284809 |
| 8086:9de0 | 103c:85b9 | Intel      | Cannon Point-LP MEI Contr... | 1     | mei_me     | 11BBC16301 |
| 8086:a0a8 | 8086:7270 | Intel      | Tiger Lake-LP Serial IO U... | 1     | intel_lpss | A4AEFCD9B2 |
| 8086:a0e0 | 17aa:508b | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | AAC22AF3A1 |
| 8086:a0e0 | 8086:7270 | Intel      | Tiger Lake-LP Management ... | 1     | mei_me     | A4AEFCD9B2 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 1     | mei_me     | 9C72670AA1 |

### Digitizer pen (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a0d0 | 1414:0056 | Intel      | Digitizer Pen                | 1     |            | A4AEFCD9B2 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 111   | mei_txe    | 3317BA664D |
| 8086:2298 | 17aa:380c | Intel      | Atom/Celeron/Pentium Proc... | 31    | mei_txe    | F21B55E1F7 |
| 8086:2298 | 17aa:380a | Intel      | Atom/Celeron/Pentium Proc... | 29    | mei_txe    | 4AC35C901A |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 22    | mei_txe    | 9B7A2A3D3B |
| 8086:2298 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | mei_txe    | E5A8BA60CF |
| 8086:2298 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | mei_txe    | 83AE87648C |
| 8086:2298 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | mei_txe    | 0542145A63 |
| 8086:0f18 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 2C99AF7703 |
| 8086:0f18 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | BE55ABE40D |
| 8086:0f18 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 6     | mei_txe    | 92D4603EA8 |
| 8086:0f18 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 2548D4154B |
| 8086:0f18 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 5     | mei_txe    | 36E2AE6F17 |
| 8086:2298 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | mei_txe    | 1C188B150F |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 4     | mei_txe    | 3B331BB4AF |
| 8086:2298 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 4     | mei_txe    | A8198C3153 |
| 8086:0f18 | 103c:8031 | Intel      | Atom Processor Z36xxx/Z37... | 3     | mei_txe    | 32C0E61EA7 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | EB2FD1CEB9 |
| 8086:0f18 | 1509:7018 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 9347717861 |
| 8086:0f18 | 1854:0211 | Intel      | Atom Processor Z36xxx/Z37... | 2     | mei_txe    | 44AF16AC16 |
| 1022:15df | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 1     | ccp        | 70C3FB3790 |
| 8086:0f18 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | B09FE8903A |
| 8086:0f18 | 1025:0949 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 4784D8BAAE |
| 8086:0f18 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | DD65C5ABF7 |
| 8086:0f18 | 17aa:3985 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | EDFF48D58F |
| 8086:1198 |           | Intel      | Encryption controller        | 1     |            | D1F5E15D8C |
| 8086:2298 | 1854:0280 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | A6AB074BB5 |
| 8086:2298 | 1bfd:0001 | Intel      | Atom/Celeron/Pentium Proc... | 1     | mei_txe    | 1BA20022CB |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 98    | i915       | 3317BA664D |
| 8086:22b0 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 31    | i915       | F21B55E1F7 |
| 8086:22b0 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 29    | i915       | 4AC35C901A |
| 8086:1916 | 1414:0014 | Intel      | Skylake GT2 [HD Graphics ... | 24    | i915       | 0E1D0B8D70 |
| 8086:1916 | 1414:0015 | Intel      | Skylake GT2 [HD Graphics ... | 24    | i915       | BF80DE79C3 |
| 8086:0a16 | 1414:0005 | Intel      | Haswell-ULT Integrated Gr... | 23    | i915       | 3672EF87DE |
| 8086:22b0 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | i915       | E5A8BA60CF |
| 8086:22b0 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | i915       | 83AE87648C |
| 8086:0a16 | 1414:0a16 | Intel      | Haswell-ULT Integrated Gr... | 13    | i915       | BA2B6488C2 |
| 8086:5916 | 1414:0026 | Intel      | HD Graphics 620              | 13    | i915       | 7A294509DE |
| 8086:22b0 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | i915       | 0542145A63 |
| 8086:0f31 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 11    | i915       | 314AA4D200 |
| 8086:1926 | 1414:0015 | Intel      | Iris Graphics 540            | 11    | i915       | EC38221F00 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 10    | i915       | 1A6758A371 |
| 1002:9804 | 1025:0577 | AMD        | Wrestler [Radeon HD 6250]    | 9     | radeon     | EC2B6926DD |
| 8086:591e | 152d:1182 | Intel      | HD Graphics 615              | 9     | i915       | 3EB69E8095 |
| 8086:22b0 | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 8     | i915       | 85D49B081C |
| 8086:0f31 | 17aa:221b | Intel      | Atom Processor Z36xxx/Z37... | 7     | i915       | 9B7A2A3D3B |
| 8086:5916 | 103c:82ca | Intel      | HD Graphics 620              | 7     | i915       | D6AB5352B8 |
| 8086:5917 | 1414:0026 | Intel      | UHD Graphics 620             | 7     | i915       | 8C4E9C3488 |
| 8086:0f31 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | 2C99AF7703 |
| 8086:0f31 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | BE55ABE40D |
| 8086:0f31 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 6     | i915       | 92D4603EA8 |
| 8086:5917 | 1414:0027 | Intel      | UHD Graphics 620             | 6     | i915       | 14A3F2D111 |
| 8086:5917 | 1414:0028 | Intel      | UHD Graphics 620             | 6     | i915       | D0D3D517EF |
| 8086:0166 | 1414:0166 | Intel      | 3rd Gen Core processor Gr... | 5     | i915       | 4E005ED117 |
| 8086:0a26 | 1414:0005 | Intel      | Haswell-ULT Integrated Gr... | 5     | i915       | AC7F0D85A6 |
| 8086:0f31 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 5     | i915       | 2548D4154B |
| 8086:0f31 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 5     | i915       | 36E2AE6F17 |
| 8086:22b0 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | i915       | 1C188B150F |
| 8086:5916 | 1028:07a4 | Intel      | HD Graphics 620              | 5     | i915       | 45B102BEAF |
| 8086:5916 | 144d:c14f | Intel      | HD Graphics 620              | 5     | i915       | C9D869A6A8 |
| 8086:591e | 103c:828b | Intel      | HD Graphics 615              | 5     | i915       | 3196DC7C2A |
| 8086:591e | 1414:0026 | Intel      | HD Graphics 615              | 5     | i915       | DBD940A4F3 |
| 1002:9807 | 1025:0577 | AMD        | Wrestler [Radeon HD 6290]    | 4     | radeon     | 560E2E570B |
| 10de:1c8d | 1414:0024 | Nvidia     | GP107M [GeForce GTX 1050 ... | 4     | nouveau    | 1099AD6DC9 |
| 8086:0a1e | 1414:0005 | Intel      | Haswell-ULT High Definiti... | 4     | i915       | 1808E45DB5 |
| 8086:0f31 | 17aa:221c | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | 0D08330F36 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 4     | i915       | 3B331BB4AF |
| 8086:191e | 1028:06e6 | Intel      | HD Graphics 515              | 4     | i915       | 36CE9AD0C9 |
| 8086:191e | 144d:c135 | Intel      | HD Graphics 515              | 4     | i915       | 4E4EF907A0 |
| 8086:22b0 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 4     | i915       | A8198C3153 |
| 8086:5917 | 1028:081d | Intel      | UHD Graphics 620             | 4     | i915       | 1ABEA9314A |
| 8086:5917 | 1414:0025 | Intel      | UHD Graphics 620             | 4     | i915       | DBD06D839B |
| 8086:5917 | 17aa:2244 | Intel      | UHD Graphics 620             | 4     | i915       | 234767F4BA |
| 8086:5917 | 17aa:397a | Intel      | UHD Graphics 620             | 4     | i915       | F78D607B1F |
| 8086:591c | 152d:1237 | Intel      | UHD Graphics 615             | 4     | i915       | 2618117BB7 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 4     | i915       | 902AD35DB3 |
| 8086:8a52 | 1414:0037 | Intel      | Iris Plus Graphics G7        | 4     | i915       | 68E21C3B5B |
| 8086:8a5a | 1414:0037 | Intel      | Iris Plus Graphics G4 (Ic... | 4     | i915       | 4265905516 |
| 10de:1c20 | 1414:0024 | Nvidia     | GP106M [GeForce GTX 1060 ... | 3     | nouveau    | 22B470ABFB |
| 8086:0f31 | 103c:8031 | Intel      | Atom Processor Z36xxx/Z37... | 3     | i915       | 32C0E61EA7 |
| 8086:161e | 17aa:222b | Intel      | HD Graphics 5300             | 3     | i915       | 5BADA8B921 |
| 8086:1916 | 1025:111e | Intel      | Skylake GT2 [HD Graphics ... | 3     | i915       | 1A171E7553 |
| 8086:1916 | 17aa:39f2 | Intel      | Skylake GT2 [HD Graphics ... | 3     | i915       | F590550713 |
| 8086:191e | 1028:06d6 | Intel      | HD Graphics 515              | 3     | i915       | 7A9C92F242 |
| 8086:191e | 1414:0015 | Intel      | HD Graphics 515              | 3     | i915       | F4054D1284 |
| 8086:191e | 17aa:2241 | Intel      | HD Graphics 515              | 3     | i915       | 1C271464F4 |
| 8086:191e | 8086:191e | Intel      | HD Graphics 515              | 3     | i915       | 5FE3179524 |
| 8086:22b0 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 3     | i915       | 42B9111B9B |
| 8086:3184 | 17aa:39ff | Intel      | GeminiLake [UHD Graphics ... | 3     | i915       | 9118598BC9 |
| 8086:5916 | 1414:0025 | Intel      | HD Graphics 620              | 3     | i915       | 26578393CC |
| 8086:591e | 1028:07a5 | Intel      | HD Graphics 615              | 3     | i915       | 0325FE3F75 |
| 8086:591e | 8086:591e | Intel      | HD Graphics 615              | 3     | i915       | 422797E8D2 |
| 8086:5a84 | 1025:1209 | Intel      | Celeron N3350/Pentium N42... | 3     | i915       | E8FB03A779 |
| 8086:5a85 | 0100:2782 | Intel      | HD Graphics 500              | 3     | i915       | 23C593482C |
| 1002:15d8 | 1414:0034 | AMD        | Picasso                      | 2     | amdgpu     | EB2FD1CEB9 |
| 8086:0a1e | 17aa:3978 | Intel      | Haswell-ULT High Definiti... | 2     | i915       | 6CBD38B3E5 |
| 8086:0f31 | 1509:7018 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 9347717861 |
| 8086:0f31 | 1854:0211 | Intel      | Atom Processor Z36xxx/Z37... | 2     | i915       | 44AF16AC16 |
| 8086:1916 | 1043:13c0 | Intel      | Skylake GT2 [HD Graphics ... | 2     | i915       | 4363CA1BD6 |
| 8086:191e | 19e5:3e00 | Intel      | HD Graphics 515              | 2     | i915       | D4C3DCBC61 |
| 8086:3185 | 17aa:39ff | Intel      | GeminiLake [UHD Graphics ... | 2     | i915       | 78A8B317D6 |
| 8086:5916 | 1025:1171 | Intel      | HD Graphics 620              | 2     | i915       | 4B0ED624FA |
| 8086:5916 | 1043:16c0 | Intel      | HD Graphics 620              | 2     | i915       | D33E67BDF4 |
| 8086:591e | 1043:1410 | Intel      | HD Graphics 615              | 2     | i915       | C66E4999F0 |
| 8086:591e | 1414:0025 | Intel      | HD Graphics 615              | 2     | i915       | 4CBF33DDA7 |
| 8086:5926 | 103c:82cb | Intel      | Iris Plus Graphics 640       | 2     | i915       | 009ABCD381 |
| 8086:5926 | 1414:0025 | Intel      | Iris Plus Graphics 640       | 2     | i915       | 0A81D643C2 |
| 8086:5926 | 1414:0026 | Intel      | Iris Plus Graphics 640       | 2     | i915       | EF73590627 |
| 8086:8a52 | 1414:0035 | Intel      | Iris Plus Graphics G7        | 2     | i915       | 79D77CFE11 |
| 8086:8a56 | 1414:0047 | Intel      | Iris Plus Graphics G1 (Ic... | 2     | i915       | D34ECF1B95 |
| 1002:15d8 | 103c:86fd | AMD        | Picasso                      | 1     | amdgpu     | 70C3FB3790 |
| 1002:68f9 | 1682:3030 | AMD        | Cedar [Radeon HD 5000/600... | 1     | radeon     | 1785E9C758 |
| 10de:1381 | 1043:84ae | Nvidia     | GM107 [GeForce GTX 750]      | 1     | nvidia     | 9C72670AA1 |
| 10de:13b4 | 103c:824c | Nvidia     | GM107GLM [Quadro M620 Mob... | 1     | nvidia     | A557059CBA |
| 8086:0102 | 1025:0589 | Intel      | 2nd Generation Core Proce... | 1     | i915       | 95C27C9FC7 |
| 8086:0166 | 10f7:8338 | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 68ECFC5409 |
| 8086:0166 | 1b0a:017b | Intel      | 3rd Gen Core processor Gr... | 1     | i915       | 5A97B2A1A7 |
| 8086:0be1 | 14c0:006c | Intel      | Atom Processor D2xxx/N2xx... | 1     | gma500     | 8FF8AE3115 |
| 8086:0f31 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | B09FE8903A |
| 8086:0f31 | 1025:0949 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | 4784D8BAAE |
| 8086:0f31 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | DD65C5ABF7 |
| 8086:0f31 | 17aa:3901 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | EDFF48D58F |
| 8086:1182 |           | Intel      | Display controller           | 1     |            | D1F5E15D8C |
| 8086:11a6 |           | Intel      | Display controller           | 1     |            | D1F5E15D8C |
| 8086:1912 | 1043:8694 | Intel      | HD Graphics 530              | 1     | i915       | 9C72670AA1 |
| 8086:1916 | 1b0a:01d3 | Intel      | Skylake GT2 [HD Graphics ... | 1     | i915       | C2D333A420 |
| 8086:191e | 1028:0702 | Intel      | HD Graphics 515              | 1     | i915       | 229409A8DC |
| 8086:1a84 | 8086:7270 | Intel      | HD Graphics                  | 1     | i915       | 555A26F0D1 |

### Iommu (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 2     |            | EB2FD1CEB9 |
| 1022:15d1 | 103c:86fd | AMD        | Raven/Raven2 IOMMU           | 1     |            | 70C3FB3790 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 113   |            | 0E1D0B8D70 |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 14    |            | D34ECF1B95 |
| 8086:9d21 | 152d:1182 | Intel      | Sunrise Point-LP PMC         | 9     |            | 3EB69E8095 |
| 8086:9d21 | 103c:82ca | Intel      | Sunrise Point-LP PMC         | 7     |            | D6AB5352B8 |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 6     |            | 5FE3179524 |
| 8086:9d21 | 1028:07a4 | Intel      | Sunrise Point-LP PMC         | 5     |            | 45B102BEAF |
| 8086:9d21 | 103c:828b | Intel      | Sunrise Point-LP PMC         | 5     |            | 3196DC7C2A |
| 8086:9d21 | 144d:c14f | Intel      | Sunrise Point-LP PMC         | 5     |            | C9D869A6A8 |
| 8086:9d21 | 1028:06e6 | Intel      | Sunrise Point-LP PMC         | 4     |            | 36CE9AD0C9 |
| 8086:9d21 | 1028:081d | Intel      | Sunrise Point-LP PMC         | 4     |            | 1ABEA9314A |
| 8086:9d21 | 144d:c135 | Intel      | Sunrise Point-LP PMC         | 4     |            | 4E4EF907A0 |
| 8086:9d21 | 152d:1237 | Intel      | Sunrise Point-LP PMC         | 4     |            | 2618117BB7 |
| 8086:9d21 | 17aa:2244 | Intel      | Sunrise Point-LP PMC         | 4     |            | 234767F4BA |
| 8086:9d21 | 17aa:3853 | Intel      | Sunrise Point-LP PMC         | 4     |            | F78D607B1F |
| 8086:9d21 | 1025:111e | Intel      | Sunrise Point-LP PMC         | 3     |            | 1A171E7553 |
| 8086:9d21 | 1028:06d6 | Intel      | Sunrise Point-LP PMC         | 3     |            | 7A9C92F242 |
| 8086:9d21 | 1028:07a5 | Intel      | Sunrise Point-LP PMC         | 3     |            | 0325FE3F75 |
| 8086:9d21 | 17aa:2241 | Intel      | Sunrise Point-LP PMC         | 3     |            | 1C271464F4 |
| 8086:9d21 | 17aa:3829 | Intel      | Sunrise Point-LP PMC         | 3     |            | F590550713 |
| 8086:9d21 | 1025:1171 | Intel      | Sunrise Point-LP PMC         | 2     |            | 4B0ED624FA |
| 8086:9d21 | 103c:82cb | Intel      | Sunrise Point-LP PMC         | 2     |            | 009ABCD381 |
| 8086:9d21 | 1043:13c0 | Intel      | Sunrise Point-LP PMC         | 2     |            | 4363CA1BD6 |
| 8086:9d21 | 1043:1410 | Intel      | Sunrise Point-LP PMC         | 2     |            | C66E4999F0 |
| 8086:9d21 | 1043:16c0 | Intel      | Sunrise Point-LP PMC         | 2     |            | D33E67BDF4 |
| 8086:9d21 | 19e5:3e00 | Intel      | Sunrise Point-LP PMC         | 2     |            | D4C3DCBC61 |
| 8086:02ef | 17aa:380d | Intel      | Comet Lake PCH-LP Shared ... | 1     |            | 6F0E0FCC43 |
| 8086:9d21 | 1028:0702 | Intel      | Sunrise Point-LP PMC         | 1     |            | 229409A8DC |
| 8086:9d21 | 103c:824c | Intel      | Sunrise Point-LP PMC         | 1     |            | A557059CBA |
| 8086:9d21 | 103c:8414 | Intel      | Sunrise Point-LP PMC         | 1     |            | 4937A2C0A8 |
| 8086:9d21 | 17aa:2243 | Intel      | Sunrise Point-LP PMC         | 1     |            | AA3F633BF5 |
| 8086:9d21 | 17aa:3834 | Intel      | Sunrise Point-LP PMC         | 1     |            | 14DC838F85 |
| 8086:9d21 | 1b0a:01d3 | Intel      | Sunrise Point-LP PMC         | 1     |            | C2D333A420 |
| 8086:9def | 1028:0895 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | FF9B284809 |
| 8086:9def | 103c:85b9 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 11BBC16301 |
| 8086:a0ef | 17aa:508b | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | AAC22AF3A1 |
| 8086:a0ef | 8086:7270 | Intel      | Tiger Lake-LP Shared SRAM    | 1     |            | A4AEFCD9B2 |
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9C72670AA1 |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 110   | ipu3_imgu  | 0E1D0B8D70 |
| 8086:9d32 | 8086:7270 | Intel      | CSI-2 Host Controller        | 106   | ipu3_cio2  | 0E1D0B8D70 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 97    | intel_a... | 3317BA664D |
| 8086:22b8 | 17aa:38e3 | Intel      | Atom/Celeron/Pentium Proc... | 31    | intel_a... | F21B55E1F7 |
| 8086:22b8 | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 29    | intel_a... | 4AC35C901A |
| 8086:22b8 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | intel_a... | 83AE87648C |
| 8086:22b8 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 16    | intel_a... | E5A8BA60CF |
| 8086:9d32 |           | Intel      | CSI-2 Host Controller        | 16    | ipu3_cio2  | 2618117BB7 |
| 8086:22b8 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 11    | atomisp    | 0542145A63 |
| 8086:1919 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | ipu3_imgu  | 3EB69E8095 |
| 8086:1919 | 8086:1919 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | ipu3_imgu  | 5FE3179524 |
| 8086:8a19 | 8086:7270 | Intel      | Image Signal Processor       | 9     |            | 4265905516 |
| 8086:22b8 | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 8     | intel_a... | 85D49B081C |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 8     |            | 902AD35DB3 |
| 8086:1919 | 103c:82ca | Intel      | Xeon E3-1200 v5/E3-1500 v... | 7     | ipu3_imgu  | D6AB5352B8 |
| 8086:9d32 | 103c:82ca | Intel      | CSI-2 Host Controller        | 7     | ipu3_cio2  | D6AB5352B8 |
| 8086:9d32 | 8086:9d32 | Intel      | CSI-2 Host Controller        | 6     | ipu3_cio2  | 5FE3179524 |
| 8086:1919 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | ipu3_imgu  | 45B102BEAF |
| 8086:1919 | 103c:828b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | ipu3_imgu  | 3196DC7C2A |
| 8086:1919 | 144d:c14f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | ipu3_imgu  | C9D869A6A8 |
| 8086:22b8 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | intel_a... | 1C188B150F |
| 8086:9d32 | 1028:07a4 | Intel      | CSI-2 Host Controller        | 5     | ipu3_cio2  | 45B102BEAF |
| 8086:9d32 | 103c:828b | Intel      | CSI-2 Host Controller        | 5     | ipu3_cio2  | 3196DC7C2A |
| 8086:9d32 | 144d:c14f | Intel      | CSI-2 Host Controller        | 5     | ipu3_cio2  | C9D869A6A8 |
| 8086:1919 | 1028:06e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | ipu3_imgu  | 36CE9AD0C9 |
| 8086:1919 | 1028:081d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | ipu3_imgu  | 1ABEA9314A |
| 8086:1919 | 144d:c135 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | ipu3_imgu  | 4E4EF907A0 |
| 8086:1919 | 152d:1237 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | ipu3_imgu  | 2618117BB7 |
| 8086:1919 | 17aa:2244 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | ipu3_imgu  | 234767F4BA |
| 8086:1919 | 17aa:382f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     |            | F78D607B1F |
| 8086:22b8 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 4     | intel_a... | A8198C3153 |
| 8086:9d32 | 1028:06e6 | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 36CE9AD0C9 |
| 8086:9d32 | 1028:081d | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 1ABEA9314A |
| 8086:9d32 | 144d:c135 | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 4E4EF907A0 |
| 8086:9d32 | 17aa:2244 | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | 234767F4BA |
| 8086:9d32 | 17aa:380c | Intel      | CSI-2 Host Controller        | 4     | ipu3_cio2  | F78D607B1F |
| 8086:0f38 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 3     | atomisp... | F19C34B72D |
| 8086:1919 | 1025:111e | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 1A171E7553 |
| 8086:1919 | 1028:06d6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 7A9C92F242 |
| 8086:1919 | 1028:07a5 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 0325FE3F75 |
| 8086:1919 | 17aa:2241 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 3     | ipu3_imgu  | 1C271464F4 |
| 8086:22b8 | 17aa:222a | Intel      | Atom/Celeron/Pentium Proc... | 3     | intel_a... | 42B9111B9B |
| 8086:9d32 | 1028:06d6 | Intel      | CSI-2 Host Controller        | 3     | ipu3_cio2  | 7A9C92F242 |
| 8086:9d32 | 1028:07a5 | Intel      | CSI-2 Host Controller        | 3     | ipu3_cio2  | 0325FE3F75 |
| 8086:9d32 | 17aa:2241 | Intel      | CSI-2 Host Controller        | 3     | ipu3_cio2  | 1C271464F4 |
| 8086:9d32 | 17aa:3804 | Intel      | CSI-2 Host Controller        | 3     | ipu3_cio2  | F590550713 |
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 2     | snd_pci... | EB2FD1CEB9 |
| 8086:1919 | 1025:1171 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 4B0ED624FA |
| 8086:1919 | 103c:82cb | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 009ABCD381 |
| 8086:1919 | 1043:13c0 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | 4363CA1BD6 |
| 8086:1919 | 19e5:3e00 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | ipu3_imgu  | D4C3DCBC61 |
| 8086:9d32 | 1025:1171 | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | 4B0ED624FA |
| 8086:9d32 | 103c:82cb | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | 009ABCD381 |
| 8086:9d32 | 1043:13c0 | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | 4363CA1BD6 |
| 8086:9d32 | 1043:1410 | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | C66E4999F0 |
| 8086:9d32 | 1043:1d2d | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | D33E67BDF4 |
| 8086:9d32 | 19e5:3e00 | Intel      | CSI-2 Host Controller        | 2     | ipu3_cio2  | D4C3DCBC61 |
| 1022:15e2 | 103c:86fd | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 70C3FB3790 |
| 8086:1919 | 1028:0702 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 229409A8DC |
| 8086:1919 | 103c:8414 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | ipu3_imgu  | 4937A2C0A8 |
| 8086:1919 | 17aa:2243 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | ipu3_imgu  | AA3F633BF5 |
| 8086:1919 | 17aa:3825 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 14DC838F85 |
| 8086:1a88 |           | Intel      | Imaging Signal Processor ... | 1     |            | 555A26F0D1 |
| 8086:22b8 | 1297:1008 | Intel      | Atom/Celeron/Pentium Proc... | 1     | intel_a... | 03137C3E6D |
| 8086:22b8 | 1854:0280 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | A6AB074BB5 |
| 8086:22b8 | 1bfd:0001 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 1BA20022CB |
| 8086:9a19 | 17aa:508b | Intel      | Multimedia controller        | 1     |            | AAC22AF3A1 |
| 8086:9d32 | 1028:0702 | Intel      | CSI-2 Host Controller        | 1     | ipu3_cio2  | 229409A8DC |
| 8086:9d32 | 103c:8414 | Intel      | CSI-2 Host Controller        | 1     | ipu3_cio2  | 4937A2C0A8 |
| 8086:9d32 | 17aa:2243 | Intel      | CSI-2 Host Controller        | 1     | ipu3_cio2  | AA3F633BF5 |
| 8086:9d32 | 17aa:3807 | Intel      | CSI-2 Host Controller        | 1     | ipu3_cio2  | 14DC838F85 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8136 | 1854:0211 | Realtek... | RTL810xE PCI Express Fast... | 2     | r8169      | 44AF16AC16 |
| 10ec:8168 | 1019:99fa | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 4F4EFBC5C6 |
| 10ec:8168 | 1509:7018 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | r8169      | 9347717861 |
| 10ec:8136 | 1019:99da | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 90B1418DAB |
| 10ec:8136 | 1019:99fa | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | 36E2AE6F17 |
| 10ec:8136 | 10ec:0123 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | BA303FB8FF |
| 10ec:8136 | 1558:5470 | Realtek... | RTL810xE PCI Express Fast... | 1     | r8169      | DD65C5ABF7 |
| 8086:156f | 1b0a:01d3 | Intel      | Ethernet Connection I219-LM  | 1     | e1000e     | C2D333A420 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 54    | iwlwifi    | F21B55E1F7 |
| 11ab:2b38 | 0003:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 38    | mwifiex... | BF80DE79C3 |
| 168c:0042 | 1a3b:2a51 | Qualcom... | QCA9377 802.11ac Wireless... | 33    | ath10k_pci | 0542145A63 |
| 11ab:2b38 | 0001:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 32    | mwifiex... | AC7F0D85A6 |
| 11ab:2b38 | 0008:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 27    | mwifiex... | 7A294509DE |
| 11ab:2b38 | 0004:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 24    | mwifiex... | 0E1D0B8D70 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 18    | iwlwifi    | 1C188B150F |
| 8086:34f0 | 8086:0074 | Intel      | Ice Lake-LP PCH CNVi WiFi    | 14    | iwlwifi    | D34ECF1B95 |
| 11ab:2b38 | 0006:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 11    | mwifiex... | DBD06D839B |
| 168c:002b | 105b:e031 | Qualcom... | AR9285 Wireless Network A... | 10    | ath9k      | 560E2E570B |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 10    | iwlwifi    | 009ABCD381 |
| 8086:31dc | 8086:0264 | Intel      | Gemini Lake PCH CNVi WiFi    | 10    | iwlwifi    | 1A6758A371 |
| 168c:003e | 168c:3370 | Qualcom... | QCA6174 802.11ac Wireless... | 9     | ath10k_pci | 3EB69E8095 |
| 8086:24fd | 8086:0150 | Intel      | Wireless 8265 / 8275         | 8     | iwlwifi    | 1ABEA9314A |
| 8086:3165 | 8086:8110 | Intel      | Wireless 3165                | 8     | iwlwifi    | 902AD35DB3 |
| 11ab:2b38 | 0002:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 7     | mwifiex... | 85D49B081C |
| 8086:24f3 | 8086:0150 | Intel      | Wireless 8260                | 7     | iwlwifi    | 7A9C92F242 |
| 8086:24f3 | 8086:8110 | Intel      | Wireless 8260                | 7     | iwlwifi    | 1C271464F4 |
| 11ab:2b38 | 0009:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 6     | mwifiex... | 14A3F2D111 |
| 11ab:2b38 | 0007:045e | Marvell... | 88W8897 [AVASTAR] 802.11a... | 5     | mwifiex... | D0D3D517EF |
| 168c:003e | 144d:c14f | Qualcom... | QCA6174 802.11ac Wireless... | 5     | ath10k_pci | C9D869A6A8 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 5     | iwlwifi    | 2548D4154B |
| 10ec:b723 | 10ec:b737 | Realtek... | RTL8723BE PCIe Wireless N... | 4     | rtl8723be  | 4F4EFBC5C6 |
| 168c:003e | 144d:c135 | Qualcom... | QCA6174 802.11ac Wireless... | 4     | ath10k_pci | 4E4EF907A0 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 4     | iwlwifi    | D6AB5352B8 |
| 8086:2723 | 8086:008c | Intel      | Wi-Fi 6 AX200                | 4     | iwlwifi    | 2618117BB7 |
| 14e4:43ec | 105b:e095 | Broadcom   | BCM4356 802.11ac Wireless... | 3     | brcmfmac   | 42B9111B9B |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 3     | iwlwifi    | F590550713 |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | 0325FE3F75 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | 52DF26FD63 |
| 8086:24fd | 8086:8010 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | A557059CBA |
| 8086:24fd | 8086:8110 | Intel      | Wireless 8265 / 8275         | 3     | iwlwifi    | 234767F4BA |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 3     | iwlwifi    | 1DD80D33E5 |
| 14e4:43ec | 19e5:3100 | Broadcom   | BCM4356 802.11ac Wireless... | 2     | brcmfmac   | D4C3DCBC61 |
| 168c:0034 | 17aa:3214 | Qualcom... | AR9462 Wireless Network A... | 2     | ath9k      | 6CBD38B3E5 |
| 168c:003e | 045e:0001 | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | EB2FD1CEB9 |
| 168c:003e | 105b:e09d | Qualcom... | QCA6174 802.11ac Wireless... | 2     | ath10k_pci | 2D71938FC4 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 2     | iwlwifi    | 8FF8AE3115 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 2     | iwlwifi    | 9347717861 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 2     | iwlwifi    | 44AF16AC16 |
| 8086:095a | 8086:9110 | Intel      | Wireless 7265                | 2     | iwlwifi    | 4363CA1BD6 |
| 8086:24fd | 8086:9110 | Intel      | Wireless 8265 / 8275         | 2     | iwlwifi    | 7A3A0603E5 |
| 8086:7360 | 8086:0020 | Intel      | XMM7360 LTE Advanced Modem   | 2     |            | 6F0E0FCC43 |
| 10ec:8179 | 10ec:0188 | Realtek... | RTL8188EE Wireless Networ... | 1     | rtl8188ee  | DD65C5ABF7 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 1     |            | 70C3FB3790 |
| 168c:003e | 1028:0410 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | 736BADEA83 |
| 168c:003e | 11ad:0807 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | 1A171E7553 |
| 168c:003e | 17aa:0827 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | F78D607B1F |
| 168c:003e | 1a56:1535 | Qualcom... | QCA6174 802.11ac Wireless... | 1     | ath10k_pci | 78DA4CD8F0 |
| 168c:0042 | 17aa:4025 | Qualcom... | QCA9377 802.11ac Wireless... | 1     | ath10k_pci | 78A8B317D6 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 1     | iwlwifi    | 6F0E0FCC43 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 1     | iwlwifi    | 5A97B2A1A7 |
| 8086:08b1 | 8086:4062 | Intel      | Wireless 7260                | 1     | iwlwifi    | 8F2478944C |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 1     | iwlwifi    | C2D333A420 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 1     | iwlwifi    | 555A26F0D1 |
| 8086:24fd | 8086:0130 | Intel      | Wireless 8265 / 8275         | 1     | iwlwifi    | 49D345EC0B |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 1     | iwlwifi    | 229409A8DC |
| 8086:2723 | 8086:0088 | Intel      | Wi-Fi 6 AX200                | 1     | iwlwifi    | 11BBC16301 |
| 8086:31dc | 8086:0234 | Intel      | Gemini Lake PCH CNVi WiFi    | 1     | iwlwifi    | FD98FD839E |
| 8086:7560 | 103c:8507 | Intel      | Wireless controller          | 1     |            | 11BBC16301 |
| 8086:9df0 | 8086:0000 | Intel      | Cannon Point-LP CNVi [Wir... | 1     | iwlwifi    | FF9B284809 |
| 8086:a0f0 | 8086:0070 | Intel      | Wi-Fi 6 AX201                | 1     | iwlwifi    | AAC22AF3A1 |
| 8086:a0f0 | 8086:0074 | Intel      | Wi-Fi 6 AX201                | 1     | iwlwifi    | A4AEFCD9B2 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | ffff:0000 | Intel      | I210 Gigabit Network Conn... | 2     | igb        | 49D345EC0B |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d35 | 8086:7270 | Intel      | Sunrise Point-LP Integrat... | 40    | intel_i... | 7A294509DE |
| 8086:22d8 | 103c:827c | Intel      | Integrated Sensor Solution   | 17    | intel_i... | E5A8BA60CF |
| 8086:22d8 | 1043:13a0 | Intel      | Integrated Sensor Solution   | 17    | intel_i... | 83AE87648C |
| 8086:22d8 | 1043:1400 | Intel      | Integrated Sensor Solution   | 12    | intel_i... | 0542145A63 |
| 8086:9d35 | 152d:1182 | Intel      | Sunrise Point-LP Integrat... | 9     | intel_i... | 3EB69E8095 |
| 8086:9d35 | 103c:82ca | Intel      | Sunrise Point-LP Integrat... | 7     | intel_i... | D6AB5352B8 |
| 8086:22d8 | 103c:82f4 | Intel      | Integrated Sensor Solution   | 5     | intel_i... | 1C188B150F |
| 8086:9d35 | 1028:07a4 | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 45B102BEAF |
| 8086:9d35 | 103c:828b | Intel      | Sunrise Point-LP Integrat... | 5     | intel_i... | 3196DC7C2A |
| 8086:22d8 | 1043:1c60 | Intel      | Integrated Sensor Solution   | 4     | intel_i... | A8198C3153 |
| 8086:9d35 | 1028:06e6 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 36CE9AD0C9 |
| 8086:9d35 | 1028:081d | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 1ABEA9314A |
| 8086:9d35 | 152d:1237 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 2618117BB7 |
| 8086:9d35 | 17aa:2244 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | 234767F4BA |
| 8086:9d35 | 17aa:3807 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | F78D607B1F |
| 8086:9d35 | 8086:9d35 | Intel      | Sunrise Point-LP Integrat... | 4     | intel_i... | C66E4999F0 |
| 8086:22d8 | 8086:7270 | Intel      | Integrated Sensor Solution   | 3     | intel_i... | 42B9111B9B |
| 8086:9d35 | 1025:111e | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1A171E7553 |
| 8086:9d35 | 1028:06d6 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 7A9C92F242 |
| 8086:9d35 | 1028:07a5 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 0325FE3F75 |
| 8086:9d35 | 17aa:2241 | Intel      | Sunrise Point-LP Integrat... | 3     | intel_i... | 1C271464F4 |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 2     | i2c_amd... | EB2FD1CEB9 |
| 8086:9d35 | 1025:1171 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 4B0ED624FA |
| 8086:9d35 | 103c:82cb | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 009ABCD381 |
| 8086:9d35 | 1043:13c0 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | 4363CA1BD6 |
| 8086:9d35 | 19e5:3e00 | Intel      | Sunrise Point-LP Integrat... | 2     | intel_i... | D4C3DCBC61 |
| 8086:9d35 | 1028:0702 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 229409A8DC |
| 8086:9d35 | 103c:824c | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | A557059CBA |
| 8086:9d35 | 103c:8414 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | 4937A2C0A8 |
| 8086:9d35 | 17aa:2243 | Intel      | Sunrise Point-LP Integrat... | 1     | intel_i... | AA3F633BF5 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | sdhci_pci  | 902AD35DB3 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | sdhci_pci  | 902AD35DB3 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | sdhci_pci  | 1A6758A371 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 10    | sdhci_pci  | 1A6758A371 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | sdhci_pci  | 902AD35DB3 |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 6     | sdhci_pci  | 5FE3179524 |
| 8086:9d2d | 8086:9d2d | Intel      | Sunrise Point-LP Secure D... | 6     | sdhci_pci  | 5FE3179524 |
| 8086:31cc | 17aa:381f | Intel      | Celeron/Pentium Silver Pr... | 5     | sdhci_pci  | 9118598BC9 |
| 8086:9d2d | 144d:c14f | Intel      | Sunrise Point-LP Secure D... | 5     | sdhci_pci  | C9D869A6A8 |
| 10ec:5209 | 10ec:5209 | Realtek... | RTS5209 PCI Express Card ... | 3     | rtsx_pci   | 44AF16AC16 |
| 8086:0f16 | 1509:7018 | Intel      | Atom Processor Z36xxx/Z37... | 2     | sdhci_pci  | 9347717861 |
| 8086:9d2b | 152d:1182 | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | 3EB69E8095 |
| 1217:8621 | 17aa:3801 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 14DC838F85 |
| 1217:8621 | 17aa:3822 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 6F0E0FCC43 |
| 8086:1190 |           | Intel      | Merrifield SD/SDIO/eMMC C... | 1     | sdhci_pci  | D1F5E15D8C |
| 8086:1aca | 8086:7270 | Intel      | SD Host Controller           | 1     | sdhci_pci  | 555A26F0D1 |
| 8086:1acc | 8086:7270 | Intel      | SD Host Controller           | 1     | sdhci_pci  | 555A26F0D1 |
| 8086:2295 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | BEF5E99067 |
| 8086:2296 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 14D1D84766 |
| 8086:31cc | 17aa:3826 | Intel      | Celeron/Pentium Silver Pr... | 1     | sdhci_pci  | FD98FD839E |
| 8086:5aca |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 49D345EC0B |
| 8086:5aca | 8086:5aca | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | D461E042A0 |
| 8086:5acc | 8086:5acc | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | D461E042A0 |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | D461E042A0 |
| 8086:9d2b | 152d:1237 | Intel      | Skylake-U/Y SCC: eMMC        | 1     | sdhci_pci  | 8BBA41EDDE |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:34a4 | 8086:7270 | Intel      | Ice Lake-LP SPI Controller   | 14    | intel_s... | D34ECF1B95 |
| 8086:34c5 | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2c... | 14    | intel_l... | D34ECF1B95 |
| 8086:34e8 | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2C... | 14    | intel_l... | D34ECF1B95 |
| 8086:34ea | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2C... | 11    | intel_l... | D34ECF1B95 |
| 8086:34eb | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2C... | 9     | intel_l... | 4265905516 |
| 8086:34e9 | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2C... | 2     | intel_l... | 79D77CFE11 |
| 8086:02a4 | 17aa:3813 | Intel      | Comet Lake SPI (flash) Co... | 1     |            | 6F0E0FCC43 |
| 8086:02c5 | 17aa:3804 | Intel      | Comet Lake Serial IO I2C ... | 1     | intel_l... | 6F0E0FCC43 |
| 8086:02e8 | 17aa:380f | Intel      | Serial IO I2C Host Contro... | 1     | intel_l... | 6F0E0FCC43 |
| 8086:1ac8 | 8086:7270 | Intel      | Serial bus controller        | 1     | pwm_lpss   | 555A26F0D1 |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | pwm_lpss   | 6DD31D6E80 |
| 8086:9da4 | 1028:0895 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | FF9B284809 |
| 8086:9da4 | 103c:85b9 | Intel      | Cannon Point-LP SPI Contr... | 1     |            | 11BBC16301 |
| 8086:9de8 | 1028:0895 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | FF9B284809 |
| 8086:9de8 | 103c:85b9 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_l... | 11BBC16301 |
| 8086:9de9 | 1028:0895 | Intel      | Cannon Point-LP Serial IO... | 1     | intel_lpss | FF9B284809 |
| 8086:a0a4 | 17aa:508b | Intel      | Tiger Lake-LP SPI Controller | 1     |            | AAC22AF3A1 |
| 8086:a0a4 | 8086:7270 | Intel      | Tiger Lake-LP SPI Controller | 1     |            | A4AEFCD9B2 |
| 8086:a0c5 | 17aa:508b | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | AAC22AF3A1 |
| 8086:a0c5 | 8086:7270 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | A4AEFCD9B2 |
| 8086:a0d8 | 8086:7270 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | A4AEFCD9B2 |
| 8086:a0e8 | 17aa:508b | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | AAC22AF3A1 |
| 8086:a0e8 | 8086:7270 | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_lpss | A4AEFCD9B2 |
| 8086:a0e9 | 17aa:508b | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | AAC22AF3A1 |
| 8086:a0eb | 17aa:508b | Intel      | Tiger Lake-LP Serial IO I... | 1     | intel_l... | AAC22AF3A1 |

### Serial controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:34fc | 8086:7270 | Intel      | Ice Lake-LP Integrated Se... | 10    | intel_i... | 4265905516 |
| 8086:9d3d | 1028:07a4 | Intel      | Sunrise Point-LP Active M... | 4     | serial     | 45B102BEAF |
| 8086:9d3d | 1028:07a5 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 0325FE3F75 |
| 8086:9d3d | 17aa:2244 | Intel      | Sunrise Point-LP Active M... | 3     | serial     | 234767F4BA |
| 8086:9d3d | 1028:06e6 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 33FE389598 |
| 8086:9d3d | 1028:081d | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 1ABEA9314A |
| 8086:9d3d | 103c:82ca | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 570747DA15 |
| 8086:9d3d | 17aa:2241 | Intel      | Sunrise Point-LP Active M... | 2     | serial     | 1C271464F4 |
| 8086:02fc | 17aa:380c | Intel      | Comet Lake Integrated Sen... | 1     | intel_i... | 6F0E0FCC43 |
| 8086:1191 |           | Intel      | Merrifield Serial IO HSUA... | 1     |            | D1F5E15D8C |
| 8086:1192 |           | Intel      | Merrifield Serial IO HSUA... | 1     |            | D1F5E15D8C |
| 8086:1e3d | 10f7:8338 | Intel      | 7 Series/C210 Series Chip... | 1     | serial     | 68ECFC5409 |
| 8086:9d3d | 1028:06d6 | Intel      | Sunrise Point-LP Active M... | 1     | serial     | 984A219BF0 |
| 8086:9de3 | 103c:85b9 | Intel      | Cannon Point-LP Keyboard ... | 1     | serial     | 11BBC16301 |
| 8086:9dfc | 1028:0895 | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | FF9B284809 |
| 8086:9dfc | 103c:85b9 | Intel      | Cannon Point-LP Integrate... | 1     | intel_i... | 11BBC16301 |
| 8086:a0fc | 17aa:508b | Intel      | Tiger Lake-LP Integrated ... | 1     | intel_i... | AAC22AF3A1 |
| 8086:a0fc | 8086:7270 | Intel      | Tiger Lake-LP Integrated ... | 1     | intel_i... | A4AEFCD9B2 |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 113   | intel_p... | 0E1D0B8D70 |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 113   | intel_l... | 0E1D0B8D70 |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 113   | intel_l... | 0E1D0B8D70 |
| 8086:9d63 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 106   | intel_l... | 0E1D0B8D70 |
| 8086:9d62 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 103   | intel_l... | 0E1D0B8D70 |
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 73    | process... | 3317BA664D |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 51    | process... | 7A294509DE |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 51    | intel_l... | 7A294509DE |
| 8086:22dc | 17aa:3809 | Intel      | Atom/Celeron/Pentium Proc... | 31    | process... | F21B55E1F7 |
| 8086:22dc | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 29    | process... | 4AC35C901A |
| 8086:22dc | 7270:8086 | Intel      | Atom/Celeron/Pentium Proc... | 26    | process... | 23E45B2B8E |
| 8086:22dc | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | process... | E5A8BA60CF |
| 8086:22dc | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | process... | 83AE87648C |
| 8086:1903 | 8086:1903 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 13    | process... | 5FE3179524 |
| 8086:22dc | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | process... | 0542145A63 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | intel_l... | 902AD35DB3 |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | intel_l... | 902AD35DB3 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | intel_l... | 902AD35DB3 |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | intel_l... | 902AD35DB3 |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | intel_l... | 902AD35DB3 |
| 8086:8a03 | 8086:7270 | Intel      | Ice Lake Dynamic Platform... | 11    | process... | 4265905516 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | process... | 1A6758A371 |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | intel_l... | 1A6758A371 |
| 8086:9d27 | 8086:9d27 | Intel      | Sunrise Point-LP Serial I... | 10    | intel_l... | 5FE3179524 |
| 8086:1903 | 152d:1182 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 9     | proc_th... | 3EB69E8095 |
| 8086:9d27 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:9d31 | 152d:1182 | Intel      | Sunrise Point-LP Thermal ... | 9     | intel_p... | 3EB69E8095 |
| 8086:9d60 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:9d61 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:9d62 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:9d63 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:9d64 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_l... | 3EB69E8095 |
| 8086:9d66 | 152d:1182 | Intel      | Sunrise Point-LP Serial I... | 9     | intel_lpss | 3EB69E8095 |
| 8086:22dc | 1414:0009 | Intel      | Atom/Celeron/Pentium Proc... | 8     | process... | 85D49B081C |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 8     | process... | 902AD35DB3 |
| 8086:1903 | 103c:82ca | Intel      | Xeon E3-1200 v5/E3-1500 v... | 7     | process... | D6AB5352B8 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | intel_l... | 902AD35DB3 |
| 8086:9d31 | 103c:82ca | Intel      | Sunrise Point-LP Thermal ... | 7     | intel_p... | D6AB5352B8 |
| 8086:9d60 | 103c:82ca | Intel      | Sunrise Point-LP Serial I... | 7     | intel_l... | D6AB5352B8 |
| 8086:9d62 | 103c:82ca | Intel      | Sunrise Point-LP Serial I... | 7     | intel_l... | D6AB5352B8 |
| 8086:9d63 | 103c:82ca | Intel      | Sunrise Point-LP Serial I... | 7     | intel_l... | D6AB5352B8 |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 6     | intel_p... | 5FE3179524 |
| 8086:9d60 | 8086:9d60 | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 5FE3179524 |
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 5FE3179524 |
| 8086:9d62 | 8086:9d62 | Intel      | Sunrise Point-LP Serial I... | 6     | intel_l... | 5FE3179524 |
| 8086:1903 | 1028:07a4 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 45B102BEAF |
| 8086:1903 | 103c:828b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | 3196DC7C2A |
| 8086:1903 | 144d:c14f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     | process... | C9D869A6A8 |
| 8086:22dc | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | process... | 1C188B150F |
| 8086:318c | 17aa:3805 | Intel      | Celeron/Pentium Silver Pr... | 5     | process... | 9118598BC9 |
| 8086:31ac | 17aa:3817 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31b2 | 17aa:381a | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31b4 | 17aa:3818 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31b6 | 17aa:3819 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31b8 | 17aa:381e | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31ba | 17aa:381b | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31bc | 17aa:381c | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31c2 | 17aa:3821 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:31c6 | 17aa:3828 | Intel      | Celeron/Pentium Silver Pr... | 5     | intel_l... | 9118598BC9 |
| 8086:9d27 | 103c:828b | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 3196DC7C2A |
| 8086:9d27 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C9D869A6A8 |
| 8086:9d31 | 1028:07a4 | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 45B102BEAF |
| 8086:9d31 | 103c:828b | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | 3196DC7C2A |
| 8086:9d31 | 144d:c14f | Intel      | Sunrise Point-LP Thermal ... | 5     | intel_p... | C9D869A6A8 |
| 8086:9d60 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 45B102BEAF |
| 8086:9d60 | 103c:828b | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 3196DC7C2A |
| 8086:9d60 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C9D869A6A8 |
| 8086:9d61 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 45B102BEAF |
| 8086:9d61 | 103c:828b | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 3196DC7C2A |
| 8086:9d61 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C9D869A6A8 |
| 8086:9d62 | 1028:07a4 | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 45B102BEAF |
| 8086:9d62 | 103c:828b | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 3196DC7C2A |
| 8086:9d62 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C9D869A6A8 |
| 8086:9d63 | 103c:828b | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | 3196DC7C2A |
| 8086:9d63 | 144d:c14f | Intel      | Sunrise Point-LP Serial I... | 5     | intel_l... | C9D869A6A8 |
| 8086:1903 | 1028:06e6 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | process... | 36CE9AD0C9 |
| 8086:1903 | 1028:081d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     | proc_th... | 1ABEA9314A |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9c22 | 1414:9c22 | Intel      | 8 Series SMBus Controller    | 45    | i2c_i801   | BA2B6488C2 |
| 1002:4385 | 1025:0577 | AMD        | SBx00 SMBus Controller       | 13    | i2c_pii... | 560E2E570B |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 13    | i801_smbus | 14A3F2D111 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | i2c_i801   | 902AD35DB3 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | i2c_i801   | 1A6758A371 |
| 8086:9d23 | 103c:82ca | Intel      | Sunrise Point-LP SMBus       | 7     | i2c_i801   | D6AB5352B8 |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 6     | i2c_i801   | 5FE3179524 |
| 8086:0f12 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 5     | i2c_i801   | 2548D4154B |
| 8086:0f12 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 5     | i2c_i801   | 36E2AE6F17 |
| 8086:1e22 | 1414:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 5     | i2c_i801   | 4E005ED117 |
| 8086:31d4 | 17aa:3823 | Intel      | Celeron/Pentium Silver Pr... | 5     | i2c_i801   | 9118598BC9 |
| 8086:9d23 | 1028:07a4 | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 45B102BEAF |
| 8086:9d23 | 103c:828b | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | 3196DC7C2A |
| 8086:9d23 | 144d:c14f | Intel      | Sunrise Point-LP SMBus       | 5     | i2c_i801   | C9D869A6A8 |
| 8086:9d23 | 1028:06e6 | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 36CE9AD0C9 |
| 8086:9d23 | 1028:081d | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 1ABEA9314A |
| 8086:9d23 | 144d:c135 | Intel      | Sunrise Point-LP SMBus       | 4     | i2c_i801   | 4E4EF907A0 |
| 8086:9d23 | 17aa:2244 | Intel      | Sunrise Point-LP SMBus       | 4     | i801_smbus | 234767F4BA |
| 8086:9d23 | 17aa:384f | Intel      | Sunrise Point-LP SMBus       | 4     | i801_smbus | F78D607B1F |
| 8086:9ca2 | 17aa:222b | Intel      | Wildcat Point-LP SMBus Co... | 3     | i2c_i801   | 5BADA8B921 |
| 8086:9d23 | 1025:111e | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 1A171E7553 |
| 8086:9d23 | 1028:06d6 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 7A9C92F242 |
| 8086:9d23 | 1028:07a5 | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | 0325FE3F75 |
| 8086:9d23 | 17aa:2241 | Intel      | Sunrise Point-LP SMBus       | 3     | i2c_i801   | 1C271464F4 |
| 8086:9d23 | 17aa:3829 | Intel      | Sunrise Point-LP SMBus       | 3     | i801_smbus | F590550713 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 2     | i2c_piix4  | EB2FD1CEB9 |
| 8086:0f12 | 1509:7018 | Intel      | Atom Processor E3800 Seri... | 2     | i2c_i801   | 9347717861 |
| 8086:0f12 | 1854:0211 | Intel      | Atom Processor E3800 Seri... | 2     | i2c_i801   | 44AF16AC16 |
| 8086:9c22 | 17aa:3978 | Intel      | 8 Series SMBus Controller    | 2     | i2c_i801   | 6CBD38B3E5 |
| 8086:9d23 | 1025:1171 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 4B0ED624FA |
| 8086:9d23 | 103c:82cb | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 009ABCD381 |
| 8086:9d23 | 1043:13c0 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | 4363CA1BD6 |
| 8086:9d23 | 1043:1410 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | C66E4999F0 |
| 8086:9d23 | 1043:16c0 | Intel      | Sunrise Point-LP SMBus       | 2     | i2c_i801   | D33E67BDF4 |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 1     | i2c_piix4  | 1785E9C758 |
| 1022:790b | 103c:86fd | AMD        | FCH SMBus Controller         | 1     | piix4_s... | 70C3FB3790 |
| 8086:0f12 | 1558:5470 | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | DD65C5ABF7 |
| 8086:0f12 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | i2c_i801   | 8F2478944C |
| 8086:1c22 | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 95C27C9FC7 |
| 8086:1e22 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | i2c_i801   | 68ECFC5409 |
| 8086:1e22 | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 5A97B2A1A7 |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | i2c_i801   | 009BEE9446 |
| 8086:27da | 14c0:006c | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | 8FF8AE3115 |
| 8086:31d4 | 17aa:3829 | Intel      | Celeron/Pentium Silver Pr... | 1     | i801_smbus | FD98FD839E |
| 8086:5ad4 |           | Intel      | Celeron N3350/Pentium N42... | 1     | i2c_i801   | 49D345EC0B |
| 8086:5ad4 | 8086:5ad4 | Intel      | Celeron N3350/Pentium N42... | 1     | i2c_i801   | D461E042A0 |
| 8086:9d23 | 1028:0702 | Intel      | Sunrise Point-LP SMBus       | 1     | i801_smbus | 229409A8DC |
| 8086:9d23 | 103c:824c | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | A557059CBA |
| 8086:9d23 | 103c:8414 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 4937A2C0A8 |
| 8086:9d23 | 17aa:2243 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | AA3F633BF5 |
| 8086:9d23 | 17aa:3833 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | 14DC838F85 |
| 8086:9d23 | 1b0a:01d3 | Intel      | Sunrise Point-LP SMBus       | 1     | i2c_i801   | C2D333A420 |
| 8086:9da3 | 1028:0895 | Intel      | Cannon Point-LP SMBus Con... | 1     | i801_smbus | FF9B284809 |
| 8086:9da3 | 103c:85b9 | Intel      | Cannon Point-LP SMBus Con... | 1     | i2c_i801   | 11BBC16301 |
| 8086:a0a3 | 17aa:508b | Intel      | Tiger Lake-LP SMBus Contr... | 1     | i2c_i801   | AAC22AF3A1 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 1     | i801_smbus | 9C72670AA1 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d70 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 62    | snd_hda... | 0E1D0B8D70 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 51    | snd_hda... | 7A294509DE |
| 8086:9c20 | 1414:9c20 | Intel      | 8 Series HD Audio Controller | 45    | snd_hda... | BA2B6488C2 |
| 8086:0a0c | 8086:0a0c | Intel      | Haswell-ULT HD Audio Cont... | 32    | snd_hda... | AC7F0D85A6 |
| 8086:34c8 | 8086:7270 | Intel      | Ice Lake-LP Smart Sound T... | 14    | snd_hda... | D34ECF1B95 |
| 1002:1314 | 1025:0577 | AMD        | Wrestler HDMI Audio          | 13    | snd_hda... | 560E2E570B |
| 1002:4383 | 1025:0577 | AMD        | SBx00 Azalia (Intel HDA)     | 13    | snd_hda... | 560E2E570B |
| 8086:0a0c | 8086:2010 | Intel      | Haswell-ULT HD Audio Cont... | 13    | snd_hda... | BA2B6488C2 |
| 8086:3198 | 1c6c:122a | Intel      | Celeron/Pentium Silver Pr... | 9     | snd_hda... | 1A8EF422E7 |
| 8086:9d71 | 152d:1182 | Intel      | Sunrise Point-LP HD Audio    | 9     | snd_hda... | 3EB69E8095 |
| 8086:9d71 | 103c:82ca | Intel      | Sunrise Point-LP HD Audio    | 7     | snd_hda... | D6AB5352B8 |
| 8086:0f04 | 1019:99a6 | Intel      | Atom Processor Z36xxx/Z37... | 5     | snd_hda... | 2548D4154B |
| 8086:0f04 | 1019:99fa | Intel      | Atom Processor Z36xxx/Z37... | 5     | snd_hda... | 36E2AE6F17 |
| 8086:1e20 | 1414:1e20 | Intel      | 7 Series/C216 Chipset Fam... | 5     | snd_hda... | 4E005ED117 |
| 8086:3198 | 17aa:3809 | Intel      | Celeron/Pentium Silver Pr... | 5     | snd_hda... | 9118598BC9 |
| 8086:9d71 | 1028:07a4 | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 45B102BEAF |
| 8086:9d71 | 103c:828b | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | 3196DC7C2A |
| 8086:9d71 | 144d:c14f | Intel      | Sunrise Point-LP HD Audio    | 5     | snd_hda... | C9D869A6A8 |
| 8086:22a8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | 53D93AFCA2 |
| 8086:5a98 | 1025:1209 | Intel      | Celeron N3350/Pentium N42... | 4     | snd_hda... | E8FB03A779 |
| 8086:9d70 | 144d:c135 | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 4E4EF907A0 |
| 8086:9d71 | 1028:081d | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 1ABEA9314A |
| 8086:9d71 | 152d:1237 | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 2618117BB7 |
| 8086:9d71 | 17aa:2244 | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | 234767F4BA |
| 8086:9d71 | 17aa:3817 | Intel      | Sunrise Point-LP HD Audio    | 4     | snd_hda... | F78D607B1F |
| 8086:160c | 17aa:222b | Intel      | Broadwell-U Audio Controller | 3     | snd_hda... | 5BADA8B921 |
| 8086:5a98 | 10ec:11ca | Intel      | Celeron N3350/Pentium N42... | 3     | snd_hda... | 23C593482C |
| 8086:9d70 | 1025:111e | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 1A171E7553 |
| 8086:9d70 | 1028:06d6 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 7A9C92F242 |
| 8086:9d70 | 1028:06e6 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 36CE9AD0C9 |
| 8086:9d70 | 10ec:114a | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 5FE3179524 |
| 8086:9d70 | 17aa:2241 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 1C271464F4 |
| 8086:9d70 | 17aa:3829 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | F590550713 |
| 8086:9d71 | 1028:07a5 | Intel      | Sunrise Point-LP HD Audio    | 3     | snd_hda... | 0325FE3F75 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 2     | snd_hda... | EB2FD1CEB9 |
| 1022:15e3 | 1022:d001 | AMD        | Family 17h (Models 10h-1f... | 2     | snd_hda... | EB2FD1CEB9 |
| 8086:0a0c | 17aa:3978 | Intel      | Haswell-ULT HD Audio Cont... | 2     | snd_hda... | 6CBD38B3E5 |
| 8086:0f04 | 1509:7018 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 9347717861 |
| 8086:0f04 | 1854:0211 | Intel      | Atom Processor Z36xxx/Z37... | 2     | snd_hda... | 44AF16AC16 |
| 8086:5a98 | 1c6c:122a | Intel      | Celeron N3350/Pentium N42... | 2     | snd_hda... | 902AD35DB3 |
| 8086:9c20 | 17aa:3978 | Intel      | 8 Series HD Audio Controller | 2     | snd_hda... | 6CBD38B3E5 |
| 8086:9d70 | 1043:13c0 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 4363CA1BD6 |
| 8086:9d70 | 19e5:3e00 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | D4C3DCBC61 |
| 8086:9d71 | 1025:1171 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 4B0ED624FA |
| 8086:9d71 | 103c:82cb | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 009ABCD381 |
| 8086:9d71 | 1043:1410 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | C66E4999F0 |
| 8086:9d71 | 1043:16c0 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | D33E67BDF4 |
| 8086:9d71 | 10ec:1082 | Intel      | Sunrise Point-LP HD Audio    | 2     | snd_hda... | 422797E8D2 |
| 1002:15de | 103c:86fd | AMD        | Raven/Raven2/Fenghuang HD... | 1     | snd_hda... | 70C3FB3790 |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | snd_hda... | 1785E9C758 |
| 1002:aa68 | 1682:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | snd_hda... | 1785E9C758 |
| 1022:15e3 | 103c:86fd | AMD        | Family 17h (Models 10h-1f... | 1     | snd_hda... | 70C3FB3790 |
| 10de:0fbc |           | Nvidia     | GM107 High Definition Aud... | 1     | snd_hda... | A557059CBA |
| 10de:0fbc | 1043:84ae | Nvidia     | GM107 High Definition Aud... | 1     | snd_hda... | 9C72670AA1 |
| 8086:02c8 | 17aa:380a | Intel      | Comet Lake PCH-LP cAVS       | 1     | snd_hda... | 6F0E0FCC43 |
| 8086:0f04 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | DD65C5ABF7 |
| 8086:0f04 | 1bab:1713 | Intel      | Atom Processor Z36xxx/Z37... | 1     | snd_hda... | 8F2478944C |
| 8086:119a |           | Intel      | Multimedia audio controller  | 1     | intel_s... | D1F5E15D8C |
| 8086:1a98 | 8086:7270 | Intel      | Smart Sound Technology (I... | 1     | snd_hda... | 555A26F0D1 |
| 8086:1c20 | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | snd_hda... | 95C27C9FC7 |
| 8086:1e20 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 68ECFC5409 |
| 8086:1e20 | 1b0a:0176 | Intel      | 7 Series/C216 Chipset Fam... | 1     | snd_hda... | 5A97B2A1A7 |
| 8086:2284 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | snd_hda... | 009BEE9446 |
| 8086:27d8 | 14c0:006c | Intel      | NM10/ICH7 Family High Def... | 1     | snd_hda... | 8FF8AE3115 |
| 8086:3198 | 10ec:1234 | Intel      | Celeron/Pentium Silver Pr... | 1     | snd_hda... | 1A6758A371 |
| 8086:3198 | 17aa:3811 | Intel      | Celeron/Pentium Silver Pr... | 1     | snd_hda... | FD98FD839E |
| 8086:5a98 | 10ec:111a | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | FBC5017959 |
| 8086:5a98 | 10ec:11d8 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 41AFF1038A |
| 8086:5a98 | 1b0a:01e6 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 49D345EC0B |
| 8086:5a98 | 8086:5a98 | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | D461E042A0 |
| 8086:9d70 | 1028:0702 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 229409A8DC |
| 8086:9d70 | 1b0a:01d3 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | C2D333A420 |
| 8086:9d71 | 103c:824c | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | A557059CBA |
| 8086:9d71 | 103c:8414 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 4937A2C0A8 |
| 8086:9d71 | 10ec:114a | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 70F839C5CB |
| 8086:9d71 | 17aa:2243 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | AA3F633BF5 |
| 8086:9d71 | 17aa:3806 | Intel      | Sunrise Point-LP HD Audio    | 1     | snd_hda... | 14DC838F85 |
| 8086:9d72 | 1028:06e6 | Intel      | 300 Series Chipset Smart ... | 1     |            | B7465A5AE4 |
| 8086:9dc8 | 1028:0895 | Intel      | Cannon Point-LP High Defi... | 1     | snd_hda... | FF9B284809 |
| 8086:9dc8 | 103c:85b9 | Intel      | Cannon Point-LP High Defi... | 1     | snd_hda... | 11BBC16301 |
| 8086:a0c8 | 17aa:508b | Intel      | Tiger Lake-LP Smart Sound... | 1     | snd_hda... | AAC22AF3A1 |
| 8086:a0c8 | 8086:7270 | Intel      | Tiger Lake-LP Smart Sound... | 1     | snd_hda... | A4AEFCD9B2 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 1     | snd_hda... | 9C72670AA1 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9c03 | 1414:9c03 | Intel      | 8 Series SATA Controller ... | 45    | ahci       | BA2B6488C2 |
| 1002:4391 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 13    | ahci       | 560E2E570B |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | ahci       | 902AD35DB3 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | ahci       | 1A6758A371 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 6     | ahci       | 5FE3179524 |
| 8086:0f23 | 1019:99a1 | Intel      | Atom Processor E3800 Seri... | 5     | ahci       | 2548D4154B |
| 8086:0f23 | 1019:99a5 | Intel      | Atom Processor E3800 Seri... | 5     | ahci       | 36E2AE6F17 |
| 8086:1e03 | 1414:1e03 | Intel      | 7 Series Chipset Family 6... | 5     | ahci       | 4E005ED117 |
| 8086:9d03 | 144d:c14f | Intel      | Sunrise Point-LP SATA Con... | 5     | ahci       | C9D869A6A8 |
| 8086:9d03 | 1028:06e6 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 36CE9AD0C9 |
| 8086:9d03 | 144d:c135 | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | 4E4EF907A0 |
| 8086:9d03 | 17aa:384d | Intel      | Sunrise Point-LP SATA Con... | 4     | ahci       | F78D607B1F |
| 8086:9c83 | 17aa:222b | Intel      | Wildcat Point-LP SATA Con... | 3     | ahci       | 5BADA8B921 |
| 8086:9d03 | 1025:111e | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 1A171E7553 |
| 8086:9d03 | 1028:06d6 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | 7A9C92F242 |
| 8086:9d03 | 103c:828b | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | D1F1D320A5 |
| 8086:9d03 | 17aa:3827 | Intel      | Sunrise Point-LP SATA Con... | 3     | ahci       | F590550713 |
| 8086:0f23 | 1509:7018 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 9347717861 |
| 8086:0f23 | 1854:0211 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 44AF16AC16 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 2     | ahci       | 6CBD38B3E5 |
| 8086:9d03 | 1028:081d | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | ECFCA15A7B |
| 8086:9d03 | 1043:13c0 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | 4363CA1BD6 |
| 8086:9d03 | 1043:1410 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | C66E4999F0 |
| 8086:9d03 | 1043:16c0 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | D33E67BDF4 |
| 8086:9d03 | 19e5:3e00 | Intel      | Sunrise Point-LP SATA Con... | 2     | ahci       | D4C3DCBC61 |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 1785E9C758 |
| 8086:0f23 | 1558:5470 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | DD65C5ABF7 |
| 8086:0f23 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | 8F2478944C |
| 8086:1e03 | 10f7:8338 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 68ECFC5409 |
| 8086:1e03 | 1b0a:017b | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 5A97B2A1A7 |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 009BEE9446 |
| 8086:27c1 | 14c0:006c | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 8FF8AE3115 |
| 8086:5ae3 |           | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | 49D345EC0B |
| 8086:5ae3 | 8086:5ae3 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | D461E042A0 |
| 8086:9d03 | 1028:0702 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 229409A8DC |
| 8086:9d03 | 1028:07a4 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 45B102BEAF |
| 8086:9d03 | 17aa:2241 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 2BC7A8E4DB |
| 8086:9d03 | 17aa:3831 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 14DC838F85 |
| 8086:9d03 | 1b0a:01d3 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | C2D333A420 |
| 8086:9dd3 | 1028:0895 | Intel      | Cannon Point-LP SATA Cont... | 1     | ahci       | FF9B284809 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 9C72670AA1 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | pata_at... | 1785E9C758 |
| 8086:1c00 | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_piix   | 95C27C9FC7 |
| 8086:1c08 | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | ata_piix   | 95C27C9FC7 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 53    | nvme       | 0E1D0B8D70 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 26    | nvme       | 234767F4BA |
| 1179:0113 | 1179:0001 | Toshiba... | BG3 NVMe SSD Controller      | 20    | nvme       | DBD940A4F3 |
| 1c5c:1327 | 1c5c:0000 | SK Hynix   | BC501 NVMe Solid State Dr... | 19    | nvme       | 8C4E9C3488 |
| 144d:a806 | 144d:a801 | Samsung... | Electronics Non-Volatile ... | 15    | nvme       | 7A294509DE |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     | Non-Volatile memory contr... | 8     | nvme       | A4AEFCD9B2 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 8     | nvme       | D0BA417102 |
| 1179:010f | 1179:0001 | Toshiba... | NVMe Controller              | 7     | nvme       | EC38221F00 |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 6     | nvme       | B2B0C29C94 |
| 1179:0116 | 1179:0001 | Toshiba... | Toshiba America Info Non-... | 5     | nvme       | 3196DC7C2A |
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 3     | nvme       | 11BBC16301 |
| 1179:0115 | 1179:0001 | Toshiba... | XG4 NVMe SSD Controller      | 2     | nvme       | 6CE5523274 |
| 1179:011a | 1179:0001 | Toshiba... | XG6 NVMe SSD Controller      | 2     | nvme       | BAA04FAF58 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 2     | nvme       | 70C3FB3790 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 7A3A0603E5 |
| 1344:5410 | 1344:0100 | Micron ... | Non-Volatile memory contr... | 1     | nvme       | 1ABEA9314A |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 1     | nvme       | 4937A2C0A8 |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 1     | nvme       | FF9B284809 |
| 15b7:5008 | 15b7:5008 | Sandisk    | Non-Volatile memory contr... | 1     | nvme       | AAC22AF3A1 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 1     | nvme       | 33FE389598 |
| 1c5c:1283 | 1c5c:0000 | SK Hynix   | PC300 NVMe Solid State Dr... | 1     | nvme       | 71F48F75D2 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | F590550713 |
| 1cc4:6204 | 1cc4:1cc4 | Union M... | Non-Volatile memory contr... | 1     | nvme       | 6F0E0FCC43 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1025:1171 | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 4B0ED624FA |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 62    |            | 0E1D0B8D70 |
| 8086:1911 | 8086:1911 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 6     |            | 5FE3179524 |
| 8086:3190 | 17aa:3802 | Intel      | Celeron/Pentium Silver Pr... | 5     |            | 9118598BC9 |
| 8086:1911 | 17aa:2244 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 4     |            | 234767F4BA |
| 8086:1911 | 17aa:2241 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 3     |            | 1C271464F4 |
| 8086:15d2 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 NHI... | 2     | thunder... | 234767F4BA |
| 8086:1193 |           | Intel      | System peripheral            | 1     |            | D1F5E15D8C |
| 8086:1194 |           | Intel      | Merrifield Serial IO SPI ... | 1     | intel_m... | D1F5E15D8C |
| 8086:1199 |           | Intel      | Merrifield GPIO Controller   | 1     | langwel... | D1F5E15D8C |
| 8086:119b |           | Intel      | System peripheral            | 1     | intel_m... | D1F5E15D8C |
| 8086:11a2 |           | Intel      | Merrifield Serial IO DMA ... | 1     | intel_m... | D1F5E15D8C |
| 8086:11a5 |           | Intel      | Merrifield Serial IO PWM ... | 1     | pwm_int... | D1F5E15D8C |
| 8086:15d2 | 103c:8414 | Intel      | JHL6540 Thunderbolt 3 NHI... | 1     | thunder... | 4937A2C0A8 |
| 8086:15eb | 103c:85b9 | Intel      | JHL7540 Thunderbolt 3 NHI... | 1     | thunder... | 11BBC16301 |
| 8086:1911 | 1028:0895 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | FF9B284809 |
| 8086:1911 | 17aa:2243 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | AA3F633BF5 |
| 8086:1911 | 17aa:3883 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 6F0E0FCC43 |
| 8086:1911 | 1b0a:01d3 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | C2D333A420 |
| 8086:3190 | 17aa:380e | Intel      | Celeron/Pentium Silver Pr... | 1     |            | FD98FD839E |
| 8086:9a11 | 17aa:508b | Intel      | GNA Scoring Accelerator m... | 1     |            | AAC22AF3A1 |

### Unclassified device (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1aa2 | 8086:7270 | Intel      | Integrated Sensor Solution   | 1     | intel_i... | 555A26F0D1 |
| 8086:31a2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_i... | 1A6758A371 |
| 8086:5aa2 |           | Intel      | Celeron N3350/Pentium N42... | 1     | intel_i... | 49D345EC0B |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d2f | 8086:7270 | Intel      | Sunrise Point-LP USB 3.0 ... | 113   | xhci_hcd   | 0E1D0B8D70 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 98    | xhci_hcd   | 3317BA664D |
| 8086:9c31 | 1414:9c31 | Intel      | 8 Series USB xHCI HC         | 45    | xhci_hcd   | BA2B6488C2 |
| 8086:22b5 | 17aa:380b | Intel      | Atom/Celeron/Pentium Proc... | 31    | xhci_hcd   | F21B55E1F7 |
| 8086:22b5 | 17aa:3806 | Intel      | Atom/Celeron/Pentium Proc... | 29    | xhci_hcd   | 4AC35C901A |
| 8086:22b7 | 8086:7270 | Intel      | USB Synopsys Controller      | 25    | dwc3_pci   | 3317BA664D |
| 8086:0f35 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 22    | xhci_hcd   | 9B7A2A3D3B |
| 8086:22b5 | 103c:827c | Intel      | Atom/Celeron/Pentium Proc... | 17    | xhci_hcd   | E5A8BA60CF |
| 8086:22b5 | 1043:13a0 | Intel      | Atom/Celeron/Pentium Proc... | 17    | xhci_hcd   | 83AE87648C |
| 8086:34ed | 8086:7270 | Intel      | Ice Lake-LP USB 3.1 xHCI ... | 14    | xhci_hcd   | D34ECF1B95 |
| 8086:8a13 |           | Intel      | Ice Lake Thunderbolt 3 US... | 14    | xhci_hcd   | D34ECF1B95 |
| 1002:4396 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 13    | ehci_hc... | 560E2E570B |
| 1002:4397 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 13    | ohci_hc... | 560E2E570B |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 13    | xhci_hcd   | 23E45B2B8E |
| 8086:9c26 | 1414:9c26 | Intel      | 8 Series USB EHCI #1         | 13    | ehci_pci   | BA2B6488C2 |
| 8086:22b5 | 1043:1400 | Intel      | Atom/Celeron/Pentium Proc... | 12    | xhci_hcd   | 0542145A63 |
| 8086:22b7 | 17aa:380a | Intel      | USB Synopsys Controller      | 11    | dwc3_pci   | 00CDB13890 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    | xhci_hcd   | 902AD35DB3 |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 10    | xhci_hcd   | 1A6758A371 |
| 8086:9d2f | 152d:1182 | Intel      | Sunrise Point-LP USB 3.0 ... | 9     | xhci_hcd   | 3EB69E8095 |
| 8086:9d2f | 103c:82ca | Intel      | Sunrise Point-LP USB 3.0 ... | 7     | xhci_hcd   | D6AB5352B8 |
| 8086:0f35 | 103c:815d | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_hcd   | 2C99AF7703 |
| 8086:0f35 | 17aa:3906 | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_hcd   | BE55ABE40D |
| 8086:0f35 | 17aa:390b | Intel      | Atom Processor Z36xxx/Z37... | 6     | xhci_hcd   | 92D4603EA8 |
| 8086:9d2f | 1043:201f | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | C66E4999F0 |
| 8086:9d2f | 8086:9d2f | Intel      | Sunrise Point-LP USB 3.0 ... | 6     | xhci_hcd   | 5FE3179524 |
| 8086:0f35 | 1019:99a1 | Intel      | Atom Processor Z36xxx/Z37... | 5     | xhci_hcd   | 2548D4154B |
| 8086:15d4 | 2222:1111 | Intel      | JHL6540 Thunderbolt 3 USB... | 5     | xhci_hcd   | 234767F4BA |
| 8086:1e26 | 1414:1e26 | Intel      | 7 Series/C216 Chipset Fam... | 5     | ehci_pci   | 4E005ED117 |
| 8086:1e2d | 1414:1e2d | Intel      | 7 Series/C216 Chipset Fam... | 5     | ehci_pci   | 4E005ED117 |
| 8086:1e31 | 1414:1e31 | Intel      | 7 Series/C210 Series Chip... | 5     | xhci_hcd   | 4E005ED117 |
| 8086:22b5 | 103c:82f4 | Intel      | Atom/Celeron/Pentium Proc... | 5     | xhci_hcd   | 1C188B150F |
| 8086:31a8 | 17aa:3812 | Intel      | Celeron/Pentium Silver Pr... | 5     | xhci_hcd   | 9118598BC9 |
| 8086:9d2f | 1028:07a4 | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 45B102BEAF |
| 8086:9d2f | 103c:828b | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | 3196DC7C2A |
| 8086:9d2f | 144d:c14f | Intel      | Sunrise Point-LP USB 3.0 ... | 5     | xhci_hcd   | C9D869A6A8 |
| 8086:0f35 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 4     | xhci_hcd   | 36E2AE6F17 |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 4     | xhci_pci   | 3B331BB4AF |
| 8086:0f37 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 4     | dwc3_pci   | F19C34B72D |
| 8086:22b5 | 1043:1c60 | Intel      | Atom/Celeron/Pentium Proc... | 4     | xhci_hcd   | A8198C3153 |
| 8086:9d2f | 1028:06e6 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 36CE9AD0C9 |
| 8086:9d2f | 1028:081d | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 1ABEA9314A |
| 8086:9d2f | 144d:c135 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 4E4EF907A0 |
| 8086:9d2f | 152d:1237 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 2618117BB7 |
| 8086:9d2f | 17aa:2244 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | 234767F4BA |
| 8086:9d2f | 17aa:3851 | Intel      | Sunrise Point-LP USB 3.0 ... | 4     | xhci_hcd   | F78D607B1F |
| 8086:0f35 | 103c:8031 | Intel      | Atom Processor Z36xxx/Z37... | 3     | xhci_hcd   | 32C0E61EA7 |
| 8086:15b6 | 2222:1111 | Intel      | DSL6540 USB 3.1 Controlle... | 3     | xhci_hcd   | FD44B61DAF |
| 8086:15db | 2222:1111 | Intel      | JHL6340 Thunderbolt 3 USB... | 3     | xhci_hcd   | 52DF26FD63 |
| 8086:9cb1 | 17aa:222b | Intel      | Wildcat Point-LP USB xHCI... | 3     | xhci_pci   | 5BADA8B921 |
| 8086:9d2f | 1025:111e | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 1A171E7553 |
| 8086:9d2f | 1028:06d6 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 7A9C92F242 |
| 8086:9d2f | 1028:07a5 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | 0325FE3F75 |
| 8086:9d2f | 17aa:2241 | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_pci   | 1C271464F4 |
| 8086:9d2f | 17aa:382c | Intel      | Sunrise Point-LP USB 3.0 ... | 3     | xhci_hcd   | F590550713 |
| 1022:15e0 | 1022:15e0 | AMD        | Raven USB 3.1                | 2     | xhci_hcd   | EB2FD1CEB9 |
| 1022:15e1 | 1022:15e1 | AMD        | Raven USB 3.1                | 2     | xhci_hcd   | EB2FD1CEB9 |
| 8086:0f34 | 1019:99a5 | Intel      | Atom Processor Z36xxx/Z37... | 2     | ehci_pci   | 4F4EFBC5C6 |
| 8086:0f35 | 1509:7018 | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci_hcd   | 9347717861 |
| 8086:0f35 | 1854:0211 | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci_hcd   | 44AF16AC16 |
| 8086:9c26 | 17aa:3978 | Intel      | 8 Series USB EHCI #1         | 2     | ehci_pci   | 6CBD38B3E5 |
| 8086:9c31 | 17aa:3978 | Intel      | 8 Series USB xHCI HC         | 2     | xhci_hcd   | 6CBD38B3E5 |
| 8086:9d2f | 1025:1171 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_pci   | 4B0ED624FA |
| 8086:9d2f | 103c:82cb | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_pci   | 009ABCD381 |
| 8086:9d2f | 19e5:3e00 | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci_hcd   | D4C3DCBC61 |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci_pci   | 1785E9C758 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_pci   | 1785E9C758 |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 1     | ohci_pci   | 1785E9C758 |
| 1002:4399 | 1025:0577 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_hc... | FD52CF4FE9 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci_pci   | 1785E9C758 |
| 1022:15e0 | 103c:86fd | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 70C3FB3790 |
| 1022:15e1 | 103c:86fd | AMD        | Raven USB 3.1                | 1     | xhci_hcd   | 70C3FB3790 |
| 1b6f:7023 | 1025:0589 | Etron T... | EJ168 USB 3.0 Host Contro... | 1     | xhci_hcd   | 95C27C9FC7 |
| 8086:02ed | 17aa:380e | Intel      | Comet Lake PCH-LP USB 3.1... | 1     | xhci_pci   | 6F0E0FCC43 |
| 8086:0f35 | 1019:980b | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | B09FE8903A |
| 8086:0f35 | 1025:0949 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | 4784D8BAAE |
| 8086:0f35 | 1558:5470 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_pci   | DD65C5ABF7 |
| 8086:0f35 | 17aa:3985 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | EDFF48D58F |
| 8086:119e |           | Intel      | Merrifield USB Device Con... | 1     | dwc3_otg   | D1F5E15D8C |
| 8086:15b5 | 2222:1111 | Intel      | DSL6340 USB 3.1 Controlle... | 1     | xhci_hcd   | 4363CA1BD6 |
| 8086:15d4 | 103c:8414 | Intel      | JHL6540 Thunderbolt 3 USB... | 1     | xhci_pci   | 4937A2C0A8 |
| 8086:15ec | 103c:85b9 | Intel      | JHL7540 Thunderbolt 3 USB... | 1     | xhci_pci   | 11BBC16301 |
| 8086:1aa8 | 8086:7270 | Intel      | USB Controller               | 1     | xhci_hcd   | 555A26F0D1 |
| 8086:1aaa | 8086:7270 | Intel      | USB Synopsys Controller      | 1     | dwc3_pci   | 555A26F0D1 |
| 8086:1c26 | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | 95C27C9FC7 |
| 8086:1c2d | 1025:0589 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci_pci   | 95C27C9FC7 |
| 8086:1e26 | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 68ECFC5409 |
| 8086:1e26 | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 5A97B2A1A7 |
| 8086:1e2d | 10f7:8338 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 68ECFC5409 |
| 8086:1e2d | 1b0a:017b | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci_pci   | 5A97B2A1A7 |
| 8086:1e31 | 10f7:8338 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 68ECFC5409 |
| 8086:1e31 | 1b0a:017b | Intel      | 7 Series/C210 Series Chip... | 1     | xhci_hcd   | 5A97B2A1A7 |
| 8086:22b5 | 1854:0280 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | A6AB074BB5 |
| 8086:22b5 | 1bfd:0001 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci_hcd   | 1BA20022CB |
| 8086:22b7 | 1854:0280 | Intel      | USB Synopsys Controller      | 1     | dwc3_pci   | A6AB074BB5 |
| 8086:27c8 | 14c0:006c | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 8FF8AE3115 |
| 8086:27c9 | 14c0:006c | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 8FF8AE3115 |
| 8086:27ca | 14c0:006c | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 8FF8AE3115 |
| 8086:27cb | 14c0:006c | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci_hcd   | 8FF8AE3115 |
| 8086:27cc | 14c0:006c | Intel      | NM10/ICH7 Family USB2 EHC... | 1     | ehci_pci   | 8FF8AE3115 |

