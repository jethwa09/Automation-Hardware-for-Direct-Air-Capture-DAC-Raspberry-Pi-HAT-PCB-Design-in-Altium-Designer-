# Source Evidence and Assumptions

This document separates facts visible in the supplied files from engineering inferences used to create the project documentation.

## Directly supported

- Altium Designer 24.10.1 generated the files.
- The PCB source filename is `RPI 3.PcbDoc`.
- The project path contains `RPI GPIO BOARD- V2.0`.
- Top and bottom copper layers are present.
- Top and bottom legend layers are present.
- 73 plated through holes are reported.
- DRC-rule export values are 10 mil clearance, 10 mil width, and 4 mil solder-mask expansion.
- Visible designators include `K1`, `Q1`, `R1`–`R3`, `D1`–`D3`, and `P1`–`P3`.
- The board includes a Raspberry Pi-style 2x20 GPIO header and four mounting holes.
- The silkscreen contains ASU / CNCEL artwork and a V2.0 marking.

## Reasonable engineering inferences

- `K1` is an electromechanical relay footprint.
- `Q1` and `R1`–`R3` form a relay or load driver stage.
- One or more of `D1`–`D3` provide protection or visual indication.
- `P1`–`P3` connect external power or process equipment.
- The board was intended to switch or control laboratory Direct Air Capture hardware.

## Not established by the supplied files

- Connector pinout and net names.
- Relay part number, coil voltage, or contact rating.
- Transistor and diode part numbers.
- Resistor values.
- Board thickness, copper weight, laminate, or finish.
- Maximum safe load current or voltage.
- Whether formal Raspberry Pi HAT compliance requirements are met.
- Electrical test results, DRC pass status, assembly status, or field deployment.
- Individual contributor responsibilities.

Any public technical claim should remain within these boundaries unless additional source documents or test evidence are added.
