# doomlink
**doomlink** is a vanilla *Doom*, *[Chocolate Doom](https://www.chocolate-doom.org)* based native app port for the Steam Link.

## Installation
  - [Download the archive](https://github.com/fuzzymannerz/doomlink/archive/master.zip) and extract it.
  - Put the "*steamlink*" folder onto the root of a *FAT32* formatted USB stick.
  - Put the stick into the Steam Link and cycle the power.
    You should now see "**Doom**" on the main screen, if so - you can remove the stick.

## Defaults
By default **doomlink** works with a keyboard, it should also work with an Xbox controller and a Steam Controller (although I have only tested a wired Xbox 360 controller.)

## Configuration
If you wish to make changes and access the *Chocolate Doom* setup menu simply edit "*toc.txt*" and replace `doom` with `doom-setup` and change it back when you have saved the setup. This is easier done [over SSH]() to save keep messing about with a USB stick.

----

## License

*doomlink* is released under the same license as *Chocolate Doom* itself - GNU GPL.

Copyright (C) 2018  Fuzzy Mannerz

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.