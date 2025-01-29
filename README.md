# Credit Risk Analysis Project

## Overview
This project implements machine learning models to predict credit risk using various customer financial and personal indicators. The analysis employs multiple classification algorithms and ensemble methods to achieve optimal prediction accuracy.

## Dataset
The dataset contains the following features:
- `person_age`: Age of the applicant
- `person_income`: Annual income
- `person_home_ownership`: Home ownership status
- `person_emp_length`: Employment length in years
- `loan_intent`: Purpose of the loan
- `loan_grade`: Loan grade assigned
- `loan_amnt`: Loan amount
- `loan_int_rate`: Interest rate
- `loan_status`: Loan status (target variable)
- `loan_percent_income`: Loan amount as percentage of income
- `cb_person_default_on_file`: Historical default status
- `cb_person_cred_hist_length`: Length of credit history

## Technical Stack
### Dependencies
```python
# Data Processing and Analysis
pandas
numpy

# Visualization
matplotlib
seaborn

# Machine Learning
scikit-learn
xgboost
imbalanced-learn
```

### Models Implemented
- Random Forest Classifier
- Logistic Regression
- Support Vector Machine (SVC)
- AdaBoost Classifier
- Bagging Classifier
- Decision Tree Classifier
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Gradient Boosting
- XGBoost
- Voting Classifier

### Key Features
- Implementation of SMOTE for handling imbalanced data
- Cross-validation with StratifiedKFold
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
- Ensemble methods for improved prediction accuracy
- Comprehensive model evaluation using multiple metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

## Project Structure
```
credit_risk_project/
├── progettocreditrisk.ipynb    # Main analysis notebook
├── data/
│   └── credit_risk_dataset.xlsx
└── images/                     # Generated visualizations
    ├── age.png
    ├── int_rate.png
    ├── chart_model.png
    ├── chart_model2.png
    └── [other visualization files]
```

## Methodology
1. Data Preprocessing
   - Feature scaling using StandardScaler
   - Categorical encoding using OneHotEncoder
   - Handling imbalanced data with SMOTE

2. Model Development
   - Multiple model implementation
   - Cross-validation
   - Hyperparameter optimization

3. Model Evaluation
   - Performance metrics comparison
   - ROC curve analysis
   - Feature importance analysis

## Author
Claudio M.

## License
This project is licensed under the MIT License