# 🌾 Smart Crop Recommender – KisaanApp

An AI-powered crop advisory system developed for the **Google Solution Challenge 2025** to support small and marginal farmers in making informed, data-driven decisions about crop selection, resource usage, and sustainable farming practices.

---

## 🔍 Problem Statement

Small and marginal farmers face unpredictable climate conditions, resource constraints, and market inefficiencies, leading to crop failures and economic instability. This project provides intelligent crop recommendations based on demand forecasting, soil-climate compatibility, and yield estimation.

---

## 🎯 Solution Overview

Our system combines machine learning models and a mobile-first user experience to:
- Predict demand for crops
- Classify soil and climate compatibility
- Estimate crop yield based on resource input
- Rank high-demand crops for profitability and sustainability
- Provide an interactive AI assistant and community support

---

## 📱 KisaanApp – Frontend (Mobile App)

A sophisticated mobile application built with **React Native + Expo** that helps farmers make informed crop decisions, access real-time agricultural support, and engage with other farmers.

### 🌟 Features

#### 1. Crop Recommendations
- ML-powered crop suggestions based on:
  - Soil parameters (NPK, organic matter)
  - Location
  - Market supply/demand
  - Weather

#### 2. Interactive AI Assistant (Chintak)
- Google Gemini AI chatbot trained on agriculture domain  
- Supports real-time query resolution for farmers

#### 3. Farmer Community Forum
- Real-time chat  
- Firebase Firestore backend for discussion and support

#### 4. Location-Based Services
- Auto location detection  
- Localized crop suggestions and weather integration

### 🛠 Frontend Tech Stack

- React Native + Expo
- Firebase Firestore
- Clerk Auth
- Google Gemini AI
- Expo Location

### 📥 Getting Started (Frontend)

```bash
git clone [repository-url]
cd kisaanapp
npm install
npx expo start
```

#### 📄 .env Configuration

```env
EXPO_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
EXPO_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
```

---

## 🧠 Backend – FastAPI API Server

This backend handles all ML predictions, model execution, and data scoring logic.

### ✅ Features

- Demand Prediction Model  
- Soil & Climate Compatibility Model  
- Yield Forecasting Model  
- Final Crop Ranking Logic  
- Modular FastAPI endpoints for integration

### 🔧 Backend Tech Stack

- FastAPI  
- scikit-learn  
- Uvicorn  
- Python, Pandas, NumPy

### 📂 Folder Structure

```
backend/
├── app/
│   ├── main.py
│── training/
│── srs/
│── models/
│── Dockerfile/
├── requirements.txt
└── README.md
kisaanapp/
│── app/
│── assets/
│── components/
│── hooks/
└── README.md
README.md
```

### 📡 API Endpoints

| Endpoint | Method | Function |
|----------|--------|----------|
| `/predict-demand` | POST | Crop demand prediction |
| `/check-compatibility` | POST | Soil and climate matching |
| `/predict-yield` | POST | Yield estimation |
| `/recommend-crops` | POST | Final ranked crop list |

### ▶️ Run Locally (Backend)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn app.main:app --reload
```

---

## 🧪 AI Models Used

- Demand Predictor (historical market data)
- Compatibility Classifier (soil + weather conditions)
- Yield Estimator (fertilizers, irrigation, organic matter)
- Custom Ranking Formula:  
  `Final Score = (Weight1 × Compatibility) + (Weight2 × Normalized Yield)`

---

## 📸 Screenshots

[Include screenshots of your mobile app here: dashboard, chat assistant, crop recommendation page, etc.]

---

## 🔮 Future Development

- Integrate government APIs for live mandi prices  
- Weather + pest prediction module  
- Voice & regional language support  
- Offline data entry mode for remote villages  
- Farmer feedback system for learning loop

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE)

---

## 🤝 Contributing

```bash
1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Push and create a pull request
```

---

## 🙏 Acknowledgments

- Google Developer Student Clubs  
- Firebase Team  
- Expo & React Native Community  
- Google Gemini AI  
- All small farmers who inspired this idea 💚

---

## 📞 Contact

**Team Name**: Tchh Aryan  
**Maintainer**: Rajeev Ahirwar – rajeev.86dev@gmail.com
**Project Link**: https://github.com/Rajeev-86/smart-crop-recommender-solution-challenge-2025

---

Built with ❤️ for **Google Solution Challenge 2025**
