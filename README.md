# Customer Churn Analysis & Prediction (Logistic Regression, Random Forest, XGBoost)

## Project Overview
This project aims to predict customer churn using machine learning techniques. Customer churn refers to customers who stop using a service. Predicting churn helps businesses take proactive retention measures.

## Dataset
The dataset contains customer demographic information, service usage details, and billing information.  
Target variable:
- `Churn` (1 = Yes, 0 = No)

## Methodology
- Data cleaning and preprocessing
- Handling categorical variables using one-hot encoding
- Handling class imbalance
- Model building using Logistic Regression, Random Forest, and XGBoost
- Model evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC

## Results
- XGBoost achieved the best performance with:
  - Accuracy: 79%
  - Recall (Churn): 52%
- The model successfully identifies customers at risk of churn.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## Future Improvements
- Threshold tuning to improve recall
- Hyperparameter optimization
- Model deployment using Flask or FastAPI
