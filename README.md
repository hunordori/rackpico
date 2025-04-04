# Purpose

Build a device to control my home lab rack fans automatically, monitor it remotely and connect to Home Assistant.

# Setup

The heart and soul of the projects is [@tjko](https://github.com/tjko)'s [fanpico](https://github.com/tjko/fanpico).
I used the Fanpico-0804D (v1.3) version with Power Board.

IMPORTANT: If you start from zero, you can use ONLY the Fanpico-0804D with 12V fans. I already had 3x 5V fans installed.

My setup has a Dig2Go, an internal fan and a 5V buck converter, but I included a more basic case with a lid. (Both of them are 1U high.)

3D files: https://makerworld.com/en/models/950427

The setup file contains everything, but I have 4 temperature sensors:
- intake (bottom)
- top
- rear
- switch (middle of my 48 Port POE switch)
and 5 fans (intake, top, back, Pfsense, and the fanpicos internal).

# Hardware list

- [fanpico 0804D](https://github.com/tjko/fanpico) (right angle connectors)
- [fanpico power board](https://github.com/tjko/fanpico/tree/main/boards/power-board) (right angle connectors)
- 2x Noctua NF-A12x25 5V PWM
- 1x Noctua NF-A20 5V PWM
- 1x Noctua NF-A4x20 12V PWM
- 1x Noctua NF-A8 12 V PWM
- [dig2Go](https://quinled.info/quinled-dig2go/) LED controller
- 2x 1-Wire temperature sensor
- 1x Kework micro USB extension (L-Micro)
- 12V 3A powersupply
- 2x B3950 Temperature sensor
- 1x USB-C 2pin power cable (right angle)

# Schematics

![Schematics](https://github.com/hunordori/rackpico/blob/main/fanpico_schematics.png)

# Final build

![installed rackpico](https://github.com/hunordori/rackpico/blob/main/pics/rackpico_installed.jpg)

![fanpico internal](https://github.com/hunordori/rackpico/blob/main/pics/rackpico_nolid.jpg)

