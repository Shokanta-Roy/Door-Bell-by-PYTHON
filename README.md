# Door-Bell-by-PYTHON
A smart doorbell system using OpenCV and face recognition that plays a doorbell sound when a face is detected.

# Smart Door Bell using Python 🎯

A simple yet effective smart doorbell system that uses your webcam to detect faces and rings a doorbell sound when someone is at your door.

## 🔧 Technologies Used
- Python
- OpenCV (cv2)
- face_recognition
- pygame (for sound)
- threading

## 🚀 How It Works
- The system continuously scans for faces using your webcam.
- If a face is detected, it plays a doorbell sound once.
- If the face disappears and comes again, it rings again.

## 🔊 Features
- Real-time face detection
- Plays sound only once per detection
- Sound control using pygame mixer
- Lightweight and fast

## ✅ Requirements
- `opencv-python`
- `face_recognition`
- `pygame`

## ▶️ Run the Code
```bash
python main.py
