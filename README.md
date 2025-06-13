# ⚡ Short-Term Load Forecasting Using DWT and Transformer

This project implements a short-term electric load forecasting model using **Discrete Wavelet Transform (DWT)** and a **Transformer-based deep learning model**. 
It is part of a Master's thesis focused on improving time series prediction for energy demand using signal decomposition and attention mechanisms.

## 🔍 Objective

To accurately forecast short-term electric load using a hybrid approach:
- **DWT** is used to decompose noisy load signals into meaningful frequency components.
- **Transformer** captures long-term temporal dependencies in load patterns.
- Results are compared against LSTM models to evaluate forecasting performance.


## 🔧 Preprocessing Techniques

- Min-Max Normalization
- Cyclical Encoding for Time (hour, day)
- Discrete Wavelet Transform (DWT) for denoising and frequency decomposition

## 🧠 Model Architecture

- Encoder-Decoder **Transformer** with attention layers
- Input: DWT-processed time series
- Output: Next N-step load predictions

## 📈 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

