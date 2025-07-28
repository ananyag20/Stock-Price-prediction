

## Overview
This project predicts future stock prices using historical data and an LSTM (Long Short-Term Memory) model. It demonstrates time-series forecasting with deep learning using Python and Keras.

## Tools Used
- Python, yfinance
- NumPy, Pandas, Scikit-learn
- TensorFlow / Keras
- Matplotlib, Streamlit (optional)

## Steps
1. Fetch stock data using `yfinance`
2. Normalize and convert to sequences
3. Train LSTM model on 60-day windows
4. Predict and visualize stock trends
5. (Optional) Deploy using Streamlit

## Run Dashboard
```bash
streamlit run app.py
