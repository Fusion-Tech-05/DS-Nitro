# DS-Nitro
My attempt at an open source DS flashcart.

The goal for this project is to create a DS flash cart that is open source, IDK if this exists currently but I want it too.

-----------------------------------------------------------------------------------------------------------------------------
Current features I know I can add (I am still trying to learn the SDIO interface so this is just stuff I know I will be able to do eventually):
 - Works on the DS/DS lite.
 - SDSC/SDHC/SDXC support -- The flashcart might not use SD cards so this is kinda uncertain if it's gonna be used or not at all.
 - Can save games to SD card/NAND.
 - Can play games without anti-piracy measures built in (so only the anti-piracy measures that the DS has included, which are by-passed by the flashcart upon boot) can be run.
 - Has an integrated IR sensor and receiver.
-----------------------------------------------------------------------------------------------------------------------------
Currently planned feautres.
 - Okay, so micro SD cards as a format are not great, mainly they are weak and unreliable, so the current plan is to use a built in NAND storage inside the flashcart, a bit like how the ncard worked. MT29F512G08CFCBBWP-10ES:B TR will be the nand chip of choice, purley because this is the only NAND chip I could find that was in the easy to solder TSOP package and had at least 64 gigabytes of storage (it's around 64 gigabytes in size).
 - Uses ESP32 Wifi features such as being able to share files/ROMS between DS NITROs, connect to some sort of desktop/mobile app to easily send ROMS to the DS NITRO over wifi, maybe external controller support, and whatever else I or developers choose to do with it.
 - Has an integrated USB C port for transfering ROMS to the DS NITRO, upgrading the FIRMWARE or OS of the flashcart, letting DS NITROs communicate with eachother for FILE transfer, acting as GBA link cable for emulaltors that could use it that way, and what ever else I or developers choose to do with it.
- Perfect game compatibility, both with included emulators and DS games.
- Integrated IR sensor.
- A custom OS maybe based off an existing solution, but unlikely due to the way the hardware is. This OS will handel control over all the software based features, such as wifi features and so on. This custom OS will be really fast, look amazing with lot's of 3D rendered graphics, and fully support the touch screen. It will also have the ability to let you change themes, including any and all icons being able to be changed in every theme, and so much more. The OS wil also be able to have powerful file manipulation tools, including but not limited too, changing names of files, deleting files, copying files, moving files, bulk moving files, creating folders, deleting folders, enable and disabling and editing features to ROMs (such as Real Time Save, Real Time Guid, Real Time Cheats, handeling multiple saves and how they work, and so on), and so much more.
- If I can figure out how to get this too work, support for homebrew games and applications to be as large as they want, without any impact.
- Perfect game compatibiltiy.
- Perfect homebrew compatibility.
- Perfect console compatibility.
- DSi ROM support, without using NTR boot.
-----------------------------------------------------------------------------------------------------------------------------

-- Everything below here hasn't been properly edited for the new goals of the project, I will do that later.

Required Features:
1. Works on the DS and DS lite.
2. Supports SD cards up to SDHC or intergrated NAND storage.
3. Can save game save files to the SD card or NAND directly.
4. Can automatically patch games, the same as what most moddern ds flash carts can do with perfect game compatibility.
5. Works on the DS and DSL.

Nice to have Features:
1. Supports sd cards up to sdxc or uses high capacity NAND storage.
2. Works with ds download play.
3. Has a built in IR for games that can untilise it.
4. Works with the ds rumble pak and the ds ram pak and slot 2 flash carts.
5. Can run emulators that emulate NES, SNES, GB, GBC, MS, MD, etc.
6. Can work on the 3DS, 2DS, New 3DS, New 2DS, DSi, DS lite, DS floorlessly no matter the software version (so perfect hardware compatibility).
7. Cheats system.
8. GBA Wirless system.
9. Real time save that works most the time without having the chance to break the ROM the RTS is tied too.
10. Fast software to complement the fast hardware of the DS NITRO.
11. Can use both Fat32 and ExFat -- not required if NAND storage is used.
12. The flashcart is cheap.

Potential Features, really extra features that I don't plan to implement until everything else is done or mostly done.
1. Built in CPU and RAM a bit like the Supercard dstwo, hopefully a lot more powerful one that can emulate consoles such as the 3DS, New 3DS or PSP, although the more likely target is perfect PS1 emulation (not accuracy but performance, this is due to cost reasons (with the goal of keeping this flashcart as cheap as possible and all) and how difficult it would be to implement a CPU powerful enough to emulate the 3DS, New 3DS or PSP).
2. The built in RAM can be utilised by applications such as the DS Internet Browser and emulators that would usually use a slot 2 RAM pak (these applications would have to be custom built for the DS nitro, of course).
3. An internet card and internet browser that have far expanded capabilities to the original, supporting moddern protocols and modern browser features (this might be done via a slot 2 expansion card that pairs with the DS NITRO!).




