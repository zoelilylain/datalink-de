# datalink-de
Datalink'd Environment (datalink'de pronounced data linked a), a Timex Datalink emulator written in C and ASM

This emulator aims to be a highly accurate emulation of the 75 and 150/150s models of the Timex Datalink. I would love to get help with this if you have the skills, info, or knowledge! especially contact me if you actually have a timex datalink 150/150s or 75, I need something to test against for accuracy.

# Target Platforms:
- PC (Very high priority)
- Emscripten (very low priority)
- GBA (high priority)

# TODO-ish
- emulation of hardware bits
- emulation of built-in watchapp features
- proper timekeeping (gba will require an rtc clock equipped cart)
- controls
- basically first the 75, then the 150
- loading of watchapps from a file (proposed extension being "dlprog")
- savestate
- failsafe for faulty rtc data (such as on malfunctioning EZFlash carts due to crystal oscillator failure)
- pogoshell loading of dlprog watchapps on gba (low priority)
