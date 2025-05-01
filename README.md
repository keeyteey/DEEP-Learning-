# LSTM Time Series Prediction

This project uses a Long Short-Term Memory (LSTM) neural network to perform time series prediction using Keras and TensorFlow. The code is implemented in a Jupyter Notebook (`LSTM_.ipynb`).

##  Project Structure

- `LSTM_.ipynb`: Main notebook containing data preprocessing, model creation, training, and evaluation.

##  Features

- Implements LSTM for univariate or multivariate time series forecasting.
- Scales data using MinMaxScaler.
- Splits data into training and testing sets.
- Builds a sequential LSTM model.
- Evaluates model performance using Mean Squared Error (MSE) or similar metrics.
- Visualizes predictions vs. actual values.

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
