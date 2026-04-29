# Stock Price Prediction with Deep Learning

Predicting NASDAQ and Vietnam stock prices using Conv1D and LSTM neural networks.

## Overview
This project compares two deep learning architectures for time-series stock price forecasting,
using multi-feature inputs from real market data (NASDAQ & Vietnam stock exchange).

## Key Results
- **Conv1D** significantly outperformed LSTM with lower MSE on test data
- Multi-feature input (Open, Close, High, Low, Volume) improved accuracy vs. single-feature baseline

## Tech Stack
- Python, TensorFlow/Keras, Pandas, NumPy, scikit-learn, Matplotlib
- Models: Conv1D, LSTM
- Techniques: MinMaxScaler normalization, sliding window (30-day), train/val/test split

## Project Structure
- 220226_project_notebook.ipynb   # Main analysis notebook
- README.md

## How to Run
1. Open notebook in Google Colab or Jupyter
2. Mount your Google Drive and update the CSV path
3. Run all cells sequentially
