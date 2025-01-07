Most popular PCI devices in Mini Pcs
------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Canbus ](#canbus-pci)
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
   * [ Pic (io(x)-apic) ](#pic-iox-apic-pci)
   * [ Processing accelerators ](#processing-accelerators-pci)
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

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 1a3b:2987 | Ralink           | RT3290 Bluetooth                     | 4     |            | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 395   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1635 | 1022:1635 | AMD              | Renoir Internal PCIe GPP Bridge t... | 374   | pcieport   | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:790e | 1022:790e | AMD              | FCH LPC Bridge                       | 368   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1630 | 1022:1630 | AMD              | Renoir/Cezanne Root Complex          | 361   | ryzen_smu  | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1634 | 1022:1453 | AMD              | Renoir/Cezanne PCIe GPP Bridge       | 283   | pcieport   | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:9d84 | 8086:2074 | Intel            | Cannon Point-LP LPC Controller       | 248   |            | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:9db8 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 247   | pcieport   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:9dbc | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 247   | pcieport   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:9db0 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 242   | pcieport   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:9db6 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 242   | pcieport   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 1022:166a |           | AMD              | Cezanne Data Fabric; Function 0      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:166b |           | AMD              | Cezanne Data Fabric; Function 1      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:166c |           | AMD              | Cezanne Data Fabric; Function 2      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:166d |           | AMD              | Cezanne Data Fabric; Function 3      | 213   | k10temp    | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:166e |           | AMD              | Cezanne Data Fabric; Function 4      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:166f |           | AMD              | Cezanne Data Fabric; Function 5      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1670 |           | AMD              | Cezanne Data Fabric; Function 6      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1671 |           | AMD              | Cezanne Data Fabric; Function 7      | 213   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 182   | k10temp    | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 182   |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:1e10 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family PCI ... | 177   | pcieport   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1e12 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 176   | pcieport   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1e14 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 173   | pcieport   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1547 | 2222:1111 | Intel            | DSL3510 Thunderbolt Controller [C... | 172   | pcieport   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1e57 | 8086:7270 | Intel            | HM77 Express Chipset LPC Controller  | 172   | lpc_ich    | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:3ed0 | 8086:2074 | Intel            | 8th Gen Core Processor Host Bridg... | 172   | skl_uncore | [31F432F98B](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/0C2EAAF79393/DEBIAN-11/5.10.0-33-AMD64/X86_64/31F432F98B>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 171   |            | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:0284 | 8086:2081 | Intel            | Comet Lake PCH-LP LPC Premium Con... | 153   |            | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:5904 | 8086:2068 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 151   | skl_uncore | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9d10 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 151   | pcieport   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9d4e | 8086:2068 | Intel            | Sunrise Point LPC/eSPI Controller    | 151   |            | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:02b5 | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #14 | 149   | pcieport   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9c16 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 4     | 149   | pcieport   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9c43 | 8086:7270 | Intel            | 8 Series LPC Controller              | 149   | lpc_ich    | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:02bc | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #5  | 148   | pcieport   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:15e7 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 Bridge [Tit... | 148   | pcieport   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9c10 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 1     | 148   | pcieport   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9c14 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 3     | 148   | pcieport   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9c18 | 8086:7270 | Intel            | 8 Series PCI Express Root Port 5     | 148   | pcieport   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:0a04 | 106b:0141 | Intel            | Haswell-ULT DRAM Controller          | 146   | hsw_uncore | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9d17 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 146   | pcieport   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9d15 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 141   | pcieport   | [4760FD05FF](<Mini Pc/Intel/NUC7/NUC7i7BNHXG/F81D2DDD5350/DEBIAN-12/6.1.0-28-AMD64/X86_64/4760FD05FF>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 138   | shpchp     | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:156d |           | Intel            | DSL5520 Thunderbolt 2 Bridge [Fal... | 136   | pcieport   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |

### Canbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4bc1 | 8086:7270 | Intel            | CANBUS                               | 3     | m_can_pci  | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 8086:4bc2 | 8086:7270 | Intel            | CANBUS                               | 2     | m_can_pci  | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 242   | rtsx_pci   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 146   | rtsx_pci   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 62    | rtsx_pci   | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 10ec:525a | 8086:3004 | Realtek Semic... | RTS525A PCI Express Card Reader      | 52    | rtsx_pci   | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 51    | rtsx_pci   | [C1AA525B89](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/3F30AC0E5D22/MANJARO-24.1.1/6.10.13-3-MANJARO/X86_64/C1AA525B89>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 20    | rtsx_pci   | [28E079A0DB](<Mini Pc/AZW/GTi/GTi14/BF2DD5B4D222/MX-23/6.11.10-1-LIQUORIX-AMD64/X86_64/28E079A0DB>) |
| 1aea:6625 | 8086:2072 | Alcor Micro      | AU6625 PCI-E Flash card reader co... | 7     | alcor_pci  | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 10ec:522a | 8086:2072 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx_pci   | [73016AA2FF](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYHN/3A1BEAE58C15/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/73016AA2FF>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx_pci   | [27D189D77F](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B6171178AD06/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/27D189D77F>) |
| 10ec:522a | 103c:815a | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx_pci   | [91EF5CE3AB](<Mini Pc/Hewlett-Packard/mt42/mt42 Mobile Thin Client/759D5A0D248F/UBUNTU-24.10/6.11.0-7-GENERIC/X86_64/91EF5CE3AB>) |
| 10ec:5261 | 8086:3026 | Realtek Semic... | RTS5261 PCI Express Card Reader      | 2     | rtsx_pci   | [1B04F5768F](<Mini Pc/Intel Client Systems/NUC12/NUC12SNKi72/D9099C1F56AE/RHEL-8/4.18.0-193.EL8.X86_64/X86_64/1B04F5768F>) |
| 10ec:522a | 103c:83d0 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     | rtsx_pci   | [4F947FFED7](<Mini Pc/Hewlett-Packard/mt21/mt21 Mobile Thin Client/9C847B3CA0BB/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/4F947FFED7>) |
| 10ec:525a | 1028:06e5 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx_pci   | [50CA449B34](<Mini Pc/Intel Client Systems/NUC12/NUC12WSKi5/AB2D8A8DF699/DEBIAN-11/5.10.0-12-AMD64/X86_64/50CA449B34>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 48    | nvidia     | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:1f18 | 8086:0000 | Intel            | Atom processor C2000 QAT             | 2     |            | [C1D37659C1](<Mini Pc/Supermicro/A1/A1SAi/F097711C2215/GENTOO-2.6/5.4.86-GENTOO/X86_64/C1D37659C1>) |
| 8086:0434 | 8086:0000 | Intel            | DH89XXCC Series QAT                  | 1     |            | [372A1D69D7](<Mini Pc/AMI/Aptio/Aptio CRB/223D303B469A/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/372A1D69D7>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9de0 | 8086:2074 | Intel            | Cannon Point-LP MEI Controller #1    | 248   | mei_me     | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 177   | mei_me     | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:02e0 | 8086:2081 | Intel            | Comet Lake Management Engine Inte... | 153   | mei_me     | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 149   | mei_me     | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9d3a | 8086:2068 | Intel            | Sunrise Point-LP CSME HECI #1        | 149   | mei_me     | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9cba | 8086:2057 | Intel            | Wildcat Point-LP MEI Controller #1   | 111   | mei_me     | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | mei_me     | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 80    | mei_me     | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 78    | mei_me     | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | mei_me     | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 71    | mei_me     | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:a2ba | 103c:829a | Intel            | 200 Series PCH CSME HECI #1          | 68    | mei_me     | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:319a | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 66    | mei_me     | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:a0e0 | 8086:3004 | Intel            | Tiger Lake-LP Management Engine I... | 63    | mei_me     | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:a13a | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | mei_me     | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:51e0 | 8086:3024 | Intel            | Alder Lake PCH HECI Controller       | 60    | mei_me     | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:a360 | 17aa:312d | Intel            | Cannon Lake PCH HECI Controller      | 55    | mei_me     | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a13a | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | mei_me     | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a328 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 53    | intel_l... | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:a360 | 8086:7270 | Intel            | Cannon Lake PCH HECI Controller      | 53    | mei_me     | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:a2ba | 17aa:3111 | Intel            | 200 Series PCH CSME HECI #1          | 48    | mei_me     | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 8086:9d3a | 8086:2063 | Intel            | Sunrise Point-LP CSME HECI #1        | 42    | mei_me     | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:51e0 | 8086:3037 | Intel            | Alder Lake PCH HECI Controller       | 38    | mei_me     | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:9d3a | 8086:2070 | Intel            | Sunrise Point-LP CSME HECI #1        | 38    | mei_me     | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 8086:4de0 |           | Intel            | Management Engine Interface          | 32    | mei_me     | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    | mei_me     | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:a360 | 17aa:3136 | Intel            | Cannon Lake PCH HECI Controller      | 29    | mei_me     | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:54e0 |           | Intel            | Alder Lake-N PCH HECI Controller     | 28    | mei_me     | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:4da8 | 1043:8813 | Intel            | Jasper Lake Serial IO UART Contro... | 27    | intel_l... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:4de0 | 1043:8813 | Intel            | Management Engine Interface          | 27    | mei_me     | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:a2ba | 17aa:310b | Intel            | 200 Series PCH CSME HECI #1          | 27    | mei_me     | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 8086:a360 | 17aa:3135 | Intel            | Cannon Lake PCH HECI Controller      | 26    | mei_me     | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:a0e0 | 8086:3002 | Intel            | Tiger Lake-LP Management Engine I... | 25    | mei_me     | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:4da8 | 8086:3027 | Intel            | Jasper Lake Serial IO UART Contro... | 23    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:4de0 | 8086:3027 | Intel            | Management Engine Interface          | 23    | mei_me     | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:319a | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 21    | mei_me     | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:a2ba | 103c:829e | Intel            | 200 Series PCH CSME HECI #1          | 20    | mei_me     | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 8086:9cba | 8086:2058 | Intel            | Wildcat Point-LP MEI Controller #1   | 19    | mei_me     | [90BBA668E6](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-209/CE8A12A00B51/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/90BBA668E6>) |
| 8086:a0e0 | 8086:2090 | Intel            | Tiger Lake-LP Management Engine I... | 17    | mei_me     | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:06e0 | 17aa:316e | Intel            | Comet Lake HECI Controller           | 16    | mei_me     | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:5a9c |           | Intel            | Communication controller             | 16    |            | [30F1621D29](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/ENDLESS-6.0.2/6.5.0-10-GENERIC/X86_64/30F1621D29>) |
| 8086:5a9e |           | Intel            | Communication controller             | 16    |            | [30F1621D29](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-402/B3229CB33E06/ENDLESS-6.0.2/6.5.0-10-GENERIC/X86_64/30F1621D29>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 16    | mei_me     | [D787DD8103](<Mini Pc/AWOW/NYI/NYI3/31159C8F37C6/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/D787DD8103>) |
| 8086:4da8 |           | Intel            | Jasper Lake Serial IO UART Contro... | 15    | intel_l... | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 15    | mei_me     | [3DD81341C1](<Mini Pc/ZOTAC/ZBOX-MI/ZBOX-MI549/FAE095EB71DD/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/3DD81341C1>) |
| 8086:7aa8 | 8086:3033 | Intel            | Alder Lake-S PCH Serial IO UART #0   | 14    | intel_l... | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 8086:7ae8 | 8086:3033 | Intel            | Alder Lake-S PCH HECI Controller #1  | 14    | mei_me     | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 8086:06e0 | 19da:b440 | Intel            | Comet Lake HECI Controller           | 13    | mei_me     | [4D77EB6ED7](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C2E035EFE6A7/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/4D77EB6ED7>) |
| 8086:5a9a | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | mei_me     | [ADB65BAAA0](<Mini Pc/Intel/AB2/AB2L/AB68C201EFD4/DEBIAN-12/6.1.0-23-AMD64/X86_64/ADB65BAAA0>) |
| 8086:a0a8 |           | Intel            | Tiger Lake-LP Serial IO UART Cont... | 12    | intel_l... | [6F862E4D32](<Mini Pc/GRT/H/H90/DCFF5513ACF6/MX-23/6.1.0-17-AMD64/X86_64/6F862E4D32>) |

### Dma controller (eisa dma) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 37    | dw_dmac... | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:0f40 | 8086:0f40 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | dw_dmac... | [62ECBE2F01](<Mini Pc/AMI/Aptio/Aptio CRB/A98F6B3CA080/LUBUNTU-18.04/5.4.0-150-GENERIC/X86_64/62ECBE2F01>) |
| 8086:0f06 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [8FE291470D](<Mini Pc/NEXCOM/VTC/VTC1010/03C726F79B18/LUBUNTU-22.04/5.15.0-33-GENERIC/X86_64/8FE291470D>) |
| 8086:0f06 | 8086:0f06 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | dw_dmac... | [62ECBE2F01](<Mini Pc/AMI/Aptio/Aptio CRB/A98F6B3CA080/LUBUNTU-18.04/5.4.0-150-GENERIC/X86_64/62ECBE2F01>) |
| 8086:2286 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:22c0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | dw_dmac... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 425   | ccp        | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 127   | mei_txe    | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 99    |            | [646B14DA1E](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M625q 10TF0036GE/3BBD0A3497CB/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/646B14DA1E>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 64    | mei_txe    | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 50    | mei_txe    | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 1022:15c7 | 1f4c:b002 | AMD              | Phoenix CCP/PSP 3.0 Device           | 39    | ccp        | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 1022:1649 | 1022:1649 | AMD              | Family 19h PSP/CCP                   | 38    | ccp        | [770D05536D](<Mini Pc/AZW/EQ/EQ/798D2A4C3C0B/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/770D05536D>) |
| 1022:15c7 | 1f4c:b016 | AMD              | Phoenix CCP/PSP 3.0 Device           | 26    | ccp        | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 18    | mei_txe    | [A506460DD5](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 3030 LT/21655F011AEA/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/A506460DD5>) |
| 1022:1649 | 1043:8895 | AMD              | Family 19h PSP/CCP                   | 17    | ccp        | [C97E55F524](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53-G/DAA5FDD6B4E7/ALT-10.4/6.1.112-UN-DEF-ALT1/X86_64/C97E55F524>) |
| 8086:0f18 | 17aa:368d | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 16    | mei_txe    | [E402A3ADDE](<Mini Pc/Lenovo/E50-00/E50-00 90BX0018MB/1E28F3D9725D/DEBIAN-12/6.1.0-18-AMD64/X86_64/E402A3ADDE>) |
| 1022:15c7 | 1022:15c7 | AMD              | Phoenix CCP/PSP 3.0 Device           | 15    | ccp        | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 13    | ccp        | [B4E3FEC13D](<Mini Pc/CompuLab/fitlet-T/fitlet-T/10BBCE226DB9/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/B4E3FEC13D>) |
| 1022:15df | 103c:872e | AMD              | Family 17h (Models 10h-1fh) Platf... | 13    | ccp        | [317DA23303](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/1298BD19153A/DEBIAN-12/6.1.0-26-AMD64/X86_64/317DA23303>) |
| 1022:15df | 17aa:3190 | AMD              | Family 17h (Models 10h-1fh) Platf... | 12    | ccp        | [4F85171760](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ008NGE/AA44AB49B8FC/UBUNTU-MATE-24.04/6.8.0-45-GENERIC/X86_64/4F85171760>) |
| 8086:0f18 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 11    | mei_txe    | [F5CD797CC8](<Mini Pc/NOBLEX/N15/N15W1/561537D5DFFE/NITRUX-3.0.0/6.4.12-2-LIQUORIX-AMD64/X86_64/F5CD797CC8>) |
| 8086:2298 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | mei_txe    | [42EABEC6D0](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/AA03F426DCF7/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/42EABEC6D0>) |
| 1022:15df | 17aa:3181 | AMD              | Family 17h (Models 10h-1fh) Platf... | 8     | ccp        | [D7B1A6E8B1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/63BF4E6C46E3/DEBIAN-12/6.1.0-18-AMD64/X86_64/D7B1A6E8B1>) |
| 8086:0f18 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     | mei_txe    | [2F577EBD19](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/FC8713610F98/DEBIAN-12/6.1.0-23-AMD64/X86_64/2F577EBD19>) |
| 1022:15df | 103c:8523 | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     | ccp        | [25028B7F54](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/73B96D7CCD1E/BAZZITE-41/6.11.5-307.BAZZITE.FC41.X86_64/X86_64/25028B7F54>) |
| 1022:15df | 103c:872c | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     | ccp        | [5204129980](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/0E8F2605F090/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/5204129980>) |
| 1022:15df | 17aa:32e4 | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     | ccp        | [04721BA11C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JN000EGE/52C68CA99B3E/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/04721BA11C>) |
| 8086:2298 | 17aa:3637 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | mei_txe    | [9DF1C6E6CA](<Mini Pc/Lenovo/C20-00/C20-00 F0BB003JRK/047B6DAA7461/ROSA-12.5.1/6.6.27-GENERIC-3ROSA2021.1-X86_64/X86_64/9DF1C6E6CA>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | mei_txe    | [6C44B84E74](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/F0151650C046/ZORIN-17/6.8.0-40-GENERIC/X86_64/6C44B84E74>) |
| 8086:0f18 | 17aa:3688 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | mei_txe    | [ED37DD2BE2](<Mini Pc/Lenovo/H500s/H500s 10157/2D892CD40463/OPENSUSE-LEAP-15.6/6.4.0-150600.23.22-DEFAULT/X86_64/ED37DD2BE2>) |
| 8086:2298 | 17aa:30dd | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [EEDDC09936](<Mini Pc/Lenovo/S200z/S200z 10K5001YRU/15AD9828B67F/RED-OS-7.3.2/5.15.72-1.EL7.3.X86_64/X86_64/EEDDC09936>) |
| 8086:2298 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | mei_txe    | [1EF2A06E65](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI323/8DABD7200E9C/DEBIAN-12/6.1.0-12-AMD64/X86_64/1EF2A06E65>) |
| 1022:1649 | 1f4c:b016 | AMD              | Family 19h PSP/CCP                   | 5     | ccp        | [88BCD7AB6C](<Mini Pc/Micro Computer (HK) Tech Limited/EliteMini/EliteMini Series/5FB314C03C22/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/88BCD7AB6C>) |
| 8086:2298 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | mei_txe    | [B470C6F201](<Mini Pc/MSI/MS-B/MS-B120/3412F4B83350/UBUNTU-24.10/6.12.1-061201-GENERIC/X86_64/B470C6F201>) |
| 1022:15df | 103c:8836 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     | ccp        | [DA34E7C710](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/DD273ADCD4AF/XUBUNTU-20.04/5.8.0-53-GENERIC/X86_64/DA34E7C710>) |
| 1022:15c7 | 1d05:1721 | AMD              | Phoenix CCP/PSP 3.0 Device           | 3     | ccp        | [3137C1D2CA](<Mini Pc/MECHREVO/F7BSC/F7BSC V1.0/198D5E70E3B4/DEBIAN-12/6.10.6+BPO-AMD64/X86_64/3137C1D2CA>) |
| 1022:1649 | 1043:8870 | AMD              | Family 19h PSP/CCP                   | 3     | ccp        | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [F341B62F96](<Mini Pc/Aquarius/Tcc/Tcc Uvl U30 S25/A0CCC50D7DCA/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/F341B62F96>) |
| 8086:0f18 | 1d05:100f | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | mei_txe    | [2ECD3DD29B](<Mini Pc/Exo/Smart/Smart R8-CE/3B57C2CC34CE/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/2ECD3DD29B>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | mei_txe    | [DC85C27EC9](<Mini Pc/Hewlett-Packard/t240/t240 Thin Client/3D4E1E139019/KALI-2024.1/6.6.9-AMD64/X86_64/DC85C27EC9>) |
| 1022:15c7 | 17aa:334a | AMD              | Phoenix CCP/PSP 3.0 Device           | 2     | ccp        | [FED7DC047A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 5 12RQCTO1WW/802F91CAC000/KUBUNTU-24.04/6.8.0-39-GENERIC/X86_64/FED7DC047A>) |
| 1022:15df | 1019:ae0f | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [F4C6464F24](<Mini Pc/Daten Tecnologia/DC5/DC5A-U/1346A423AB3F/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/F4C6464F24>) |
| 1022:15df | 103c:8522 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     | ccp        | [4E0E941C5E](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/C0E792D924B5/BAZZITE-40/6.9.12-210.FSYNC.FC40.X86_64/X86_64/4E0E941C5E>) |
| 1022:15df | 103c:873a | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [5C3BE4E9AA](<Mini Pc/Hewlett-Packard/t540/t540 Thin Client/D3480EA77BCC/XUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5C3BE4E9AA>) |
| 1022:15df | 103c:8881 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     | ccp        | [D9864F2860](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G8 Desktop Mini PC/C85E0CDAD14F/ROCKY-8.7/4.18.0-425.10.1.EL8_7.X86_64/X86_64/D9864F2860>) |
| 8086:0f18 | 1028:0720 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [4C90B31924](<Mini Pc/Dell/Edge/Edge Gateway 5000/C50F3F9F774B/DEBIAN-12/6.1.0-25-AMD64/X86_64/4C90B31924>) |
| 8086:0f18 | 1028:07b9 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F444E9914B](<Mini Pc/Dell/Edge/Edge Gateway 3001/9349E7ABA493/UBUNTU-CORE-16/4.4.0-171-GENERIC/X86_64/F444E9914B>) |
| 8086:0f18 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [F2F4C5E23E](<Mini Pc/AMI/Aptio/Aptio CRB/4331D427A030/UBUNTU-18.04/5.4.0-48-GENERIC/X86_64/F2F4C5E23E>) |
| 8086:0f18 | 17aa:30b3 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [D7F55DF5B8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre E63z 10D60041HX/30A535407B9C/LINUXMINT-20/5.4.0-159-GENERIC/X86_64/D7F55DF5B8>) |
| 8086:2298 | 1019:9af1 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [71EF9C5BC6](<Mini Pc/AMI/Aptio/Aptio CRB/5DE9AB2F6049/DEVUAN-5/6.1.0-10-AMD64/X86_64/71EF9C5BC6>) |
| 8086:2298 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 222   | firewir... | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 138   | firewir... | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 21    | firewir... | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 11c1:5901 | c111:0159 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 7     | firewir... | [4AE6A646DD](<Mini Pc/Apple/Macmini6/Macmini6,1/6788160F4AC1/KALI-2024.2/6.6.15-AMD64/X86_64/4AE6A646DD>) |

### Generic system peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 99    |            | [646B14DA1E](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M625q 10TF0036GE/3BBD0A3497CB/CHIMERAOS-46-2/6.9.12-CHOS7-CHIMERAOS-1/X86_64/646B14DA1E>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3ea5 | 8086:2074 | Intel            | CoffeeLake-U GT3e [Iris Plus Grap... | 246   | i915       | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 1002:1638 | 1002:0123 | AMD              | Cezanne [Radeon Vega Series / Rad... | 199   | amdgpu     | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 122   | i915       | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 8086:0a2e | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 99    | i915       | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:0166 | 106b:00ff | Intel            | 3rd Gen Core processor Graphics C... | 96    | i915       | [E1F2728DE3](<Mini Pc/Apple/Macmini6/Macmini6,1/42E06C31CD6E/FEDORA-41/6.12.6-200.FC41.X86_64/X86_64/E1F2728DE3>) |
| 8086:9bca | 8086:2081 | Intel            | Comet Lake UHD Graphics              | 86    | i915       | [A8590C9436](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/01AA0F125F1B/FEDORA-41/6.12.4-200.FC41.X86_64/X86_64/A8590C9436>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 84    | i915       | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:0166 | 106b:0101 | Intel            | 3rd Gen Core processor Graphics C... | 77    | i915       | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:9b41 | 8086:2081 | Intel            | CometLake-U GT2 [UHD Graphics]       | 67    | i915       | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:5a85 | 8086:2067 | Intel            | HD Graphics 500                      | 65    | i915       | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:22b1 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 64    | i915       | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:5926 | 8086:2068 | Intel            | Iris Plus Graphics 640               | 64    | i915       | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:0126 | 106b:00e6 | Intel            | 2nd Generation Core Processor Fam... | 59    | i915       | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:9a49 | 8086:3004 | Intel            | TigerLake-LP GT2 [Iris Xe Graphics]  | 59    | i915       | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 1002:1636 | 1043:87e7 | AMD              | Renoir [Radeon Vega Series / Rade... | 57    | amdgpu     | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:193b | 8086:2064 | Intel            | Iris Pro Graphics 580                | 54    | i915       | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 53    | i915       | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5916 | 8086:2068 | Intel            | HD Graphics 620                      | 52    | i915       | [9319560A05](<Mini Pc/Intel/NUC7/NUC7i3BNK/54E5A6D28C1F/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/9319560A05>) |
| 8086:591b | 8086:2073 | Intel            | HD Graphics 630                      | 52    | i915       | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 10de:0861 | 106b:00ae | Nvidia           | C79 [GeForce 9400]                   | 48    | nouveau    | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:3e9b | 106b:0207 | Intel            | CoffeeLake-H GT2 [UHD Graphics 630]  | 48    | i915       | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 1002:164c | 1002:0123 | AMD              | Lucienne                             | 47    | amdgpu     | [86C93A37B2](<Mini Pc/AZW/SER/SER/621DD3B2632D/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/86C93A37B2>) |
| 8086:1912 | 103c:829a | Intel            | HD Graphics 530                      | 47    | i915       | [5A2B68B423](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/66623DC27EFC/UBUNTU-24.10/6.11.0-12-GENERIC/X86_64/5A2B68B423>) |
| 8086:0a26 | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 46    | i915       | [0316594714](<Mini Pc/Apple/Macmini7/Macmini7,1/DAA328755C92/FEDORA-40/6.12.4-100.FC40.X86_64/X86_64/0316594714>) |
| 8086:1626 | 8086:2057 | Intel            | HD Graphics 6000                     | 46    | i915       | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 1002:694c | 8086:2073 | AMD              | Polaris 22 XT [Radeon RX Vega M GH]  | 45    | amdgpu     | [BF03EA6576](<Mini Pc/Intel/NUC8/NUC8i7HVK/2B9C580F17EB/UBUNTU-24.04/6.8.0-38-GENERIC/X86_64/BF03EA6576>) |
| 10de:08a4 | 106b:00c0 | Nvidia           | MCP89 [GeForce 320M]                 | 44    | nouveau    | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:3e92 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 43    | i915       | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 1002:15bf | 1f4c:b002 | AMD              | Phoenix1                             | 39    | amdgpu     | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 8086:3185 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 600]        | 39    | i915       | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 1002:1681 | 1002:0124 | AMD              | Rembrandt [Radeon 680M]              | 38    | amdgpu     | [770D05536D](<Mini Pc/AZW/EQ/EQ/798D2A4C3C0B/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/770D05536D>) |
| 1002:9874 | 103c:8158 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 37    | amdgpu     | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 8086:1616 | 8086:2057 | Intel            | HD Graphics 5500                     | 37    | i915       | [4F40E1382C](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/04A17F0B404A/ZORIN-17/6.8.0-48-GENERIC/X86_64/4F40E1382C>) |
| 8086:46a6 | 8086:3024 | Intel            | Alder Lake-P GT2 [Iris Xe Graphics]  | 37    | i915       | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:5927 | 8086:2068 | Intel            | Iris Plus Graphics 650               | 35    | i915       | [4760FD05FF](<Mini Pc/Intel/NUC7/NUC7i7BNHXG/F81D2DDD5350/DEBIAN-12/6.1.0-28-AMD64/X86_64/4760FD05FF>) |
| 8086:5912 | 17aa:3111 | Intel            | HD Graphics 630                      | 34    | i915       | [86C67997C9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR000XGE/0E0FC76D9FC6/LINUXMINT-22/6.11.0-061100-GENERIC/X86_64/86C67997C9>) |
| 1002:98e4 | 1e50:8014 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 32    | amdgpu     | [52815E439B](<Mini Pc/ATOPNUC/MA/MA90/9664EDEE7102/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/52815E439B>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 32    | i915       | [01D751219D](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/AD866FD9F595/DEBIAN-12/6.1.0-23-AMD64/X86_64/01D751219D>) |
| 8086:162b | 8086:2057 | Intel            | Iris Graphics 6100                   | 29    | i915       | [F3B250B116](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-102/1EA24459978E/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/F3B250B116>) |
| 1002:15dd | 17aa:3130 | AMD              | Raven Ridge [Radeon Vega Series /... | 27    | amdgpu     | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 1002:6741 | 106b:00e8 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 27    | radeon     | [F220B96AA0](<Mini Pc/Apple/Macmini5/Macmini5,2/358A8F5F2FBF/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/F220B96AA0>) |
| 8086:3184 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 605]        | 27    | i915       | [73016AA2FF](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYHN/3A1BEAE58C15/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/73016AA2FF>) |
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 26    | i915       | [167B271811](<Mini Pc/BESSTAR Tech/Z83/Z83-F/81B4AA056E38/LINUXMINT-21.3/5.15.0-112-GENERIC/X86_64/167B271811>) |
| 8086:3e92 | 17aa:3136 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 26    | i915       | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 1002:9806 | 103c:17e2 | AMD              | Wrestler [Radeon HD 6320]            | 25    | radeon     | [E7DC3222F7](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A01F5CBD22D4/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/E7DC3222F7>) |
| 8086:1926 | 8086:2063 | Intel            | Iris Graphics 540                    | 25    | i915       | [63DBE4F965](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/FB12EDE50DE4/UBUNTU-22.04/6.5.0-45-GENERIC/X86_64/63DBE4F965>) |
| 8086:5912 | 103c:829a | Intel            | HD Graphics 630                      | 25    | i915       | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:a7a0 | 8086:3037 | Intel            | Raptor Lake-P [Iris Xe Graphics]     | 25    | i915       | [B3512C9EE2](<Mini Pc/Intel Client Systems/NUC13/NUC13ANHi7/FB3BFEA75C43/FEDORA-41/6.12.5-200.FC41.X86_64/X86_64/B3512C9EE2>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | i915       | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 8086:4e61 | 1e50:800f | Intel            | JasperLake [UHD Graphics]            | 24    | i915       | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |

### Iommu (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 374   |            | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 83    |            | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 1022:14e9 | 1f4c:b002 | AMD              | Phoenix IOMMU                        | 39    |            | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 1022:14b6 | 1022:14b6 | AMD              | Family 17h-19h IOMMU                 | 38    |            | [770D05536D](<Mini Pc/AZW/EQ/EQ/798D2A4C3C0B/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/770D05536D>) |
| 1022:14e9 | 1f4c:b016 | AMD              | Phoenix IOMMU                        | 26    |            | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 1022:14b6 | 1043:8895 | AMD              | Family 17h-19h IOMMU                 | 17    |            | [C97E55F524](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53-G/DAA5FDD6B4E7/ALT-10.4/6.1.112-UN-DEF-ALT1/X86_64/C97E55F524>) |
| 1022:14e9 | 1022:14e9 | AMD              | Phoenix IOMMU                        | 15    |            | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 1022:1631 | 17aa:3190 | AMD              | Renoir/Cezanne IOMMU                 | 11    |            | [4F85171760](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ008NGE/AA44AB49B8FC/UBUNTU-MATE-24.04/6.8.0-45-GENERIC/X86_64/4F85171760>) |
| 1022:15d1 | 103c:8523 | AMD              | Raven/Raven2 IOMMU                   | 7     |            | [25028B7F54](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/73B96D7CCD1E/BAZZITE-41/6.11.5-307.BAZZITE.FC41.X86_64/X86_64/25028B7F54>) |
| 1022:1631 | 17aa:32e4 | AMD              | Renoir/Cezanne IOMMU                 | 6     |            | [04721BA11C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JN000EGE/52C68CA99B3E/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/04721BA11C>) |
| 1022:14b6 | 1f4c:b016 | AMD              | Family 17h-19h IOMMU                 | 5     |            | [88BCD7AB6C](<Mini Pc/Micro Computer (HK) Tech Limited/EliteMini/EliteMini Series/5FB314C03C22/BAZZITE-41/6.11.10-304.BAZZITE.FC41.X86_64/X86_64/88BCD7AB6C>) |
| 1022:1423 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 4     |            | [19C575A4D8](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E94D038C9E51/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/19C575A4D8>) |
| 1022:14b6 | 1043:8870 | AMD              | Family 17h-19h IOMMU                 | 3     |            | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 1022:14e9 | 1d05:1721 | AMD              | Phoenix IOMMU                        | 3     |            | [3137C1D2CA](<Mini Pc/MECHREVO/F7BSC/F7BSC V1.0/198D5E70E3B4/DEBIAN-12/6.10.6+BPO-AMD64/X86_64/3137C1D2CA>) |
| 8086:1f16 | 8086:0000 | Intel            | Atom processor C2000 RCEC            | 3     |            | [9F6B0B41E9](<Mini Pc/Supermicro/A1/A1SAi/2BA9D78E414C/KALI-2023.2/6.1.0-KALI9-AMD64/X86_64/9F6B0B41E9>) |
| 1022:14e9 | 17aa:334a | AMD              | Phoenix IOMMU                        | 2     |            | [FED7DC047A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 5 12RQCTO1WW/802F91CAC000/KUBUNTU-24.04/6.8.0-39-GENERIC/X86_64/FED7DC047A>) |
| 1022:15d1 | 103c:8522 | AMD              | Raven/Raven2 IOMMU                   | 2     |            | [4E0E941C5E](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/C0E792D924B5/BAZZITE-40/6.9.12-210.FSYNC.FC40.X86_64/X86_64/4E0E941C5E>) |
| 1022:1631 | 1019:ae0f | AMD              | Renoir/Cezanne IOMMU                 | 2     |            | [F4C6464F24](<Mini Pc/Daten Tecnologia/DC5/DC5A-U/1346A423AB3F/UBUNTU-24.04/6.8.0-40-GENERIC/X86_64/F4C6464F24>) |

### Ipmi interface (kcs) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 46    |            | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10ec:816c | 17aa:3151 | Realtek Semic... | RTL8111xP IPMI interface             | 9     |            | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 10ec:816c | 103c:83dd | Realtek Semic... | RTL8111xP IPMI interface             | 7     |            | [A000EF7E0E](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/44702C600CC4/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/A000EF7E0E>) |
| 10ec:816c | 17aa:30fd | Realtek Semic... | RTL8111xP IPMI interface             | 5     |            | [C41E4D04F8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M30009US/2E7C2ABFFDEE/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/C41E4D04F8>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [3DD5227110](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/9AC0AB63F3A5/ARCH-ROLLING/6.9.7-ARCH1-1/X86_64/3DD5227110>) |
| 10ec:816c | 17aa:3181 | Realtek Semic... | RTL8111xP IPMI interface             | 3     |            | [D7B1A6E8B1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/63BF4E6C46E3/DEBIAN-12/6.1.0-18-AMD64/X86_64/D7B1A6E8B1>) |
| 10ec:816c | 103c:8620 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [08D49CD98C](<Mini Pc/Hewlett-Packard/mt45/mt45 Mobile Thin Client/A620A8DF5907/ELEMENTARY-7.1/6.8.0-40-GENERIC/X86_64/08D49CD98C>) |
| 10ec:816c | 103c:8522 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |

### Ipmi smic interface (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816c | 17aa:3130 | Realtek Semic... | RTL8111xP IPMI interface             | 29    |            | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 25    | ipmi_si    | [5204129980](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/0E8F2605F090/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/5204129980>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 248   |            | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 153   | vfio_pci   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 151   |            | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 129   |            | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:51ef |           | Intel            | Alder Lake PCH Shared SRAM           | 107   |            | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:a2a1 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family Po... | 73    |            | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:a121 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    |            | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM              | 57    |            | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 55    |            | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a121 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    |            | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 49    |            | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 48    |            | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 48    |            | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 48    |            | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 48    |            | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:a2a1 | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family Po... | 48    |            | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:9d21 | 8086:2063 | Intel            | Sunrise Point-LP PMC                 | 42    |            | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:9d21 | 8086:2070 | Intel            | Sunrise Point-LP PMC                 | 38    |            | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 32    |            | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 8086:a36f | 17aa:3136 | Intel            | Cannon Lake PCH Shared SRAM          | 29    |            | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:54ef |           | Intel            | Alder Lake-N PCH Shared SRAM         | 28    |            | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:a2a1 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family Po... | 28    |            | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 8086:4def | 1043:8813 | Intel            | Jasper Lake Shared SRAM              | 27    |            | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:a36f | 17aa:3135 | Intel            | Cannon Lake PCH Shared SRAM          | 26    |            | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 26    |            | [01C529E25C](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/F0A1DC460BE8/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/01C529E25C>) |
| 8086:a2a1 | 103c:829e | Intel            | 200 Series/Z370 Chipset Family Po... | 23    |            | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 17    |            | [3DD81341C1](<Mini Pc/ZOTAC/ZBOX-MI/ZBOX-MI549/FAE095EB71DD/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/3DD81341C1>) |
| 8086:06ef | 17aa:316e | Intel            | Comet Lake PCH Shared SRAM           | 16    |            | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 16    |            | [23DDE7A5E9](<Mini Pc/Intel Client Systems/NUC8/NUC8i3PNH/6F9877D0D4F1/DEBIAN-12/6.1.0-26-AMD64/X86_64/23DDE7A5E9>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 15    |            | [4D77EB6ED7](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C2E035EFE6A7/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/4D77EB6ED7>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 12    |            | [0BEE319571](<Mini Pc/BESSTAR Tech/U/U850/A659ABA3A179/SLACKWARE-15.0/6.12.1/X86_64/0BEE319571>) |
| 8086:a2a1 | 103c:82a5 | Intel            | 200 Series/Z370 Chipset Family Po... | 12    |            | [1A5069219B](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/BF54BF0857DB/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/1A5069219B>) |
| 8086:06ef | 103c:871a | Intel            | Comet Lake PCH Shared SRAM           | 10    |            | [C3E106F381](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/6BB6ECE7CCCC/ARCH-ROLLING/6.6.23-1-LTS/X86_64/C3E106F381>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 10    |            | [ADA7EBF233](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q Gen 2 11MY0033SP/6C7769E0369D/KUBUNTU-24.04/6.8.0-45-GENERIC/X86_64/ADA7EBF233>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 10    |            | [DC1E680DB3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/D2D0ACCE07EB/OPENMANDRIVA-23.11/6.6.2-DESKTOP-1OMV2390/X86_64/DC1E680DB3>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM              | 9     |            | [6D2A7397D1](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/15DE3F3C710F/ARCO-ROLLING/6.9.2-HARDENED1-1-HARDENED/X86_64/6D2A7397D1>) |
| 8086:a121 | 19da:b333 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [BFD62247AA](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/F5F7BF243CCA/ALPINE-3.19_ALPHA20230901/6.1.55-0-LTS/X86_64/BFD62247AA>) |
| 8086:06ef | 17aa:3172 | Intel            | Comet Lake PCH Shared SRAM           | 8     |            | [83582F654C](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DF001KUS/4CD6233315A4/DEBIAN-12/6.1.0-17-AMD64/X86_64/83582F654C>) |
| 8086:43ef | 8086:3019 | Intel            | Tiger Lake-H Shared SRAM             | 8     |            | [82B4880445](<Mini Pc/Intel Client Systems/NUC11/NUC11DBBi9/E1ADA35C85BB/DEEPIN-20.9/5.15.77-AMD64-DESKTOP/X86_64/82B4880445>) |
| 8086:02ef | 1043:87bd | Intel            | Comet Lake PCH-LP Shared SRAM        | 7     |            | [181ED93C2F](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN62/B1FA9822101A/ALT-20240122/6.6.54-UN-DEF-ALT1/X86_64/181ED93C2F>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f38 |           | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [C4198C729C](<Mini Pc/AMI/Aptio/Aptio CRB/D031FAB792D1/ROSA-2016.1/4.13.6-NRJ-DESKTOP-1ROSA-X86_64/X86_64/C4198C729C>) |

### Multimedia controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 482   | snd_pci... | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1022:15e2 | 1f4c:b002 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 39    | snd_pci... | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 1022:15e2 | 1f4c:b016 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 26    | snd_pci... | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 1022:15e2 | 1043:8895 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 17    | snd_pci... | [C97E55F524](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53-G/DAA5FDD6B4E7/ALT-10.4/6.1.112-UN-DEF-ALT1/X86_64/C97E55F524>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 12    | snd_pci... | [4F85171760](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ008NGE/AA44AB49B8FC/UBUNTU-MATE-24.04/6.8.0-45-GENERIC/X86_64/4F85171760>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     | snd_pci... | [25028B7F54](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/73B96D7CCD1E/BAZZITE-41/6.11.5-307.BAZZITE.FC41.X86_64/X86_64/25028B7F54>) |
| 1022:15e2 | 17aa:32e4 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     | snd_pci... | [04721BA11C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JN000EGE/52C68CA99B3E/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/04721BA11C>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     | intel_a... | [62ECBE2F01](<Mini Pc/AMI/Aptio/Aptio CRB/A98F6B3CA080/LUBUNTU-18.04/5.4.0-150-GENERIC/X86_64/62ECBE2F01>) |
| 8086:7d19 | 8086:7270 | Intel            | Meteor Lake IPU                      | 4     | intel_ipu6 | [28E079A0DB](<Mini Pc/AZW/GTi/GTi14/BF2DD5B4D222/MX-23/6.11.10-1-LIQUORIX-AMD64/X86_64/28E079A0DB>) |
| 1022:15e2 | 1043:8870 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 1022:15e2 | 1d05:1721 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     | snd_pci... | [3137C1D2CA](<Mini Pc/MECHREVO/F7BSC/F7BSC V1.0/198D5E70E3B4/DEBIAN-12/6.10.6+BPO-AMD64/X86_64/3137C1D2CA>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [4E0E941C5E](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/C0E792D924B5/BAZZITE-40/6.9.12-210.FSYNC.FC40.X86_64/X86_64/4E0E941C5E>) |
| 1022:15e2 | 17aa:334a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     | snd_pci... | [FED7DC047A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 5 12RQCTO1WW/802F91CAC000/KUBUNTU-24.04/6.8.0-39-GENERIC/X86_64/FED7DC047A>) |
| 8086:0f38 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | intel_a... | [8932D07801](<Mini Pc/TMAX/TM800/TM800W560L/9FF0FC2CDFA2/ZORIN-16/5.13.0-48-GENERIC/X86_64/8932D07801>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | intel_a... | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 1022:15e2 | 103c:873a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     | snd_pci... | [5C3BE4E9AA](<Mini Pc/Hewlett-Packard/t540/t540 Thin Client/D3480EA77BCC/XUBUNTU-22.04/5.15.0-56-GENERIC/X86_64/5C3BE4E9AA>) |
| 109e:0878 |           | Brooktree        | Bt878 Audio Capture                  | 1     |            | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:0f38 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | atomisp    | [0734F58B03](<Mini Pc/NOBLEX/N15/N15W1/561537D5DFFE/KUBUNTU-22.04/6.0.0-060000-GENERIC/X86_64/0734F58B03>) |
| 8086:22b8 | 103c:8623 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | intel_a... | [DC85C27EC9](<Mini Pc/Hewlett-Packard/t240/t240 Thin Client/3D4E1E139019/KALI-2024.1/6.6.9-AMD64/X86_64/DC85C27EC9>) |
| 8086:4e19 |           | Intel            | JasperLake IPU                       | 1     | intel_i... | [4D57E57019](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/F8E05E061E2B/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/4D57E57019>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 642   | r8169      | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 318   | tg3        | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:15be | 8086:2074 | Intel            | Ethernet Connection (6) I219-V       | 246   | e1000e     | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:0d4f | 8086:2081 | Intel            | Ethernet Connection (10) I219-V      | 152   | e1000e     | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:15d8 | 8086:2068 | Intel            | Ethernet Connection (4) I219-V       | 150   | e1000e     | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 138   | tg3        | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:15a3 | 8086:2057 | Intel            | Ethernet Connection (3) I218-V       | 112   | e1000e     | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 82    | r8169      | [C312F5A37C](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/0191C0AB4C2A/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/C312F5A37C>) |
| 8086:15f3 | 8086:0000 | Intel            | Ethernet Controller I225-V           | 82    | igc        | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:15e3 | 103c:829a | Intel            | Ethernet Connection (5) I219-LM      | 73    | e1000e     | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 10ec:8168 | 8086:2072 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 66    | r8169      | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:15b7 | 8086:0000 | Intel            | Ethernet Connection (2) I219-LM      | 64    | e1000e     | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 10ec:8168 | 8086:2067 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 63    | r8169      | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:15f3 | 8086:3004 | Intel            | Ethernet Controller I225-V           | 62    | igc        | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 10ec:8168 | 8086:2060 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 61    | r8169      | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:15f3 | 8086:3024 | Intel            | Ethernet Controller I225-V           | 59    | igc        | [9F5263B2E2](<Mini Pc/ASUSTek Computer/NUC12/NUC12WSH-B/E366D2D7136B/TUXEDO-24.04/6.11.0-107009-TUXEDO/X86_64/9F5263B2E2>) |
| 8086:15bc | 17aa:312d | Intel            | Ethernet Connection (7) I219-V       | 54    | e1000e     | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:15b7 | 8086:2064 | Intel            | Ethernet Connection (2) I219-LM      | 53    | e1000e     | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 48    | forcedeth  | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10ec:8168 | 1043:85b5 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 48    | r8169      | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:15b8 | 17aa:3111 | Intel            | Ethernet Connection (2) I219-V       | 48    | e1000e     | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 8086:1570 | 8086:2063 | Intel            | Ethernet Connection I219-V           | 42    | e1000e     | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 10ec:8125 | 1f4c:b002 | Realtek Semic... | RTL8125 2.5GbE Controller            | 39    | r8169      | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 14e4:1686 | 106b:0099 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 39    | tg3        | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:156f | 8086:2070 | Intel            | Ethernet Connection I219-LM          | 38    | e1000e     | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 10ec:8168 | 103c:8158 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 37    | r8169      | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 8086:125c | 8086:3037 | Intel            | Ethernet Controller I226-V           | 37    | igc        | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 10ec:8168 | 17aa:3130 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 31    | r8169      | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 30    | r8169      | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:15bb | 17aa:3136 | Intel            | Ethernet Connection (7) I219-LM      | 29    | e1000e     | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:15b7 | 17aa:310b | Intel            | Ethernet Connection (2) I219-LM      | 27    | e1000e     | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 14e4:16b1 | 103c:17e2 | Broadcom         | NetLink BCM57781 Gigabit Ethernet... | 26    | tg3        | [E7DC3222F7](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A01F5CBD22D4/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/E7DC3222F7>) |
| 8086:15bb | 17aa:3135 | Intel            | Ethernet Connection (7) I219-LM      | 26    | e1000e     | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 25    | r8169      | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:15f2 | 8086:3002 | Intel            | Ethernet Controller I225-LM          | 25    | igc        | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 10ec:8168 | 8086:3027 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 23    | r8169      | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:125c | 8086:0000 | Intel            | Ethernet Controller I226-V           | 23    | igc        | [4188B696FB](<Mini Pc/Trigkey/S/S7/BA5347E06DA7/NIXOS-25.05/6.11.11/X86_64/4188B696FB>) |
| 8086:15e3 | 103c:829e | Intel            | Ethernet Connection (5) I219-LM      | 23    | e1000e     | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 21    | sky2       | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 8086:15bb | 8086:0000 | Intel            | Ethernet Connection (7) I219-LM      | 21    | e1000e     | [01C529E25C](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/F0A1DC460BE8/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/01C529E25C>) |
| 8086:0d4d | 17aa:316e | Intel            | Ethernet Connection (11) I219-V      | 16    | e1000e     | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:15f2 | 8086:2090 | Intel            | Ethernet Controller I225-LM          | 16    | igc        | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 1d6a:14c0 | 8086:3033 | Aquantia         | AQC113C NBase-T/IEEE 802.3an Ethe... | 14    | atlantic   | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 10ec:3000 | 09a3:1028 | Realtek Semic... | Killer E3000 2.5GbE Controller       | 13    | r8169      | [4D77EB6ED7](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C2E035EFE6A7/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/4D77EB6ED7>) |
| 10ec:8168 | 103c:872e | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [317DA23303](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 405 G6 Desktop Mini PC/1298BD19153A/DEBIAN-12/6.1.0-26-AMD64/X86_64/317DA23303>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 13    | r8169      | [0A6390F528](<Mini Pc/Others/GB3/GB3B/3C8EDFAE809B/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/0A6390F528>) |
| 14e4:1686 | 14e4:9686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 13    | tg3        | [6BD8291A58](<Mini Pc/Apple/Macmini8/Macmini8,1/735A73561A9A/KUBUNTU-22.04/6.8.0-48-GENERIC/X86_64/6BD8291A58>) |
| 10ec:8168 | 103c:82a5 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 12    | r8169      | [1A5069219B](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/BF54BF0857DB/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/1A5069219B>) |
| 10ec:8168 | 17aa:3190 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 12    | r8169      | [4F85171760](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJ008NGE/AA44AB49B8FC/UBUNTU-MATE-24.04/6.8.0-45-GENERIC/X86_64/4F85171760>) |
| 14e4:1692 | 14e4:9692 | Broadcom         | NetLink BCM57780 Gigabit Ethernet... | 12    | tg3        | [3B1029927C](<Mini Pc/Hewlett-Packard/t5740e/t5740e Thin Client/B8EE2DA1CA8B/DEBIAN-12/6.1.0-23-686-PAE/I686/3B1029927C>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 263   | iwlwifi    | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 247   | iwlwifi    | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 161   | iwlwifi    | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 14e4:43a0 | 106b:013b | Broadcom Limited | BCM4360 802.11ac Dual Band Wirele... | 145   | wl         | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 141   | iwlwifi    | [4760FD05FF](<Mini Pc/Intel/NUC7/NUC7i7BNHXG/F81D2DDD5350/DEBIAN-12/6.1.0-28-AMD64/X86_64/4760FD05FF>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 132   | iwlwifi    | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 128   | iwlwifi    | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 122   | bcma       | [BF173B637E](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/BF173B637E>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 120   | iwlwifi    | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 112   | iwlwifi    | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 14e4:4331 | 106b:010e | Broadcom         | BCM4331 802.11a/b/g/n                | 109   | wl         | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 105   | r8169      | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 91    | mt7921e    | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 88    | iwlwifi    | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 73    | iwlwifi    | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 73    | iwlwifi    | [88E255BA8A](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.04/6.12.3-061203-GENERIC/X86_64/88E255BA8A>) |
| 14e4:4331 | 106b:00e4 | Broadcom Limited | BCM4331 802.11a/b/g/n                | 71    | wl         | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 61    | iwlwifi    | [83D310469E](<Mini Pc/BESSTAR Tech/GK/GK41/30CC7CA82A03/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/83D310469E>) |
| 8086:51f0 | 8086:0094 | Intel            | Alder Lake-P PCH CNVi WiFi           | 60    | iwlwifi    | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 57    | iwlwifi    | [F238160729](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/F238160729>) |
| 8086:2725 | 1a56:1674 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 50    | iwlwifi    | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 14e4:4464 | 106b:07bf | Broadcom         | BCM4364 802.11ac Wireless Network... | 49    | brcmfmac   | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 14e4:4328 | 106b:0090 | Broadcom Limited | BCM4321 802.11a/b/g/n                | 45    | ssb        | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 14e4:4353 | 106b:0093 | Broadcom         | BCM43224 802.11a/b/g/n               | 45    | wl         | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6E(802.11ax) AX210/AX1675* ... | 41    | iwlwifi    | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 40    | iwlwifi    | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 39    | iwlwifi    | [90BBA668E6](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-209/CE8A12A00B51/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/90BBA668E6>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 38    | ath10k_pci | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 35    | iwlwifi    | [C312F5A37C](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/0191C0AB4C2A/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/C312F5A37C>) |
| 10ec:c822 | 1a3b:3751 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 34    | rtw88_8... | [52815E439B](<Mini Pc/ATOPNUC/MA/MA90/9664EDEE7102/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/52815E439B>) |
| 8086:51f1 | 8086:0094 | Intel            | Raptor Lake PCH CNVi WiFi            | 34    | iwlwifi    | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 33    | iwlwifi    | [D787DD8103](<Mini Pc/AWOW/NYI/NYI3/31159C8F37C6/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/D787DD8103>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 31    | rtw88_8... | [1A7E1409B3](<Mini Pc/Shenzhen DOKE electronic/MP/MP80/E3D3F661B6A1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/1A7E1409B3>) |
| 14c3:0616 | 105b:e0cd | MediaTek         | MT7922 802.11ax PCI Express Wirel... | 30    | mt7921e    | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 30    | iwlwifi    | [36F4CCF453](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7CTO1WW/816BAB70CE9B/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/36F4CCF453>) |
| 10ec:b852 | 10ec:b852 | Realtek Semic... | RTL8852BE PCIe 802.11ax Wireless ... | 28    | rtw89_8... | [C6D2F011FA](<Mini Pc/Digma Pro/Minimax/Minimax U1 DPP5-8CXN01/11F2C32C1D33/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/C6D2F011FA>) |
| 8086:2526 | 8086:0014 | Intel            | Wi-Fi 5(802.11ac) Wireless-AC 9x6... | 25    | iwlwifi    | [08D49CD98C](<Mini Pc/Hewlett-Packard/mt45/mt45 Mobile Thin Client/A620A8DF5907/ELEMENTARY-7.1/6.8.0-40-GENERIC/X86_64/08D49CD98C>) |
| 8086:54f0 | 8086:0244 | Intel            | CNVi: Wi-Fi                          | 24    | iwlwifi    | [8F5B821532](<Mini Pc/AZW/MINI/MINI S/8D613D648E1E/UBUNTU-24.04/6.11.0-061100-GENERIC/X86_64/8F5B821532>) |
| 8086:06f0 | 8086:0070 | Intel            | Comet Lake PCH CNVi WiFi             | 23    | iwlwifi    | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:2723 | 1a56:1654 | Intel            | Wi-Fi 6 AX200                        | 22    | iwlwifi    | [4D77EB6ED7](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C2E035EFE6A7/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/4D77EB6ED7>) |
| 168c:001c | 106b:0086 | Qualcomm Atheros | AR242x / AR542x Wireless Network ... | 21    | ath5k      | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 8086:4df0 | 8086:02a4 | Intel            | Wi-Fi 6 AX201 160MHz                 | 20    | iwlwifi    | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 10ec:c822 | 17aa:c123 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 19    | rtw88_8... | [04721BA11C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JN000EGE/52C68CA99B3E/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/04721BA11C>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 19    | iwlwifi    | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:4df0 | 8086:0034 | Intel            | Wi-Fi 6 AX201 160MHz                 | 18    | iwlwifi    | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 17    | iwlwifi    | [28BF51645A](<Mini Pc/ZOTAC/ZBOX-RI323/ZBOX-RI323NANO/D0CC508105CA/LUBUNTU-16.04/4.15.0-222-GENERIC/X86_64/28BF51645A>) |
| 8086:4df0 | 8086:0074 | Intel            | Wi-Fi 6 AX201 160MHz                 | 17    | iwlwifi    | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:24fd | 8086:0110 | Intel            | Wireless 8265 / 8275                 | 15    | iwlwifi    | [693560BE85](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/65ED76199328/UBUNTU-22.04/6.8.0-47-GENERIC/X86_64/693560BE85>) |
| 8086:7af0 | 1a56:1692 | Intel            | Alder Lake-S PCH CNVi WiFi           | 14    | iwlwifi    | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 10ec:c822 | 1a3b:4210 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 13    | rtw88_8... | [0A6390F528](<Mini Pc/Others/GB3/GB3B/3C8EDFAE809B/UBUNTU-22.04/5.4.0-156-GENERIC/X86_64/0A6390F528>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 89    | r8169      | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 8086:157b | 8086:0000 | Intel            | I210 Gigabit Network Connection      | 63    | igb        | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:1539 | 8086:0000 | Intel            | I211 Gigabit Network Connection      | 42    | igb        | [40BA7BC623](<Mini Pc/AMI/Aptio/Aptio CRB/ECEB3EB9D825/DEBIAN-12/6.1.0-27-AMD64/X86_64/40BA7BC623>) |
| 8086:1533 | ffff:0000 | Intel            | I210 Gigabit Network Connection      | 40    | igb        | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 10ec:8125 | 1f4c:b016 | Realtek Semic... | RTL8125 2.5GbE Controller            | 29    | r8169      | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:4ba0 | 8086:7270 | Intel            | Ethernet controller                  | 5     | dwmac_i... | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 8086:1502 | 8086:0000 | Intel            | 82579LM Gigabit Network Connectio... | 4     | e1000e     | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:1521 | 15d9:0652 | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [8DC6B94CBD](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF-OS012/E04529F8DAEB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DC6B94CBD>) |
| 8086:1503 | 1734:11d9 | Intel            | 82579V Gigabit Network Connection    | 3     | e1000e     | [273CE0954A](<Mini Pc/Fujitsu/ESPRIMO/ESPRIMO Q510/694AE29C9C7C/DEBIAN-11/5.10.0-17-AMD64/X86_64/273CE0954A>) |
| 8086:1533 | 1ab6:0214 | Intel            | I210 Gigabit Network Connection      | 3     | igb        | [8EF2E84F50](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/285ACAA734D3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/8EF2E84F50>) |
| 8086:1539 | 8086:2080 | Intel            | I211 Gigabit Network Connection      | 3     | igb        | [D686B50BA5](<Mini Pc/Intel Client Systems/NUC8/NUC8CCHK/6D7DBA663446/DEBIAN-11/5.10.0-13-AMD64/X86_64/D686B50BA5>) |
| 14e4:5f69 | 106b:4378 | Broadcom         | BRCM4378 Bluetooth Controller        | 2     | hci_bcm... | [E6566D9C7C](<Mini Pc/Others/Apple/Apple Mac mini/294A2E5AEE79/NIXOS-23.05/6.4.0-ASAHI/AARCH64/E6566D9C7C>) |
| 8086:150c | 8086:0000 | Intel            | 82583V Gigabit Network Connection    | 2     | e1000e     | [E9512E994E](<Mini Pc/AMI/Aptio/Aptio CRB/2943B1F024BC/UBUNTU-22.04/6.2.0-31-GENERIC/X86_64/E9512E994E>) |
| 8086:4bb0 | 8086:7270 | Intel            | Ethernet controller                  | 2     | dwmac_i... | [E0C6234F77](<Mini Pc/congatec/conga-PA7/conga-PA7 A.0/FC51E41C422F/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/E0C6234F77>) |
| 001c:0008 | 001c:0005 | PEAK-System T... | Network controller                   | 1     | peak_pci   | [3EBBC89B09](<Mini Pc/congatec/conga-MA7/conga-MA7 B.4/0A4DC4D7916D/DEBIAN-11/6.5.0-0.DEB12.4-AMD64/X86_64/3EBBC89B09>) |
| 14e4:5f72 | 106b:4388 | Broadcom         | Network controller                   | 1     | hci_bcm... | [D608F4A433](<Mini Pc/Others/Apple/Apple Mac mini/2A5B757123D6/FEDORA-ASAHI-REMIX-39/6.6.3-411.ASAHI.FC39.AARCH64+16K/AARCH64/D608F4A433>) |
| 8086:1093 | 8086:0001 | Intel            | PRO/100 VM Network Connection        | 1     | e100       | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:10d3 | 8086:0000 | Intel            | 82574L Gigabit Network Connection    | 1     | e1000e     | [321433260C](<Mini Pc/AMI/Aptio/Aptio CRB/D1BBC681F9A1/UBUNTU-20.04/5.15.0-122-GENERIC/X86_64/321433260C>) |
| 8086:10fe | 17aa:3605 | Intel            | 82552 10/100 Network Connection      | 1     | e100       | [F077B2F98E](<Mini Pc/Lenovo/3000/3000 IdeaCentre Q150 10053/8A86675CFC31/UBUNTU-18.04/5.0.0-27-GENERIC/X86_64/F077B2F98E>) |
| 8086:1533 | 15bd:100a | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [593A489E8D](<Mini Pc/ARBOR/LYNC/LYNC-712/F11739CA6754/ALT-9.1/5.4.51-STD-DEF-ALT1/X86_64/593A489E8D>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [6C00869D7B](<Mini Pc/ASUSTek Computer/PN/PN41/868E1EC59BE7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6C00869D7B>) |
| 8086:1539 | 1297:4033 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [B31E28E55F](<Mini Pc/Shuttle/XS35/XS35V5/00878A051AA2/UBUNTU-19.10/5.3.0-42-GENERIC/X86_64/B31E28E55F>) |
| 8086:422b | 8086:0000 | Intel            | Centrino Ultimate-N 6300             | 1     |            | [86523F9A5F](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 3290/3455973AC1A4/LINUX-LITE-6.0/5.15.0-46-GENERIC/X86_64/86523F9A5F>) |

### Non-essential instrumentation (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 56    |            | [68A8804C89](<Mini Pc/AZW/SER/SER/17CBCB5805CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/68A8804C89>) |
| 1022:14ec | 1f4c:b002 | AMD              | Phoenix Dummy Function               | 39    |            | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 1022:14ec | 1f4c:b016 | AMD              | Phoenix Dummy Function               | 26    |            | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 1022:14ec | 1022:14ec | AMD              | Phoenix Dummy Function               | 17    |            | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 8086:a126 |           | Intel            | 100 Series/C230 Series Chipset Fa... | 6     | intel_t... | [DDF9A67ACA](<Mini Pc/ZOTAC/ZBOX-MI531/ZBOX-MI531-MI551-MI571/0DC5E3E4749B/DEBIAN-12/6.1.0-23-AMD64/X86_64/DDF9A67ACA>) |
| 1022:14ec | 1d05:1721 | AMD              | Phoenix Dummy Function               | 3     |            | [3137C1D2CA](<Mini Pc/MECHREVO/F7BSC/F7BSC V1.0/198D5E70E3B4/DEBIAN-12/6.10.6+BPO-AMD64/X86_64/3137C1D2CA>) |
| 8086:9d26 |           | Intel            | Skylake-U/Y Northpeak                | 1     | intel_t... | [D88CB8B5AE](<Mini Pc/Fanless Mini PC/PCG35/PCG35 GLK/E97F04B2B1C1/KUBUNTU-22.04/5.13.0-19-GENERIC/X86_64/D88CB8B5AE>) |

### Non-vga unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 106b:1801 | 106b:1801 | Apple            | T2 Bridge Controller                 | 49    | apple_bce  | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 106b:1802 | 106b:1802 | Apple            | T2 Secure Enclave Processor          | 49    |            | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 35    | i2c_amd... | [18AB5DC9A6](<Mini Pc/AZW/SER/SER/80F98A2B0F5C/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/18AB5DC9A6>) |
| 8086:a135 | 15d9:0898 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | intel_i... | [8DC6B94CBD](<Mini Pc/Supermicro/SYS-5039/SYS-5039MS-H12TRF-OS012/E04529F8DAEB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/8DC6B94CBD>) |
| 8086:22d8 | 8086:22d8 | Intel            | Integrated Sensor Solution           | 1     |            | [DC85C27EC9](<Mini Pc/Hewlett-Packard/t240/t240 Thin Client/3D4E1E139019/KALI-2024.1/6.6.9-AMD64/X86_64/DC85C27EC9>) |

### Performance counters (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 21    |            | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     | bdx_uncore | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     | bdx_uncore | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     | bdx_uncore | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     | bdx_uncore | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |

### Pic (io(x)-apic) (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:6f2c | 8086:0000 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 1     |            | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |

### Processing accelerators (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7d1d | 1043:88c8 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [517ED86059](<Mini Pc/ASUSTek Computer/NUC14/NUC14RVK-B/460C79B95F2B/DEBIAN/6.11.4-AMD64/X86_64/517ED86059>) |
| 8086:7d1d | 8086:7270 | Intel            | Meteor Lake NPU                      | 4     | intel_vpu  | [28E079A0DB](<Mini Pc/AZW/GTi/GTi14/BF2DD5B4D222/MX-23/6.11.10-1-LIQUORIX-AMD64/X86_64/28E079A0DB>) |
| 8086:7d1d | 2014:8009 | Intel            | Meteor Lake NPU                      | 3     | intel_vpu  | [97418C5C44](<Mini Pc/GMKtec/NucBox/NucBox K9/3071CB9AE3E2/KDE-NEON-22.04/6.8.0-45-GENERIC/X86_64/97418C5C44>) |
| 8086:7d1d | 1043:88ca | Intel            | Meteor Lake NPU                      | 1     |            | [23D1FF7D6D](<Mini Pc/ASUSTek Computer/NUC14/NUC14SRK/78C206BE09A8/ARCH-ROLLING/6.6.46-1-LTS/X86_64/23D1FF7D6D>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc | 14e4:0000 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 456   | sdhci_pci  | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 149   | sdhci_pci  | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 74    | sdhci_pci  | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 70    | sdhci_pci  | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 66    | sdhci_pci  | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | sdhci_pci  | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 1217:8621 | 8086:2073 | O2 Micro         | SD/MMC Card Reader Controller        | 62    | sdhci_pci  | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 1217:8621 | 8086:2064 | O2 Micro         | SD/MMC Card Reader Controller        | 52    | sdhci_pci  | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | sdhci_pci  | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 47    | sdhci_pci  | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | sdhci_pci  | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:9d2d | 8086:2063 | Intel            | Sunrise Point-LP Secure Digital I... | 39    | sdhci_pci  | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:2296 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 37    | sdhci_pci  | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:4dc4 |           | Intel            | Jasper Lake eMMC Controller          | 32    | sdhci_pci  | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    | sdhci_pci  | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:4df8 |           | Intel            | Jasper Lake SD Controller            | 30    | sdhci_pci  | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 1022:7906 | 1022:7806 | AMD              | FCH SD Flash Controller              | 27    | sdhci_pci  | [52815E439B](<Mini Pc/ATOPNUC/MA/MA90/9664EDEE7102/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/52815E439B>) |
| 8086:4dc4 | 1043:8813 | Intel            | Jasper Lake eMMC Controller          | 27    | sdhci_pci  | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:54c4 |           | Intel            | Alder Lake-N SD Host Controller      | 25    | sdhci_pci  | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:4dc4 | 8086:3027 | Intel            | Jasper Lake eMMC Controller          | 22    | sdhci_pci  | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [BA0B41D87C](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/C448CE9EA620/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/BA0B41D87C>) |
| 8086:5aca | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [ADB65BAAA0](<Mini Pc/Intel/AB2/AB2L/AB68C201EFD4/DEBIAN-12/6.1.0-23-AMD64/X86_64/ADB65BAAA0>) |
| 8086:5acc | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [ADB65BAAA0](<Mini Pc/Intel/AB2/AB2L/AB68C201EFD4/DEBIAN-12/6.1.0-23-AMD64/X86_64/ADB65BAAA0>) |
| 8086:5ad0 | 8086:1e8b | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [ADB65BAAA0](<Mini Pc/Intel/AB2/AB2L/AB68C201EFD4/DEBIAN-12/6.1.0-23-AMD64/X86_64/ADB65BAAA0>) |
| 8086:2295 | 1028:07c1 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | sdhci_pci  | [42EABEC6D0](<Mini Pc/Dell/Wyse/Wyse 3040 Thin Client/AA03F426DCF7/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/42EABEC6D0>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 10    | sdhci_pci  | [321433260C](<Mini Pc/AMI/Aptio/Aptio CRB/D1BBC681F9A1/UBUNTU-20.04/5.15.0-122-GENERIC/X86_64/321433260C>) |
| 17a0:9755 | 8086:3004 | Genesys Logic    | GL9755 SD Host Controller            | 9     | sdhci_pci  | [7232D92C69](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/E0ECB94FBAC3/DEBIAN-11/5.10.0-21-AMD64/X86_64/7232D92C69>) |
| 1217:8520 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 8     | sdhci_pci  | [71009C6209](<Mini Pc/ZOTAC/ZBOX-EN3740/ZBOX-EN374070C/6435D8892050/UBUNTU-MATE-24.04/6.8.0-35-GENERIC/X86_64/71009C6209>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 8     | sdhci_pci  | [CB9ACD742E](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/A9C09A7F82E5/DEBIAN-12/6.8.12-1-PVE/X86_64/CB9ACD742E>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | sdhci_pci  | [BA0B41D87C](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/C448CE9EA620/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/BA0B41D87C>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake eMMC Controller          | 7     | sdhci_pci  | [6D2A7397D1](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/15DE3F3C710F/ARCO-ROLLING/6.9.2-HARDENED1-1-HARDENED/X86_64/6D2A7397D1>) |
| 8086:4df8 | 8086:7270 | Intel            | Jasper Lake SD Controller            | 7     | sdhci_pci  | [6D2A7397D1](<Mini Pc/Chuwi/HeroBox/HeroBox Pro/15DE3F3C710F/ARCO-ROLLING/6.9.2-HARDENED1-1-HARDENED/X86_64/6D2A7397D1>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 6     | sdhci_pci  | [0BEE319571](<Mini Pc/BESSTAR Tech/U/U850/A659ABA3A179/SLACKWARE-15.0/6.12.1/X86_64/0BEE319571>) |
| 8086:5acc | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [72CDAF6B97](<Mini Pc/Intel/NUC6/NUC6CAYS/150D2AC24183/DEBIAN-12/6.1.0-21-AMD64/X86_64/72CDAF6B97>) |
| 8086:0f16 | 19da:b219 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 5     | sdhci_pci  | [CB9ACD742E](<Mini Pc/ZOTAC/ZBOX-CI320NANO/ZBOX-CI320NANO series/A9C09A7F82E5/DEBIAN-12/6.8.12-1-PVE/X86_64/CB9ACD742E>) |
| 8086:2294 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [B470C6F201](<Mini Pc/MSI/MS-B/MS-B120/3412F4B83350/UBUNTU-24.10/6.12.1-061201-GENERIC/X86_64/B470C6F201>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | sdhci_pci  | [89EFFD522F](<Mini Pc/AMI/Aptio/Aptio CRB/EE0E4CF77196/DEBIAN-12/6.1.0-13-AMD64/X86_64/89EFFD522F>) |
| 14e4:16bc | 14e4:96bc | Broadcom Limited | BCM57765/57785 SDXC/MMC Card Reader  | 4     | sdhci_pci  | [A093B3B3DD](<Mini Pc/Apple/Macmini8/Macmini8,1/98F02F8D9CF1/MANJARO-24.0.0/6.9.0-2-MANJARO/X86_64/A093B3B3DD>) |
| 8086:0f50 | 8086:7270 | Intel            | Atom Processor E3800 Series eMMC ... | 4     | sdhci_pci  | [A506460DD5](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 3030 LT/21655F011AEA/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/A506460DD5>) |
| 8086:2294 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | sdhci_pci  | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | sdhci_pci  | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 8086:5aca | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [F55EB84442](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI225/A1AD3A1F0C59/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/F55EB84442>) |
| 8086:5acc | 19da:b342 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [F55EB84442](<Mini Pc/ZOTAC/ZBOX-PI/ZBOX-PI225/A1AD3A1F0C59/OPENMANDRIVA-24.07/6.9.7-DESKTOP-1OMV2490/X86_64/F55EB84442>) |
| 1022:7806 | 19da:a261 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |
| 1022:7806 | 19da:b218 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [08840508A8](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/EB7C0132389E/ZORIN-17/6.5.0-35-GENERIC/X86_64/08840508A8>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [B4E3FEC13D](<Mini Pc/CompuLab/fitlet-T/fitlet-T/10BBCE226DB9/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/B4E3FEC13D>) |
| 8086:2294 | 19da:b273 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [0D05B404DD](<Mini Pc/ZOTAC/ZBOX-BI/ZBOX-BI324/C214E8207F22/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0D05B404DD>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [10C1838B9D](<Mini Pc/AMI/Aptio/Aptio CRB/6C7827486731/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C1838B9D>) |
| 8086:31cc | 103c:83c3 | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [EC89883EF7](<Mini Pc/Hewlett-Packard/t430/t430 Thin Client/5698BAEF3ADF/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/EC89883EF7>) |
| 8086:4b47 | 8086:7270 | Intel            | Atom SD Host Controller              | 3     | sdhci_pci  | [3EBBC89B09](<Mini Pc/congatec/conga-MA7/conga-MA7 B.4/0A4DC4D7916D/DEBIAN-11/6.5.0-0.DEB12.4-AMD64/X86_64/3EBBC89B09>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 248   | spi_int... | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 153   | spi_int... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 153   | intel_l... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 153   | intel_l... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:4dab |           | Intel            | Jasper Lake Serial IO SPI Control... | 65    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:a0a4 | 8086:3004 | Intel            | Tiger Lake-LP SPI Controller         | 63    | spi_int... | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:a0e8 | 8086:3004 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 63    | intel_l... | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:51a4 | 8086:3024 | Intel            | Alder Lake-P PCH SPI Controller      | 60    | spi_int... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:51e8 | 8086:3024 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 60    | intel_l... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:51e9 | 8086:3024 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 60    | intel_l... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 55    | spi_int... | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 53    | spi_int... | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | pwm_lpss   | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:51a4 | 8086:3037 | Intel            | Alder Lake-P PCH SPI Controller      | 38    | spi_int... | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:51e8 | 8086:3037 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 38    | intel_l... | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:51e9 | 8086:3037 | Intel            | Alder Lake PCH Serial IO I2C Cont... | 38    | intel_l... | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:22c6 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 37    | i2c_des... | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:22c7 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 37    | i2c_des... | [7A4E426512](<Mini Pc/Intel/NUC5PGYB/NUC5PGYB H78167-102/E551A2C0F3DD/VANILLA-2.0/6.10.9-AMD64/X86_64/7A4E426512>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 32    | spi_int... | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 8086:a324 | 17aa:3136 | Intel            | Cannon Lake PCH SPI Controller       | 29    | spi_int... | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:54a4 |           | Intel            | Alder Lake-N SPI (flash) Controller  | 28    | spi_int... | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:4da4 | 1043:8813 | Intel            | Jasper Lake SPI Controller           | 27    | spi_int... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:4dc5 | 1043:8813 | Intel            | Jasper Lake Serial IO I2C Host Co... | 27    | intel_l... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:4dc6 | 1043:8813 | Intel            | Jasper Lake Serial IO I2C Host Co... | 27    | intel_l... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:4de8 | 1043:8813 | Intel            | Jasper Lake Serial IO I2C Host Co... | 27    | intel_l... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:4dea | 1043:8813 | Intel            | Jasper Lake Serial IO I2C Host Co... | 27    | intel_l... | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:a324 | 17aa:3135 | Intel            | Cannon Lake PCH SPI Controller       | 26    | intel_spi  | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:a0a4 | 8086:3002 | Intel            | Tiger Lake-LP SPI Controller         | 25    | spi_int... | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:a0e8 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 25    | intel_l... | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:54c5 |           | Intel            | Serial bus controller                | 24    | intel_l... | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:54c6 |           | Intel            | Serial bus controller                | 24    | intel_l... | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:54e8 |           | Intel            | Alder Lake-N Other Interface         | 24    | intel_l... | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:4da4 | 8086:3027 | Intel            | Jasper Lake SPI Controller           | 23    | spi_int... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:4dc5 | 8086:3027 | Intel            | Jasper Lake Serial IO I2C Host Co... | 23    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:4dc6 | 8086:3027 | Intel            | Jasper Lake Serial IO I2C Host Co... | 23    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:4de8 | 8086:3027 | Intel            | Jasper Lake Serial IO I2C Host Co... | 23    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:4dea | 8086:3027 | Intel            | Jasper Lake Serial IO I2C Host Co... | 23    | intel_l... | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:a0e9 | 8086:3002 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 22    | intel_l... | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:a0a4 | 8086:2090 | Intel            | Tiger Lake-LP SPI Controller         | 17    | intel_spi  | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:a0e8 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 17    | intel_lpss | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:a0e9 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 17    | intel_lpss | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:06a4 | 17aa:316e | Intel            | Comet Lake PCH SPI Controller        | 16    | spi_int... | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:31c8 | 8086:7270 | Intel            | Serial bus controller                | 16    | pwm_lpss   | [01D751219D](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/AD866FD9F595/DEBIAN-12/6.1.0-23-AMD64/X86_64/01D751219D>) |
| 10de:1adb | 8086:2090 | Nvidia           | TU106 USB Type-C UCSI Controller     | 15    | i2c_nvi... | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:4de8 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 15    | intel_l... | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:4de9 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 15    | intel_l... | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:4dea |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 15    | intel_l... | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | pwm_lpss   | [9D9A814FFB](<Mini Pc/CompuLab/fitlet/fitlet2/FE9990A90ADA/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/9D9A814FFB>) |
| 8086:4dc5 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 14    | intel_lpss | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |
| 8086:4dc6 |           | Intel            | Jasper Lake Serial IO I2C Host Co... | 14    | intel_lpss | [AAA2F63111](<Mini Pc/BYTENUC/AZ/AZ51/1A77C2AC53A8/FEDORA-40/6.10.9-200.FC40.X86_64/X86_64/AAA2F63111>) |

### Serial controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a2bd | 103c:829a | Intel            | 200 Series Chipset Family KT Redi... | 68    | serial     | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 10ec:816a | 1043:85b5 | Realtek Semic... | RTL8111xP UART #1                    | 46    | serial     | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10ec:816b | 1043:85b5 | Realtek Semic... | RTL8111xP UART #2                    | 46    | serial     | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10ec:816a | 17aa:3130 | Realtek Semic... | RTL8111xP UART #1                    | 29    | serial     | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 10ec:816b | 17aa:3130 | Realtek Semic... | RTL8111xP UART #2                    | 29    | serial     | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 8086:9d3d | 8086:2070 | Intel            | Sunrise Point-LP Active Managemen... | 29    | serial     | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 8086:a363 | 17aa:3136 | Intel            | Cannon Lake PCH Active Management... | 27    | serial     | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 10ec:816a | 10ec:8168 | Realtek Semic... | RTL8111xP UART #1                    | 25    | serial     | [5204129980](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/0E8F2605F090/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/5204129980>) |
| 8086:a363 | 17aa:3135 | Intel            | Cannon Lake PCH Active Management... | 24    | serial     | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:a2bd | 17aa:310b | Intel            | 200 Series Chipset Family KT Redi... | 23    | serial     | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 8086:a2bd | 103c:829e | Intel            | 200 Series Chipset Family KT Redi... | 20    | serial     | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 8086:a0e3 | 8086:3003 | Intel            | Tiger Lake-LP Active Management T... | 11    | serial     | [68E4F41DE9](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv5/19F5B126590F/DEBIAN-12/6.1.0-23-AMD64/X86_64/68E4F41DE9>) |
| 10ec:816a | 17aa:3151 | Realtek Semic... | RTL8111xP UART #1                    | 9     | serial     | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 10ec:816b | 17aa:3151 | Realtek Semic... | RTL8111xP UART #2                    | 9     | serial     | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 8086:06e3 | 103c:871a | Intel            | Comet Lake Keyboard and Text (KT)... | 9     | serial     | [C3E106F381](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/6BB6ECE7CCCC/ARCH-ROLLING/6.6.23-1-LTS/X86_64/C3E106F381>) |
| 8086:06e3 | 17aa:3172 | Intel            | Comet Lake Keyboard and Text (KT)... | 8     | serial     | [83582F654C](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DF001KUS/4CD6233315A4/DEBIAN-12/6.1.0-17-AMD64/X86_64/83582F654C>) |
| 10ec:816a | 103c:83dd | Realtek Semic... | RTL8111xP UART #1                    | 7     | serial     | [A000EF7E0E](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/44702C600CC4/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/A000EF7E0E>) |
| 10ec:816b | 103c:83dd | Realtek Semic... | RTL8111xP UART #2                    | 7     | serial     | [A000EF7E0E](<Mini Pc/Hewlett-Packard/mt44/mt44 Mobile Thin Client/44702C600CC4/UBUNTU-24.04/6.8.0-31-GENERIC/X86_64/A000EF7E0E>) |
| 8086:06e3 | 103c:8715 | Intel            | Comet Lake Keyboard and Text (KT)... | 7     | serial     | [DCAF1A5094](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/7A21AB2D0D5E/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/DCAF1A5094>) |
| 8086:a13d | 103c:82c0 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | serial     | [F6987473A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/593502302703/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/F6987473A1>) |
| 8086:a363 | 8086:2088 | Intel            | Cannon Lake PCH Active Management... | 6     | serial     | [01C529E25C](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/F0A1DC460BE8/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/01C529E25C>) |
| 10ec:816a | 17aa:30fd | Realtek Semic... | RTL8111xP UART #1                    | 5     | serial     | [C41E4D04F8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M30009US/2E7C2ABFFDEE/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/C41E4D04F8>) |
| 10ec:816b | 17aa:30fd | Realtek Semic... | RTL8111xP UART #2                    | 5     | serial     | [C41E4D04F8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10M30009US/2E7C2ABFFDEE/UBUNTU-22.04/6.5.0-26-GENERIC/X86_64/C41E4D04F8>) |
| 8086:a2bd | 17aa:310c | Intel            | 200 Series Chipset Family KT Redi... | 5     | serial     | [EB3FF37603](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C1S0160C/1E797AA92C48/ENDEAVOUROS-ROLLING/6.12.6-ARCH1-1/X86_64/EB3FF37603>) |
| 10ec:816a | 103c:8523 | Realtek Semic... | RTL8111xP UART #1                    | 4     | serial     | [3DD5227110](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/9AC0AB63F3A5/ARCH-ROLLING/6.9.7-ARCH1-1/X86_64/3DD5227110>) |
| 10ec:816b | 103c:8523 | Realtek Semic... | RTL8111xP UART #2                    | 4     | serial     | [3DD5227110](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/9AC0AB63F3A5/ARCH-ROLLING/6.9.7-ARCH1-1/X86_64/3DD5227110>) |
| 8086:06e3 | 103c:8710 | Intel            | Comet Lake Keyboard and Text (KT)... | 4     | serial     | [BE32ECBA69](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/F01F267484F7/XERO-ROLLING/6.6.4-ARCH1-1/X86_64/BE32ECBA69>) |
| 8086:7e45 | 1043:88c8 | Intel            | Meteor Lake-P Integrated Sensor Hub  | 4     | intel_i... | [517ED86059](<Mini Pc/ASUSTek Computer/NUC14/NUC14RVK-B/460C79B95F2B/DEBIAN/6.11.4-AMD64/X86_64/517ED86059>) |
| 8086:a363 | 8086:7270 | Intel            | Cannon Lake PCH Active Management... | 4     | serial     | [F6A1D71984](<Mini Pc/CompuLab/Airtop/Airtop3/5F4EB4EF9A37/LINUXMINT-21.3/6.8.1-060801-GENERIC/X86_64/F6A1D71984>) |
| 10ec:816a | 17aa:3181 | Realtek Semic... | RTL8111xP UART #1                    | 3     | serial     | [D7B1A6E8B1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/63BF4E6C46E3/DEBIAN-12/6.1.0-18-AMD64/X86_64/D7B1A6E8B1>) |
| 8086:1e3d | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 3     | serial     | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:9de3 | 17aa:314c | Intel            | Cannon Point-LP Keyboard and Text... | 3     | serial     | [D219A806AA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AMS07K00/1084B1DAC405/UBUNTU-CORE-22/5.15.0-76-GENERIC/X86_64/D219A806AA>) |
| 8086:9de3 | 8086:2096 | Intel            | Cannon Point-LP Keyboard and Text... | 3     | serial     | [1C0A54696F](<Mini Pc/Intel Client Systems/NUC8/NUC8v7PNH/971A07F5CF5B/UBUNTU-22.04/6.8.0-45-GENERIC/X86_64/1C0A54696F>) |
| 10ec:816a | 103c:8620 | Realtek Semic... | RTL8111xP UART #1                    | 2     | serial     | [08D49CD98C](<Mini Pc/Hewlett-Packard/mt45/mt45 Mobile Thin Client/A620A8DF5907/ELEMENTARY-7.1/6.8.0-40-GENERIC/X86_64/08D49CD98C>) |
| 10ec:816b | 103c:8620 | Realtek Semic... | RTL8111xP UART #2                    | 2     | serial     | [08D49CD98C](<Mini Pc/Hewlett-Packard/mt45/mt45 Mobile Thin Client/A620A8DF5907/ELEMENTARY-7.1/6.8.0-40-GENERIC/X86_64/08D49CD98C>) |
| 8086:06e3 | 103c:8711 | Intel            | Comet Lake Keyboard and Text (KT)... | 2     | serial     | [DD252958EA](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G6 Desktop Mini PC/9619805E9D55/DEBIAN-12/6.1.0-21-AMD64/X86_64/DD252958EA>) |
| 8086:06e3 | 17aa:316c | Intel            | Comet Lake Keyboard and Text (KT)... | 2     | serial     | [5106B27020](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M80q 11DQS2NU09/51908D93D66A/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/5106B27020>) |
| 8086:43e3 | 17aa:32dd | Intel            | Tiger Lake AMT SOL Redirection       | 2     | serial     | [DB2BF2ECF2](<Mini Pc/Lenovo/ThinkStation/ThinkStation P350 Tiny 30EF000NUK/F08EC2ADB6ED/FEDORA-40/6.8.7-300.FC40.X86_64/X86_64/DB2BF2ECF2>) |
| 8086:54fc |           | Intel            | Alder Lake-N Integrated Sensor So... | 2     | intel_i... | [0622406385](<Mini Pc/SHENZHEN YOUDISI E-COMMERCE/M/M1/0B9F5AEEE8AF/DEBIAN-12/6.8.8-4-PVE/X86_64/0622406385>) |
| 8086:7aeb | 103c:894f | Intel            | Alder Lake-S Keyboard and Text (K... | 2     | serial     | [A8F31F2C15](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 800 G9 Desktop PC/5E0700453162/CENTOS-7/3.10.0-1160.108.1.EL7.X86_64/X86_64/A8F31F2C15>) |
| 8086:7aeb | 103c:8952 | Intel            | Alder Lake-S Keyboard and Text (K... | 2     | serial     | [5A5C598609](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 600 G9 Desktop PC/22343F6ECC6C/DEBIAN-12/6.1.0-23-AMD64/X86_64/5A5C598609>) |
| 8086:7aeb | 17aa:3309 | Intel            | Alder Lake-S Keyboard and Text (K... | 2     | serial     | [DCEF7100E1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M80q Gen 3 11U2S00W00/FC5934C93DF0/ELEMENTARY-7.1/6.5.0-41-GENERIC/X86_64/DCEF7100E1>) |
| 8086:8c3d | 103c:2145 | Intel            | 8 Series/C220 Series Chipset Fami... | 2     | serial     | [9C26D1B3DD](<Mini Pc/Hewlett-Packard/t820/t820 Flexible Thin Client/94B86B15DFFF/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/9C26D1B3DD>) |
| 8086:9c3d | 8086:7270 | Intel            | 8 Series HECI KT                     | 2     | serial     | [41E5FEECD5](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/99D07E01E379/UBUNTU-24.04/6.8.0-44-GENERIC/X86_64/41E5FEECD5>) |
| 8086:9cbd | 8086:2058 | Intel            | Wildcat Point-LP KT Controller       | 2     | serial     | [E904EF7A24](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-202/7B4D2C094AB2/FEDORA-37/6.0.8-300.FC37.X86_64/X86_64/E904EF7A24>) |
| 8086:9d3d | 8086:1999 | Intel            | Sunrise Point-LP Active Managemen... | 2     | serial     | [3DD81341C1](<Mini Pc/ZOTAC/ZBOX-MI/ZBOX-MI549/FAE095EB71DD/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/3DD81341C1>) |
| 10ec:816a | 103c:8522 | Realtek Semic... | RTL8111xP UART #1                    | 1     | serial     | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 10ec:816b | 103c:8522 | Realtek Semic... | RTL8111xP UART #2                    | 1     | serial     | [28B79EA28B](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/84561BBF7057/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/28B79EA28B>) |
| 10ec:816b | 10ec:8168 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [5DD127A865](<Mini Pc/Daten Tecnologia/DC2/DC2C-U/DEAB1E021B3F/LINUXMINT-19/4.15.0-20-GENERIC/X86_64/5DD127A865>) |
| 13a8:0354 |           | Exar             | Exar's 4-Port UART PCIe Card         | 1     | 8250_exar  | [FF584585FE](<Mini Pc/Congatec/conga-B7/conga-B7XD/AE6B8E18D583/DEBIAN-12/6.1.0-18-AMD64/X86_64/FF584585FE>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9df9 | 8086:2074 | Intel            | Cannon Point-LP Thermal Controller   | 248   | intel_p... | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:02f9 | 8086:2081 | Intel            | Comet Lake Thermal Subsytem          | 153   | intel_p... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9d31 | 8086:2068 | Intel            | Sunrise Point-LP Thermal subsystem   | 151   | intel_p... | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 89    | process... | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:467d |           | Intel            | Platform Monitoring Technology       | 89    | intel_vsec | [89BD7EAC30](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q Gen 4 12E3004LGE/376C069BD652/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/89BD7EAC30>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 80    | amd_sfh    | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 76    | intel_l... | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 76    | intel_l... | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:a2b1 | 103c:829a | Intel            | 200 Series PCH Thermal Subsystem     | 73    |            | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:5abc |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 70    | intel_l... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:5ac4 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 70    | intel_l... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:5ac6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 70    | intel_l... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 66    | process... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5aac | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | intel_l... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:5ac2 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | intel_l... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:a127 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | intel_l... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a131 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | intel_p... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a160 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | intel_l... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a161 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | intel_l... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a162 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | intel_l... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 59    | process... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:a77d |           | Intel            | Raptor Lake Crashlog and Telemetry   | 57    | intel_vsec | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 54    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:a131 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | intel_p... | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a379 | 8086:7270 | Intel            | Cannon Lake PCH Thermal Controller   | 53    | intel_p... | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 52    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 52    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 52    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 49    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 49    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:a2b1 | 17aa:3111 | Intel            | 200 Series PCH Thermal Subsystem     | 48    |            | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 47    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 42    | intel_l... | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:9d27 | 8086:2063 | Intel            | Sunrise Point-LP Serial IO UART C... | 42    | intel_l... | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:9d31 | 8086:2063 | Intel            | Sunrise Point-LP Thermal subsystem   | 42    | intel_p... | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 39    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    | intel_l... | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 368   | i2c_piix4  | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:9da3 | 8086:2074 | Intel            | Cannon Point-LP SMBus Controller     | 248   | i2c_i801   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 177   | i2c_i801   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:02a3 | 8086:2081 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 153   | i2c_i801   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9d23 | 8086:2068 | Intel            | Sunrise Point-LP SMBus               | 151   | i2c_i801   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 149   | i801_smbus | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9ca2 | 8086:2057 | Intel            | Wildcat Point-LP SMBus Controller    | 112   | i2c_i801   | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | i2c_i801   | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 80    | i2c_i801   | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | i2c_i801   | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:a2a3 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family SM... | 73    | i2c_i801   | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 71    | i2c_i801   | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 70    | i2c_i801   | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 8086:31d4 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 66    | i2c_i801   | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:5ad4 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | i2c_i801   | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:2292 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 64    | i2c_i801   | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:a0a3 | 8086:3004 | Intel            | Tiger Lake-LP SMBus Controller       | 63    | i2c_i801   | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:a123 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | i2c_i801   | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:51a3 | 8086:3024 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 60    | i2c_i801   | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 1022:790b | 1043:87e7 | AMD              | FCH SMBus Controller                 | 57    | i2c_piix4  | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:a323 | 17aa:312d | Intel            | Cannon Lake PCH SMBus Controller     | 55    | i2c_i801   | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a123 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | i801_smbus | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a323 | 8086:7270 | Intel            | Cannon Lake PCH SMBus Controller     | 53    | i2c_i801   | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 48    | i2c_nfo... | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:a2a3 | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family SM... | 48    | i2c_i801   | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 10de:0d79 | 10de:cb89 | Nvidia           | MCP89 SMBus                          | 44    |            | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:9d23 | 8086:2063 | Intel            | Sunrise Point-LP SMBus               | 42    | i2c_i801   | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 1022:790b | 1f4c:b002 | AMD              | FCH SMBus Controller                 | 39    | piix4_s... | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 8086:51a3 | 8086:3037 | Intel            | Alder Lake PCH-P SMBus Host Contr... | 38    | i2c_i801   | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:9d23 | 8086:2070 | Intel            | Sunrise Point-LP SMBus               | 38    | i2c_i801   | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 1022:790b | 103c:8158 | AMD              | FCH SMBus Controller                 | 37    | i2c_piix4  | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 1022:790b | 1043:880a | AMD              | FCH SMBus Controller                 | 34    | i2c_piix4  | [195B7AC36C](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN52/7A9FE09D067A/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/195B7AC36C>) |
| 8086:4da3 |           | Intel            | Jasper Lake SMBus                    | 32    | i2c_i801   | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 1022:790b | 17aa:3130 | AMD              | FCH SMBus Controller                 | 31    | i2c_pii... | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 1022:790b | 1f4c:b016 | AMD              | FCH SMBus Controller                 | 31    | i2c_piix4  | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:31d4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    | i2c_i801   | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:a323 | 17aa:3136 | Intel            | Cannon Lake PCH SMBus Controller     | 29    | i2c_i801   | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:54a3 |           | Intel            | Alder Lake-N SMBus                   | 28    | i2c_i801   | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:a2a3 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family SM... | 28    | i2c_i801   | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 8086:4da3 | 1043:8813 | Intel            | Jasper Lake SMBus                    | 27    | i2c_i801   | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 1002:4385 | 103c:17e2 | AMD              | SBx00 SMBus Controller               | 26    | i2c_piix4  | [E7DC3222F7](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/A01F5CBD22D4/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/E7DC3222F7>) |
| 8086:a323 | 17aa:3135 | Intel            | Cannon Lake PCH SMBus Controller     | 26    | i2c_i801   | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:a0a3 | 8086:3002 | Intel            | Tiger Lake-LP SMBus Controller       | 25    | i2c_i801   | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | i2c_i801   | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 8086:4da3 | 8086:3027 | Intel            | Jasper Lake SMBus                    | 23    | i2c_i801   | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:a2a3 | 103c:829e | Intel            | 200 Series/Z370 Chipset Family SM... | 23    | i2c_i801   | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 22    | i2c_i801   | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 8086:31d4 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 21    | i2c_i801   | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:9ca2 | 8086:2058 | Intel            | Wildcat Point-LP SMBus Controller    | 19    | i2c_i801   | [90BBA668E6](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-209/CE8A12A00B51/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/90BBA668E6>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 18    | i2c_i801   | [A506460DD5](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 3030 LT/21655F011AEA/UBUNTU-24.04/6.8.0-48-GENERIC/X86_64/A506460DD5>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 353   | snd_hda... | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:9dc8 | 8086:2074 | Intel            | Cannon Point-LP High Definition A... | 244   | snd_hda... | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 177   | snd_hda... | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:02c8 | 8086:2081 | Intel            | Comet Lake PCH-LP cAVS               | 152   | snd_hda... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 149   | snd_hda... | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9d71 | 8086:2068 | Intel            | Sunrise Point-LP HD Audio            | 147   | snd_hda... | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:0a0c | 106b:0141 | Intel            | Haswell-ULT HD Audio Controller      | 145   | snd_hda... | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 1022:15e3 | 1022:d270 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 143   | snd_hda... | [68A8804C89](<Mini Pc/AZW/SER/SER/17CBCB5805CA/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/68A8804C89>) |
| 8086:160c | 8086:2057 | Intel            | Broadwell-U Audio Controller         | 111   | snd_hda... | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:9ca0 | 8086:2057 | Intel            | Wildcat Point-LP High Definition ... | 111   | snd_hda... | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | snd_hda... | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 1022:15e3 | 10ec:0000 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 89    | snd_hda... | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 77    | snd_hda... | [46204EEB51](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q-1 11A40011US/467E9C948DD7/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/46204EEB51>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 77    | snd_hda... | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 1002:1640 | 1002:1640 | AMD              | Rembrandt Radeon High Definition ... | 73    | snd_hda... | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 8086:a2f0 | 103c:829a | Intel            | 200 Series PCH HD Audio              | 68    | snd_hda... | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:3198 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 65    | snd_hda... | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:2284 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | snd_hda... | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:a171 | 8086:2073 | Intel            | CM238 HD Audio Controller            | 62    | snd_hda... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:5a98 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 61    | snd_hda... | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 1002:ab08 | 8086:2073 | AMD              | Polaris 22 HDMI Audio                | 58    | snd_hda... | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a0c8 | 8086:3004 | Intel            | Tiger Lake-LP Smart Sound Technol... | 58    | snd_hda... | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:51c8 | 8086:3024 | Intel            | Alder Lake PCH-P High Definition ... | 57    | snd_hda... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:a348 | 17aa:312d | Intel            | Cannon Lake PCH cAVS                 | 54    | snd_hda... | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a170 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 53    | snd_hda... | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a348 | 8086:7270 | Intel            | Cannon Lake PCH cAVS                 | 53    | snd_hda... | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 106b:1803 | 106b:1884 | Apple            | Audio Device                         | 49    | aaudio     | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 48    | snd_hda... | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:a2f0 | 17aa:3111 | Intel            | 200 Series PCH HD Audio              | 48    | snd_hda... | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 1022:15e3 | 1043:87bc | AMD              | Family 17h/19h/1ah HD Audio Contr... | 45    | snd_hda... | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10de:0d94 | 10de:cb89 | Nvidia           | MCP89 High Definition Audio          | 44    | snd_hda... | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 44    | snd_hda... | [270457BC3C](<Mini Pc/AMI/Aptio/Aptio CRB/B8EEE095C5DC/UBUNTU-22.04/5.15.0-118-GENERIC/X86_64/270457BC3C>) |
| 1002:1640 | 1f4c:b002 | AMD              | Rembrandt Radeon High Definition ... | 39    | snd_hda... | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 1022:15e3 | 1f4c:b002 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 39    | snd_hda... | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 8086:9d70 | 8086:2063 | Intel            | Sunrise Point-LP HD Audio            | 39    | snd_hda... | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 8086:51ca | 8086:3037 | Intel            | Raptor Lake-P/U/H cAVS               | 37    | snd_hda... | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:9d71 | 8086:2070 | Intel            | Sunrise Point-LP HD Audio            | 37    | snd_hda... | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 1002:9840 | 103c:8158 | AMD              | Kabini HDMI/DP Audio                 | 36    | snd_hda... | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 1022:157a | 103c:8158 | AMD              | Family 15h (Models 60h-6fh) Audio... | 36    | snd_hda... | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 1022:15e3 | 1043:8873 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 33    | snd_hda... | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 1002:15b3 | 1002:15b3 | AMD              | High Definition Audio Controller     | 32    | snd_hda... | [52815E439B](<Mini Pc/ATOPNUC/MA/MA90/9664EDEE7102/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/52815E439B>) |
| 1002:1640 | 1f4c:b016 | AMD              | Rembrandt Radeon High Definition ... | 31    | snd_hda... | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 1022:157a | 14f1:0215 | AMD              | Family 15h (Models 60h-6fh) Audio... | 31    | snd_hda... | [52815E439B](<Mini Pc/ATOPNUC/MA/MA90/9664EDEE7102/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/52815E439B>) |
| 1022:15e3 | 1f4c:b016 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 31    | snd_hda... | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 31    | snd_hda... | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 8086:3198 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    | snd_hda... | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 1022:15e3 | 1043:8820 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 28    | snd_hda... | [693560BE85](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/65ED76199328/UBUNTU-22.04/6.8.0-47-GENERIC/X86_64/693560BE85>) |
| 1002:aa90 | 0000:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 27    | snd_hda... | [F220B96AA0](<Mini Pc/Apple/Macmini5/Macmini5,2/358A8F5F2FBF/KUBUNTU-24.10/6.11.0-13-GENERIC/X86_64/F220B96AA0>) |
| 1022:15e3 | 17aa:3130 | AMD              | Family 17h/19h/1ah HD Audio Contr... | 27    | snd_hda... | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 8086:a348 | 17aa:3136 | Intel            | Cannon Lake PCH cAVS                 | 27    | snd_hda... | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9dd3 | 8086:2074 | Intel            | Cannon Point-LP SATA Controller [... | 236   | ahci       | [31F432F98B](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/0C2EAAF79393/DEBIAN-11/5.10.0-33-AMD64/X86_64/31F432F98B>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 226   | ahci       | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 177   | ahci       | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:9d03 | 8086:2068 | Intel            | Sunrise Point-LP SATA Controller ... | 148   | ahci       | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:02d3 | 8086:2081 | Intel            | Comet Lake SATA AHCI Controller      | 147   | ahci       | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 137   | ahci       | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:9c83 | 8086:2057 | Intel            | Wildcat Point-LP SATA Controller ... | 100   | ahci       | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 85    | ahci       | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 80    | ahci       | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | ahci       | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 72    | ahci       | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:a282 | 103c:829a | Intel            | 200 Series PCH SATA controller [A... | 68    | ahci       | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:31e3 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 66    | ahci       | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:5ae3 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | ahci       | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 62    | ahci       | [51528B49B0](<Mini Pc/AMI/Aptio/Aptio CRB/CE33A578FA08/LINUXMINT-20.3/5.4.0-200-GENERIC/X86_64/51528B49B0>) |
| 8086:22a3 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 62    | ahci       | [BC8AD1755C](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-106/221D1663B6D0/ROSA-12.5.1/6.6.47-GENERIC-1ROSA2021.1-X86_64/X86_64/BC8AD1755C>) |
| 8086:a0d3 | 8086:3004 | Intel            | Tiger Lake-LP SATA Controller        | 59    | ahci       | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 1022:7901 | 1043:87e7 | AMD              | FCH SATA Controller [AHCI mode]      | 57    | ahci       | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:51d3 | 8086:3024 | Intel            | Alder Lake-P SATA AHCI Controller    | 57    | ahci       | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:a352 | 17aa:312d | Intel            | Cannon Lake PCH SATA AHCI Controller | 54    | ahci       | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:a282 | 17aa:3111 | Intel            | 200 Series PCH SATA controller [A... | 47    | ahci       | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 10de:0d88 | 106b:cb89 | Nvidia           | MCP89 SATA Controller (AHCI mode)    | 44    | ahci       | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |
| 8086:9d03 | 8086:2063 | Intel            | Sunrise Point-LP SATA Controller ... | 42    | ahci       | [0D6DD4B561](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/FAE792E61AC2/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/0D6DD4B561>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 40    | ahci       | [47271C8EB9](<Mini Pc/Apple/Macmini3/Macmini3,1/61BDA93F49B5/ENDEAVOUROS-ROLLING/6.10.2-ARCH1-1/X86_64/47271C8EB9>) |
| 8086:51d3 | 8086:3037 | Intel            | Alder Lake-P SATA AHCI Controller    | 38    | ahci       | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:9d03 | 8086:2070 | Intel            | Sunrise Point-LP SATA Controller ... | 37    | ahci       | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 1022:7901 | 103c:8158 | AMD              | FCH SATA Controller [AHCI mode]      | 35    | ahci       | [27469D63A1](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/1AF24C549C62/RED-OS-7.3/6.1.110-1.EL7.3.X86_64/X86_64/27469D63A1>) |
| 1022:7901 | 1043:880a | AMD              | FCH SATA Controller [AHCI mode]      | 34    | ahci       | [195B7AC36C](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN52/7A9FE09D067A/LINUXMINT-22/6.8.0-49-GENERIC/X86_64/195B7AC36C>) |
| 8086:4dd3 |           | Intel            | Jasper Lake SATA AHCI Controller     | 32    | ahci       | [23A07D616D](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3C/1C22D3BF4B4A/CENTOS-STREAM/6.10.11-1.EL8.ELREPO.X86_64/X86_64/23A07D616D>) |
| 1022:7901 | 17aa:3130 | AMD              | FCH SATA Controller [AHCI mode]      | 30    | ahci       | [3F2770B9FE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M715q 10VHS2DL00/E4809D71F4E7/DEVUAN-6/6.11.4-AMD64/X86_64/3F2770B9FE>) |
| 8086:31e3 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    | ahci       | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:a282 | 17aa:310b | Intel            | 200 Series PCH SATA controller [A... | 28    | ahci       | [B53A9B97FC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS2NV00/6B8AF0880774/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/B53A9B97FC>) |
| 8086:a352 | 17aa:3136 | Intel            | Cannon Lake PCH SATA AHCI Controller | 28    | ahci       | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1061/ASM1062 Serial ATA Contro... | 27    | ahci       | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 8086:4dd3 | 1043:8813 | Intel            | Jasper Lake SATA AHCI Controller     | 26    | ahci       | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:a352 | 17aa:3135 | Intel            | Cannon Lake PCH SATA AHCI Controller | 26    | ahci       | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 24    | ahci       | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 8086:54d3 |           | Intel            | Alder Lake-N SATA AHCI Controller    | 24    | ahci       | [52B9EE705B](<Mini Pc/Chuwi/HeroBox/HeroBox/1D5A038AC1ED/DEBIAN-12/6.1.0-27-AMD64/X86_64/52B9EE705B>) |
| 8086:a0d3 | 8086:3002 | Intel            | Tiger Lake-LP SATA Controller        | 23    | ahci       | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:4dd3 | 8086:3027 | Intel            | Jasper Lake SATA AHCI Controller     | 22    | ahci       | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:31e3 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 21    | ahci       | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:a282 | 103c:829e | Intel            | 200 Series PCH SATA controller [A... | 21    | ahci       | [C1DAB94853](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/CE6E4D983EDC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/C1DAB94853>) |
| 8086:9c83 | 8086:2058 | Intel            | Wildcat Point-LP SATA Controller ... | 19    | ahci       | [90BBA668E6](<Mini Pc/Intel/NUC5i3MYBE/NUC5i3MYBE H47781-209/CE8A12A00B51/LINUXMINT-22.1/6.8.0-51-GENERIC/X86_64/90BBA668E6>) |
| 8086:a103 | 8086:2064 | Intel            | HM170/QM170 Chipset SATA Controll... | 18    | ahci       | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 17    | ahci       | [3DD81341C1](<Mini Pc/ZOTAC/ZBOX-MI/ZBOX-MI549/FAE095EB71DD/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/3DD81341C1>) |
| 1002:4390 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 16    | ahci       | [A2BE55EC15](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/64E62AD5D1DE/FEDORA-39/6.6.9-200.FC39.X86_64/X86_64/A2BE55EC15>) |
| 144d:a801 | 144d:a801 | Samsung Elect... | S4LN058A01[SSUBX] AHCI SSD Contro... | 16    | ahci       | [99E4338A2D](<Mini Pc/Apple/Macmini7/Macmini7,1/49D4D094D347/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/99E4338A2D>) |
| 8086:06d2 | 17aa:316e | Intel            | Comet Lake SATA AHCI Controller      | 16    | ahci       | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:0f23 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 15    | ahci       | [E402A3ADDE](<Mini Pc/Lenovo/E50-00/E50-00 90BX0018MB/1E28F3D9725D/DEBIAN-12/6.1.0-18-AMD64/X86_64/E402A3ADDE>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 15    | ahci       | [D787DD8103](<Mini Pc/AWOW/NYI/NYI3/31159C8F37C6/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/D787DD8103>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 21    | pata_acpi  | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 14    | pata_acpi  | [973E09E6EB](<Mini Pc/Apple/Macmini2/Macmini2,1/C0FBE2569FA5/LMDE-6/6.1.0-15-AMD64/X86_64/973E09E6EB>) |
| 1106:9001 | 1106:9001 | VIA Technologies | VX900 Series Serial-ATA Controller   | 11    | pata_vi... | [2CEF0FA0F1](<Mini Pc/Hewlett-Packard/t510/t510 Thin Client/362AD698331E/ALPINE-3.19.1/6.6.14-0-LTS/X86_64/2CEF0FA0F1>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 9     | ahci, p... | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:1c01 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 9     | pata_acpi  | [4BBD294790](<Mini Pc/Apple/Macmini5/Macmini5,1/337DD5D34BEB/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/4BBD294790>) |
| 1002:439c | 19da:a191 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [2B0FBC5661](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD10/63E0DADDC3BA/DEBIAN-12/6.5.10-1-LIQUORIX-AMD64/X86_64/2B0FBC5661>) |
| 1002:439c | 19da:a233 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | pata_at... | [C7C537BD79](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/9A49AACC4D63/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C7C537BD79>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 4     | ata_gen... | [19C575A4D8](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E94D038C9E51/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/19C575A4D8>) |
| 8086:27c0 | 8086:544b | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | ata_piix   | [DC0F48314D](<Mini Pc/Intel/D425KT/D425KT AAE93083-400/F9CAE375B1F3/ANTIX-22/4.9.0-326-ANTIX.1-AMD64-SMP/X86_64/DC0F48314D>) |
| 1022:780c | 19da:a261 | AMD              | FCH IDE Controller                   | 3     | pata_at... | [3A6297D90B](<Mini Pc/ZOTAC/ZBOXNANO-AD/ZBOXNANO-AD12/1942AB43E912/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/3A6297D90B>) |
| 1022:780c | 19da:b218 | AMD              | FCH IDE Controller                   | 3     | pata_at... | [08840508A8](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ02/EB7C0132389E/ZORIN-17/6.5.0-35-GENERIC/X86_64/08840508A8>) |
| 1002:439c | 19da:a183 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 2     | pata_at... | [B4447459DF](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD02/BB1B94107982/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/B4447459DF>) |
| 8086:0f21 | 17aa:368d | Intel            | Atom Processor E3800 Series SATA ... | 2     | ata_pii... | [97A08F730E](<Mini Pc/Lenovo/H30-00/H30-00 90C2007LGE/F163053D4532/OPENMANDRIVA-23.08/6.4.11-DESKTOP-1OMV2390/X86_64/97A08F730E>) |
| 8086:0f21 | 8086:0f21 | Intel            | Atom Processor E3800 Series SATA ... | 2     | ata_pii... | [520F0FD81E](<Mini Pc/AMI/Aptio/Aptio CRB/F79EAED60BA9/NIXOS-24.05/6.6.43/X86_64/520F0FD81E>) |
| 8086:1e3c | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 2     | pata_acpi  | [AD65FE187A](<Mini Pc/CompuLab/Intense-PC/Intense-PC/F82D466DC54E/KDE-NEON-22.04/5.15.0-56-GENERIC/X86_64/AD65FE187A>) |
| 8086:27c0 | 19da:a140 | Intel            | NM10/ICH7 Family SATA Controller ... | 2     | pata_acpi  | [620812FE84](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID41/E272C7549D5E/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/620812FE84>) |
| 8086:0f21 | 17aa:3688 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ata_piix   | [5611B13B59](<Mini Pc/Lenovo/H500s/H500s 10157/F927F05A57CD/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/5611B13B59>) |
| 8086:1e01 | 19da:b211 | Intel            | 7 Series Chipset Family 4-port SA... | 1     | pata_acpi  | [F93A41EF95](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID18/0D5FCE777B3D/UBUNTU-20.04/5.15.0-100-GENERIC/X86_64/F93A41EF95>) |
| 8086:1e09 | 19da:b211 | Intel            | 7 Series Chipset Family 2-port SA... | 1     | pata_acpi  | [F93A41EF95](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID18/0D5FCE777B3D/UBUNTU-20.04/5.15.0-100-GENERIC/X86_64/F93A41EF95>) |
| 8086:24cb | 8086:1977 | Intel            | 82801DB (ICH4) IDE Controller        | 1     | ata_piix   | [4A3E3CD4EE](<Mini Pc/Radiant Systems/P/P845/6CDD298F6645/ANTIX-17.4.1/4.9.160-ANTIX.2-486-SMP/I686/4A3E3CD4EE>) |
| 8086:27c0 | 19da:a218 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | ata_pii... | [E907BA80AE](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID80/E1C6E46AEEE7/ROSA-2014.1/4.1.38-NRJ-DESKTOP-2ROSA-X86_64/X86_64/E907BA80AE>) |
| 8086:27c0 | 19da:b209 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [6162BE584A](<Mini Pc/ZOTAC/ZBOX-ID/ZBOX-ID84/2624D8EDD4B1/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/6162BE584A>) |
| 8086:27c0 | 8086:7270 | Intel            | NM10/ICH7 Family SATA Controller ... | 1     | pata_acpi  | [6B9414B09F](<Mini Pc/Intel/CedarTrail/CedarTrail Platform/009433D25421/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/6B9414B09F>) |
| 8086:27c4 | 8086:27c4 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 1     | pata_acpi  | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |
| 8086:2928 | 8086:2928 | Intel            | 82801IBM/IEM (ICH9M/ICH9M-E) 2 po... | 1     | ata_pii... | [3B1029927C](<Mini Pc/Hewlett-Packard/t5740e/t5740e Thin Client/B8EE2DA1CA8B/DEBIAN-12/6.1.0-23-686-PAE/I686/3B1029927C>) |
| 8086:292d | 8086:292d | Intel            | 82801IBM/IEM (ICH9M/ICH9M-E) 2 po... | 1     | ata_pii... | [3B1029927C](<Mini Pc/Hewlett-Packard/t5740e/t5740e Thin Client/B8EE2DA1CA8B/DEBIAN-12/6.1.0-23-686-PAE/I686/3B1029927C>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 334   | nvme       | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 110   | nvme       | [EED87DE39C](<Mini Pc/AZW/SER/SER/DDEDAF22F789/FEDORA-41/6.11.4-301.FC41.X86_64/X86_64/EED87DE39C>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 98    | nvme       | [ABBE5E18A9](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/FBB1F1EDB949/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/ABBE5E18A9>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 97    | nvme       | [EB3FF37603](<Mini Pc/Lenovo/ThinkStation/ThinkStation P320 Tiny 30C1S0160C/1E797AA92C48/ENDEAVOUROS-ROLLING/6.12.6-ARCH1-1/X86_64/EB3FF37603>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980 (DRAM-less)  | 82    | nvme       | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT (DRAM-less) NVM... | 68    | nvme       | [C6D2F011FA](<Mini Pc/Digma Pro/Minimax/Minimax U1 DPP5-8CXN01/11F2C32C1D33/ELEMENTARY-8/6.8.0-51-GENERIC/X86_64/C6D2F011FA>) |
| 2646:500f | 2646:500f | Kingston Tech... | NV1 NVMe SSD [SM2263XT] (DRAM-less)  | 56    | nvme       | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 106b:2005 | 106b:1800 | Apple            | ANS2 NVMe Controller                 | 49    | nvme       | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 43    | nvme       | [9D0494EA1B](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/7BA272E9E4FC/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/9D0494EA1B>) |
| 2646:5017 | 2646:5017 | Kingston Tech... | NV2 NVMe SSD [SM2267XT] (DRAM-less)  | 41    | nvme       | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 1344:5416 | 1344:1100 | Micron Techno... | 2550 NVMe SSD (DRAM-less)            | 40    | nvme       | [4188B696FB](<Mini Pc/Trigkey/S/S7/BA5347E06DA7/NIXOS-25.05/6.11.11/X86_64/4188B696FB>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 39    | nvme       | [2684305E77](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi5/77E85ADF2A1E/KUBUNTU-24.10/6.11.0-12-GENERIC/X86_64/2684305E77>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | Extreme Pro / WD Black SN750 / PC... | 37    | nvme       | [5204129980](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/0E8F2605F090/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/5204129980>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202 (DRAM... | 36    | nvme       | [72054648D0](<Mini Pc/AZW/SER/SER/CE65584EE726/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/72054648D0>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | Ultra 3D / WD PC SN530, IX SN530,... | 32    | nvme       | [4188B696FB](<Mini Pc/Trigkey/S/S7/BA5347E06DA7/NIXOS-25.05/6.11.11/X86_64/4188B696FB>) |
| 2646:5021 | 2646:5021 | Kingston Tech... | OM8SEP4 Design-In PCIe 4 NVMe SSD... | 27    | nvme       | [69507F80B5](<Mini Pc/AZW/SER/SER/4182AB1E2E39/DEBIAN-12/6.1.0-26-AMD64/X86_64/69507F80B5>) |
| 144d:a80c | 144d:a801 | Samsung Elect... | NVMe SSD Controller S4LV008[Pascal]  | 26    | nvme       | [5D9F2B4584](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi9/1814222DA7BE/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/5D9F2B4584>) |
| 15b7:5017 | 15b7:5017 | SanDisk          | WD Black SN770 / PC SN740 256GB /... | 26    | nvme       | [9F5263B2E2](<Mini Pc/ASUSTek Computer/NUC12/NUC12WSH-B/E366D2D7136B/TUXEDO-24.04/6.11.0-107009-TUXEDO/X86_64/9F5263B2E2>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 26    | nvme       | [9319560A05](<Mini Pc/Intel/NUC7/NUC7i3BNK/54E5A6D28C1F/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/9319560A05>) |
| 2646:501b | 2646:501b | Kingston Tech... | OM8PGP4 NVMe PCIe SSD (DRAM-less)    | 25    | nvme       | [62C313072F](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/0AE4D4E1A91B/OPENMANDRIVA-24.12/6.13.0-DESKTOP-0.RC4.1OMV2490/X86_64/62C313072F>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013-E13 PCIe3 NVMe Controller ... | 24    | nvme       | [30DF458D10](<Mini Pc/Apple/Macmini7/Macmini7,1/5CFBADE3C618/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/30DF458D10>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 [Nick P2] / P3 / P3 Plus NVMe ... | 24    | nvme       | [C21529E69D](<Mini Pc/Fanless Mini PC/Quieter/Quieter HD3/288AC4710772/OPENMANDRIVA-24.07/6.10.0-DESKTOP-1OMV2490/X86_64/C21529E69D>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/BC711/PC711 NVMe Solid S... | 23    | nvme       | [DCAF1A5094](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/7A21AB2D0D5E/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/DCAF1A5094>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | Extreme Pro / WD Black 2018/SN750... | 22    | nvme       | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 15b7:501a | 15b7:501a | SanDisk          | Ultra 3D / WD Blue SN570 NVMe SSD... | 22    | nvme       | [E7BF848205](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/B0E8BB9EF367/FEDORA-40/6.8.5-301.FC40.X86_64/X86_64/E7BF848205>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD [SM2263EN]            | 20    | nvme       | [B71F20BE35](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/D8AABA3E7A02/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/B71F20BE35>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD[Frampton]           | 19    | nvme       | [08F4EFBFDD](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/21F183649EC3/ARCH-ROLLING/6.11.6-ARCH1-1/X86_64/08F4EFBFDD>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 17    | nvme       | [52C58EEEC2](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/F90AF7C79925/FEDORA-40/6.8.8-300.FC40.X86_64/X86_64/52C58EEEC2>) |
| 2646:5013 | 2646:5013 | Kingston Tech... | KC3000/FURY Renegade NVMe SSD [E18]  | 17    | nvme       | [A6240AB56C](<Mini Pc/System76/Meerkat/Meerkat/84EC97CD2EDE/POP!_OS-22.04/6.9.3-76060903-GENERIC/X86_64/A6240AB56C>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 16    | nvme       | [B984E53994](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/8AB72321363F/FEDORA-40/6.10.10-200.FC40.X86_64/X86_64/B984E53994>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD DC P4101/Pro 7600p/760p/E 610... | 16    | nvme       | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 15    | nvme       | [460BBA640E](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/483ABB36C97B/UBUNTU-24.04/6.8.0-47-GENERIC/X86_64/460BBA640E>) |
| 1e4b:1602 | 1e4b:1602 | MAXIO Technol... | NVMe SSD Controller MAP1602 (DRAM... | 15    | nvme       | [7FDBDBC1A6](<Mini Pc/AZW/SEi12/SEi12 MAX/B3F370149071/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/7FDBDBC1A6>) |
| 8086:f1aa | 8086:390f | Intel            | SSD 670p Series [Keystone Harbor]    | 15    | nvme       | [519BF54E21](<Mini Pc/AZW/SER/SER/D618F23B2EE6/FEDORA-41/6.11.8-300.FC41.X86_64/X86_64/519BF54E21>) |
| 1179:0116 | 1179:0001 | Toshiba Ameri... | XG5 NVMe SSD Controller              | 14    | nvme       | [5BD4FDC8D1](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/F687C7012505/UBUNTU-MATE-23.04/6.2.0-20-GENERIC/X86_64/5BD4FDC8D1>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 14    | nvme       | [2601C319B5](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/3AE24AADCC22/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/2601C319B5>) |
| c0a9:5407 | c0a9:0100 | Micron/Crucia... | P5 Plus NVMe PCIe SSD                | 14    | nvme       | [D4B0B233E3](<Mini Pc/Others/V/V00/E60AD76FB6FF/OPENMANDRIVA-24.09/6.11.0-DESKTOP-2OMV2490/X86_64/D4B0B233E3>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | RTS5765DL NVMe SSD Controller (DR... | 13    | nvme       | [5563F43111](<Mini Pc/Others/V/V00/E9E13DA0AE6C/KUBUNTU-24.04/6.8.0-50-GENERIC/X86_64/5563F43111>) |
| 1987:5015 | 1987:5015 | Phison Electr... | PS5015-E15 PCIe3 NVMe Controller ... | 13    | nvme       | [3259423D78](<Mini Pc/AZW/SER/SER/1115FD308ECB/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/3259423D78>) |
| 1179:011a | 1179:0001 | Toshiba Ameri... | XG6 NVMe SSD Controller              | 11    | nvme       | [2D257AFC82](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/A54FADB6211F/FEDORA-40/6.9.9-200.FC40.X86_64/X86_64/2D257AFC82>) |
| 15b7:5030 | 15b7:5030 | Sandisk          | WD Black SN850X NVMe SSD             | 11    | nvme       | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 1d97:1602 | 1d97:1602 | Shenzhen Long... | Lexar NM790 NVME SSD (DRAM-less)     | 11    | nvme       | [BAE098EAAB](<Mini Pc/Micro Computer (HK) Tech Limited/Venus/Venus series/D725A40F6BE7/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.11.6-2-DEFAULT/X86_64/BAE098EAAB>) |
| 2646:5019 | 2646:5019 | Kingston Tech... | NV2 NVMe SSD [E21T] (DRAM-less)      | 11    | nvme       | [A23B8BCD4C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920x Tiny/758016AB6F4D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/A23B8BCD4C>) |
| 025e:f1ab | 025e:3910 | Solidigm         | P41 Plus NVMe SSD (DRAM-less) [Ec... | 10    | nvme       | [CE06DD06F1](<Mini Pc/BLEU JOUR/KUBB/KUBB & OCTO/2E1A925C9653/LINUXMINT-21.3/5.15.0-122-GENERIC/X86_64/CE06DD06F1>) |
| 1c5c:1327 | 1c5c:0000 | SK hynix         | BC501 NVMe Solid State Drive         | 10    | nvme       | [7A5D375262](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RS0014US/E9E8294E13E0/BAZZITE-41/6.11.5-307.BAZZITE.FC41.X86_64/X86_64/7A5D375262>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 9     | nvme       | [1545F1AD9F](<Mini Pc/GMKtec/M5/M5 Pro/C46764A4355B/LMDE-6/6.1.0-18-AMD64/X86_64/1545F1AD9F>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4 (DRAM-less)  | 9     | nvme       | [D270F65914](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUSBVM00/6A6ACA909F6B/DEBIAN-12/6.1.0-26-AMD64/X86_64/D270F65914>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | A1000/U-SNS8154P3 x2 NVMe SSD        | 9     | nvme       | [A7372E4BBC](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G6 Desktop Mini PC/74BE63B62162/ENDEAVOUROS-ROLLING/6.6.10-ARCH1-1/X86_64/A7372E4BBC>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 9     | nvme       | [0BEE319571](<Mini Pc/BESSTAR Tech/U/U850/A659ABA3A179/SLACKWARE-15.0/6.12.1/X86_64/0BEE319571>) |
| c0a9:5421 | c0a9:5021 | Micron/Crucia... | P3 Plus NVMe PCIe SSD (DRAM-less)    | 9     | nvme       | [EB3EBCC1FD](<Mini Pc/Win element/M/M600/6FEB8CCAF9C0/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/EB3EBCC1FD>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 8086:2074 | Intel            | 82801 Mobile SATA Controller [RAI... | 10    | ahci       | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:467f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 8     | vmd        | [F08DDE0FA4](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PL64/615D37FF196A/UBUNTU-24.04/6.8.0-45-GENERIC/X86_64/F08DDE0FA4>) |
| 8086:2822 | 103c:82c0 | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [F6987473A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/593502302703/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/F6987473A1>) |
| 8086:2822 | 103c:829a | Intel            | SATA Controller [RAID mode]          | 5     | ahci       | [3DD0A36034](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/1D9EFC42D25A/UBUNTU-24.10/6.11.0-12-GENERIC/X86_64/3DD0A36034>) |
| 8086:2822 | 103c:8458 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [3004E844FD](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/7F3F3EDE7620/LINUXMINT-21.2/5.15.0-76-GENERIC/X86_64/3004E844FD>) |
| 8086:282a | 8086:2081 | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [042FB842D2](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/FF9B4FBF244B/DEBIAN-11/5.10.0-20-AMD64/X86_64/042FB842D2>) |
| 8086:06d6 | 103c:8754 | Intel            | Comet Lake PCH-H RAID                | 3     | ahci       | [869F3E6995](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G5 Workstation/C6A832D343B8/DEBIAN-12/6.2.16-19-PVE/X86_64/869F3E6995>) |
| 8086:9a0b | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 3     | vmd        | [DB9625869B](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKi7/68005F9CCDFD/FEDORA-40/6.10.12-200.FC40.X86_64/X86_64/DB9625869B>) |
| 8086:2822 | 103c:829e | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [246C5D2532](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 600 G3 DM/A91BA6239351/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/246C5D2532>) |
| 8086:282a | 8086:2068 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [4760FD05FF](<Mini Pc/Intel/NUC7/NUC7i7BNHXG/F81D2DDD5350/DEBIAN-12/6.1.0-28-AMD64/X86_64/4760FD05FF>) |
| 1022:43bd | 103c:872c | AMD              | FCH RAID Controller                  | 1     |            | [0E48C94F83](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/FB1F518D1327/CENTOS-8/4.18.0-240.22.1.EL8_3.X86_64/X86_64/0E48C94F83>) |
| 8086:06d6 | 103c:871a | Intel            | Comet Lake PCH-H RAID                | 1     | ahci       | [C3E106F381](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G6 Desktop Mini PC/6BB6ECE7CCCC/ARCH-ROLLING/6.6.23-1-LTS/X86_64/C3E106F381>) |
| 8086:2822 | 103c:82a5 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [1A5069219B](<Mini Pc/Hewlett-Packard/ProDesk/ProDesk 400 G3 DM/BF54BF0857DB/RED-OS-8.0/6.6.51-1.RED80.X86_64/X86_64/1A5069219B>) |
| 8086:2822 | 103c:82bf | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [305883BE65](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/A9881D706083/MANJARO/6.1.19-1-MANJARO/X86_64/305883BE65>) |
| 8086:2822 | 103c:8457 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [9B6E5BB6EA](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G4 Workstation/E2A11D014692/LINUXMINT-20.3/5.4.0-120-GENERIC/X86_64/9B6E5BB6EA>) |
| 8086:2822 | 8086:7270 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [1643C675CC](<Mini Pc/CompuLab/Airtop/Airtop3/7191A7A476BB/FEDORA-40/6.8.9-300.FC40.X86_64/X86_64/1643C675CC>) |
| 8086:282a | 1043:8744 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [F0BAB8D97C](<Mini Pc/ASUSTek Computer/UN65/UN65U/859CC84F4A33/AXYL-ROLLING/5.19.13-ARCH1-1/X86_64/F0BAB8D97C>) |
| 8086:282a | 19da:b248 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [D521E3AD79](<Mini Pc/ZOTAC/ZBOX-EN/ZBOX-EN760/C87907D81660/LINUXMINT-19.3/5.4.0-42-GENERIC/X86_64/D521E3AD79>) |
| 8086:282a | 8086:2073 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [6D946007B8](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/6F86351FEFD1/KALI-2022.3/5.19.0-KALI2-AMD64/X86_64/6D946007B8>) |
| 8086:282a | 8086:2079 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [985AA77681](<Mini Pc/Intel Client Systems/NUC8/NUC8i5INH/B39881C57542/CLEAR-LINUX-OS-34440/5.10.19-1032.NATIVE/X86_64/985AA77681>) |
| 8086:43de | 17aa:31a7 | Intel            | 500 Series Chipset Family SATA RA... | 1     |            | [29F9DA7451](<Mini Pc/Lenovo/THINKCENTER/THINKCENTER M70Q 11MY002VMH/D2A37048CE3B/UBUNTU-22.04/6.2.0-36-GENERIC/X86_64/29F9DA7451>) |
| 8086:467f | 103c:8952 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [5A5C598609](<Mini Pc/Hewlett-Packard/Elite/Elite Mini 600 G9 Desktop PC/22343F6ECC6C/DEBIAN-12/6.1.0-23-AMD64/X86_64/5A5C598609>) |
| 8086:467f | 103c:895e | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [13804B587B](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G9 Workstation Desktop PC/29A83A936127/OPENMANDRIVA-23.09/6.5.2-DESKTOP-1OMV2390/X86_64/13804B587B>) |
| 8086:a77f | 8086:0000 | Intel            | Volume Management Device NVMe RAI... | 1     | vmd        | [A977B2E8FF](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN64-E1/7F1FA6048FC8/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/A977B2E8FF>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 8086:2074 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 248   |            | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:1911 | 8086:2081 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 152   |            | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:1911 | 8086:2068 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 151   |            | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:15e8 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 148   | thunder... | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 136   | thunder... | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 94    | thunder... | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:1911 | 8086:2073 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 63    |            | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:9a11 | 8086:3004 | Intel            | GNA Scoring Accelerator module       | 61    |            | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:464f | 8086:3024 | Intel            | 12th Gen Core Processor Gaussian ... | 59    |            | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:1911 | 17aa:312d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 55    |            | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 8086:1911 | 8086:2064 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 54    |            | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:15eb | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 49    | thunder... | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:1911 | 8086:2070 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 38    |            | [EF0B742827](<Mini Pc/Intel Client Systems/NUC7/NUC7i5DNKPC/C93FD235134E/ULTRAMARINE-41/6.12.6-200.FC41.X86_64/X86_64/EF0B742827>) |
| 8086:a74f | 8086:3037 | Intel            | GNA Scoring Accelerator module       | 38    |            | [2F800631CA](<Mini Pc/Intel Client Systems/NUC13/NUC13ANKi5/78E0BC244D76/KUBUNTU-24.10/6.11.0-8-GENERIC/X86_64/2F800631CA>) |
| 8086:3190 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 30    |            | [79856FBF5B](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/ACDB386C87DC/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/79856FBF5B>) |
| 8086:1911 | 17aa:3136 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 29    |            | [856E7958E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS2NA00/065FE7CF1D79/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/856E7958E3>) |
| 8086:4e11 | 1043:8813 | Intel            | Jasper Lake System Peripheral        | 27    |            | [82480441F8](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN41-S1/FA110AA93FB9/TUXEDO-22.04/6.11.0-103009-TUXEDO/X86_64/82480441F8>) |
| 8086:1911 | 17aa:3135 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 26    |            | [0518E5912F](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CES3QF18/91B5792D0623/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/0518E5912F>) |
| 8086:9a11 | 8086:3002 | Intel            | GNA Scoring Accelerator module       | 24    |            | [7BED793675](<Mini Pc/Prime Computer/PrimeMini5/PrimeMini5 i7 11G/2B9572D6CEF1/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/7BED793675>) |
| 8086:4e11 | 8086:3027 | Intel            | Jasper Lake System Peripheral        | 22    |            | [8C390F15D5](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKPE/BC99F9CDC500/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/8C390F15D5>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 21    |            | [3DD81341C1](<Mini Pc/ZOTAC/ZBOX-MI/ZBOX-MI549/FAE095EB71DD/UBUNTU-22.04/5.15.0-126-GENERIC/X86_64/3DD81341C1>) |
| 8086:3190 | 1043:875e | Intel            | Celeron/Pentium Silver Processor ... | 21    |            | [3605503634](<Mini Pc/ASUSTek Computer/PN/PN40/FD7D2D30EAA5/OPENMANDRIVA-5.0/6.6.2-DESKTOP-1OMV2390/X86_64/3605503634>) |
| 8086:15eb | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 17    | thunder... | [01C529E25C](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/F0A1DC460BE8/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/01C529E25C>) |
| 8086:9a11 | 8086:2090 | Intel            | GNA Scoring Accelerator module       | 17    |            | [F93A2B50EE](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/876601EF0821/GARUDA-SOARING/6.11.4-ZEN1-1-ZEN/X86_64/F93A2B50EE>) |
| 8086:1911 | 17aa:316e | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 16    |            | [1344277AB7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT00B4GE/EB1C9AFCC119/DEBIAN-12/6.1.0-27-AMD64/X86_64/1344277AB7>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 16    |            | [0BEE319571](<Mini Pc/BESSTAR Tech/U/U850/A659ABA3A179/SLACKWARE-15.0/6.12.1/X86_64/0BEE319571>) |
| 8086:1911 | 19da:b440 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 13    |            | [4D77EB6ED7](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/C2E035EFE6A7/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/4D77EB6ED7>) |
| 8086:a74f | 8086:3033 | Intel            | GNA Scoring Accelerator module       | 13    |            | [9EF1488E0B](<Mini Pc/Intel Client Systems/NUC13/NUC13RNGi5/04FA1B600620/UBUNTU-20.04/5.15.0-105-GENERIC/X86_64/9EF1488E0B>) |
| 8086:15d9 | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 NHI (C step... | 11    | thunder... | [D00575213D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/B1AD0E64616C/KDE-NEON-22.04/6.5.0-35-GENERIC/X86_64/D00575213D>) |
| 8086:9a11 | 8086:3003 | Intel            | GNA Scoring Accelerator module       | 11    |            | [68E4F41DE9](<Mini Pc/Intel Client Systems/NUC11/NUC11TNKv5/19F5B126590F/DEBIAN-12/6.1.0-23-AMD64/X86_64/68E4F41DE9>) |
| 8086:1911 | 17aa:314d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [DC1E680DB3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/D2D0ACCE07EB/OPENMANDRIVA-23.11/6.6.2-DESKTOP-1OMV2390/X86_64/DC1E680DB3>) |
| 8086:1911 | 8086:2089 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [DAE336E37E](<Mini Pc/Intel Client Systems/NUC9/NUC9i9QNX/8BA72AAAC77B/KUBUNTU-24.04/6.8.0-45-LOWLATENCY/X86_64/DAE336E37E>) |
| 8086:1911 | 17aa:3172 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [83582F654C](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DF001KUS/4CD6233315A4/DEBIAN-12/6.1.0-17-AMD64/X86_64/83582F654C>) |
| 8086:9a11 | 8086:3019 | Intel            | GNA Scoring Accelerator module       | 8     |            | [82B4880445](<Mini Pc/Intel Client Systems/NUC11/NUC11DBBi9/E1ADA35C85BB/DEEPIN-20.9/5.15.77-AMD64-DESKTOP/X86_64/82B4880445>) |
| 8086:1911 | 19da:b333 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 7     |            | [BFD62247AA](<Mini Pc/ZOTAC/ZBOX-EN1070/ZBOX-EN1070-1060,EN1070K-1060K/F5F7BF243CCA/ALPINE-3.19_ALPHA20230901/6.1.55-0-LTS/X86_64/BFD62247AA>) |
| 8086:464f | 1043:87f2 | Intel            | 12th Gen Core Processor Gaussian ... | 7     |            | [D5F8A58F3C](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN64/3BD4F1462E75/ARCH-ROLLING/6.10.10-ARCH1-1/X86_64/D5F8A58F3C>) |
| 1ac1:089a | 1ac1:089a | Global Unichip   | Coral Edge TPU                       | 6     | apex       | [130C6292D1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S59F0V/E53999E94A7E/FEDORA-40/6.8.9-300.FC40.X86_64/X86_64/130C6292D1>) |
| 8086:1575 | 2222:1111 | Intel            | DSL6340 Thunderbolt 3 NHI [Alpine... | 6     | thunder... | [94AFCAF73D](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/DDE9BAC39F50/UBUNTU-23.04/6.2.0-23-GENERIC/X86_64/94AFCAF73D>) |
| 8086:1911 | 17aa:3307 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [BC437E32B7](<Mini Pc/Lenovo/IdeaCentre/IdeaCentre Mini 5 01IMH05 90Q70030GF/DDF707B361F6/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/BC437E32B7>) |
| 8086:1911 | 8086:2088 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [01C529E25C](<Mini Pc/Intel Client Systems/NUC9/NUC9VXQNX/F0A1DC460BE8/KUBUNTU-24.04/6.8.0-49-GENERIC/X86_64/01C529E25C>) |
| 8086:3190 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [73016AA2FF](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYHN/3A1BEAE58C15/FEDORA-41/6.11.10-300.FC41.X86_64/X86_64/73016AA2FF>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [0068FDF226](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/05B19E7B7DAF/XUBUNTU-23.04/6.2.0-26-GENERIC/X86_64/0068FDF226>) |
| 8086:464f | 8086:3020 | Intel            | 12th Gen Core Processor Gaussian ... | 6     |            | [FF4B08D223](<Mini Pc/Intel Client Systems/NUC12/NUC12DCMi9/E20B9963B4D2/KDE-NEON-22.04/6.8.0-45-GENERIC/X86_64/FF4B08D223>) |
| 8086:1911 | 19da:b411 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [FEF5F08978](<Mini Pc/ZOTAC/ZBOX-EN7208/ZBOX-EN72080V-EN72070V-EN52060V-EN51660T/FEC8FB1A3ACB/XUBUNTU-20.04/5.4.0-65-GENERIC/X86_64/FEF5F08978>) |
| 8086:4511 | 8086:7270 | Intel            | Elkhart Lake Gaussian and Neural ... | 5     |            | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 8086:4bb3 | 8086:7270 | Intel            | System peripheral                    | 5     | intel_i... | [53A2979277](<Mini Pc/Dell EMC/Edge/Edge Gateway 3200/688BB18AF5F8/UBUNTU-20.04/5.15.0-72-GENERIC/X86_64/53A2979277>) |
| 14e4:16be | 14e4:96be | Broadcom         | BCM57765/57785 MS Card Reader        | 4     |            | [A093B3B3DD](<Mini Pc/Apple/Macmini8/Macmini8,1/98F02F8D9CF1/MANJARO-24.0.0/6.9.0-2-MANJARO/X86_64/A093B3B3DD>) |
| 8086:15d2 | 8086:2073 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 4     | thunder... | [68B65FDA4C](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/0FA94421095F/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/68B65FDA4C>) |
| 8086:15de | 2222:1111 | Intel            | JHL6340 Thunderbolt 3 Controller ... | 4     | thunder... | [78B5820785](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-303/3A9D186752F0/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/78B5820785>) |
| 8086:15e8 | 8086:2096 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 4     | thunder... | [23DDE7A5E9](<Mini Pc/Intel Client Systems/NUC8/NUC8i3PNH/6F9877D0D4F1/DEBIAN-12/6.1.0-26-AMD64/X86_64/23DDE7A5E9>) |

### Tv card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 109e:036e |           | Brooktree        | Bt878 Video Capture                  | 1     | bttv       | [10DB69DD6C](<Mini Pc/Kontron/SMX/SMX945/327FC59121CA/UBUNTU-18.04/4.15.0-88-GENERIC/I686/10DB69DD6C>) |

### Unclassified device (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5aa2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | intel_i... | [224597688F](<Mini Pc/AMI/Aptio/Aptio CRB/0421BC2A6F1E/UBUNTU-20.04/5.4.0-90-GENERIC/X86_64/224597688F>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1639 | 1022:1639 | AMD              | Renoir/Cezanne USB 3.1               | 262   | xhci_pci   | [21AAA2D92A](<Mini Pc/AZW/S/S5/6F9D8C9AC851/LILIDOG-12/6.11.10+BPO-AMD64/X86_64/21AAA2D92A>) |
| 8086:9ded | 8086:2074 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 248   | xhci_hcd   | [CC4E4FFE1A](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/6C0029DC8B93/DEBIAN-12/6.1.0-26-AMD64/X86_64/CC4E4FFE1A>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 177   | ehci_pci   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 177   | ehci_pci   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 177   | xhci_hcd   | [6F31B0C5A7](<Mini Pc/Apple/Macmini6/Macmini6,2/F8D6CF6478FF/LINUXMINT-22/6.8.0-51-GENERIC/X86_64/6F31B0C5A7>) |
| 8086:02ed | 8086:2081 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 153   | xhci_pci   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9d2f | 8086:2068 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 151   | xhci_hcd   | [D06ADF16E1](<Mini Pc/Intel Client Systems/NUC7/NUC7i5BNH/AEB46873549B/DEBIAN-12/6.1.0-28-AMD64/X86_64/D06ADF16E1>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 149   | xhci_hcd   | [70C961D7B8](<Mini Pc/Apple/Macmini7/Macmini7,1/1319D3DC8516/DEBIAN-12/6.1.0-28-AMD64/X86_64/70C961D7B8>) |
| 8086:15e9 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 148   | xhci_pci   | [69EE875B7E](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNK/0125FFC3D382/OPENMANDRIVA-24.12/6.12.1-DESKTOP-1OMV2490/X86_64/69EE875B7E>) |
| 8086:9a13 |           | Intel            | Tiger Lake-LP Thunderbolt 4 USB C... | 128   | xhci_pci   | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:9a1b | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #0   | 125   | thunder... | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:9a1d | 2222:1111 | Intel            | Tiger Lake-LP Thunderbolt 4 NHI #1   | 124   | thunder... | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 114   | xhci_hcd   | [61B4034745](<Mini Pc/AMI/Aptio/Aptio CRB/8783C5AF059F/LUBUNTU-24.04/6.8.0-41-GENERIC/X86_64/61B4034745>) |
| 8086:9cb1 | 8086:2057 | Intel            | Wildcat Point-LP USB xHCI Controller | 111   | xhci_hcd   | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:9ca6 | 8086:2057 | Intel            | Wildcat Point-LP USB EHCI Controller | 108   | ehci_pci   | [DDE09FE131](<Mini Pc/Wortmann AG/TERRA_PC/TERRA_PC/8A83B891A972/ELEMENTARY-8/6.8.0-49-GENERIC/X86_64/DDE09FE131>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | ehci_pci   | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | uhci_hcd   | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | uhci_hcd   | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 94    | ehci_pci   | [34AE2BE0AA](<Mini Pc/Apple/Macmini5/Macmini5,1/7041E498F954/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/34AE2BE0AA>) |
| 8086:31a8 | 8086:31a8 | Intel            | Celeron/Pentium Silver Processor ... | 80    | xhci_pci   | [B713008508](<Mini Pc/Chuwi/HeroBox/HeroBox/29575FD0E502/UBUNTU-20.04/5.15.0-126-GENERIC/X86_64/B713008508>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 74    | xhci_pci   | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | xhci_pci   | [75F7559D30](<Mini Pc/CSL-Computer/Tiny/Tiny Box/598EE128A07D/LINUXMINT-22/6.8.0-38-GENERIC/X86_64/75F7559D30>) |
| 8086:a2af | 103c:829a | Intel            | 200 Series/Z370 Chipset Family US... | 73    | xhci_pci   | [215280111A](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/767E0051AB7F/UBUNTU-24.04/6.8.0-51-GENERIC/X86_64/215280111A>) |
| 8086:15db | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 72    | xhci_hcd   | [1E0B38853D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CC63723A9946/DEBIAN-12/6.1.0-18-AMD64/X86_64/1E0B38853D>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 72    | xhci_hcd   | [327A884D55](<Mini Pc/Acute angle/AA-B/AA-B4/B25D5E98BF59/UBUNTU-24.10/6.11.0-9-GENERIC/X86_64/327A884D55>) |
| 8086:31a8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 66    | xhci_pci   | [ADB5D55CF4](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYHN/3A95FF73D4BD/UBUNTU-MATE-24.10/6.12.3-061203-GENERIC/X86_64/ADB5D55CF4>) |
| 8086:461e |           | Intel            | Alder Lake-P Thunderbolt 4 USB Co... | 65    | xhci_pci   | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:5aa8 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | xhci_hcd   | [471682953F](<Mini Pc/Intel/NUC6/NUC6CAYH/F5399D2B455A/DEBIAN-12/6.1.0-28-AMD64/X86_64/471682953F>) |
| 1b21:2142 | 8086:2073 | ASMedia Techn... | ASM2142/ASM3142 USB 3.1 Host Cont... | 63    | xhci_hcd   | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:a0ed | 8086:3004 | Intel            | Tiger Lake-LP USB 3.2 Gen 2x1 xHC... | 63    | xhci_pci   | [5CB8B93A47](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/87502A19E545/NOBARA-41/6.12.8-200.FSYNC.FC41.X86_64/X86_64/5CB8B93A47>) |
| 8086:a12f | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 63    | xhci_hcd   | [99045D77BC](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HNK/9344657AF525/LINUXMINT-22/6.8.0-49-LOWLATENCY/X86_64/99045D77BC>) |
| 8086:51ed | 8086:3024 | Intel            | Alder Lake PCH USB 3.2 xHCI Host ... | 60    | xhci_pci   | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 1022:15d6 | 1022:15d6 | AMD              | Rembrandt USB4 XHCI controller #5    | 58    | xhci_pci   | [770D05536D](<Mini Pc/AZW/EQ/EQ/798D2A4C3C0B/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/770D05536D>) |
| 1022:15d7 | 1022:15d7 | AMD              | Rembrandt USB4 XHCI controller #6    | 58    | xhci_pci   | [770D05536D](<Mini Pc/AZW/EQ/EQ/798D2A4C3C0B/KUBUNTU-24.04/6.8.0-51-GENERIC/X86_64/770D05536D>) |
| 8086:463e | 2222:1111 | Intel            | Alder Lake-P Thunderbolt 4 NHI #0    | 58    | thunder... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 8086:466d | 2222:1111 | Intel            | Alder Lake-P Thunderbolt 4 NHI #1    | 58    | thunder... | [72C75ED73B](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi7/56700FD3FD77/DEBIAN-12/6.1.0-28-AMD64/X86_64/72C75ED73B>) |
| 1022:1639 | 1043:87e7 | AMD              | Renoir/Cezanne USB 3.1               | 57    | xhci_pci   | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 8086:a36d | 17aa:312d | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 55    | xhci_hcd   | [05DE1B24E3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BFR/8A2C05F94176/FEDORA-40/6.12.6-100.FC40.X86_64/X86_64/05DE1B24E3>) |
| 1022:162e | 1022:162e | AMD              | Rembrandt USB4/Thunderbolt NHI co... | 54    | thunder... | [2029A257EB](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN53/9E8C49E69A2F/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/2029A257EB>) |
| 8086:a12f | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 54    | xhci_hcd   | [55CE99F45F](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-404/258F86C20360/FEDORA-40/6.11.4-201.FC40.X86_64/X86_64/55CE99F45F>) |
| 8086:a36d | 8086:7270 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 53    | xhci_pci   | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 51    | xhci_hcd   | [DCB299A261](<Mini Pc/AMI/Aptio/Aptio CRB/43133D883C9F/UBUNTU-24.04/6.8.0-41-GENERIC/X86_64/DCB299A261>) |
| 8086:15ec | 8086:0000 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 50    | xhci_pci   | [5D251E379C](<Mini Pc/Apple/Macmini8/Macmini8,1/BDE5ABDC6215/UBUNTU-24.04/6.8.0-49-GENERIC/X86_64/5D251E379C>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 48    | ohci_pci   | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 48    | ehci_pci   | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 48    | ohci_pci   | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 48    | ehci_pci   | [20FEC0C721](<Mini Pc/Apple/Macmini3/Macmini3,1/CB722E4FAEA5/ROCKY-8.10/4.18.0-553.22.1.EL8_10.X86_64/X86_64/20FEC0C721>) |
| 8086:a2af | 17aa:3111 | Intel            | 200 Series/Z370 Chipset Family US... | 48    | xhci_pci   | [319DAA2C12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8/ARCO-ROLLING/6.12.7-ZEN1-1-ZEN/X86_64/319DAA2C12>) |
| 10ec:816d | 1043:85b5 | Realtek Semic... | RTL811x EHCI host controller         | 46    | ehci_pci   | [0C16B7182B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/38B5F469A134/LINUXMINT-21.3/6.8.0-50-LOWLATENCY/X86_64/0C16B7182B>) |
| 10de:0d9c | 10de:cb89 | Nvidia           | MCP89 OHCI USB 1.1 Controller        | 44    | ohci_pci   | [892E57AE56](<Mini Pc/Apple/Macmini4/Macmini4,1/AAC098D8DB44/LINUXMINT-21.3/5.15.0-126-GENERIC/X86_64/892E57AE56>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 43    |            | [5204129980](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 805 G6 Desktop Mini PC/0E8F2605F090/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/5204129980>) |
| 10ec:816e | 17aa:3181 | Realtek Semic... | RealManage BMC                       | 8     |            | [D7B1A6E8B1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75n 11GW000BUS/63BF4E6C46E3/DEBIAN-12/6.1.0-18-AMD64/X86_64/D7B1A6E8B1>) |
| 10ec:5261 | 1043:88ca | Realtek Semic... | RTS5261 PCI Express Card Reader      | 1     | rtsx_pci   | [23D1FF7D6D](<Mini Pc/ASUSTek Computer/NUC14/NUC14SRK/78C206BE09A8/ARCH-ROLLING/6.6.46-1-LTS/X86_64/23D1FF7D6D>) |

