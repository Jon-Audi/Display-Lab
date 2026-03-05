# LVGL Display Configuration

Recommended settings for 800×480 RGB displays.


LV_COLOR_DEPTH 16


Framebuffer allocation:

```cpp
heap_caps_malloc(size, MALLOC_CAP_SPIRAM | MALLOC_CAP_DMA);
```

Double buffering recommended.
