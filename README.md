🌿 Plant Disease Detection System
🚀 Overview
The Plant Disease Detection System is a MERN stack and Machine Learning-based application designed to help farmers diagnose crop diseases efficiently. By leveraging Deep Learning (ResNet50), the system provides accurate classification of plant diseases.

🔬 Tech Stack
Frontend: React (UI for user interaction)
Backend: FastAPI (handling API requests)
Database: MongoDB (storing user data)
Machine Learning: ResNet50 (Deep Learning model for classification)
🎯 Features
📸 Image-based Disease Classification using CNN (ResNet50)
🛠 FastAPI Backend for handling model inference
📂 MongoDB Integration for user data storage
📈 Achieved high accuracy:
✅ Training Accuracy: 88.99%
✅ Validation Accuracy: 90.32%
🌍 Future Enhancements:
💽 Real-time monitoring
🗣 Multilingual support
🌾 Expansion to other crops
📚 Project Structure
/ Plant-Disease-Detection-System
  |-- frontend/         # React Frontend
  |-- backend/          # FastAPI Backend
  |-- model/            # ResNet50 Model & Scripts
  |-- data/             # Dataset (ignored in .gitignore)
  |-- README.md         # Project Documentation
🔄 Installation & Setup
1⃣ Clone the repository
git clone https://github.com/BharathJP-72/Plant-Disease-Detection-System.git
cd Plant-Disease-Detection-System
2⃣ Install dependencies
Frontend (React)
cd frontend
npm install
npm start
Backend (FastAPI)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
🎯 Usage
1⃣ Upload an image of a plant leaf.
2⃣ The ResNet50 model will classify the disease.
3⃣ Users get detailed disease information and suggestions.

🐝 API Endpoints
POST /predict - Upload an image and get a prediction.
GET /health - Check if the backend is running.
📚 License
This project is licensed under the MIT License.
