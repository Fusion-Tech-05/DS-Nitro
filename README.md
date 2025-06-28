# I need a new name for this flashcart.
My attempt at an open source DS flashcart.

The goal for this project is to create a DS flash cart that is open source, IDK if this exists currently but I want it too.

-----------------------------------------------------------------------------------------------------------------------------
Required features.
 - Works on the DS/DS lite.
 - SDIO/SDHC/SDXC support (so SD cards from the smallest possible up to 2 Terrabytes).
 - Can save games to SD card (the player chooses this on the first run of the game).
 - Can play games without anti-piracy measures built in (so only the anti-piracy measures that the DS has included, which are by-passed by the flashcart upon boot) can be run.
 - Has an integrated IR sensor/blaster.
 - Fully legal.
-----------------------------------------------------------------------------------------------------------------------------
Planned feautres.
- A dual storage solution, with both Micro SD card support and NAND support, like the Acekard RPG, except the NAND is a higher capacity and it is not based off any Acekard hardware.
- An integrated USB-C port, or maybe some other kind of port that is easier to fit within the form factor, for upgrading the firmware or flashing new information to the FPGA.
- Perfect game compatibility.
- Integrated IR sensor/blaster for games that can use it.
- A custom kernel that can do the following: allow the integrated IR sensor to get full use, use a custom DLDI autopatcher that allows for homebrew that uses the IR sensor/blaster and more powerful file manipulation, so in theory you could fully organise your files without using a PC with ease including creating new folders and re-naming files, .
- Perfect game, homebrew and console compatibility, in a perfectly legal way.
- Supports booting DSi ROMs and DSi mode homebrew without a modded console.
- GBA wireless system support.
- Use the built in IR sensor for GBA games hthat require IR support but the cartridge it's being run off doesn't have it.
- Hardware based real time save that works with all games flawlessly.
- Can use both Fat12/Fat16/Fat32 (required) and ExFat (doesn't exist elsewhere, Fat32 is often only supported) Micro SD formats.
-----------------------------------------------------------------------------------------------------------------------------
Nice to have features (these features will be included on a later, seperate flashcart likely).
- Built in CPU and RAM like the Supercard DSTWO, except likely more powerful.
- The RAM within the flashcart can be used with games instead of the RAM built into external GBA cartridges.
- A built in WiFi card, this might be built into a seperate GBA flashcart.
- 3DS game support, even though custom firmware will be better, this will be more or less a 'why not?' feature.
-----------------------------------------------------------------------------------------------------------------------------
Current Parts List:
- Maybe this 64GB NAND chip, purley because of it's size, and that it's in the TSOP form factor, very easy to solder with: MT29F512G08CFCBBWP-10ES:B TR
- FPGA - Latice IceBreaker ICE40UP5K-SG48ITR
- Micro SD Slot - microSD_HC_Hirose_DM3D-SF
- Some SOIC-8 form factor SPI NAND that can run off 3.3v
- Resistor of some value, I don't know what yet.
-----------------------------------------------------------------------------------------------------------------------------



