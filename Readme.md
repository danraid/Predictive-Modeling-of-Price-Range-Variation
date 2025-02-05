# Predictive Modeling of EUR/USD Price Variations

## 📌 Project Overview

This project focuses on predictive modeling of price range variations in the EUR/USD forex market based on economic news sentiment analysis. The goal is to develop a machine learning model capable of forecasting price movements based on historical price data and sentiment indicators extracted from financial news.

## 🚀 Features

- Data preprocessing and feature engineering for forex price data.
- Implementation of sentiment analysis on economic news.
- Application of machine learning and deep learning models to predict price variations.
- Model evaluation and performance analysis.
- Visualization of results and insights.

## 📂 Repository Structure

```
/project-name/
│── README.md                 # Project description
│── requirements.txt           # Dependencies
│── .gitignore                 # Git ignored files
│── LICENSE                    # License
│── docs/                      # Documentation
│   │── project_description.md # Technical documentation
│   │── scrum_documentation.md # Scrum documentation
│   │── requirements.md        # Requirements engineering
│   │── diagrams/              # UML diagrams
│── notebooks/                 # Jupyter Notebooks
│   │── PROJETO_IBM_COMPLETO_VER1_0_15_01_24.ipynb
│── src/                       # Source code
│── data/                      # Datasets
│   │── EURUSD_ForexTrading_4hrs_05.05.2003_to_16.10.2021.csv
```

## 📄 Documentation & Diagrams

- [📜 Project Requirements](sandbox:/mnt/data/requirements.md)
- [📜 Scrum Documentation](sandbox:/mnt/data/scrum_documentation.md)
- [📊 UML Diagrams]
  - [Use Case Diagram](sandbox:/mnt/data/use_case_diagram.png)
  - [Class Diagram](sandbox:/mnt/data/class_diagram.png)
  - [Sequence Diagram](sandbox:/mnt/data/sequence_diagram.png)

## 🛠 Technologies Used

| Technology  | Description |
|------------|------------|
| ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) | Core programming language |
| ![NumPy](https://img.shields.io/badge/NumPy-Matrix%20Operations-orange) | Numerical computing |
| ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue) | Data manipulation and analysis |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-green) | Data visualization |
| ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow) | Machine Learning framework |
| ![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red) | Deep learning framework |
| ![InvestPy](https://img.shields.io/badge/InvestPy-Financial%20Data-lightgrey) | Financial data extraction |

This project leverages a combination of Python libraries and frameworks to process, analyze, and model forex data.

## 🔎 Data Processing Workflow
1. 📥 **Data Collection**: Load forex price data and economic news.
2. 🔄 **Data Preprocessing**: Handle missing values, outliers, and feature extraction.
3. 📊 **Exploratory Data Analysis (EDA)**: Generate statistical summaries and visualizations.
4. 🧠 **Feature Engineering**: Create new features from raw data.
5. 📖 **Sentiment Analysis**: Apply NLP techniques to analyze economic news.
6. 🏋️ **Model Training**: Train various ML/DL models and tune hyperparameters.
7. 📈 **Model Evaluation**: Assess model performance using RMSE, MAE, and accuracy.
8. 🚀 **Deployment**: Deploy the best-performing model using Flask or FastAPI.

## 🛠 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-name.git
   cd project-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run the project:
   ```bash
   jupyter notebook notebooks/PROJETO_IBM_COMPLETO_VER1_0_15_01_24.ipynb
   ```

## 📊 Dataset
The dataset used in this project contains forex price data for EUR/USD with 4-hour timeframes spanning from **May 5, 2003, to October 16, 2021**. It includes features such as:
- Open, High, Low, Close prices
- Volume
- Technical indicators
- Sentiment analysis results

## 🔍 Model Performance
- **Machine Learning models**: Random Forest, XGBoost, LSTM, etc.
- **Evaluation Metrics**: RMSE, MAE, Accuracy, R-Squared

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing
Feel free to submit pull requests and contribute to the project!

---

✅ **Author:** Daniel Raid
✅ **Contact:** daniel.e.raid@gmail.com

