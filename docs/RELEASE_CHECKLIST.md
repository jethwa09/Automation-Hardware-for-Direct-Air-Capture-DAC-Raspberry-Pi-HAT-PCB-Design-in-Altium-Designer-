# GitHub Release Checklist

## Documentation

- [ ] README accurately states project purpose and status
- [ ] Personal contribution is described precisely
- [ ] Schematic PDF is included
- [ ] Connector pinout is included
- [ ] BOM contains manufacturer part numbers
- [ ] Architecture diagram matches the schematic
- [ ] Assembled-board photos are included
- [ ] Demo video or GIF is linked

## Design verification

- [ ] Schematic ERC completed
- [ ] PCB DRC completed with zero unexplained violations
- [ ] Board outline verified
- [ ] Header orientation verified
- [ ] Relay and transistor ratings verified
- [ ] Trace-current capacity reviewed
- [ ] Mounting-hole fit checked
- [ ] Gerbers reviewed in an independent viewer

## Bench validation

- [ ] Current-limited power-up completed
- [ ] GPIO idle state tested
- [ ] Relay switching tested
- [ ] Flyback transient measured
- [ ] External connector continuity verified
- [ ] Rated-load thermal test completed
- [ ] Repeated-cycle endurance test completed

## Release package

- [ ] Source `.PrjPcb`, `.SchDoc`, and `.PcbDoc`
- [ ] Complete Gerber set
- [ ] NC drill files
- [ ] BOM
- [ ] Pick-and-place file
- [ ] Fabrication drawing
- [ ] Assembly drawing
- [ ] Test report
- [ ] License
- [ ] Version tag and release notes
