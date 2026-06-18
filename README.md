# Stock Market Prediction

## Mid-Price Forecasting of Microsoft (MSFT) Stock Using Deep Learning

### Project Overview

This project focuses on forecasting the mid-price of Microsoft (MSFT) stock using deep learning techniques. The mid-price is calculated as the average of the daily high and low prices and is used as the target variable for prediction.

Financial time-series data is highly nonlinear and influenced by numerous market factors, making accurate forecasting a challenging task. To address this challenge, this project implements and compares multiple deep learning architectures for stock price prediction.

A big data pipeline was developed using Hadoop and PySpark to collect, store, preprocess, and transform historical stock market data. Different look-back windows ranging from 30 to 60 trading days were evaluated to investigate how sequence length impacts forecasting performance across different neural network architectures.

### Objectives

* Predict future MSFT stock mid-prices using deep learning models.
* Build a scalable data processing pipeline using Hadoop and PySpark.
* Compare the performance of different neural network architectures.
* Evaluate the effect of 30-day to 60-day look-back windows on model accuracy.
* Identify the optimal architecture and sequence length for stock price forecasting.

### Technologies Used

* Python
* TensorFlow / Keras
* Hadoop
* PySpark
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

### Methodology

1. Collect historical MSFT stock data.
2. Calculate the mid-price using daily high and low prices.
3. Clean and preprocess the data using PySpark.
4. Generate sequences with varying look-back periods (30–60 days).
5. Train and evaluate deep learning models.
6. Compare model performance using forecasting metrics.

### Results

The study demonstrates how prediction accuracy varies across different deep learning architectures and look-back periods. Results highlight the importance of selecting an appropriate sequence length for financial time-series forecasting and provide insights into building more effective quantitative trading models.

### Future Improvements

* Incorporate additional technical indicators.
* Include macroeconomic and market sentiment data.
* Experiment with Transformer-based architectures.
* Deploy the model as a real-time prediction service.
