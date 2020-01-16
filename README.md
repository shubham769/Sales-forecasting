### Product Sales Forecasting using Quantitative Methods

Time series forecasting is one of the major building blocks of Machine Learning. There are many methods in the literature to achieve this like Autoregressive Integrated Moving Average (ARIMA), Seasonal Autoregressive Integrated Moving-Average (SARIMA), Vector Autoregression (VAR), and so on.


<b>Goal:</b> The goal of this project was to apply various quantitative methods, (i.e. Times Series Models and Causal Models) to forecast the sales of the products available in the dataset obtained from Kaggle.

You are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores.

What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together? Does deep learning work better than ARIMA? Can either beat xgboost?

In this notebook we will see what seasonality is and how we can use statistical models for forecasting.

You can get train dataset from [here](https://drive.google.com/file/d/1PZ45sBF-9FiULVrDp43bPvDegp1mdqGp/view?usp=sharing) and test dataset from [here](https://drive.google.com/file/d/1PgrZErBIpNv3GSmqu0OBO9d-9_8IPHRR/view?usp=sharing).

<b> Models covered in the notebook include: </b>

1. Seasonal Naive Model
2. Holt-Winters Model (Triple Exponential Smoothing)
3. ARIMA and Seasonal ARIMA Models
4. Linear Regression Model

Note:
I am also working on LSTM for forecasting


