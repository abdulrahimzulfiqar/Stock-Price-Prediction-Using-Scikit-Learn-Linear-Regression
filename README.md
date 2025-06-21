# 📈 Stock Price Prediction Using Scikit-Learn Linear Regression

This project demonstrates how to predict the next day's **stock closing price** using supervised learning with **Linear Regression** from `scikit-learn`. We use public stock data from Yahoo Finance, engineer lag-based features, and evaluate the model's performance with error metrics and visualizations.

---

## 🧠 Overview

- ✅ Downloaded historical stock data (Apple Inc.) using `yfinance`
- ✅ Created lag features from past 5 days to use as inputs
- ✅ Applied feature scaling using `StandardScaler`
- ✅ Trained a Linear Regression model using `sklearn`
- ✅ Evaluated the model using **MSE** and **R²**
- ✅ Visualized **actual vs predicted prices**
- ✅ Built entirely in Google Colab using free tools

---

## 🗂️ Project Structure

| File | Description |
|------|-------------|
| `stock_prediction_sklearn.ipynb` | Full notebook with training, evaluation, and plots |
| `README.md` | Project documentation (this file) |
| `images/` | <img width="833" alt="Screenshot 2025-06-21 at 3 40 43 pm" src="https://github.com/user-attachments/assets/801a86c1-5b10-4ead-8680-3e71007768d6" />|

---

## 📊 Data Source

- Ticker: `AAPL` (Apple Inc.)
- Timeframe: Jan 2020 to Jan 2024
- Source: [Yahoo Finance](https://finance.yahoo.com/)

---

## ⚙️ Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib
- scikit-learn
- yfinance

---

## 📉 Model Details

- **Input features**: Closing prices of the last 5 days
- **Target**: Next day's closing price
- **Model**: `sklearn.linear_model.LinearRegression`
- **Metrics**:
  - Mean Squared Error (MSE)
  - R² Score

---

## 📈 Results

- Prediction error is relatively low, and the model captures general trends.
- Perfect accuracy is not expected as stock markets are affected by external, unmodeled factors.

---

## 🖼️ Visualizations

<img width="833" alt="Screenshot 2025-06-21 at 3 40 43 pm" src="https://github.com/user-attachments/assets/801a86c1-5b10-4ead-8680-3e71007768d6" />
