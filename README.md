# Smart Eyewear for the Visually Impaired 👓

This project is an assistive device designed to help visually impaired individuals recognize Indian currency using a Raspberry Pi, camera, and machine learning.

## 🔍 Overview

The smart eyewear captures real-time images of currency notes using a Pi Camera, applies ORB feature detection, and classifies the denomination using machine learning models. Results are announced through audio feedback and optionally logged to the cloud using ThingSpeak.

## 🧠 Features
- Real-time image capture & processing
- ORB feature detection
- Audio feedback using text-to-speech
- Cloud logging using ThingSpeak
- Voltage protection using Zener diodes
- Signal control using BJTs

## 🛠️ Tech Stack
- Python
- OpenCV
- Raspberry Pi 5
- ThingSpeak (IoT)
- Zener Diodes, BJTs
- Scikit-learn (model training)

## 📂 Files
- `main.py` – Raspberry Pi image processing script
- `Report.pdf` – Full academic project report

## ⚠️ Disclaimer
This project was built for educational purposes. It partially follows concepts shown in public tutorials and is not intended for commercial use.

---
Made with ❤️ by Neelambari P, Arushi Uppal, and Yaalini R