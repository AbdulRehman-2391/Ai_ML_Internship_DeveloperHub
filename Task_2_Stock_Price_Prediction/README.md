# Task 2: Predict Future Stock Prices (Short-Term)

## Objective
Use historical stock data from Yahoo Finance to predict the next day's closing price using regression modeling.

## Files in this folder
- `stock_price_prediction.ipynb` — Jupyter notebook containing data fetching, training, and plotting.
- `README.md` — this file.

## Steps performed
1. Selected stock: **Apple (AAPL)**.
2. Loaded historical stock data using the `yfinance` library.
3. Extracted features: `Open`, `High`, `Low`, and `Volume`.
4. Target variable: `Close` (next day).
5. Created lag features to predict the next day's closing price.
6. Split data into training and testing sets (80/20 split).
7. Trained a **Linear Regression** model.
8. Predicted closing prices on the test set.
9. Plotted **Actual vs Predicted** closing prices for comparison.

## Libraries used
- pandas
- yfinance
- scikit-learn
- matplotlib

## How to run
1. Install required libraries:
   ```bash
   pip install pandas yfinance scikit-learn matplotlib
