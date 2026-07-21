# Manufacturing Notes

## Confirmed from supplied outputs

- Generated using Altium Designer 24.10.1.
- Source PCB name: `RPI 3.PcbDoc`.
- Source project path references `RPI GPIO BOARD- V2.0`.
- Two signal layers are present: top copper and bottom copper.
- The NC drill report lists 73 plated through holes.
- Exported rules specify 10 mil minimum clearance, 10 mil minimum width, and 4 mil solder-mask expansion.

## Supplied layer files

The package includes selected copper, legend, mechanical, assembly, component-outline, courtyard, keep-out, drill, and report files. Several files referenced by the CAM report were not included in the uploaded set, including the dedicated profile, solder-mask, and top-side assembly outputs.

## Fabrication blockers

Do not send this package directly to fabrication until the following are available and checked:

1. Closed board-profile Gerber.
2. Top and bottom solder-mask Gerbers.
3. Complete plated and non-plated drill outputs.
4. Fabrication drawing with dimensions and tolerances.
5. Stack-up specification: material, thickness, copper weight, surface finish, and solder-mask color.
6. Netlist or IPC-356 file for connectivity verification.
7. Approved schematic and BOM.
8. Independent Gerber-viewer review.

## Suggested prototype specification

The following values are common prototype defaults but are **not encoded in the supplied files** and must be approved by the designer:

- FR-4 material
- 1.6 mm board thickness
- 1 oz copper
- HASL lead-free or ENIG finish
- Green solder mask
- White silkscreen

These are suggestions only, not source-derived design requirements.

## Assembly considerations

- Confirm the Raspberry Pi header orientation and pin-1 marking.
- Confirm relay coil voltage and contact rating.
- Confirm transistor pinout matches the selected footprint.
- Confirm diode polarity and whether each diode is a flyback diode, rectifier, or LED.
- Confirm resistor values for GPIO current and transistor drive.
- Confirm terminal-block pitch and current rating.
- Use standoffs compatible with the mechanical hole pattern.
- Perform first power-up with a current-limited bench supply and no external load.
