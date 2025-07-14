Autism Detection & Learning Platform through Interactive Games


This is a full-stack web platform that assists in the early detection of Autism Spectrum Disorder (ASD) in children through interactive games. The platform also helps autistic children learn and engage via therapeutic game-based activities.

Built using:

⚛️ React (Frontend)

🐍 Python (Backend)

📡 FastAPI, WebSockets

🧠 TensorFlow, OpenCV, MediaPipe

💾 MongoDB, Firebase

🧩 Table of Contents
Introduction

System Architecture

Key Features

Technical Stack

Technical Modules

Installation

Results & Impact

License

📘 Introduction
This platform offers a game-based approach to autism detection, enabling early behavioral analysis through:

Color recognition tasks

Gesture imitation tasks

Emotion recognition from facial expressions

A comprehensive autism assessment test

It offers real-time video processing and adaptive difficulty to keep children engaged and gather insightful data.

🏗️ System Architecture
Our platform follows a client-server model:

Users sign up or log in.

They land on a game selection menu.

After selecting a game, video input is processed in real-time.

Results are analyzed and displayed.

Users can choose to play other games.

🎮 Games Included
🎨 Color Recognition Game

✋ Gesture Recognition Game

😊 Emotion Recognition Game

🧠 Autism Assessment Test

✨ Key Features
✅ Real-time facial & gesture analysis

📊 Adaptive difficulty adjustment

⚡ Fast WebSocket communication (~83ms latency)

🔐 Secure user data storage

📁 Modular backend architecture

🧰 Technical Stack
Layer	Technology Used
Frontend	React, TypeScript, Vite
Backend	Python 3.9, FastAPI, WebSocket
Computer Vision	OpenCV, MediaPipe
Machine Learning	TensorFlow, scikit-learn
Database	MongoDB, Firebase

🔧 Technical Modules
🎥 Computer Vision Module
Built with OpenCV 4.5.3 & MediaPipe

Performs hand tracking, pose estimation, and facial analysis

🧠 Machine Learning Module
TensorFlow-based emotion and gesture classifiers

Trained on datasets with over 10,000 hand poses

🧩 Game Logic Module
Written in native Python

Adjusts task difficulty in real-time

🔌 API Services
Built with FastAPI 0.73

Uses WebSocket for ultra-fast video communication

🗃️ Data Management
MongoDB and Firebase handle:

User authentication

Session tracking

Game scores and metrics

💻 Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/autism-detection-platform.git
cd autism-detection-platform
2. Setup Frontend
bash
Copy
Edit
cd frontend
npm install
npm run dev
3. Setup Backend
bash
Copy
Edit
cd ../backend
pip install -r requirements.txt
uvicorn main:app --reload
Make sure to configure your .env files for both frontend and backend, especially for MongoDB and Firebase credentials.

📈 Results & Impact
⏱️ WebSocket latency: ~83ms

🤖 Trained on: 10,000+ gesture images

🧪 Emotion detection: High precision CNN-based classifiers

🧠 Helps professionals with early autism screening

🧒 Friendly UI design for children with diverse developmental needs




