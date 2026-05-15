# 🩺 Breast Cancer Prediction System (Machine Learning)

This project is a Machine Learning-based web application that predicts whether a tumor is **Malignant (Cancerous)** or **Benign (Non-Cancerous)** based on input features.

---

## 🚀 Features
- Predict breast cancer using trained ML model
- Simple and user-friendly interface
- Fast and accurate predictions
- Frontend built with React + Vite
- Backend powered by Python (Flask)

---

## 🛠️ Tech Stack

### Frontend:
- React (Vite)
- Tailwind CSS

### Backend:
- Python
- Flask

### Machine Learning:
- Scikit-learn
- Pandas
- NumPy

---

## 📂 Project Structure

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/khushi-1531/Breast_Cancer_Prediction_Machine_Learning.git
cd Breast_Cancer_Prediction_Machine_Learning

## Backend
cd src
backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python app.py (remember patient.db delete and then ctrl+c and again python app.py and click on patient.db and sqllite viewer)

## Frontend
cd src
frontend
npm install
npm run dev

Run Project
Frontend: http://localhost:5173
Backend: http://127.0.0.1:5000
