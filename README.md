# week-10
# Data Preprocessing Report – Customer Churn Prediction

## Dataset Overview
The dataset contains customer demographic, billing, and service usage
information. The target variable is Churn (Yes/No).

## Data Cleaning
- Removed outliers using IQR and Z-score methods
- Converted target variable into binary format

## Encoding Techniques
- Label Encoding for binary categorical features
- One-Hot Encoding for nominal features
- Binary Encoding discussed for scalability

## Feature Scaling
- Min-Max Scaling used for normalization
- Standard Scaling used for model robustness

## Outlier Handling
Outliers in MonthlyCharges were detected and removed to prevent
model bias.

## Preprocessing Pipeline
A complete preprocessing pipeline was created using
ColumnTransformer and Pipeline to avoid data leakage.
