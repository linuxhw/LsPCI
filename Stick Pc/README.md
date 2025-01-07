Most popular PCI devices in Stick Pcs
-------------------------------------

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Stick Pcs ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 8     | pcieport   | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 8     |            | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31d7 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 7     | pcieport   | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 7     | pcieport   | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31f0 | 8086:7270 | Intel            | Gemini Lake Host Bridge              | 4     |            | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | iosf_mb... | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | lpc_ich    | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | lpc_ich    | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     |            | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:0f00 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | iosf_mb... | [D19C52B3FD](<Stick Pc/Meegopad/T/T02/67B503D11D89/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-I586/I686/D19C52B3FD>) |
| 8086:0f00 | 17aa:3646 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | iosf_mb... | [28B902C9B7](<Stick Pc/Lenovo/IdeaCentre/IdeaCentre Stick 300-01IBY 90ER0005RN/2DD4B730FC08/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/28B902C9B7>) |
| 8086:0f1c | 17aa:3646 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | lpc_ich    | [28B902C9B7](<Stick Pc/Lenovo/IdeaCentre/IdeaCentre Stick 300-01IBY 90ER0005RN/2DD4B730FC08/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/28B902C9B7>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | lpc_ich    | [D19C52B3FD](<Stick Pc/Meegopad/T/T02/67B503D11D89/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-I586/I686/D19C52B3FD>) |
| 8086:2280 | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | iosf_mb... | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |
| 8086:229c | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | lpc_ich    | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |
| 8086:22c8 | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | pcieport   | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | pcieport   | [50585544F9](<Stick Pc/AWOW/Others/Others/A11940EE2CBD/ARCO-ROLLING/5.9.14-ARCH1-1/X86_64/50585544F9>) |
| 8086:31d6 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 1     | pcieport   | [C9D263F2FA](<Stick Pc/GMK/NucBox/NucBox/8B370D79A223/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/C9D263F2FA>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 1     | pcieport   | [C9D263F2FA](<Stick Pc/GMK/NucBox/NucBox/8B370D79A223/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/C9D263F2FA>) |
| 8086:31db | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 1     | pcieport   | [C9D263F2FA](<Stick Pc/GMK/NucBox/NucBox/8B370D79A223/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/C9D263F2FA>) |
| 8086:5ad6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | pcieport   | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ad7 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | pcieport   | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | mei_me     | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | mei_me     | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | mei_txe    | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:0f18 | 17aa:3646 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [28B902C9B7](<Stick Pc/Lenovo/IdeaCentre/IdeaCentre Stick 300-01IBY 90ER0005RN/2DD4B730FC08/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/28B902C9B7>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | mei_txe    | [D19C52B3FD](<Stick Pc/Meegopad/T/T02/67B503D11D89/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-I586/I686/D19C52B3FD>) |
| 8086:2298 | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | mei_txe    | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 6     | i915       | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 4     | i915       | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:22b0 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | i915       | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:3185 | f000:02f3 | Intel            | GeminiLake [UHD Graphics 600]        | 2     | i915       | [8BBC53C60C](<Stick Pc/Others/GB/GB01/B45DF39CB557/ROSA-12.2/5.15.32-GENERIC-6ROSA2021.1-X86_64/X86_64/8BBC53C60C>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 2     | i915       | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:0f31 | 1027:2014 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | i915       | [D19C52B3FD](<Stick Pc/Meegopad/T/T02/67B503D11D89/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-I586/I686/D19C52B3FD>) |
| 8086:0f31 | 17aa:3646 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | i915       | [28B902C9B7](<Stick Pc/Lenovo/IdeaCentre/IdeaCentre Stick 300-01IBY 90ER0005RN/2DD4B730FC08/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/28B902C9B7>) |
| 8086:22b0 | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | i915       | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8211/8411 PCI Expres... | 7     | r8169      | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 8     | iwlwifi    | [BDF33A0EC1](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/66115FCC763D/UBUNTU-22.04/6.5.0-21-GENERIC/X86_64/BDF33A0EC1>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 3     | iwlwifi    | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 3     | iwlwifi    | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31dc | 8086:0264 | Intel            | Gemini Lake PCH CNVi WiFi            | 1     | iwlwifi    | [AD54F075F6](<Stick Pc/Leader/SC8/SC8-PRO/0C92B652A563/DEBIAN-12/6.1.0-9-AMD64/X86_64/AD54F075F6>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | sdhci_pci  | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 6     | sdhci_pci  | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [032170EA66](<Stick Pc/Others/GB/GB01/B45DF39CB557/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-X86_64/X86_64/032170EA66>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31c8 | 8086:7270 | Intel            | Serial bus controller                | 3     | pwm_lps... | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 8     | process... | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 7     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | intel_l... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 4     | process... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:22dc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | process... | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 2     | process... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | intel_l... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | i2c_i801   | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | i2c_i801   | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3198 | 10ec:111c | Intel            | Celeron/Pentium Silver Processor ... | 6     | snd_soc... | [8463DC3B40](<Stick Pc/Fanless Mini PC/PCG02/PCG02 GLE/4DA55C5A68E4/DEBIAN-12/6.1.0-21-AMD64/X86_64/8463DC3B40>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 4     | snd_hda... | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:3198 | 02f3:f000 | Intel            | Celeron/Pentium Silver Processor ... | 2     | snd_hda... | [8BBC53C60C](<Stick Pc/Others/GB/GB01/B45DF39CB557/ROSA-12.2/5.15.32-GENERIC-6ROSA2021.1-X86_64/X86_64/8BBC53C60C>) |
| 8086:5a98 | 10ec:10fc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | snd_hda... | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:5a98 | 1c6c:122a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | snd_hda... | [032170EA66](<Stick Pc/Others/GB/GB01/B45DF39CB557/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-X86_64/X86_64/032170EA66>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ahci       | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [032170EA66](<Stick Pc/Others/GB/GB01/B45DF39CB557/ROSA-2016.1/4.15.0-DESKTOP-60.7ROSA-X86_64/X86_64/032170EA66>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | xhci_pci   | [320DF6B7CC](<Stick Pc/AWOW/AR40/AR40S/D46A1F588233/OPENMANDRIVA-24.08/6.10.0-DESKTOP-1OMV2490/X86_64/320DF6B7CC>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | xhci_pci   | [678542F4FE](<Stick Pc/DEPO Computers/T09/T09-D/99E2E2FF451E/ALT-8.2/5.4.113-STD-DEF-ALT0.C9F/X86_64/678542F4FE>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | xhci_hcd   | [554C7240CC](<Stick Pc/Azulle/A-1164/A-1164-AA3-2/4E5FC7753496/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/554C7240CC>) |
| 8086:0f35 | 17aa:3646 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 1     | xhci_hcd   | [28B902C9B7](<Stick Pc/Lenovo/IdeaCentre/IdeaCentre Stick 300-01IBY 90ER0005RN/2DD4B730FC08/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/28B902C9B7>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 1     | xhci_pci   | [D19C52B3FD](<Stick Pc/Meegopad/T/T02/67B503D11D89/ROSA-2014.1/4.4.1-NRJ-DESKTOP-1ROSA-I586/I686/D19C52B3FD>) |
| 8086:22b5 | 8086:2066 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | xhci_hcd   | [0F27631293](<Stick Pc/Intel Client Systems/STK1/STK1AW32SC/DDE0B7B64D87/CLEAR-LINUX-OS-37980/6.1.2-1232.NATIVE/X86_64/0F27631293>) |

