# Monocular_Depth_Estimation
# 🚗 Smart Vehicle Assistant using YOLOv8 + MiDaS + Multilingual Voice

This project is a real-time Smart Assistant system for vehicles, integrating:

- **YOLOv8 Object Detection**
- **MiDaS v3.1 Depth Estimation**
- **Multilingual Voice Assistant (English + Tamil)**
- Designed and optimized for **NVIDIA Jetson devices**

This system helps the user understand obstacles, diversions, and surroundings with real-time visual + voice feedback, especially useful for intelligent vehicles or driver assistance systems.

---

## 🧠 Features

- 🔍 Real-time object detection using YOLOv8
- 🌊 Depth estimation from a single image using MiDaS
- 🗣️ Voice output in **English and Tamil** using gTTS
- 🧠 Obstacle analysis and explanation with voice
- 🎯 Path tracking and diversion explanation
- ⚡ CUDA/GPU support for Jetson acceleration

---

## 📂 Folder Structure
project-root/
├── main.py                   # Main integrated script
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation

├── models/                   # Model weights
│   ├── yolov8.pt
│   └── dpt_large.pt

├── midas/                    # MiDaS model files (if not using pip)
│   └── (MiDaS source files)

├── utils/                    # Helper modules
│   ├── voice_assistant.py    # Tamil + English speech engine
│   └── depth_utils.py        # Depth estimation helpers

├── sample_inputs/            # Sample input images/videos
└── outputs/                  # Saved outputs (optional)
