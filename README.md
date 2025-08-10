# Predictive-Analytics-for-Stock-Market-using-LSTM-and-ARIMA
The goal of this project is to develop a software application that can analyze and predict stock market trends using Long Short-Term Memory (LSTM) neural networks and ARIMA (AutoRegressive Integrated Moving Average) models. It provides users (like investors or analysts) with predictive analytics, data visualization, and a user-friendly interface.
# 📈 Predictive Analytics for Stock Market using LSTM and ARIMA

A **full-stack stock prediction application** that uses **Long Short-Term Memory (LSTM)** neural networks and **ARIMA (AutoRegressive Integrated Moving Average)** models to forecast future stock prices.  
The project includes a **Flask backend** for data processing and predictions, and a **React (Vite) frontend** for visualization and user interaction.

---

## 🚀 Features

- 🔍 **Stock Data Fetching** from Yahoo Finance API (`yfinance`)
- 🧠 **LSTM Model** for deep learning-based predictions
- 📊 **ARIMA Model** for statistical time-series predictions
- 📈 Interactive **charts** for prediction visualization
- ⚡ **Fast frontend** built with React + Vite
- 🔄 Switch between **LSTM** and **ARIMA** predictions
- 📱 Fully **responsive design**

---

## 🏗️ Project Structure

stock-predictor/
├── backend/
│ ├── app/
│ │ ├── init.py
│ │ ├── routes.py
│ │ ├── lstm_model.py
│ │ ├── arima_model.py
│ │ └── utils.py
│ ├── main.py
│ └── requirements.txt
└── frontend/
├── index.html
├── package.json
├── vite.config.js
└── src/
├── App.jsx
├── api.js
└── components/
└── PredictionChart.jsx




---

## 🛠️ Tech Stack

### **Frontend**
- React.js (Vite)
- Chart.js & react-chartjs-2
- Axios

### **Backend**
- Python (Flask)
- TensorFlow/Keras (LSTM)
- Statsmodels (ARIMA)
- Pandas, NumPy
- yfinance

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/stock-predictor.git
cd stock-predictor
