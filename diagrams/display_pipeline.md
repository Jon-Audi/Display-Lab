# Display Pipeline Diagram

```
LVGL
  │
  ▼
Framebuffer (PSRAM)
  │
  ▼
DMA Transfer
  │
  ▼
LCD_CAM Peripheral (ESP32-S3)
  │
  ▼
RGB Parallel Interface
  │
  ▼
TFT Display (800×480)
```

Framebuffer size: 768 KB (RGB565)
Double buffer: 1.5 MB
