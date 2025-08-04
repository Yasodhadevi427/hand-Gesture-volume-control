
# Hand Gesture Volume Control 🎚️✋

This project is a **real-time computer vision system** that allows you to control your computer's system volume using just your **hand gestures**. It uses your webcam to detect hand landmarks, calculates the distance between your fingers, and changes the volume accordingly.

##  Features

- Detects hand gestures using a webcam
- Measures the distance between thumb and index finger
- Maps finger distance to system volume
- Real-time volume feedback
- Smooth volume transitions

## Technologies Used

- **Python**
- **OpenCV** - For webcam access and drawing
- **MediaPipe** - For hand tracking and landmark detection
- **Pycaw** - To control system volume on Windows
- **comtypes** - Support library for Pycaw

##  How It Works

1. Capture video using your webcam.
2. Detect your hand using MediaPipe.
3. Measure the distance between your thumb and index finger.
4. Map that distance to a volume level.
5. Control system volume accordingly.

##  How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/gesture-volume-control.git
cd gesture-volume-control
