# Rainfall Prediction Classifier Using Machine Learning

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pathananas2007/Rainfall-Prediction-Classifier-Using-Machine-Learning/blob/main/final%202.ipynb)

**Author:** [@pathananas2007](https://github.com/pathananas2007)

---

## 📄 About
End-to-end **Rainfall Prediction pipeline** using Python. Implements **data cleaning, feature engineering (Season), preprocessing, and multiple ML models** (Random Forest, XGBoost, SVM, KNN, Logistic Regression, Gradient Boosting) with **hyperparameter tuning, evaluation, and model comparison**.

---

## 📊 Dataset
- **File:** `data final.csv`  
- **Source:** [Australian Government Bureau of Meteorology – Climate Data Online](http://www.bom.gov.au/climate/dwo/)  
- Contains cleaned weather data for Melbourne, Melbourne Airport, and Watsonia.

---

## 🐍 Python Version
This project is tested with **Python 3.11**.

---

## 🛠 Dependencies
All required libraries are listed in `requirements.txt`. Key packages:
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn

Install dependencies with:

```bash
pip install -r requirements.txt
## 📈 Results Snapshot

### Accuracy & AUC Scores
| Model                  | Test Accuracy | AUC Score |
|------------------------|---------------|-----------|
| Random Forest          | 0.85          | 0.91      |
| Gradient Boosting      | 0.84          | 0.90      |
| XGBoost                | 0.86          | 0.92      |
| Logistic Regression    | 0.79          | 0.82      |
| SVM                    | 0.80          | 0.83      |
| KNN                    | 0.78          | 0.80      |



### ROC Curve Comparison (All Models)
![ROC Curve](https://github.com/user-attachments/assets/1c814834-f1c1-40fc-8381-02c9f6a0cefe)

