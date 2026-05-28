---
weight: 3
---

# Files

## Roms

All roms must have proper extensions. Only the extensions gb, gbc, gba, and nds 
are supported.

## Saves

Save files are generated or overwritten at runtime, they will always be in the 
same directory as rom, with the same file path except with an additional ".save"
at the time. The rom "./mario.nds", will have the save "./mario.nds.save".

## Bios / Firmware

Bios and firmware files are not required. The emulator uses Drastic open source
alternatives bios files. If you do want to include bios and firmware files, add them
through the config.toml or settings ui.
