# Comparative Analysis of Stock Price Prediction using Machine Learning and Deep Learning

A comparative study of **Machine Learning** and **Deep Learning** models for forecasting stock prices using historical **Adani Enterprises Ltd.** stock market data. This project evaluates the performance of **LSTM**, **Random Forest**, and **XGBoost** models to identify the most effective approach for time-series stock price prediction.

---

## Project Overview

Stock price prediction is a challenging time-series forecasting problem influenced by market trends, investor sentiment, and external events. Accurate prediction models can support better investment decisions and financial analysis.

This project investigates the effectiveness of three predictive models—**Long Short-Term Memory (LSTM)**, **Random Forest**, and **XGBoost**—using historical stock data from **Adani Enterprises Ltd.** The performance of each model is evaluated using standard regression metrics to compare prediction accuracy.

---

## Project Highlights

- Historical stock price analysis of Adani Enterprises Ltd.
- Comparative evaluation of Machine Learning and Deep Learning models
- Time-series forecasting using LSTM
- Regression-based prediction using Random Forest and XGBoost
- Performance evaluation using MAE, MSE, RMSE, and R² Score
- Data visualization for trend analysis and model predictions

---

## Problem Statement

The objective of this project is to develop predictive models capable of forecasting stock prices based on historical market data and to compare the performance of different machine learning and deep learning approaches.

---

## Dataset

The project uses historical stock market data of **Adani Enterprises Ltd.**

The dataset contains historical trading information such as:

- Open Price
- High Price
- Low Price
- Closing Price
- Adjusted Closing Price
- Trading Volume

> **Note:** The dataset is not included in this repository. It can be obtained from publicly available financial data providers such as Yahoo Finance.

---

## Project Workflow

```
Historical Stock Data
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Feature Engineering
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
 ┌───────────────┬───────────────┬──────────────┐
 │               │               │
 ▼               ▼               ▼
LSTM      Random Forest      XGBoost
 │               │               │
 └───────────────┴───────────────┘
          │
          ▼
Performance Evaluation
          │
          ▼
Prediction & Comparison
```

---

## Models Used

### Long Short-Term Memory (LSTM)

A deep learning model designed for sequential and time-series data. LSTM captures long-term temporal dependencies and is well suited for stock market forecasting.

### Random Forest

An ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### XGBoost

An optimized gradient boosting algorithm known for high predictive performance and efficient handling of structured datasets.

---

## Model Performance

| Model | MAE | MSE | RMSE | R² Score |
|------|------:|------:|------:|------:|
| **LSTM** | **₹98.03** | **25,126.50** | **158.51** | **0.9299** |
| Random Forest | ₹232.59 | 84,391.31 | 290.50 | 0.7640 |
| XGBoost | ₹109.22 | 22,479.30 | — | 0.9158 |

### Performance Summary

Among the evaluated models, the **LSTM model achieved the highest predictive performance**, obtaining the highest **R² Score (0.9299)** and the lowest prediction error. The comparative analysis demonstrates the effectiveness of deep learning techniques for capturing temporal dependencies in financial time-series data.

---

## Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, Random Forest |
| Deep Learning | TensorFlow, Keras (LSTM) |
| Gradient Boosting | XGBoost |
| Visualization | Matplotlib, Seaborn |
| Development | Jupyter Notebook |

---

## Repository Structure

```
stock-price-prediction-using-machine-learning
│
├── Stock_Price_Prediction.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
│
├── dataset/
│   └── README.md
│
├── images/
│
└── results/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/MangaiS20/stock-price-prediction-using-machine-learning.git
```

Move into the project directory:

```bash
cd stock-price-prediction-using-machine-learning
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```
Stock_Price_Prediction.ipynb
```

---

## Future Enhancements

- Incorporate real-time stock market data
- Evaluate Transformer-based forecasting models
- Hyperparameter optimization
- Multi-stock prediction
- Sentiment analysis using financial news
- Deployment as a web application

---

## Academic Project

This project was developed as an **Academic Group Project** as part of the **M.Sc. Data Science** curriculum at **SASTRA Deemed to be University**.

The project focuses on comparing machine learning and deep learning techniques for stock price prediction using historical financial data.

---

## Author

**Mangai S**

**M.Sc. Data Science**

SASTRA Deemed to be University

**Python | Machine Learning | Deep Learning | Data Analytics**

📧 Email: **mangaiofficial20@gmail.com**

💼 LinkedIn: **https://www.linkedin.com/in/mangais20**

---

⭐ If you find this project useful, consider giving it a star.
