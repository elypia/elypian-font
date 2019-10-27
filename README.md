# Elypian Font [![Discord][discord-members]][discord] [![Donate][donate-shield]][elypia-donate]

## About
A font based on the Elypia logo to write more sexy things to go with it.  
This project contains all SVGs (Scalable Vector Graphics) for each character,
and a SFD (Spline Font Database) to maintain and export the font files.

**_Anyone_** is free to use this font, for any purpose, free of charge.

## Introduction
### Inception
This font imagines that all characters are strips of paper, folded
similarly to origami to create shapes forming abstract lettering.  
Each strip is allowed to have up to one fold on each side to achieve this.  

### Grid
We replicate these shapes to the screen by simulating the folds on a 12
block tall grid.
Each cell in the aforementioned grid must be a square; these squares
will only ever be filled completely, or half-filled from opposite corners. 
The specifications will use grid cells to refer to sizes.

## Specification
The Elypia logo and font follow a specification to ensure consistency throughout 
all characters, and to objectively determine the optimal or most correct shape for them.

* Each strip must be a square of one grid cell or rectangle that is one cell wide.
* Strips may start with a slant by cutting one or both sides.
* Only the shorter side may be slanted.
* All slants that appear must slant at a 45 degree angle.
* Parralel slants should not be within one grid cell of eachother.
* All apertures must be 2 grid cells wide.
* All characters are a fixed 2 grid cells away from eachother.
* If a slant occurs between two strips that represent the same character,
the angle should face upwards or downwards _towards_ the corresponding strip. 

## FontForge
This font is being made and maintained using [FontForge][fontforge], a completely free and
open-source font editor that works on all major operating systems.

You can find their [GitHub repository here][font-forge-git]!

## Open-Source
This project is licensed under the [SIL Open Font License][license] ([TL;DR][license-tldr]), 
don't be afraid to derive or reference from this project however you want, but 
please rename your derivative work so it does not conflict with this.

[discord]: https://discord.gg/hprGMaM "Discord Invite"
[discord-members]: https://discordapp.com/api/guilds/184657525990359041/widget.png "Discord Shield"
[donate-shield]: https://img.shields.io/badge/Elypia-Donate-blueviolet "Donate Shield"
[elypia-donate]: https://elypia.org/donate "Donate to Elypia"
[fontforge]: https://fontforge.github.io/en-US/ "FontForge"
[font-forge-git]: https://github.com/fontforge "FontForge on GitHub"
[license]: https://scripts.sil.org/OFL "Official License Page"
[license-tldr]: https://tldrlegal.com/license/open-font-license-(ofl)-explained "TL;DR of License"