# Display-Lab

Display-Lab is a development knowledge base and firmware lab for ESP32 display systems.

Supported hardware:

- CrowPanel DIS07050H
- ESP32-8048S050
- Spotify Car Thing

This repository documents:

- hardware specifications
- ESP32 pinouts
- RGB LCD pipelines
- LVGL configuration
- networking dashboards
- OTA firmware updates
- reverse engineering notes

---

## Repository Structure

docs/ → documentation
drivers/ → hardware drivers
firmware/ → example firmware
diagrams/ → architecture diagrams

---

## Supported Development Frameworks

ESP-IDF
Arduino
PlatformIO + Arduino
PlatformIO + ESP-IDF

---

## Display Specifications

Typical display configuration used by these boards:

Resolution: **800x480**

Framebuffer (RGB565):

```
800 × 480 × 2 bytes = 768 KB
```

Recommended configuration:

Double buffering in PSRAM.

---

## Networking Features

WiFi
MQTT
HTTP API
Websocket updates
OTA updates

---

## UI Framework

LVGL (Light and Versatile Graphics Library)

Used for:

- dashboards
- smart home panels
- media controllers
- vehicle displays
