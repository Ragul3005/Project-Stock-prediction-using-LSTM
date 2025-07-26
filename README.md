
# 📈 Stock Price Trend Prediction with LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict stock price trends based on historical data. The model is built and trained using Python and TensorFlow/Keras within a Jupyter Notebook environment.

## 🔍 Overview

- Data Source: Yahoo Finance (using `yfinance`)
- Model: LSTM (Long Short-Term Memory) neural network
- Objective: Predict future closing prices based on past stock data
- Visualization: Matplotlib

## 📦 Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

**Main Libraries:**

- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow
- yfinance

## 📁 Project Structure

```text
Stock_Price_Trend_Prediction_with_LSTM.ipynb  # Main notebook
README.md                                     # Project description
requirements.txt                              # Python dependencies
```

## 🚀 How to Run

1. Clone this repository or download the files.
2. Install the dependencies.
3. Open the notebook:

```bash
jupyter notebook Stock_Price_Trend_Prediction_with_LSTM.ipynb
```

4. Run all the cells to fetch data, preprocess it, train the model, and visualize results.

## 📊 Output

- Data visualization for training and test sets
- Model prediction vs actual values
- MSE (Mean Squared Error) for performance evaluation

## 🧠 Model Details

- **LSTM layers:** 1 or more (configurable)
- **Loss function:** Mean Squared Error
- **Optimizer:** Adam

## 📌 Notes

- You can change the stock ticker symbol (e.g., `'AAPL'`) in the notebook to try different stocks.
- Make sure you have a stable internet connection while fetching data from Yahoo Finance.

## 📃 License

This project is licensed under the MIT License. Feel free to use or modify it as needed.
