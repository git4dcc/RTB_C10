# RTB_C10
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Kicad_Libs](https://img.shields.io/badge/Kicad_Libs-29C7FF)](https://github.com/git4dcc/RTB_SamacSys)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

The RTB Bus Master connects the PC with the layout via USB.

<img src="https://rtb4dcc.de/wp-content/uploads/2024/07/C10_2.png">

# Hardware
My current PCB layout uses SMD footprints with 0.4mm pitch and postly 0603 parts. Reflow soldering is my recommendation, but with some experience handsoldering is also possible.

## PCB
- 4-layer PCB, FR4, 1.6mm
- CPU: AVR64DB48
- USB: FT232X (Mini-B)

## Kicad
:yellow_circle: Dependency: Requires my Kicad project library [RTB_SamacSys](https://github.com/git4dcc/RTB_SamacSys)

[Schematic](doc/C10_schematic.pdf) | [Layout](doc/C10_layout.pdf)

## Firmware
Filename structure: { **pcb** }{ **code** }{ **version** }.hex

Example: **C10F0001**.hex

|   | Description |
| --- | --- |
| **pcb** | Name of matching hardware (**C10**) |
| **code** | Type of code contained (**R**=rom, **B**=bootloader, **F**=flash, **U**=bld update, **P**=UPDI factory code) |
| **version** | Release version (**####**) |

## UPDI

## Debug Interface

# Software

# Images
