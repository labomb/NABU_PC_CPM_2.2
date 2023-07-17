# CP/M 2.2 for the NABU PC

This repository contains disk images and related configuration files that will enable booting a standard implementation of the CP/M version 2.2 operating system on the NABU PC.

 
## Features

* Supports multiple disk formats:
	- 5.25" single-side, double-density, 40 track, 48 TPI
	- 5.25" double-side, double-density, 80 track, 48 TPI
	- 3.5" double-side, double-density, 160 track, 96 TPI
* Dynamically re-configures for SSDD or DSDD disks on 5.25" drives
* Serial option board support
* Parallel port support
* Virtual 80 column mode
* ADM-3a terminal emulation
* Includes several customization utilities
* Official patches provided by DRI have been applied
* Uses standard DRI CP/M operating system components
* No external server software or network/RS-422 connectivity needed

 
## Directories

* The 'images' directory contains the CP/M boot disk and blank images
* The 'flashfloppy' directory contains a configuration file suitable for a Gotek device running the [flashfloppy firmware](https://github.com/keirf/flashfloppy)
* The 'cpmtools' directory contains the cpmtools utility disk definitions for the various image formats supported by this release of CP/M
* The 'extras' directory contains a disk image with WordStar version 4, configured for the ADM-3A terminal

 
## Prerequisites

- A floppy disk controller is required. You can find an excellent replica of the original floppy controller [here](https://klyball.com/nabu-page).
- A ROM that supports booting from floppy disks. Note that the standard ROM included with the NABU PC does *not* support booting from disk. An excellent alternative ROM that supports everything the original ROM does but with the added capability of booting from disks can be found [here](https://github.com/labomb/NABU_PC_Stuff/tree/master/ROM-version-14-patched).
- A serial board (available at the same floppy controller link above) is optional. The serial board opens up support for attaching a true 80 column terminal if desired, support for xmodem file transfers to/from the NABU PC using the included transfer utilities, and much more.

 
## Documentation

Please review the NABU_CPM_2.2_Readme.pdf file for an overview of this implementation of CP/M 2.2 and the included custom utilities.

 
# Bug reports, feedback, etc...

Please use the [github issues page](https://github.com/labomb/NABU_PC_CPM_2.2/issues) to report any problems.

>**Please Note:**
 I cannot provide general support for the NABU PC, it's usage, or issues that you may have with it. Accordingly, I ask that you please not post anything relative to general usage/issues/questions here. There are several other venues for these types of questions, including websites, forums, and a Discord server. Thanks!
 
