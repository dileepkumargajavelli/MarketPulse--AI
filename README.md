# MarketPulse AI – Smart Stock Market Prediction Platform

MarketPulse AI is a stock market analysis and prediction platform built using Python, Streamlit, TensorFlow, and Yahoo Finance data. The application helps users analyze stock trends, visualize technical indicators, and generate AI-based stock price predictions using an LSTM deep learning model.

## Features

- Real-time stock market data using Yahoo Finance API
- AI-powered stock price prediction using LSTM
- Interactive Streamlit dashboard
- Technical indicator analysis
  - Moving Averages (MA50, MA100, MA200)
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
- Historical stock performance visualization
- Model evaluation metrics
- User-friendly interface

## Technology Stack

- Python
- Streamlit
- TensorFlow / Keras
- Pandas
- NumPy
- Yahoo Finance (yfinance)
- Matplotlib
- Scikit-learn

## Project Structure

```
MarketPulse-AI/
│
├── app.py
├── Stock Predictions Model.keras
├── requirements.txt
└── README.md
```

## How It Works

1. User enters a stock symbol.
2. Historical stock data is fetched using Yahoo Finance.
3. Technical indicators are calculated.
4. Data is processed and passed to the trained LSTM model.
5. Predictions and visualizations are displayed on the dashboard.

## Installation

Clone the repository:

```bash
git clone https://github.com/dileepkumargajavelli/MarketPulse--AI.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Future Improvements

- Multi-stock comparison
- Sentiment analysis from financial news
- Portfolio performance tracking
- Advanced forecasting models

## Author

**Dileep Kumar Gajavelli**

B.Tech CSE | AI & ML Enthusiast

- GitHub: https://github.com/dileepkumargajavelli
- LinkedIn: https://www.linkedin.com/in/dileep-kumar-gajavelli
