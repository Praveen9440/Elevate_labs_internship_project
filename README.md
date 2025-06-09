# 🧮 Customer Lifetime Value (CLV) Prediction Model

## 🎯 Objective
Predict the lifetime value of customers based on their purchase behavior to assist businesses in identifying high-value customers and optimizing marketing strategies.

---

## 🧠 Problem Statement
Businesses need a way to estimate the future value of their customers in order to make data-driven decisions around marketing spend, customer retention, and loyalty programs. This project uses historical purchase data to build a machine learning model that predicts the Customer Lifetime Value (CLV) for each customer.

---

## 📂 Project Structure

```
clv_prediction_model/
├── data/                   # Raw dataset (Excel file)
├── notebooks/              # Jupyter Notebook with code
├── models/                 # Trained model (.pkl)
├── output/                 # Predicted CLV CSV
├── report/                 # Final 2-page PDF report
├── requirements.txt        # List of required packages
└── README.md               # Project description
```

---

## 🧰 Tools & Libraries Used

- **Language**: Python 3.10+
- **IDE**: Jupyter Notebook
- **Libraries**:
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn
  - xgboost
  - joblib
  - openpyxl

---

## 📊 Key Features Engineered

- **Recency**: Days since last purchase  
- **Frequency**: Number of transactions  
- **Monetary Value**: Total amount spent  
- **Average Order Value (AOV)**: Monetary value / Frequency  
- **Quantity**: Total quantity purchased  

---

## 📈 Model Used

- **XGBoost Regressor**  
  Trained on key features to predict customer lifetime value (CLV).

- **Evaluation Metrics**:  
  - MAE (Mean Absolute Error)  
  - RMSE (Root Mean Squared Error)

---

## 🏷️ Output

- Trained model saved as: `models/clv_model.pkl`  
- Final predictions with segmentation saved to: `output/predicted_clv.csv`  
- Customers segmented into 4 groups: `High`, `Mid-High`, `Mid-Low`, `Low`

---

## ✅ Steps to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/clv_prediction_model.git
cd clv_prediction_model
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook notebooks/CLV_Prediction_Model.ipynb
```

---

## 📄 Report

You can find the final 2-page project report in:
```
report/🧮 Customer Lifetime Value (CLV) Prediction Model.pdf
```

---

## 🤝 Acknowledgements

- Dataset: UCI Machine Learning Repository – Online Retail II Dataset
- Tools: Jupyter, XGBoost, Scikit-learn

---
