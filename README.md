# ppide-z50
PPIDE card for Z50Bus

Heavily based on https://github.com/electrified/rc2014-82c55-ide

Intended for use with a horizontal-mounting 44-pin IDE Disk-On-Module module, this card omits the 40-pin connector and external power input jack.

Notes:
1. Address selection is with the jumper pins in the lower right. Address bits A1 and A0 are ignored. Set to 0x20 (one jumper, on pin A5) for use with RomWBW and/or Fuzix.
2. You may wish to lower the value of R1 or use a super-bright LED if the disk activity light is a bit dim.

![Image](/doc/pcb.jpg)
