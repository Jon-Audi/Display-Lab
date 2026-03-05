# LVGL Configuration

Recommended settings for ESP32 RGB displays.

LV_COLOR_DEPTH = 16

Memory allocation example:

heap_caps_malloc(size, MALLOC_CAP_SPIRAM | MALLOC_CAP_DMA)

Double buffering improves animation performance.
