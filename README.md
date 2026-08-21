
# StockX AI – Intelligent Stock Price Forecasting Platform 

**StockX AI** is an advanced stock market forecasting web application that combines deep learning techniques (LSTM) with technical indicators such as RSI, MACD, and Moving Averages to generate accurate and actionable stock price predictions. Developed using Streamlit, the application offers an interactive, real-time experience tailored for data analysts, investors, and financial researchers.



## Demo Previews

* **Moving Averages:** [View Demo](https://drive.google.com/file/d/1vP5HFN8jBzvP8HYQmBMEwgEOtaTo_ex6/view?usp=sharing)
* **Technical Indicators (RSI, MACD):** [View Demo](https://drive.google.com/file/d/1rTtuGLmlbDFcfPfpXqcl3rtkVTqvFdjf/view?usp=sharing)
* **Price Prediction Example:** [View Demo](https://drive.google.com/file/d/1IoznqKGHkYxytWyPPnJMQRpGvXASTiHp/view?usp=sharing)
* **Full Application Walkthrough:** [Watch Recording](https://drive.google.com/file/d/1-I_LfmYrw9-WQHm5734QHSIFEoUVcXf7/view?usp=sharing)



## Key Features

* Real-time stock data integration via **Yahoo Finance**
* Next-day closing price prediction using a pre-trained **LSTM model**
* Technical indicators visualization:

  * Moving Averages (MA50, MA100, MA200)
  * Relative Strength Index (RSI)
  * Moving Average Convergence Divergence (MACD)
* Model performance evaluation using:

  * Mean Absolute Error (MAE)
  * Root Mean Squared Error (RMSE)
  * R² Score
* Deployed with **Streamlit** for a smooth and responsive user interface

---

## Sample Output

| Metric                         | Value                       |
| ------------------------------ | --------------------------- |
| Mean Absolute Error (MAE)      | \$11.36                     |
| Root Mean Squared Error (RMSE) | \$14.30                     |
| R² Score                       | 0.9109 (Excellent Accuracy) |

**Predicted Closing Price:** \$508.30
**Evaluation Period:** Microsoft (MSFT), 2015–2025

---

## How It Works

1. The user provides a stock ticker and date range.
2. Historical data is retrieved using the `yfinance` API.
3. Technical indicators are computed using the `ta` library.
4. Data is preprocessed and passed into a pre-trained **LSTM** model.
5. The model predicts the next closing prices and visualizes actual vs. predicted results.
6. Performance metrics are calculated and displayed on-screen.

---

## Project Structure

```
StockX-AI/
│
├── app.py                         # Main Streamlit application script
├── Stock Predictions Model.keras  # Pre-trained LSTM model
├── indicators.pdf, ma.pdf         # Graphical representations
├── Screen Recording.mp4           # Application walkthrough video
├── requirements.txt               # List of dependencies
└── README.md                      # Project documentation
```

---

## Technology Stack

| Layer         | Technologies Used                         |
| ------------- | ----------------------------------------- |
| Frontend      | Streamlit                                 |
| Backend       | Python, TensorFlow (Keras), NumPy, Pandas |
| Data Source   | Yahoo Finance (`yfinance` API)            |
| Indicators    | `ta` (Technical Analysis Library)         |
| Visualization | Matplotlib                                |

---

## Installation & Setup

### Prerequisites

Ensure the following Python packages are installed:

* Python 3.x
* TensorFlow / Keras
* Streamlit
* yfinance
* scikit-learn
* ta
* pandas
* matplotlib
* numpy

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/StockX-AI.git
   cd StockX-AI
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Streamlit app:

   ```bash
   streamlit run app.py
   ```

---

## Author

**Yash Yadav**
B.Tech in Artificial Intelligence & Data Science
Specialized in predictive modeling, machine learning, and financial data analysis

* 📧 Email: Yashydv9313@gmail.com
* 🔗 LinkedIn:https://www.linkedin.com/in/yash-yadav7/


---

