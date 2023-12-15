# Stock Price Prediction with Linear Regression

## Overview

This project utilizes linear regression to predict stock prices based on historical data obtained from the Alpha Vantage API. The goal is to provide users with insights into potential future stock price movements, aiding in investment decisions, risk management, and financial planning.

## Features Used for Prediction

The project uses the following columns from the Alpha Vantage dataset:

1. Open: The price at which a stock started trading when the market opened on a particular day.
2. Close: The price of an individual stock when the stock exchange closed the market for the day.
3. High: The highest price at which a stock traded during a period.
4. Low: The lowest price of the period.
5. Volume: The total amount of trading activity during a period of time.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries (install using `pip install -r requirements.txt`):
  - pandas
  - numpy
  - scikit-learn
  - matplotlib

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pekincelif/stock-price-prediction-ml.git

2. Install dependencies:
    ```bash
   cd stock-price-prediction-ml
   pip install -r requirements.txt

3. Obtain an API key from Alpha Vantage: [Alpha Vantage API](https://www.alphavantage.co/support/#api-key)
4. Update the configuration(config.py):
 
    ```bash
    ALPHA_VANTAGE_API_KEY = "your_api_key_here"

### Usage

1. Run the Jupyter notebook or Python script to train the linear regression model and make predictions.

   ```bash
      python stock_price_prediction.py
2. Explore the visualizations and evaluation metrics in the notebook or generated plots.

 ### Results and Achievements
 - Users can make informed investment decisions based on predicted stock prices.
 - Risk management is facilitated through insights into potential future stock price movements.
 - Financial planning can benefit from projections for companies of interest.
 - Educational resource for learning about machine learning in the finance domain.
 - Contribution to the broader field of machine learning and finance research.
 
### Notes
  This project is for educational and experimental purposes. Predicting stock prices is inherently uncertain, and users should exercise caution when making financial decisions based on model predictions.

### Acknowledgments
  This project uses data from [Alpha Vantage](https://www.alphavantage.co/).



   
