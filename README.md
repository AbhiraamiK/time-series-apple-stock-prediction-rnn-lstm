# 📈 Apple Stock Price Prediction using RNN & LSTM

This project focuses on predicting Apple Inc. (AAPL) stock prices using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models.

---

## 🔍 Objective

To develop time-series forecasting models using deep learning techniques (RNN, LSTM) to predict future stock prices based on historical data.

---

## 🗂️ Dataset

- Source: Yahoo Finance (`yfinance`)
- Ticker: `AAPL`
- Data includes: Date, Open, High, Low, Close, Adj Close, Volume
- Time range: [you can specify, e.g., Jan 2010 to Dec 2023]

---

## ⚙️ Tech Stack

- Python
- Google Colab
- Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras, yfinance

---

## 🧠 Models Used

- RNN
- LSTM

Each model was trained to predict the next closing price based on the past 60 time steps.

---

## 📊 Evaluation Metrics

- **RMSE (Root Mean Square Error)**

---

## 📈 Results

| Model |  RMSE  | 
|-------|--------|
| RNN   |  12.20 | 
| LSTM  |  4.22  | 

---

## 📉 Visualization

![Prediction vs Actual](images/predicted_vs_actual.png)

- Line plot showing actual vs predicted closing prices
- Loss vs Epochs graphs for model training

---


## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/AbhiraamiK/apple-stock-prediction.git
   cd apple-stock-prediction
