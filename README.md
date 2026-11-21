# Mega-Man-9-MiSTer-FPGA-port
A faithful port of Mega Man 9 to the MiSTer FPGA platform with added features. 

**Mega Man is owned by Capcom, I own nothing.**

This project is fully LLM/AI coded, with about 90 hours of human QA so far and some custom spritework and soundtrack implementation done by myself.

This page will be updated with a proper github release with source code once it is organized and cleaned up as best as it can be for any potential human review or reuse. Issues/bug reports from current fully compiled versions released elsewhere will be attended to here for now. **Bug/issue reports welcome.**

**New features:**

Simultaneous 240p output from Analog I/O board, and 1080p output from HDMI port.

Charge/Slide version of Mega Man separate from the Normal version with his own single player campaign.

Playable Bass mode from Mega Man 10, with new graphics to interact with different stage obstacles and enemies, including shield enemies. His shop is also implemented.

Upgraded Proto Man mode from the original game, now with his shop from 10.

All 3 new characters have access to Hero, Superhero, Special Stage, Time Attack, and Endless Attack modes with updated local record keeping.

Easily moddable streaming music system using wav files and a tracklist plain text file with loop indicators and loop sample positions provided. This frees up all in game sound channels for sound effects.

**Known/WIP issues:**

Minor performance tweaks in the sound, music and graphics engines are needed.

Bass and Charge/Slide Modes need more bugtesting to find less obvious bugs.

Certain enemies do not play certain sound effects.

This will all be corrected through more testing and updates.
