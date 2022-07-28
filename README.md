# ppide-z50
PPIDE card for Z50Bus

Heavily based on https://github.com/electrified/rc2014-82c55-ide

Intended for use with a horizontal-mounting 44-pin IDE Disk-On-Module module, this card omits the 40-pin IDE connector and external power input jack.

Notes:
1. Address selection is with the jumper pins in the lower right. Address bits A1 and A0 are ignored. Set to 0x20 (one jumper, on pin A5) for use with RomWBW and/or Fuzix.
2. You may wish to lower the value of R101 or use a super-bright LED if the disk activity light is a bit dim.

![Image](/doc/pcb.jpg)

| Reference |  Value |
|-----------|--------|
| R101 | 470R resistor or lower value suitable for your LED |
| R102 | 10K resistor |
| R103 | 10K resistor |
| R104 | 10K resistor |
| C101 | 0.1uF ceramic capacitor |
| C102 | 0.1uF ceramic capacitor |
| C103 | 0.1uF ceramic capacitor |
| RN101 | 10K SIP resistor (8 pins, 7 resistors) |
| D101 | LED |
| U101 | 74HCT688 |
| U102 | 74HCT04 |
| U103 | 82C55A (PLCC package) |
| J101 | 2x25 2.54mm right-angle male box header |
| J102 | 2x8 2.54mm pitch right-angle pin header |
| J103 | 2x22 2mm pitch pin header |


![Image](/doc/assembled.jpg)
