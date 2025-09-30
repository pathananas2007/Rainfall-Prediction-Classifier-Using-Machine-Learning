# Rainfall Prediction Classifier Using Machine Learning

**Author:** [@pathananas2007](https://github.com/pathananas2007)  

## 📄 Project Overview
This project implements an **end-to-end machine learning pipeline** to predict rainfall in Melbourne using historical weather data. The workflow includes:  
- Data cleaning and filtering  
- Feature engineering (Date → Season)  
- Preprocessing pipelines (scaling + encoding)  
- Model building and hyperparameter tuning for:  
  - Random Forest  
  - Logistic Regression  
  - SVM  
  - KNN  
  - Gradient Boosting  
  - XGBoost  
- Model evaluation using **accuracy, confusion matrices, classification reports, ROC curves, and AUC scores**  
- Comparison of models to select the best performer  

## 📊 Dataset
- **File:** `data final.csv`  
- **Source:** [Australian Government Bureau of Meteorology – Climate Data Online](http://www.bom.gov.au/climate/dwo/)  
- Contains cleaned weather data for Melbourne, Melbourne Airport, and Watsonia.  

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
