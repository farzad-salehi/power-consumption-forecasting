# power-consumption-forecasting
Electricity consumption forecasting using deep learning models (MLP &amp; CNN) on time series data
# Power Consumption Forecasting using Deep Learning

This project focuses on forecasting electricity consumption for three different zones using deep learning models on time series data.

## Project Objectives
- Analyze electricity consumption patterns over time
- Perform feature engineering on time-based data
- Build and compare deep learning models for multi-output regression
- Predict power consumption for multiple zones simultaneously

## Dataset
The dataset contains:
- Electricity consumption data for three zones
- Weather-related features:
  - Temperature
  - Humidity
  - Wind Speed
- Datetime column used for time-series feature extraction

## Feature Engineering
Time-based features extracted include:
- Hour, day of week, month, year
- Day of year, week of year, quarter
- Season and weekend indicators
- Business hours and peak hours

##  Models Implemented
### 1. Multi-Layer Perceptron (MLP)
- Fully connected neural network
- Adam optimizer
- Mean Squared Error (MSE) loss

### 2. Convolutional Neural Network (CNN)
- 1D convolution layers for time-series data
- MaxPooling and Dense layers
- Multi-output regression for three zones

## Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

##  Technologies & Libraries
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

##  How to Run
1. Install Python 3.10
2. Install dependencies:
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
