# Mega Man 9 MiSTer FPGA port

A faithful port of Mega Man 9 to the MiSTer FPGA platform with added features, targeting 128mb single SDRAM setups (Dual RAM setup compatible) and running the latest MiSTer unstable main.

**Mega Man is owned by Capcom, I own nothing.**

This project is fully LLM/AI coded, with about 90 hours of human QA so far by myself, Omorty, and kandowontu, and some custom spritework and soundtrack implementation done by myself.

This page will be updated with a proper github release with source code once it is organized and cleaned up as best as it can be for any potential human review or reuse. Issues/bug reports from current fully compiled versions released elsewhere will be attended to here for now. **Bug/issue reports welcome.**

**New features:**

Simultaneous 240p output from Analog I/O board, and 1080p output from HDMI port.

Charge/Slide version of Mega Man separate from the Normal version with his own single player campaign.

Playable Bass mode from Mega Man 10, with new graphics to interact with different stage obstacles and enemies, including shield enemies. His shop is also implemented.

Upgraded Proto Man mode from the original game, now with his shop from Mega Man 10.

All 3 new characters have access to Hero, Superhero, Special Stage, Time Attack, and Endless Attack modes with updated local record keeping.

W-tanks added to the shop.

Easily moddable streaming music system using wav files and a tracklist plain text file with loop indicators and loop sample positions provided. This frees up all in game sound channels for sound effects.

**Known/WIP issues:**

Minor performance tweaks in the sound, music and graphics engines are needed.

Bass and Charge/Slide Modes need more bugtesting to find less obvious bugs.

Certain enemies do not play certain sound effects.

**To do:**

Bugtesting and fixes.

Create simple ending sequences using existing assets for Bass and Proto Man modes; utilizing dialogue from other games or ancillary media (manga etc), that play before the credits sequence.

Playable Roll, with Mega Man 6 Power and Jet transformations via Tango, broom melee, and Mega Man 6 charge shot and slide. 

**Credits:**

GregarLink10 for the Honey Woman sprite sheet.

Yorkieyt and HANSUNGKEE for the Roll sprite sheet.

Mega Man 8-bit Deathmatch and Megaman Maker projects for various sprites.
