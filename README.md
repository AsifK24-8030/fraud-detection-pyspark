# Credit Card Fraud Detection with PySpark
This project implements a machine learning pipeline in **PySpark** to detect fraudulent credit card transactions.  
It handles imbalanced datasets, trains models (Logistic Regression, Decision Tree), evaluates their performance, and saves the best model.

---

## Project Contents

- `Frauddetection.py` → main Python script  
- `Final_Project.ipynb` → Jupyter notebook version  
- `credit_card_model.pkl` → saved model (using joblib)  
- `requirements.txt` → Python dependencies  
- `README.md` → this file  

---

## Features

1) Data preprocessing with PySpark  
2) Handle imbalanced dataset (undersampling)  
3) Train Logistic Regression & Decision Tree classifiers  
4) Evaluate using accuracy, precision, recall, F1-score  
5) Save/load model with `joblib`  
6) Make predictions on new transactions

---

## Requirements

Make sure you have:
- Python 3.x  
- PySpark  
- pandas  
- numpy  
- scikit-learn  
- imbalanced-learn  
- joblib

Install all dependencies:
```bash
pip install -r requirements.txt
