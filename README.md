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

### Actual vs Predicted

![Prediction vs Actual](images_1/predicted_vs_actual_RNN.png)
![Prediction vs Actual](images_1/predicted_vs_actual_LSTM.png)

### Training Loss

![Training Loss](images_1/loss_curve.png)

### Stock Price History

![Stock Price History](images_1/stock_price_history.png)

### 4. Model Comparison (RMSE)

![Model Comparison](images_1/compare_results.png)

- Line plot showing actual vs predicted closing prices for RNN and LSTM.
- Loss vs Epochs graphs for model training
- This plot shows the historical closing prices of Apple Inc. (AAPL) used for training and testing the models.
- Bar chart comparing RMSE values for RNN and LSTM models.
---


## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/AbhiraamiK/apple-stock-prediction.git
   cd apple-stock-prediction
