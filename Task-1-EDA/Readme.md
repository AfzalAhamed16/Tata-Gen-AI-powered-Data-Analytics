# Exploratory Data Analysis and Risk Profiling – Geldium

This project performs Exploratory Data Analysis (EDA) on Geldium’s customer dataset to evaluate data quality, detect inconsistencies, and identify early indicators of credit delinquency risk before predictive modeling.

The objective of this analysis is to help Tata iQ’s analytics team and Geldium’s decision-makers better understand the current state of the data and improve the reliability of future delinquency risk models.

The dataset contains information for 500 customers and includes key financial and credit-related variables such as Age, Income, Credit Score, Credit Utilization, Missed Payments, Debt-to-Income Ratio, Employment Status, and Credit Card Type.

Both numerical and categorical variables were reviewed to understand the dataset structure and identify potential quality issues that could affect modeling outcomes.

Initial exploration revealed missing values in important fields, particularly Income and Loan Balance. These missing values could bias model predictions if not handled appropriately.

To address data quality issues, missing numeric values were treated using median imputation to reduce the influence of outliers. In addition, AI-assisted synthetic estimation was used for selected fields to preserve realistic data distributions.

Anomaly detection was also performed to identify unusual patterns, such as high-income customers with low credit scores, which may require further investigation for accuracy or fraud risk.

The analysis explored relationships between key variables and delinquency outcomes. High credit utilization (above 50%) was found to be strongly associated with higher default risk.

Customers with three or more missed payments within six months showed a significantly increased likelihood of delinquency, making missed payment history a critical risk indicator.

GenAI tools were used to summarize missing values, surface trends, and prioritize important predictors of delinquency. These insights were validated using standard financial risk indicators.

Key risk factors identified include high credit utilization, repeated missed payments, and unfavorable debt-to-income ratios.

Unexpected patterns, such as customers with high income but low credit scores, were flagged for further review by the analytics team.

The findings of this EDA support improved data preparation and feature selection for future predictive modeling tasks.

This analysis also helps refine intervention strategies by highlighting customer segments that are more likely to become delinquent.

Overall, the EDA provides a strong foundation for building reliable and explainable credit risk prediction models.
