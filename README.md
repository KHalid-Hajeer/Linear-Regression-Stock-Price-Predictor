# Stock Price Movement Prediction Using Linear Regression #

## Project Overview
This project aims to predict stock price movements (e.g., +0.41, +3.13, -21.00) using linear regression. By analysing historical stock price data and various financial indicators, we will develop a model to forecast the changes in stock prices.

## Features
- **Previous Day's Closing Price:** The closing price of the stock from the previous day.
- **5-Day Moving Average (Simple Moving Average (SMA)):** The average closing price over the last 5 days.
- **20-Day Moving Average (Exponential Moving Average (EMA)):** The exponential moving average over the last 20 days.
- **Relative Strength Index (RSI):** Measures the speed and change of price movements.
- **Trading Volume:** The number of shares traded in the previous day
- **Earnings Per Share (EPS):** The company's earnings divided by the number of outsdanding shares.

## Project Structure 
```
├── data
│   ├── stock_data.csv
├── notebooks
│   ├── data_preprocessing.ipynb
│   ├── exploratory_data_analysis.ipynb
│   ├── model_building.ipynb
│   ├── model_evaluation.ipynb
├── app
│   ├── app.py
├── README.md
└── requirements.txt
```

## Contibuting
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT license - see the LICENSE file for details

## Acknowledgements
- Yahoo Finance for the stock price data
- Scikit-learn for the machine learning library
- Flask and Streamlit for web application deployment
