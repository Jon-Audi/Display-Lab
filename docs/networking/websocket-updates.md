# WebSocket Updates

WebSockets allow real-time push updates from a server to the display.

---

## Flow

Server sends data
↓
WebSocket client receives message
↓
Event bus dispatches update
↓
UI widget refreshes

---

## Use Cases

Live sensor readings
Real-time dashboards
Media playback state
