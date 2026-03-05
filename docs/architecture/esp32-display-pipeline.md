# ESP32 Display Pipeline

Rendering pipeline:

LVGL
↓
Framebuffer
↓
DMA
↓
LCD_CAM peripheral
↓
RGB display

---

Framebuffer size:

800 x 480 x RGB565

768KB

---

Recommended configuration:

Double buffering using PSRAM.
