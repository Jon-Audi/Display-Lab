# ESP32 RGB Display Performance

The ESP32-S3 supports RGB displays using the LCD_CAM peripheral.

Rendering pipeline:

LVGL
↓
Framebuffer
↓
DMA
↓
LCD_CAM
↓
Display

---

## Framebuffer Size

```
800 × 480 × 2 bytes

= 768 KB
```

---

## Performance Tips

- Use PSRAM framebuffer
- Use DMA transfers
- Use double buffering
