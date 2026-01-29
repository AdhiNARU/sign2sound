# Sign2Sound 🎯  
### Real-Time Sign Language to Speech Translation System

Sign2Sound is an assistive technology project that converts sign language gestures into synthesized speech in real time using computer vision and deep learning. It aims to improve communication accessibility for Deaf and Hard-of-Hearing individuals in public and professional environments.

---

## 📖 Overview

This system captures live video input, extracts hand and body landmarks using MediaPipe, and processes them using machine learning models to recognize sign language gestures. The recognized signs are converted into text and further synthesized into speech.

The project supports offline processing and focuses on low-latency, privacy-preserving inference.

---

## ✨ Features

- Real-time sign language recognition  
- On-device processing for privacy  
- Low-latency inference  
- Text and speech output  
- Supports multiple sign languages (extensible)  
- Works in offline environments  

---

## 🛠 Technology Stack

- *Programming Language:* Python  
- *Frameworks:* TensorFlow / PyTorch  
- *Computer Vision:* OpenCV, MediaPipe  
- *Deep Learning Models:* CNN + LSTM  
- *Text-to-Speech:* gTTS / pyttsx3  
- *Environment Management:* Python Virtual Environment  

---

## 📂 Project Structure

sign2sound/ │ ├── src/            # Source code ├── data/           # Dataset files ├── build/          # Trained model files ├── README.md       # Documentation ├── project.toml    # Project configuration ├── LICENSE         # License file └── init.py         # Initialization script

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/AdhiNARU/sign2sound.git
cd sign2sound

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt

pip install opencv-python mediapipe numpy tensorflow torch pyttsx3

python src/main.py
