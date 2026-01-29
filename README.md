# Sign2Sound – Real-Time Sign Language to Speech Translation

## Overview
Sign2Sound is an assistive technology project that converts sign language gestures into synthesized speech in real time using computer vision and deep learning. The system is designed to help Deaf and Hard-of-Hearing individuals communicate effectively in public and professional environments.

## Features
- Real-time sign language recognition
- On-device processing for privacy
- Low-latency inference
- Text and speech output
- Support for multiple sign languages (extensible)
- Works in offline environments

## Technology Stack
- Programming Language: Python
- Frameworks: TensorFlow / PyTorch
- Computer Vision: OpenCV, MediaPipe
- Deep Learning Models: CNN + LSTM
- Text-to-Speech: pyttsx3 / gTTS
- Platform: Windows / Linux

## Dataset
- IEEE DataPort Sign Language Datasets (ASL, ISL)
- Preprocessed using normalization and augmentation
- Split into training, validation, and test sets

## System Architecture
1. Webcam captures video input
2. MediaPipe extracts hand and pose landmarks
3. Feature vectors are generated
4. CNN-LSTM model performs classification
5. Output text is generated
6. Text-to-Speech converts text to audio

## Installation

1. Clone the repository
2. Install dependencies
3. Run the application
## Project Structure

## Performance
- Average latency: <120 ms
- Real-time FPS: 20–25 FPS (device dependent)
- Optimized for low-resource devices

## Challenges
- Dataset imbalance
- Limited hardware resources
- Real-time latency optimization

These were addressed using data augmentation, model compression, and pipeline optimization.

## Future Work
- Expand vocabulary
- Add more sign languages
- Improve accuracy
- Integrate wearable devices
- Deploy mobile application

## Team
- G S Adhi Narayanan – Electronics & Biomedical Engineering
- Alwin Reji – Computer Science & Design Engineering
- Jithin Sunildas – Computer Science Engineering

## License
This project is developed for academic and research purposes.

## Installation

1. Clone the repository
