# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.


# Requirements
In order to build dmenu you need the Xlib header files.


# Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


# Running dmenu
See the man page for details.

# Credits
Originally developed by the [suckless team](https://suckless.org)

## Patches

catppuccin theme:
- Spaxly <@Spaxly>
- Cat <@Denperidge>
- Isabel <@isabelincorp>

fuzzyhighlight patch:
- Chris Noxz <chris@noxz.tech>
- Oleh Kopeykin <olehkopeykin@yandex.by>

fuzzymatch patch:
- Jan Christoph Ebersbach <jceb@e-jc.de>
- Laslo Hunhold <dev@frign.de>
- Aleksandrs Stier

vi mode patch:
- zerg <zergrusherncrusher@disroot.org>
