# 🖐️ PalmPainter

**PalmPainter** is a fully web-based application that lets you draw in the air using just your hand and a webcam — no controllers, no downloads. All magic happens right in your browser!



---

## ✨ Features

### 🎮 Control Modes
- **Draw Mode**: Pinch your thumb and index finger – 👌
- **Erase Mode**: Show a peace sign – ✌️
- **Change Color**: Point one finger upward – 👆

### 🖼️ Visual Interface
- Full-screen canvas for immersive drawing
- Real-time hand tracking using MediaPipe
- Color picker with cursor feedback
- Smooth, low-latency gesture control

---

## ⚙️ How It Works

PalmPainter uses advanced hand-tracking to convert gestures into digital brushstrokes:

- Tracks hand movement with **MediaPipe Hands** (21 key landmarks)
- Recognizes gestures in **real time** with basic vector analysis
- Applies **smoothing (factor: 0.36)** to reduce jitter and create natural lines
- Projects your finger movements into brushstrokes on the canvas

---

## 🗂️ Project Structure

PalmPainter/
├── index.html # Landing page with project showcase (no drawing logic)
├── app.html # Main drawing interface with video stream and canvas
├── app.js # All gesture recognition and drawing logic
├── app.css # UI and layout styles
├── assets/ # Optional: images, icons, banners

---


---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/mr-amanu3l/palmpainter.git

