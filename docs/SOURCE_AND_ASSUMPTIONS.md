# Source Evidence and Assumptions

## Directly supported by the supplied files

- Altium output project name: `RPI GPIO BOARD - V2.0`
- Output-generation date: January 30, 2025
- Two copper signal layers
- Top and bottom solder mask, legend, paste, assembly, courtyard, and component documentation layers
- Board profile and mechanical outputs
- Raspberry Pi 40-pin header visible in the Gerber-derived board view
- Designators `K1`, `Q1`, `R1`–`R3`, `D1`–`D3`, and `P1`–`P3`
- 73 plated through holes
- 10 mil minimum width and clearance rules
- 4 mil solder-mask expansion rule

## Engineering inferences

- `K1` is treated as a relay footprint because of its reference designator and geometry.
- `Q1` and the nearby resistors are described as a likely relay-driver network.
- `D1`–`D3` may provide protection, polarity control, or status indication.
- `P1`–`P3` are treated as field connectors.
- The board is described as HAT-style because it interfaces with a Raspberry Pi 40-pin header; formal HAT compliance is not established.

## Not supported by the supplied archive

- Exact net names or connector pin assignments
- Part numbers and electrical ratings
- Board stack-up material, thickness, copper weight, or surface finish
- Schematic connectivity
- BOM and procurement data
- Pick-and-place data
- Test results, assembled-board photos, or working demonstration
- Editable Altium source files

All application-level descriptions should therefore be treated as documentation context rather than a substitute for the missing schematic and BOM.
