# 📈 Advanced Stock Price Forecasting using Bidirectional LSTM & Technical Indicators

Deep Learning • Time Series Forecasting • Quantitative Finance • Streamlit • Hugging Face Spaces

---

## 🚀 Live Demo

🌐 **Try the Application**
https://huggingface.co/spaces/abhishekgupta01/Advanced-Stock-Price-Forecasting-using-Bidirectional-LSTM-Technical-Indicators

📦 **Source Code**
https://github.com/AbhishekKumarGuptaDev/Advanced-Stock-Price-Forecasting-using-Bidirectional-LSTM-Technical-Indicators

---

## 📌 Project Overview

This project implements an **end-to-end deep learning pipeline for stock market forecasting** using a **Bidirectional Long Short-Term Memory (BiLSTM)** architecture combined with **technical indicators and multivariate financial features**.

The system forecasts future stock price movement using historical market behavior and provides predictions through an interactive web application.

Users can enter any supported ticker symbol and generate forecasts directly from live market data.

Examples:

* AAPL
* TSLA
* MSFT
* RELIANCE.NS
* BTC-USD
* ETH-USD

---

## 🎯 Objectives

* Forecast future stock movement using deep learning
* Improve prediction quality with technical indicators
* Enable multi-step future prediction
* Deploy an accessible real-time forecasting platform

---

# 🏗 System Architecture

```text
Yahoo Finance
      │
      ▼
Data Collection (yfinance)
      │
      ▼
Feature Engineering
(SMA • EMA • RSI • MACD • BBANDS • Returns)
      │
      ▼
Data Scaling
      │
      ▼
Bidirectional LSTM
      │
      ▼
Multi-Step Forecast
      │
      ▼
Streamlit UI
      │
      ▼
Hugging Face Deployment
```

---

# 🧠 Model Architecture

```text
Input Layer
     │
Bidirectional LSTM (64)
     │
Dropout
     │
Bidirectional LSTM (64)
     │
Dense (64, ReLU)
     │
Output Layer
(Future Forecast Horizon)
```

---

## Why Bidirectional LSTM?

Traditional LSTMs process sequential information in one direction.

Bidirectional LSTM improves representation learning by capturing:

✔ Short-term market behavior
✔ Long-range dependencies
✔ Temporal relationships across multiple indicators

This allows improved feature extraction for financial time series.

---

# ✨ Features

### Real-Time Market Data

* Live stock retrieval using Yahoo Finance

### Automated Feature Engineering

* SMA
* EMA
* RSI
* MACD
* Bollinger Bands
* Daily Returns

### Forecasting Engine

* Multi-step future prediction
* Business-day aligned output

### Interactive Dashboard

* Forecast visualization
* Candlestick analysis
* Trend overlays

### Export Support

* Prediction table generation

---

# 📊 Sample Outputs

✔ Historical Price Visualization
✔ Candlestick + Forecast Overlay
✔ Future Price Projection
✔ Growth Percentage Metrics

---

# 🛠 Tech Stack

| Layer                | Technology               |
| -------------------- | ------------------------ |
| Model                | TensorFlow / Keras       |
| Deep Learning        | Bidirectional LSTM       |
| Data Source          | Yahoo Finance            |
| Backend              | Python                   |
| Data Processing      | Pandas, NumPy            |
| Technical Indicators | TA                       |
| Visualization        | Plotly, Matplotlib       |
| Deployment           | Streamlit + Hugging Face |
| Serialization        | Joblib, Pickle           |

---

# 📂 Project Structure

```bash
Advanced-Stock-Price-Forecasting/
│
├── app.py
├── requirements.txt
├── model/
│     ├── bilstm_model.h5
│     ├── scaler.pkl
│     └── metadata.pkl
│
├── notebooks/
│     └── Stock_Price_Prediction_using_Bidirectional_LSTM.ipynb
│
├── src/
│     ├── preprocessing.py
│     ├── indicators.py
│     ├── forecasting.py
│     └── visualization.py
│
├── assets/
│     ├── banner.png
│     └── screenshots/
│
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/AbhishekKumarGuptaDev/Advanced-Stock-Price-Forecasting-using-Bidirectional-LSTM-Technical-Indicators.git
```

## Move to Project Directory

```bash
cd Advanced-Stock-Price-Forecasting-using-Bidirectional-LSTM-Technical-Indicators
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
streamlit run app.py
```

---

# 🧪 Training Notebook

Retraining pipeline available in:

```bash
notebooks/Stock_Price_Prediction_using_Bidirectional_LSTM.ipynb
```

Includes:

* Data Collection
* Feature Engineering
* Sequence Generation
* Model Training
* Evaluation
* Model Export

---

# 📈 Future Improvements

* Sentiment Analysis Integration
* News-based Signals
* Walk Forward Validation
* Transformer Models
* Portfolio Optimization
* Telegram Alert System
* PDF Forecast Reports
* Multi-Asset Forecasting

---

# ⚠ Disclaimer

This project is intended for:

✔ Research
✔ Learning
✔ Portfolio Demonstration

It is **NOT financial advice**.

Predictions should not be used for real trading decisions without additional validation and risk management.

---

# 🤝 Contributions

Contributions are welcome.

If you'd like to improve forecasting performance or extend deployment features:

1. Fork repository
2. Create feature branch
3. Commit changes
4. Open Pull Request

---

# 👨‍💻 Author

### Abhishek Kumar Gupta

B.Tech CSE (AI & ML)
Machine Learning • Deep Learning • Quantitative Finance

⭐ If you found this project useful, consider starring the repository.
