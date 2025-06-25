# 🔒 Liveness Detection Model
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-API-red?style=flat-square&logo=keras)
![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![Google Colab](https://img.shields.io/badge/Colab-Google-yellow?style=flat-square&logo=googlecolab)

![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?style=flat-square&logo=fastapi)
![Express.js](https://img.shields.io/badge/Express.js-Server-black?style=flat-square&logo=express)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=flat-square&logo=mongodb)

![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=flat-square&logo=tailwind-css)

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
## 📈 model performance
![Alt Text](![Face Liveness Screenshot](FaceLivelinessOnCode/FaceLivelinessOnCode/frontend/src/Screenshot%202025-06-25%20131135.png)
)

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
---

**Project Structure
FaceLivelinessProject/
├── FaceLivelinessOnCode/
│   ├── backend/
│   │   ├── config/              # Configuration files (e.g., DB, environment)
│   │   ├── controllers/         # API logic and route controllers
│   │   ├── models/              # Database models or schemas
│   │   ├── routes/              # Route definitions
│   │   └── server.js            # Main backend entry point (Express server)
│   │
│   ├── frontend/
│   │   ├── public/              
│   │   │   ├── tf_model/        # TensorFlow.js model files
│   │   │   ├── tfjs_model/      # Alternate/converted model files
│   │   │   ├── favicon.ico
│   │   │   ├── index.html       # Main HTML template
│   │   │   ├── logo192.png
│   │   │   ├── logo512.png
│   │   │   ├── manifest.json
│   │   │   └── robots.txt
│   │   │
│   │   └── src/
│   │       ├── assets/          # Static assets (images, styles, etc.)
│   │       ├── components/      # Reusable React components
│   │       ├── context/         # React context for global state
│   │       ├── pages/           # Route-level React components
│   │       ├── App.css
│   │       ├── App.js           # Root React component
│   │       ├── App.test.js
│   │       ├── index.css
│   │       ├── index.js         # React entry point
│   │       ├── logo.svg
│   │       ├── reportWebVitals.js
│   │       └── setupTests.js
│
├── FaceLiveliness_ModelTraining.ipynb   # google collab file used for model training/inference/testing


