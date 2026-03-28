# AI Fire & Smoke Detection System
# 🔥 AI Fire & Smoke Detection System

An AI-powered real-time fire and smoke detection system built using Python, OpenCV, and YOLOv8.

This project monitors live video feed (webcam or video file), detects fire or smoke events, captures evidence images, and logs detection timestamps.

Designed for:
- AI & Computer Vision learning
- Smart safety monitoring systems
- Engineering mini/major projects
- Hackathons

---

## 🎯 Features

- Real-time video monitoring
- Fire detection
- Smoke detection
- Automatic image capture
- Timestamp logging
- Works with webcam or video file
- Lightweight YOLO-based detection pipeline

---

## 🧠 Tech Stack

- Python 3.10+
- OpenCV
- Ultralytics YOLOv8
- Pre-trained / Custom-trained YOLO model

---

## 📂 Project Structure

AI_Fire_Smoke_Detection_System/
│
├── main.py
├── detector.py
├── config.py
├── requirements.txt
├── logs/
├── captures/
└── README.md

---

## ⚙️ Installation

1. Install Python 3.10 or later.
2. Clone the repository:

   git clone <your-repository-link>

3. Navigate to the project folder:

   cd AI_Fire_Smoke_Detection_System

4. Install dependencies:

   pip install -r requirements.txt

5. Run the system:

   python main.py

---

## ⚠️ Important Note

The default YOLOv8 COCO model does NOT include fire or smoke classes.

For accurate detection:
- Train a custom YOLO model on a fire/smoke dataset
- Replace the model file in `detector.py` with your trained weights

This repository provides the full detection pipeline structure ready for integration with a trained model.

---

## 🖥 System Requirements

Minimum:
- Windows 11
- 8GB RAM
- Webcam or video input

Recommended:
- NVIDIA GPU for faster inference

---

## 📸 How It Works

1. Live video is captured from webcam or file.
2. YOLO model processes each frame.
3. If fire or smoke is detected:
   - Bounding box is drawn
   - Image is saved in `/captures`
   - Event is logged in `/logs`

---

## 🔒 Ethical & Safety Disclaimer

This project is for educational and research purposes only.  
It should not be used as a certified fire safety system without proper validation and compliance with safety standards.

---

## 📈 Future Improvements

- Email/SMS alert integration
- IoT alarm trigger (ESP32 / Raspberry Pi)
- Real-time dashboard
- Cloud notification system
- Confidence threshold adjustment UI
- Heatmap visualization

---

## 👨‍💻 Author

Developed as an AI-based safety monitoring project.
Real-time fire and smoke detection system using YOLOv8 and OpenCV.

⚠ IMPORTANT:
Default YOLOv8 COCO model does not include fire/smoke classes.
For accurate detection, use a custom-trained fire/smoke YOLO model.

## Features
- Real-time video monitoring
- Fire and smoke detection
- Automatic image capture
- Timestamp logging
- Webcam or video file support

## Setup

1. Install Python 3.10+
2. Install dependencies:
   pip install -r requirements.txt
3. Run:
   python main.py

Replace model with a trained fire/smoke model for real-world use.
