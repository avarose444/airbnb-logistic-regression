## Project Overview

This project explores logistic regression model selection using Airbnb listing data. It includes:
- Hyperparameter tuning via GridSearchCV
- Model evaluation using confusion matrix, ROC/AUC curves, and precision-recall analysis
- Feature selection using SelectKBest
- Comparison of models with default vs. optimized hyperparameters
- Final evaluation using only the top 5 most informative features

The goal is to develop a classification model with improved predictive performance by systematically tuning and evaluating logistic regression parameters.

## Key Tools & Techniques
- Python (pandas, scikit-learn, seaborn, matplotlib)
- LogisticRegression
- GridSearchCV
- AUC-ROC & PR curves
- SelectKBest (f_classif)

## Dataset
Airbnb listings dataset (training and test sets split from original source).

