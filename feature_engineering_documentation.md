# Feature Engineering Documentation

## Engineered Features

### Customer Lifetime Value (CLV)
Formula: MonthlyCharges × Tenure  
Purpose: Identifies high-value customers

### Average Monthly Spend
Formula: TotalCharges / Tenure  
Purpose: Normalizes customer spending

### High Value Customer
Logic: MonthlyCharges above median  
Purpose: Revenue impact analysis

### Payment Efficiency
Formula: TotalCharges / MonthlyCharges  
Purpose: Measures payment consistency

### Log Monthly Charges
Purpose: Reduces skewness in cost data

## Impact
Engineered features improve churn prediction accuracy by capturing
customer behavior and value patterns.
