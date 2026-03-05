# CrowPanel DIS07050H

## Overview

The CrowPanel DIS07050H is a 7-inch ESP32-S3 touchscreen HMI development board.

## Main MCU

ESP32-S3-WROOM-1-N16R8

Specifications:

| Feature | Value |
|-------|------|
CPU | Dual-core Xtensa LX7 |
Clock | 240 MHz |
Flash | 16 MB |
PSRAM | 8 MB |
WiFi | 802.11 b/g/n |
Bluetooth | BLE 5 |

---

## Display

Resolution: 800 × 480
Interface: RGB Parallel (LCD_CAM peripheral)

Signals include:

R0–R7
G0–G7
B0–B7
HSYNC
VSYNC
DE
PCLK

---

## Touch Controller

GOODIX GT911

Interface: I²C

Features:

- capacitive multi-touch
- up to 5 touch points
- interrupt driven

Typical I²C address:

0x5D

---

## Audio

Amplifier chip: **NS4168**

Type: Class-D audio amplifier

Specifications:

| Feature | Value |
|------|------|
Output | 3W |
Supply Voltage | 2.5V – 5.5V |
Efficiency | up to 90% |

Used to drive onboard speaker.

---

## Storage

MicroSD card slot

Used for:

- assets
- images
- fonts
- audio files

---

## Development Frameworks

Supported:

ESP-IDF
Arduino
PlatformIO
