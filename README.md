# LSTM for Time Series Prediction

This project demonstrates how to use Long Short-Term Memory (LSTM) networks in PyTorch to predict the next value in a sine wave time series.

## Features
- Data generation:
  - Synthetic sine wave data is generated as a sequence of 50 steps to predict the next step.
- Model:
  - An LSTM-based model with two layers and 64 hidden units per layer.
- Training:
  - The model is trained using Mean Squared Error (MSE) loss and the Adam optimizer.
- Evaluation:
  - The predictions of the model are compared with the true values on a test dataset.
