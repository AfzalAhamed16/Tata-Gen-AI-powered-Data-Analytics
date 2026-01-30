# Predicting Delinquency with AI – Geldium

This project presents a conceptual predictive modeling plan to identify customers who are most likely to become delinquent using Geldium’s customer and financial dataset.

The objective of this task is to design a structured modeling approach with the help of GenAI tools, focusing on logic, feature selection, justification, and evaluation rather than writing executable code.

The model is formulated as a binary classification problem where each customer account is classified as either delinquent or non-delinquent.

Key input features considered for prediction include Age, Income, Credit Score, Credit Utilization, Missed Payments, Loan Balance, Debt-to-Income Ratio, Employment Status, Account Tenure, and Payment History.

The proposed workflow begins with data ingestion and preprocessing. Numerical variables are handled using appropriate imputation methods, while categorical variables are transformed using encoding techniques.

Feature engineering is applied to derive meaningful predictors such as total missed payments over time and ratios of late payments to total payments.

Feature scaling is performed to ensure that numerical variables operate on a comparable range for model learning.

The dataset is divided into training and testing subsets using stratified sampling to preserve class distribution.

Logistic Regression is selected as the primary modeling technique due to its strong suitability for binary outcomes such as delinquency prediction.

This model is preferred because it provides interpretable coefficients that clearly indicate how each feature influences the final risk prediction.

Compared to more complex models such as decision trees or neural networks, Logistic Regression offers a balance between performance, transparency, and regulatory compliance.

The trained model produces a probability score for each customer representing the likelihood of delinquency.

Customers whose predicted probability exceeds a defined threshold are classified as high-risk and flagged for early intervention.

This enables Geldium to take proactive actions such as customer outreach, policy adjustments, or risk-based decision making.

Model performance is evaluated using standard classification metrics including Precision, Recall, F1 Score, and AUC-ROC.

Precision ensures that predicted delinquent accounts are truly risky, while Recall ensures that high-risk customers are not missed.

The F1 Score balances Precision and Recall, and AUC-ROC measures the model’s ability to distinguish between delinquent and non-delinquent accounts.

In addition to performance metrics, fairness and bias checks are incorporated into the evaluation strategy.

Error rates and prediction outcomes are compared across different customer subgroups to detect potential bias.

Bias mitigation strategies such as data balancing, threshold tuning, and fairness-aware training are considered to improve equity.

Ethical principles are integrated into the model design, including transparency of predictions and protection of customer data privacy.

Human review is recommended for critical decisions to prevent over-reliance on automated outcomes.

Continuous monitoring is planned to track model performance and retrain the model as new data becomes available.

This predictive modeling plan supports Geldium in building reliable, explainable, and responsible credit risk prediction systems.

The approach demonstrates how GenAI can assist in structuring, justifying, and evaluating predictive models for real-world financial applications.
