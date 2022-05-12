# MiSTer_Pix
.pix images for the [MiSTer_i2c2OLED](https://github.com/venice1200/MiSTer_i2c2oled) project by venice1200.

Images are 128x64 and intended for a one-color 0.96" SSD1306 OLED.  They'll work any 128x64 display compatible with the project, but might look funny on a two-color display.

The goal is not to create images for every core, but for the "AAA" stuff (consoles, CPS1/2, and the like).

Note that *i2c2oled-system.ini* must be edited if using *loading.pix* from this collection:

**Line 464** (under the *Show Loading Screen* function)
- From `set_cursor 24 5`
- to `set_cursor 24 3`

---

### IMMEDIATE:
- Finish console core pix
- CPS0
- CPS1
- CPS2
- SEGA

### LONG-TERM:
- Major arcade games from Konami, Data East, etc.
- (maybe) NeoGeo MRA project
