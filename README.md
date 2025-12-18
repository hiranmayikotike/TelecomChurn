Telecom Customer Churn Prediction

Business Problem
Customer churn leads to revenue loss in the telecom industry. The objective of this project is to identify high-risk customers so that proactive retention strategies can be applied.

Dataset
Source: Telco Customer Churn Dataset
Rows: 7043
Target Variable: Churn (Yes/No)

EDA Insights
- Month-to-month customers churn more
- Customers with low tenure are more likely to churn
- High monthly charges increase churn probability
- Lack of technical support is associated with higher churn

Feature Engineering
- Encoded categorical variables
- Scaled numerical features
- Final dataset prepared for modeling

Models
Logistic Regression (Baseline)
Recall (Churn): ~0.56
ROC-AUC: ~0.84

Random Forest
Better capture of non-linear patterns and interactions

Business Recommendation
Focus retention efforts on month-to-month customers with low tenure and high monthly charges by offering targeted plans and support.
