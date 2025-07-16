# YES-BANK-STOCK-PRICE-CLOSING-PREDICTION

# 📈 Yes Bank Stock Closing Price Prediction

A Machine Learning project to predict the **monthly closing stock price** of Yes Bank using historical stock data and regression modeling.

---

## 📌 Project Overview

This project aims to forecast the **closing price** of Yes Bank’s stock using historical monthly trading data, including Open, High, Low, Close prices and trading Volume.

The prediction model is built using **Linear Regression**, and evaluates performance based on **Mean Absolute Error (MAE)**. The project demonstrates how basic time series regression can uncover useful patterns even from limited data.

---

## 🧠 Problem Statement

The objective is to build a machine learning model that can **predict the closing stock price** for a given month based on historical values and engineered features like moving averages and lag values.

---

## 📂 Dataset

- **Source**: https://drive.google.com/file/d/1QsxZSROg7nZjwAhwY7zgGwZQOF6aL8vP/view?usp=sharing
- **Type**: Monthly stock data of Yes Bank
- **Records**: 185 rows (monthly entries)
- **Columns**: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn, Plotly
- Google Colab

---

## 🔎 Exploratory Data Analysis (EDA)

- Time series visualization of closing price
- Volume analysis
- Correlation matrix
- Trend detection using moving averages

---

## 🔧 Feature Engineering

- Lag features: Previous month's closing price
- Moving averages: 3-month and 7-month
- Percentage change

---

## 🤖 Model Used

- **Linear Regression**
- Dataset split: 80% Training / 20% Testing

---

## 📊 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

---

## 📈 Results

- The model effectively captured trends in the closing price
- Actual vs Predicted plots showed close alignment on test data

---

## 📚 Learnings

- Basics of financial time series data handling
- The importance of feature engineering (lag & moving average)
- How regression can be applied to stock prediction
- Evaluation of models using real-world metrics

---

## 💡 Future Improvements

- Use of advanced models like **XGBoost**, **ARIMA**, or **LSTM**
- Include external features like market news or macro indicators
- Deploy as a web app using **Streamlit** or **Gradio**

---

## 🙏 Acknowledgment

Special thanks to **Winnovation** for the guidance and opportunity to work on this practical ML project. Your mentorship made this experience truly valuable!

---

## 🔗 Project Demo

[👉 Click here to view full notebook and video](https://drive.google.com/drive/u/1/folders/1VLELwn3ybi0pUchf5QZrFNQfyAkE87kJ)

---

## 📬 Contact

**Abhinav Kumar**  
_B.Tech CSE (Data Science)_  
[LinkedIn](https://www.linkedin.com/in/abhinav-kumar-b0b0ba253/) | [Email](abhinav8934g@gmail.com)

---

## ⭐️ Don't forget to star this repo if you found it helpful!

