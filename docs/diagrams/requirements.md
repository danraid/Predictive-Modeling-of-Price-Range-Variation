# 📌 Project Requirements Documentation

## 🎯 Project Overview
This project focuses on predictive modeling of EUR/USD price variations based on economic news sentiment analysis. The goal is to develop a machine learning model capable of forecasting price movements using historical price data and sentiment indicators.

## 🔥 Functional Requirements
### 1. **Data Processing**
- The system must be able to load historical forex price data from CSV files.
- The system must preprocess data by handling missing values and outliers.
- The system must extract relevant technical indicators from forex data.

### 2. **Sentiment Analysis**
- The system must collect economic news articles from external sources.
- The system must apply NLP techniques to analyze the sentiment of news articles.

### 3. **Machine Learning Models**
- The system must support multiple ML models (Random Forest, XGBoost, LSTM, etc.).
- The system must allow hyperparameter tuning to optimize models.
- The system must evaluate model performance using RMSE, MAE, and R-Squared.

### 4. **Visualization & Reporting**
- The system must generate visualizations of model predictions.
- The system must provide performance comparison charts.

### 5. **Deployment**
- The system must deploy the trained model via an API using Flask or FastAPI.
- The system must allow real-time price prediction based on input features.

## 🔍 Non-Functional Requirements
### 1. **Performance**
- The system must preprocess data within a reasonable time frame (< 1 min for standard dataset sizes).
- The model inference should return predictions within 2 seconds.

### 2. **Scalability**
- The system should support new data sources without major modifications.
- The API should handle concurrent requests efficiently.

### 3. **Security**
- The system must ensure data privacy and prevent unauthorized access.
- API endpoints must have basic authentication mechanisms.

### 4. **Maintainability**
- The system should be modular and easy to extend with new ML models.
- Code should follow best practices and be well-documented.

## 📊 System Constraints
- The system relies on publicly available forex price datasets.
- Sentiment analysis accuracy depends on the quality of the collected news articles.

## 🏆 Acceptance Criteria
- The ML model achieves at least **70% accuracy** in predicting price variations.
- The system correctly preprocesses data and extracts features.
- The API provides reliable predictions with minimal latency.

---
✅ **Author:** Daniel Raid  
✅ **Contact:** daniel.e.raid@gmail.com