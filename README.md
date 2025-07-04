# Nvidia-Stock-Prediction-Using-LSTM
This project uses Long Short-Term Memory (LSTM) networks, a type of Recurrent Neural Network (RNN), to predict the future stock prices of Nvidia Corporation (NVDA) based on historical data.

## 📂 Project Structure
.
### ├── NvIdia stock prediction using LSTM.ipynb
### ├── README.md
### └── requirements.txt 

## 🧠 Model Overview

The model uses an LSTM architecture trained on Nvidia's stock price data with the objective of forecasting the closing price.

## 🏗️ Architecture

### Input Sequence Length: 60 days

### LSTM Layers: 2

### Dense Output Layer: 1 neuron

### Loss Function: Mean Squared Error (MSE)

### Optimizer: Adam

## 📊 Features Used

### Close prices are used as the main predictive feature.

### Data is scaled using MinMaxScaler.

### Data split: 80% training, 20% testing.

### Visualization of predictions vs. actual prices is included.

## 📌 Notes
### This model is trained on past data and is not suitable for actual financial trading without further validation.

### LSTM models capture short- to medium-term trends but may not generalize well over long horizons.

