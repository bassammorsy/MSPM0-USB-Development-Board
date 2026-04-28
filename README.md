# MSPM0 USB Development Board

A 2-layer development board built around the Texas Instruments MSPM0
microcontroller, designed for prototyping and peripheral interfacing
via USB-C.

## Features
- TI MSPM0 microcontroller
- USB-C connector with CH340 USB-to-UART bridge for serial communication
- Manually routed USB differential pair with impedance matching
- Crystal oscillator with datasheet-compliant layout guidelines
- I2C header for connecting external sensors and peripherals
- Hardware reset circuit via NRST line
- Decoupling capacitors on all IC power pins
- 3.3V power regulation from 5V VBUS
- Dual-layer GND copper pour
- Mounting holes at all four corners

## Specs
- Layers: 2
- Pads: 205
- Nets: 61
- Track Segments: 328

## Tools
- KiCad 9

## Files
- `/gerbers` — fabrication-ready Gerber and drill files
- `MSPM0.kicad_pcb` — PCB layout
- `MSPM0.kicad_sch` — schematic
- `MSPM0.kicad_pro` — project file
