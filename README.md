# Credit-Card-Fraud-Detection
Credit Card Fraud Detection using XGBoost, SMOTE and threshold tuning
# Credit Card Fraud Detection

## Objective
To detect fraudulent credit card transactions using **XGBoost** on a highly imbalanced dataset.

## Dataset
- **IEEE-CIS Fraud Detection Dataset**
- Target variable: `isFraud`
- Source: Kaggle

## Methodology
1. Data preprocessing and missing value handling
2. Stratified sampling for manageable processing
3. Train-validation split
4. **SMOTE** for handling class imbalance
5. **XGBoost** for fraud classification
6. Decision threshold tuning
7. Model evaluation using **ROC-AUC, PR-AUC, Precision, Recall and F1-score**
8. Feature importance analysis

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Matplotlib
- Google Colab

## Files
- `credit_card_fraud_detection_case_study.ipynb` – Complete implementation
- `fraud_predictions.csv` – Model predictions

## Result
The model identifies potentially fraudulent transactions and provides fraud probabilities. Feature importance is used to understand the features contributing to the predictions.

## Dataset Source
Kaggle: IEEE-CIS Fraud Detection
