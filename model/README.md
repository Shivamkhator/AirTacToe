# Hand Gesture Recognition for AirTacToe

## 📌 Project Overview
This project implements a **real-time hand gesture recognition system** using OpenCV and MediaPipe. It captures hand signs for numbers and processes them for training a machine learning model. The system is designed for applications in **gesture-based control, accessibility, and interactive gaming (AirTacToe)**.

## 🚀 Features
- Real-time **hand tracking** using **cvzone** and **MediaPipe**
- **Image preprocessing** and dataset collection for training models
- **Gesture-based number recognition** (1-9)
- Keyboard shortcuts for **saving, restarting, and quitting**
- Lightweight and optimized for **efficient image acquisition**

## 🛠️ Technologies Used
- **Python**
- **OpenCV** (for image processing)
- **cvzone** (for hand tracking)
- **MediaPipe** (for keypoint extraction)
- **NumPy** (for matrix operations)
- **OS & Shutil** (for file handling)
- **Time & Sys** (for timing and system interactions)

## 📂 Installation & Setup
### 1️⃣ Install Dependencies
Run the following command to install required libraries:
```bash
pip install opencv-python cvzone mediapipe numpy
```

### 2️⃣ Run the Script
For **Jupyter Notebook**, use:
```python
!pip install opencv-python cvzone mediapipe numpy
```
For **local execution**, run:
```bash
python script.py
```

## 🎮 Controls & Keybinds
| Key  | Action |
|------|--------|
| S    | Save Image |
| Q    | Quit Program |
| R    | Restart Collection |

## 📸 How It Works
1. Captures live hand gestures using OpenCV.
2. Detects and extracts **21 hand landmarks** using **MediaPipe**.
3. Crops and preprocesses the hand image for training.
4. Saves images in structured folders for **ML model training**.
5. Switches between numbers (1-9) and automatically manages the dataset collection process.

## 🤝 Contributing
Pull requests are welcome! If you’d like to improve the project, feel free to fork the repository and make changes.

## 🏆 Credits
Developed by **Shivam Khator** as part of the **AirTacToe** project.

---
### ⚠️ Note:
This script works best on **local machines (VS Code, PyCharm, Terminal)** due to webcam access limitations in **Google Colab** and **Jupyter Notebook**.

