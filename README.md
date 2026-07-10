🌿 Plant Disease Detection System
🚀 Overview

The Plant Disease Detection System is an AI-powered web application built using the python Stack, FastAPI, and Deep Learning to identify diseases in plant leaves. The application enables farmers and agricultural professionals to upload leaf images and receive instant disease predictions along with treatment recommendations.

The deep learning model is based on ResNet50, which provides high classification accuracy across multiple plant disease categories.

🔬 Technology Stack
Layer	Technologies
Frontend	React.js, HTML, CSS, JavaScript
Backend	FastAPI, Python
Database	MongoDB
Machine Learning	TensorFlow, Keras, ResNet50
Image Processing	OpenCV, Pillow
API Testing	Postman
✨ Features
🌿 AI-powered plant disease detection
📸 Upload plant leaf images for instant diagnosis
⚡ FastAPI-based REST API for real-time prediction
🧠 ResNet50 transfer learning model
📊 Displays disease name and confidence score
💾 MongoDB integration for storing user information
📱 Responsive React user interface
🚀 Fast prediction with optimized inference
📈 Model Performance
Metric	Score
Training Accuracy	88.99%
Validation Accuracy	90.32%
📂 Project Structure
Plant-Disease-Detection-System/
│
├── frontend/              # React Frontend
├── backend/               # FastAPI Backend
├── model/                 # ResNet50 Model Files
├── dataset/               # Training Dataset (ignored in Git)
├── uploads/               # Uploaded Images
├── requirements.txt
├── README.md
└── .gitignore
⚙️ Installation
1. Clone the Repository
git clone https://github.com/your-username/Plant-Disease-Detection-System.git

cd Plant-Disease-Detection-System
2. Frontend Setup
cd frontend

npm install

npm start

Frontend will run on

http://localhost:3000
3. Backend Setup
cd backend

pip install -r requirements.txt

uvicorn main:app --reload

Backend will run on

http://127.0.0.1:8000
