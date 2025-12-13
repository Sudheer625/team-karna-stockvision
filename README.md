
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

**Libraries & Tools**
- Pandas, NumPy
- Facebook Prophet
- LangChain
- OpenAI and  Gemini 
- Matplotlib (optional)

---

## 📂 Project Structure
```

StockVision/
│
├── data/
│   ├── raw/
│   │   └── stock_data.csv          # F8 stock market dataset
│   ├── processed/
│   │   └── cleaned_stock_data.csv  # optional (after preprocessing)
│   └── load_data.py                # data loading & cleaning logic
│
├── models/
│   └── prophet_model.py            # Prophet forecasting logic
│
├── services/
│   ├── gemini_client.py             # Google Gemini API initialization
│   ├── risk_analysis.py             # volatility, returns, trend logic
│   └── explainer.py                 # Gemini-based risk advisory generator
│
├── app.py                           # Streamlit POC application
│
├── requirements.txt                 # project dependencies
│
├── README.md                        # judges-ready documentation
│
└── .env                             # Gemini API key

```

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

## ⚙️ Installation
```

pip install -r requirements.txt

```
---

## ▶️ Run the Project
```

python app.py

```

---

## 🔐 Limitations

- Short-term forecasting only
- Sensitive to sudden news
- Depends on historical data accuracy

---

## 👨‍💻 Author

**Team - KARNA**   
**Singidi Sai Naga Sudheer** - Team Lead + AI Assistant  
**Pogiri Venkata Narsimhulu** - Associate Team Lead + Github  
**Potnuru Uday Teja** - Prompt Engineer + Team Member  
**Reyyi Harshitha** - Documentation + Team Member  



