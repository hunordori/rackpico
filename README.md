# Purpose

Build a device to control my home lab rack fans automatically, monitor it remotely and connect to Home Assistant.

# Setup

The heart and soul of the projects is @tkjo's [fanpico](https://github.com/tjko/fanpico).
I used the Fanpico-0804D (v1.3) version with Power Board.

IMPORTANT: If you start from zero, you can use ONLY the Fanpico-0804D with 12V fans. I already had 3x 5V fans installed.

My setup has a Dig2Go, an internal fan and a 5V buck converter, but I included a more basic case with a lid. (Both of them are 1U high.)


# Hardware list

- fanpico 0804D (right angle connectors)
- fanpico power board (right angle connectors)
- 2x Noctua NF-A12x25 5V PWM
- 1x Noctua NF-A20 5V PWM
- 1x Noctua NF-A4x20 12V PWM
- 1x Noctua NF-A8 12 V PWM
- Dig2Go LED controller
- 2x 1-Wire temperature sensor
- 1x Kework micro USB extension (L-Micro)
- 12V 3A powersupply
- 2x B3950 Temperature sensor
- 1x USB-C 2pin power cable (right angle)

