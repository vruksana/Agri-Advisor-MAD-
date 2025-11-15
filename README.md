🌾 Agri Advisor – Smart Farming Assistant

Agri Advisor is a mobile application built using Java (Android), Firebase, and a Flask ML API to help farmers make informed agricultural decisions. The app provides weather updates, crop recommendations, and detailed crop information through an easy-to-use interface.

🚀 Features
🔐 User Authentication

Secure login & signup using Firebase Authentication.

🌤 Weather Updates

Fetches real-time weather based on user location.

🌱 Crop Recommendation (ML)

Users enter N, P, K, temperature, humidity, rainfall.

Data is sent to a Flask API with a trained ML model.

Returns the best crop to grow.

📘 Crop Information

Search and browse detailed descriptions of crops.

Shows growth conditions, soil needs, and benefits.

🧭 User Dashboard

View and update user details.

Access recent crop suggestions.

🧠 Tech Stack

Frontend: Java, XML (Android Studio)
Backend: Firebase Auth & Firestore
ML API: Flask, Python
Model: Scikit-Learn (Pickle file)

⚙️ Setup
Android App

Clone repository

Open in Android Studio

Add google-services.json

Build & run the project

Flask API
pip install -r requirements.txt
python app.py


Ensure Android uses your correct Flask server URL.

📡 API Endpoint
POST /predict

Sample Request

{
  "N": 90,
  "P": 40,
  "K": 50,
  "temperature": 25,
  "humidity": 75,
  "rainfall": 180
}


Sample Response

{
  "recommended_crop": "Rice"
}

📂 Project Structure
AgriAdvisor/
│── app/
│── backend/
│   ├── app.py
│   └── model.pkl
└── README.md



👨‍💻 Developer

Ruksana – Android & ML Integration
