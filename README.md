# Stock Price Prediction Using SVR and Sentiment Analysis

This repository contains a project focused on predicting stock prices using a Support Vector Regression (SVR) model with a Radial Basis Function (RBF) kernel. The project integrates **sentiment analysis** of news articles to enhance prediction accuracy. 

## Features

- **Historical Data Analysis**: Utilized `yfinance` to retrieve historical stock data for three stocks over a one-month period.
- **Sentiment Analysis**: Implemented `TextBlob` to calculate sentiment polarity scores from news articles related to the selected stocks.
- **Machine Learning Model**: Developed an SVR model with an RBF kernel to predict future stock prices based on historical and sentiment data.
- **Feature Engineering**: Standardized features to optimize the SVR model's performance.
- **Prediction and Evaluation**: Generated 30-day future stock price predictions and evaluated the model using Mean Absolute Error (MAE).

## Table of Contents

- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Data Collection](#data-collection)
- [Model Workflow](#model-workflow)
- [Results](#results)
- [Future Work](#future-work)


---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/stock-price-prediction-svr.git
cd stock-price-prediction-svr
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Requirements

- Python 3.8+
- Libraries:
  - `yfinance`
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `TextBlob`
  - `matplotlib`

---

## Data Collection

1. **Historical Stock Data**: 
   - Used `yfinance` to extract historical stock prices for three selected stocks over a one-month period.
2. **News Sentiment Data**: 
   - Processed relevant news articles to derive sentiment polarity scores using the `TextBlob` library.

---

## Model Workflow

1. **Data Preprocessing**:
   - Standardized the features for optimal model performance.
2. **Sentiment Integration**:
   - Incorporated sentiment polarity scores as additional predictors in the SVR model.
3. **SVR Model Training**:
   - Used the RBF kernel to capture non-linear patterns in the data.
4. **Prediction**:
   - Predicted stock prices for the next 30 days based on historical and sentiment data.
5. **Evaluation**:
   - Assessed the model's accuracy using Mean Absolute Error (MAE).

---

## Results

- **Predictions**:
  - The model provided a 30-day forecast of stock prices with satisfactory accuracy.
- **Evaluation**:
  - Achieved an MAE of `X.XX` (replace with actual value).

---

## Future Work

- Explore more sophisticated sentiment analysis techniques such as pre-trained transformers (e.g., BERT, GPT).
- Expand the dataset to include longer time frames and a larger set of stocks.
- Experiment with additional machine learning models such as LSTM for time-series forecasting.

---





---

### Contributions

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests. 

---



Happy Coding! 😊
