
# 📈 StockVision – Market Forecast & Risk Advisory Agent

StockVision is an AI-powered market analysis system that provides **next-day stock price forecasts** along with **human-readable risk advisories**.  
It is designed for retail investors who want **simple, explainable insights** instead of complex charts and jargon.

This project combines **time-series forecasting models** with **LLM-based explanation generation** to deliver actionable market intelligence.

---

## 🚀 Project Motivation

Most retail investors struggle with:
- Understanding raw stock data
- Interpreting technical indicators
- Assessing risk for short-term trades

**StockVision solves this problem by:**
- Predicting **next-day stock movement**
- Explaining **why** the forecast was made
- Providing **risk-level advisories** in plain English

⚠️ *This system is for educational and analytical purposes only. It is NOT financial advice.*

---

## 🧠 Key Features

- 📊 Next-Day Price Forecast
- 🧮 Time-Series Modeling (Prophet)
- 🗣️ AI-Generated Risk Advisory
- 📉 Risk Classification (Low / Medium / High)
- 🔍 Explainable AI Outputs
- 🧩 Modular & Scalable Design

---

## 🏗️ System Architecture
```

Historical Stock Data  
      ↓  
Data Cleaning & Preprocessing  
      ↓  
Forecasting Model (Prophet)  
      ↓  
Prediction + Confidence Estimation  
      ↓  
Risk Classification Engine  
      ↓  
LLM Risk Advisory Generator  
      ↓  
Final Investor-Friendly Report  

```
---

## 🛠️ Tech Stack

**Programming Language**
- Python 3.10+

**Libraries & Tools** : 
- Y finance : For fetching real time and historical stock data from Yahoo Finance 
- Pandas, NumPy : A corner stone for data manipulation and analysis primarily used for DataFrames , for numerical operations , especially useful in calculating volatility 
- Facebook Prophet : A robust forecasting library designed for the time series data , used here for time series data for predicting next day stock prices 
- LangChain : An Integration that allows the use of google natural language explanations for the stock analysis 
- Gradio : A Popular library for building user friendly web interfaces for machine learning models and data applications making the StockVision
- OpenAI and  Gemini : Current AI Models 

---



---

## 📊 Sample Output

```
Predicted Next-Day Close : ₹1245.30
Expected Trend : Mild Uptrend
Risk Level : Medium Risk


AI Advisory:
"The stock shows moderate volatility with uncertain momentum.
Short-term investors should trade cautiously and avoid overexposure."

```

---

## 📉 Risk Classification Logic

Low Volatility + High Confidence → Low Risk  
Medium Volatility → Medium Risk  
High Volatility + Low Confidence → High Risk  

---




## 🔐 Limitations

- It is for Short Term Investors 
- Sensitive to sudden news
- Depends on historical data model accuracy

---

## 👨‍💻 Author

**Team - KARNA**   
**Singidi Sai Naga Sudheer** - Quantitative Data Engineer  
**Potnuru Uday Teja** - AI Engineer 
**Reyyi Harshitha** - Application Developer (UI / UX )



