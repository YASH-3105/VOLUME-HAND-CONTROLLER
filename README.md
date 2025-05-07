# VOLUME-HAND-CONTROLLER
# 🖐️ Hand Gesture Volume Control

This project uses your webcam to track your hand using **MediaPipe** and adjust the system volume based on the distance between your thumb and index finger.

---

## 📸 Demo

> [▶️ Click here to watch the demo](demo.mp4.mp4)

---

## 💡 Features

- Real-time hand tracking using webcam
- Adjusts system volume using finger distance
- Visual feedback with OpenCV
- Displays current FPS on screen

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Webcam
- Windows (Pycaw only supports Windows for volume control)

### Installation

```bash
git clone https://github.com/your-username/HandGestureVolumeControl.git
cd HandGestureVolumeControl
pip install -r requirements.txt

🛠️ Technologies Used
OpenCV

MediaPipe

PyCaw

Python

📂 Project Structure
Copy
Edit
HandGestureVolumeControl/
├── HandTrackingModule.py
├── VolumeHandControl.py
├── requirements.txt
└── README.md
