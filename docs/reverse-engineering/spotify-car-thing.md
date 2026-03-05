# Spotify Car Thing — Reverse Engineering

## Overview

The Spotify Car Thing runs a Linux-based system on Amlogic S905D2 hardware.

Community projects have enabled custom firmware installation.

---

## Tools

Superbird toolkit

UART debugging

ADB over USB

Firmware extraction via eMMC

---

## Boot Chain

ROM
→ BL2
→ U-Boot
→ Linux Kernel
→ Spotify UI

## Notes

Custom firmware can replace the Spotify UI with a custom application.
UART pins are accessible on internal pads.
