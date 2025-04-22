# 🪙 Gold Price Prediction Using Machine Learning

This project develops a **machine learning-based regression model** to predict gold prices using historical market data. The goal is to capture underlying market trends and dependencies to forecast future gold prices accurately.

---

## 📂 Data

The dataset used for this project:

- `FINAL_USO.csv`

### Key Features:

- **Date** – Timestamp of each data point  
- **Open, High, Low, Close** – Daily market values of US Oil Fund (USO)  
- **Volume** – Trading volume  
- Other engineered features may be included based on preprocessing

---

## 🔍 Workflow

The project follows a systematic data science pipeline:

- **Exploratory Data Analysis (EDA)**:
  - Visualizing trends and distributions  
  - Detecting correlations and patterns with gold prices

- **Feature Engineering**:
  - Creating lag variables, rolling statistics, and other relevant features  
  - Handling missing or inconsistent data  

- **Model Development**:
  - Training **regression models** such as:
    - Linear Regression  
    - Random Forest Regressor  
    - XGBoost  
  - Evaluating model performance using RMSE and R² metrics  

- **Model Optimization**:
  - Hyperparameter tuning using Grid Search / Cross-Validation

---

## 🎯 Key Outcomes

- Built robust regression models to predict gold prices using market indicators  
- Identified significant predictors through feature importance analysis  
- Demonstrated how **machine learning** can effectively model time series financial data

---

## 📁 Notebook & Outputs

- `Gold Price Prediction Dataset.ipynb`: Full pipeline from data preprocessing to model evaluation and prediction visualization

Key outputs:

- Correlation heatmaps and feature importance plots  
- Comparative performance of different models  
- Final prediction plots against actual values

---

## 🛠️ Libraries Used

- **Data Handling**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  
- **Modeling**: `scikit-learn`, `xgboost`  
- **Tuning & Evaluation**: `GridSearchCV`, performance metrics from `sklearn`

---

## ✅ How to Use

1. Clone this repository  
2. Place `FINAL_USO.csv` in the same directory as the notebook  
3. Open and run `Gold Price Prediction Dataset.ipynb`  
4. Experiment with different models or time windows to fine-tune predictions

---

## 🚀 Future Enhancements

- Incorporate **external market indicators** (e.g., inflation, interest rates, USD index)  
- Implement **LSTM-based deep learning models** for time series prediction  
- Deploy the model via a **Flask/Django API**  
- Create a **real-time dashboard** with auto-updating predictions

---

## 👤 Author

**Rohit Shivhare**  
[LinkedIn](https://www.linkedin.com/in/rohit-shivhare-a857a4233/)  
*MSc Data Science – Brunel University, London*
