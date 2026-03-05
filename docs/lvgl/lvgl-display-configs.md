# LVGL Configuration for ESP32 RGB Displays

Recommended configuration for 800×480 displays.

---

## Color Depth

```
LV_COLOR_DEPTH 16
```

---

## Framebuffer Allocation

Allocate framebuffer in PSRAM.

Example:

```cpp
heap_caps_malloc(size, MALLOC_CAP_SPIRAM | MALLOC_CAP_DMA);
```

## Double Buffering

Recommended for smooth animation.

Benefits:

- reduced tearing
- smoother rendering
- higher FPS
