Certainly! Here's the modified README file for your "Yes Bank Stock Closing Price Prediction" project with the addition of the dataset section:

---

# Yes Bank Stock Closing Price Prediction

## Table of Contents
1. [Introduction](#introduction)
2. [Models Used](#prediction-models)
3. [Evaluation Metrics](#evaluation-metrics)
4. [How to Execute](#how-to-execute)
5. [Dataset](#dataset)
6. [Conclusion and Future Considerations](#conclusion-and-future-considerations)

## Introduction

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

A Stock or share (also known as a company’s 'equity') is a financial instrument that represents ownership in a company. Units of stock are called "shares." Stocks are bought and sold predominantly on stock exchanges, though there can be private sales as well, and are the foundation of many individual investors' portfolios.

## Dataset

The dataset used in this project is stored in the "data" folder. You can access it by [clicking here](https://drive.google.com/file/d/1qE-lEu9VDFTQ26ivGoBpg4Ztoe1sek7f/view?usp=drive_link).

**Objective:**

The objective of this project is to analyze the impact of a fraud case involving Rana Kapoor on the stock prices of Yes Bank, a prominent bank in the Indian financial domain. The dataset used in this project consisted of monthly stock prices of Yes Bank since its inception, including closing, starting, highest, and lowest stock prices.

## Prediction Models:

To predict the stock's closing price, I developed three models: Ridge Regression, Random Forest, and XGBoost Regressor. These models were trained using historical stock price data and various features, including the mean of Open, High, and Low prices. Additionally, lag features were engineered to capture temporal trends in the data. The XGBoost Regressor model performed exceptionally well both on training and test datasets.

## Evaluation Metrics:

The performance of the models was evaluated using the following metrics:
- RMSE (Root Mean Squared Error)
- Adjusted R2
- R2 score

## How to Execute:

To execute this project and make predictions on Yes Bank's closing stock prices, follow these steps:

1. Open the Jupyter Notebook file named `Yes_Bank_Stock_Price_Prediction.ipynb`:

2. Execute the notebook cell by cell to load and preprocess the data, train the machine learning models, and make predictions.

3. The notebook provides detailed insights into data analysis, feature engineering, model training, and evaluation.



## Conclusion and Future Considerations

The main goal of the project is to create a machine learning model capable of predicting the closing price of Yes Bank stock, taking into account the impact of the fraud case involving Rana Kapoor. The XGBoost Regressor model performed exceptionally well, achieving a high R2 score.

Future considerations for enhancing this project include:
- Exploring daily-level stock price data for finer predictions.
- Incorporating additional features such as holidays, political decisions, events, and volume data.
- Evaluating time series models like ARIMA and LSTM for more precise stock price predictions.

With the current dataset and features, the model performs well on all data points.

I believe that this detailed README provides you with all the necessary insights to delve into the world of "Yes Bank Stock Closing Price Prediction." If you have any questions or need further assistance, please don't hesitate to reach out to me [LinkedIn](www.linkedin.com/in/subhash-somarouthu)

May your predictions be accurate, and your financial decisions be informed! 📈💰


