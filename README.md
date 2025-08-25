# 📈 Stock Price Prediction using LSTM

This project uses **Long Short-Term Memory (LSTM) Neural Networks** to predict stock prices based on historical closing price data.  
It leverages the **Yahoo Finance API (`yfinance`)** to fetch stock market data and trains an LSTM model for time-series prediction.  

---

## 🚀 Features
- Fetches stock price data using `yfinance`
- Visualizes stock closing price and moving averages (100-day & 200-day)
- Prepares training & testing datasets with **MinMax scaling**
- Builds a deep **LSTM neural network** with dropout regularization
- Predicts and plots **actual vs. predicted stock prices**
- Saves trained models in `.keras` format
- User can input **stock symbols at runtime** (e.g., AAPL, GOOG, TSLA)

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Libraries**:  
  - `pandas`, `numpy` → Data manipulation  
  - `matplotlib` → Visualization  
  - `yfinance` → Stock data fetching  
  - `scikit-learn` → Data scaling  
  - `tensorflow / keras` → LSTM model  

---

## 📂 Project Structure
  -- Stock-Prediction-LSTM
  - Stock_Prediction.ipynb # Jupyter Notebook (main code)
  - Stock-Price-Data # dataset
  - README.md # Project documentation

## ⚡ Usage

### 1️⃣ Clone the repository

git clone https://github.com/your-username/Stock-Prediction-LSTM.git
cd Stock-Prediction-LSTM


### Execute cells in order:

Cell 1: Import libraries

Cell 2: Define the function stock_price_prediction()

Cell 3: Run the function with user input

## 📊 Example Output

- Stock Price with Moving Averages (100 & 200 days)

- Predicted vs. Actual stock prices

- Trained model saved as AAPL_Stock_Prediction_Model.keras

## 🔮 Future Improvements

- Predict next-day future stock prices

- Add hyperparameter tuning for better accuracy

- Extend to multiple stock features (Open, High, Low, Volume)

- Deploy as a web app using Streamlit or Flask

## 📝 License

This project is licensed under the MIT License – you are free to use, modify, and distribute it.
