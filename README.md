# Stock Price Predictor using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict stock closing prices based on historical stock market data.

Historical stock data is collected using Yahoo Finance, processed using Pandas, and a Linear Regression model is trained to predict stock prices.

The project demonstrates a simple end-to-end Machine Learning workflow, from data collection and preprocessing to model training, evaluation, and visualization.

## 🎯 Objective

To develop a simple Machine Learning model that predicts stock closing prices using historical stock market features.

## 🚀 Features

* Fetches historical stock data automatically
* Data preprocessing and cleaning
* Uses Open, High, Low, and Volume as input features
* Linear Regression Machine Learning model
* Training and testing dataset split
* Model performance evaluation
* Actual vs Predicted price visualization
* Generates prediction results

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Yahoo Finance (`yfinance`)

## 📊 Machine Learning Model

The project uses **Linear Regression** for stock price prediction.

### Input Features

* Open Price
* High Price
* Low Price
* Trading Volume

### Target

* Closing Price

## 🔄 Project Workflow

```text
Historical Stock Data
        ↓
Data Collection
        ↓
Data Cleaning
        ↓
Feature Selection
        ↓
Train/Test Split
        ↓
Linear Regression
        ↓
Price Prediction
        ↓
Model Evaluation
        ↓
Visualization
```

## 📈 Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Example result from the current experiment:

```text
Mean Absolute Error : 0.74
Mean Squared Error  : 1.00
R² Score            : 0.9994
```

> Note: These results are specific to the dataset and experiment configuration used in this project. Stock-market prediction performance can vary significantly with different time periods and modeling approaches.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/gokhulnath7/Stock-Price-Predictor.git
```

Move into the project:

```bash
cd Stock-Price-Predictor
```

Create a virtual environment:

```bash
python3 -m venv venv
```

Activate it:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

```bash
python3 stock_predictor.py
```

The program downloads the historical stock data, trains the model, displays evaluation metrics, and generates a prediction graph.

## 📷 Output

The project generates a visualization comparing:

```text
Actual Stock Prices
        vs
Predicted Stock Prices
```

## 📁 Project Structure

```text
Stock-Price-Predictor/
│
├── stock_predictor.py
├── requirements.txt
├── README.md
├── prediction.png
└── .gitignore
```

## 🔮 Future Improvements

* Predict the next day's closing price
* Add technical indicators such as Moving Average and RSI
* Compare Linear Regression with Random Forest
* Implement XGBoost
* Explore LSTM-based time-series prediction
* Add a Streamlit web interface
* Support multiple stocks
* Add real-time prediction functionality

## ⚠️ Disclaimer

This project is created for educational and Machine Learning purposes. Stock price predictions are uncertain and should not be considered financial advice.

## 👨‍💻 Author

**Gokhulnath**

GitHub:
https://github.com/gokhulnath7
