# KIM-1 Replica

## Introduction

Welcome to the MOS KIM-1 reproduction project repository, where you will find what aims to be a faithful replica of the MOS KIM-1 computer, in particular a revision "D" PCB, based on photos and information gathered from various sources on the internet. With minimal modifications, later revisions should be easy to reproduce as well.

The KIM-1 was a single-board computer released in 1976 by MOS Technology, later acquired by Commodore, as a demonstrator of the capabilities of the recently released 6502 microprocessor.

## About

This recreation has been an excruciating process using entirely free software: Inkscape, Kicad and Freecad.

First, a high resolution image of a KIM-1 was used as a template in Inkscape. The image was resized to scale using the IC footprints as a reference. Then, the rest of the footprints were placed and the tracks were traced using bézier curves. I used a layer for each type graphic components (footprints, tracks, copper zones, typography, ...)

The logo was created from the MOS logo, adding the commodore name with the [Eurostile Extended 2 Bold font](https://fontsgeek.com/fonts/eurostile-extended-2-bold).

Component references where placed with the [Futura STD Bold font](https://fontsgeek.com/fonts/Futura-Std-Bold). The [Arial-like Aria font](https://fontsgeek.com/aria_1-font) was used for other typography.

The inkscape image was imported from Kicad to an user layer and used as a template for placing the footprints. Then, the image with the tracks was imported to the copper layer and converted to kicad tracks, so it was possible to check the pcb against the schematic.

The logo and the typography were converted to footprints using the svg2shenzhen plugin.

This is the end result:

![components](https://github.com/eduardocasino/kim-1/raw/main/images/kim-1-comp.png)
![front](https://github.com/eduardocasino/kim-1/raw/main/images/kim-1-front.png)
![back](https://github.com/eduardocasino/kim-1/raw/main/images/kim-1-back.png)


WARNING: I have not yet sent the board to fabrication, so it is untested!

## Licensing

This is a personal project that I am sharing in case it is of interest to any retrocomputing enthusiast and all the information in this repository is provided "as is", without warranty of any kind.  

[![license](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

See the license.md file for details.

## Acknowledgements

* Hans Otten and his [Retro Computing blog](http://retro.hansotten.nl/). Tons of information and high resolution pictures of various KIM-1
* Chuck Hutkins, for his [hi-res scans of an unpopulated Rev. D PCB](http://retro.hansotten.nl/6502-sbc/kim-1-manuals-and-software/kim-1-revisions/)
* Budi Prakosa "badgeek" for the [svg2shenzhen](https://github.com/badgeek/svg2shenzhen) plugin for Inkscape
* Ralf (User ralf02 from forum64.de) for info on actual dimensions of a KIM-1 and ideas from [his thread on a KIM-1 clone](https://www.forum64.de/index.php?thread/124855-instandsetzung-und-nachbau-eines-kim-1/).