# ESP32 RGB Display Performance

ESP32-S3 supports RGB displays using the LCD_CAM peripheral.

Rendering pipeline:

LVGL
↓
Framebuffer
↓
DMA
↓
LCD_CAM peripheral
↓
Display

Framebuffer size:

800 × 480 × 2 bytes = 768 KB

Recommended configuration:

Double framebuffer using PSRAM.
