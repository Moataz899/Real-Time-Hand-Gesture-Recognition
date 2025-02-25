# 🚀 Real-Time Hand Gesture Recognition using OpenCV & MediaPipe 🤖🖐️

## 📌 Project Overview

In this project, I implemented a **real-time hand gesture recognition system** using **Python, OpenCV, and MediaPipe**. The system detects and tracks hands in real-time, recognizing various gestures and displaying corresponding emojis on the screen.

## 🔍 How It Works

The project follows a structured pipeline for gesture recognition:

- **🖐️ Hand Tracking** – Utilizes **MediaPipe Hands** to detect and track hand landmarks.
- **📐 Angle Calculation** – Computes angles between key landmarks to analyze thumb positioning.
- **✋ Finger Detection** – Determines which fingers are extended using landmark positions.
- **🤖 Gesture Classification** – Recognizes common gestures like:
  - 👍 Thumbs Up
  - ✌️ Peace Sign
  - ✊ Fist
  - 👋 Waving Hand
  - ☝️ Pointing Up
  - 🤟 Love You Gesture
- **🎥 Real-Time Display** – Uses **OpenCV** to overlay detected gestures onto the camera feed.

## 🎯 Applications

This project can serve as a foundation for various real-world applications, including:

- 🧏 **Sign Language Interpretation** – Helping the hearing impaired communicate through AI-powered hand tracking.
- 🕶️ **AR/VR Interactions** – Enabling immersive, gesture-controlled environments.
- 🖥️ **Touchless UI Navigation** – Creating intuitive and hygienic interfaces.
- 🎮 **Gaming & Robotics** – Controlling devices and applications through gestures.

## 🚀 Installation & Usage

### 🔧 Prerequisites

Make sure you have the following dependencies installed:

```sh
pip install opencv-python mediapipe numpy
```

### ▶️ Running the Project

Clone the repository and run the script:

```sh
git clone https://github.com/your-username/hand-gesture-recognition.git
cd hand-gesture-recognition
python gesture_recognition.py
```

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

💡 *Excited to explore more AI-powered computer vision applications! Let me know your thoughts and suggestions!* 🚀🔥

