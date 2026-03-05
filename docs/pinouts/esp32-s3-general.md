# ESP32-S3 General Pinout

## Overview

General GPIO reference for ESP32-S3 based display boards.

---

## RGB LCD Signals (LCD_CAM peripheral)

| Signal | Description |
|--------|-------------|
R0–R7 | Red channel |
G0–G7 | Green channel |
B0–B7 | Blue channel |
HSYNC | Horizontal sync |
VSYNC | Vertical sync |
DE | Data enable |
PCLK | Pixel clock |

---

## I²C (Touch Controller)

| Signal | Description |
|--------|-------------|
SDA | Data |
SCL | Clock |
INT | Interrupt |
RST | Reset |

---

## SPI (microSD)

| Signal | Description |
|--------|-------------|
MOSI | Master out |
MISO | Master in |
SCK | Clock |
CS | Chip select |

---

## Notes

Exact GPIO numbers vary by board manufacturer.
Always verify against the specific board schematic.
