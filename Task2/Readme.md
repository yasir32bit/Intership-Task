
# Task 02: Short-Term Stock Price Prediction Using Machine Learning

## Objective

The objective of this task is to predict the short-term closing price of a stock using historical market data. The task demonstrates the application of regression-based machine learning models to time-series financial data and evaluates their performance using standard error metrics.

---

## Dataset

* **Source:** Yahoo Finance
* **Access Method:** `yfinance` Python library
* **Stock Selected:** Apple Inc. (AAPL)
* **Time Period:** January 2023 – December 2024

### Features Used

* Open Price
* High Price
* Low Price
* Trading Volume

### Target Variable

* Closing Price

---

## Tools and Technologies

* **Programming Language:** Python
* **Libraries Used:**

  * yfinance – data retrieval
  * Pandas – data manipulation
  * Matplotlib & Seaborn – visualization
  * Scikit-learn – model training and evaluation

---

## Methodology

### 1. Data Collection

* Historical stock price data was fetched directly from Yahoo Finance using the `yfinance` API.
* The dataset includes daily trading records with open, high, low, close prices, and volume.

### 2. Data Exploration

* Displayed the first few rows of the dataset
* Examined dataset structure and data types using `.info()`
* Generated descriptive statistics using `.describe()`

### 3. Feature Selection

* Input Features: Open, High, Low, Volume
* Target Variable: Close Price

### 4. Train-Test Split

* Data was split into training and testing sets using an 80/20 ratio.
* Shuffling was disabled to preserve the time-series order of stock prices.

---

## Models Implemented

1. **Linear Regression**

   * Used as a baseline regression model.

2. **Random Forest Regressor**

   * An ensemble learning model used to capture non-linear relationships in the data.

---

## Model Evaluation

Models were evaluated using the following metrics:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**

Both models’ predictions were compared against actual closing prices to assess performance.

---

## Visualization

* A line plot was generated to compare:

  * Actual closing prices
  * Predicted prices from Linear Regression
  * Predicted prices from Random Forest

This visualization helps assess how closely the models track real market behavior.

---

## Key Findings

* Random Forest generally performed better than Linear Regression due to its ability to model non-linear patterns.
* Linear Regression provided a simple and interpretable baseline.
* Stock price prediction remains challenging due to market volatility and external factors.

---