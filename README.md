# 🔒 Liveness Detection Model
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![React](https://img.shields.io/badge/Frontend-React-blue?style=flat-square&logo=react)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-green?style=flat-square&logo=fastapi)

A real-time, deep learning-based liveness detection and face verification platform designed for secure, fast, and browser-based identity authentication — optimized for low-end devices and Aadhaar-ready!

---

## 🚀 Overview

Face recognition is powerful, but without liveness detection, it’s vulnerable to spoof attacks. This project aims to **bridge that gap** using an intelligent, full-stack solution:

- ✅ Detects whether a face is real or spoofed (photo/video attack)
- ✅ Enables secure Aadhaar face verification
- ✅ Runs directly in web browsers using TensorFlow.js
- ✅ Optimized for low-end devices

---

## 🧠 Core Features

- 🧬 **Deep Learning-Based Liveness Detection**  
  Built using TensorFlow and Keras with high accuracy in differentiating live faces from spoof attempts.

- 🌐 **Web Deployment via TensorFlow.js**  
  Real-time inference in the browser — no server round-trips, ensuring speed and privacy.

- ⚡ **Model Optimization**  
  Applied **quantization** and **pruning** to reduce model size by **30%** with zero compromise on accuracy.  
  Improved inference speed by **15%** on low-end devices.

- 🛡️ **Secure Face Verification Platform**  
  Full-stack implementation for Aadhaar-level authentication:
  - Backend powered by **FastAPI**
  - Face matching using a **ResNet model** achieving **92% accuracy**

- 👥 **Tested and Verified**  
  Deployed and tested with **30+ users** to evaluate spoof resistance and usability.

---

## 🛠️ Tech Stack

**Machine Learning / Deep Learning**
- TensorFlow
- Keras
- TensorFlow.js
- ResNet

**Backend**
- FastAPI
- Express.js
- MongoDB

**Frontend**
- React.js
- JavaScript
- Tailwind CSS

---

## 📸 Demo    https://youtu.be/q5oJCUSrBRI

[![Watch Demo](https://img.youtube.com/vi/q5oJCUSrBRI/hqdefault.jpg)](https://youtu.be/q5oJCUSrBRI)

> 👆 Click the thumbnail to see the liveness detection model in action!  


---

## 🧠 How It Works

### 🕵️‍♂️ Liveness Detection
- Deep CNN trained on real vs spoofed faces
- Handles printed photos, digital screens, and replay attacks
- Runs directly in-browser with TensorFlow.js

### 🧬 Face Matching
- Backend face matcher using **ResNet**
- Achieves ~92% accuracy on benchmark Aadhaar-like data

### 🚀 Optimization Techniques
- 🔧 **Quantization** to reduce float precision
- ✂️ **Model pruning** to remove redundant weights
- ⚡ Faster inference with reduced compute and memory footprint

---

## 🛠️ Tech Stack

| Layer         | Technology                                         |
|---------------|-----------------------------------------------------|
| ML/AI         | TensorFlow, Keras, TensorFlow.js, ResNet           |
| Backend       | FastAPI, Express.js, MongoDB                       |
| Frontend      | React.js, Tailwind CSS, JavaScript                 |
| DevOps/Tools  | Git, VS Code, Postman                              |

---

**Clone the repo**
   ```bash
   git clone https://github.com/akhilRathour/liveness-Detection-model.git
