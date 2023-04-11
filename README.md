# Awesome DS Development

An opinionated, curated list of awesome NDS/DSi development resources and tools. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## Contents

- [Documentation](#documentation)
  - [Datasheets](#datasheets)
- [Software Development](#software-development)
  - [Toolchains](#toolchains)
  - [Libraries](#libraries)
    - [Graphics](#graphics)
    - [Audio](#audio)
    - [Other](#other-libraries)
- [Open-source Homebrew](#open-source-hombrew)
  - [Games](#games)
  - [Applications](#applications)
  - [Demos](#demos)
  - [Other](#other-homebrew)
- [Emulators](#emulators)
- [Historical](#historical)

## Community

- [GBAdev Discord](https://discord.io/gbadev) - while GBA-centric, it contains a small sub-section for NDS development.
- [devkitPro Forums](https://devkitpro.org/index.php) - the best place for getting support pertaining to the devkitARM toolchain.

## Documentation

- **[GBAtek](https://problemkaputt.de/gbatek.htm)** (multi-megabyte HTML, [paged version](https://problemkaputt.de/gbatek-contents.htm)) - the terse go-to reference for everything DS/DSi. It covers about 97% of everything there is to know about the devices. Supplementary information is provided in the following documents:
  - [GBAtek addendum/errata](https://melonds.kuribo64.net/board/thread.php?id=13) - a thread which compiles many niche and edge-case aspects not covered in GBAtek
  - [Additional notes on W_POWERFORCE/W_US_COUNT/W_RXFILTER (Arisotura, September 4th, 2022](https://forums.nesdev.org/viewtopic.php?p=282881#p282881)

### Datasheets

- [Seiko S-35180A](http://www.hico.com.hk/seiko/s35180a_e.pdf) - NDS real-time clock
- [Seiko S-35199A01](https://www.mouser.com/datasheet/2/360/SIISS03574_1-2514274.pdf) - DSi real-time clock

## Software Development

### Toolchains

- [devkitARM](https://devkitpro.org/) - the community standard toolchain, maintained by the devkitPro organization.
  - devkitPro and devkitARM are [trademarks](https://devkitpro.org/wiki/Trademarks) of Dave Murphy. This document is not endorsed by or connected to devkitPro.
- [BlocksDS](https://github.com/blocksds/sdk) - a newer toolchain, maintained by AntonioND.

### Libraries

#### Graphics

- [NightFox's Lib](https://github.com/knightfox75/nds_nflib) (MIT) - high-level wrapper for tilemaps, sprites and collision maps, using the 2D engine.
- [Nitro Engine](https://github.com/AntonioND/nitro-engine) (MIT) - high-level wrapper for the 3D engine; models, textures, text, GUI, physics.

#### Audio

- [maxmod](https://maxmod.devkitpro.org/) (BSD) - highly capable and efficient ARM7 .MOD/.S3M/.XM/.IT-compatible playback engine, written in ASM.
- [libxm7](https://github.com/blocksds/libxm7) (MIT) - .MOD/.XM playback engine.

#### Other Libraries

- [posprintf](http://www.danposluns.com/gbadev/posprintf/index.html) - tiny, limited sprintf()-like library written in ARMv4 ASM.

## Open-source Homebrew

### Games

### Applications

* [NitrousTracker](https://github.com/asiekierka/nitrotracker/) (GPLv3) - DSi-compatible, enhanced fork of NitroTracker
* [uxnds](https://github.com/asiekierka/uxnds) (MIT) - [varvara](https://wiki.xxiivv.com/site/varvara.html) virtual machine implementation

### Demos

### Other Homebrew

## Emulators

- [melonDS](https://melonds.kuribo64.net/)
- [DeSmuME](https://desmume.org/)
- [NO$GBA](https://problemkaputt.de/gba.htm)

## Historical

These are links to files and sources which are noteworthy from a historical perspective, but have been superseded.

- [Introduction to Nintendo DS Programming (2008)](https://www.patater.com/files/projects/manual/manual.html) - a crucial tutorial in the early days of Nintendo DS homebrew.
- [The History of DS Homebrew (2008)](https://web.archive.org/web/20081022153947/http://www.ndshb.com/modules.php?name=Content&pa=showpage&pid=40&page=1) by James "Lynx" Zawacki - an oral record of the first years of the homebrew scene.
