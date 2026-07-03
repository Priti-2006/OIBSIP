# Fraud Detection with Machine Learning

## Oasis Infobyte Data Analytics Internship
**Name:** Priti Ranjit
**Track:** Data Analytics
**Task:** Level 2 - Task 3 (Fraud Detection)

## Objective
Build a machine learning pipeline to detect fraudulent 
financial transactions from a heavily imbalanced dataset.

## Tools Used
- Python 3.11
- Pandas, NumPy
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Jupyter Notebook (VS Code)

## Dataset
Credit Card Fraud Detection Dataset from Kaggle
- 284,807 transactions
- Only 492 fraudulent (0.17%)
- Dataset too large for GitHub (143MB)
- Download from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Steps Performed
1. Class Imbalance Analysis
2. EDA — Transaction Amount Analysis
3. Why Standard Accuracy is Misleading
4. SMOTE Oversampling
5. Logistic Regression Training
6. Decision Tree Training
7. Random Forest Training
8. Model Evaluation (Precision, Recall, F1, AUC-ROC)
9. Confusion Matrices
10. AUC-ROC Curve
11. Feature Importance
12. Scalability Discussion

## Key Insights
- Dataset is highly imbalanced (99.83% normal vs 0.17% fraud)
- Recall is the most important metric for fraud detection
- Random Forest achieved best AUC-ROC score
- SMOTE significantly improved model recall

## Files
- PritiRanjit_L2Task3_FraudDetection.ipynb
- All chart PNG files
- creditcard.csv (not included - too large for GitHub)

