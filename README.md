Customer Churn Prediction

This project predicts customer churn for a telecom company using machine learning models. It involves data preprocessing, exploratory data analysis, and model training with hyperparameter tuning.

Key aspects:

1.Dataset Insights:

Identified a significant class imbalance in the target variable (Churn), with more customers opting to stay than churn.

2.Data Preprocessing:

Removed irrelevant features like customerID to focus on meaningful data.
Applied SMOTE to address class imbalance, improving model performance.
Label Encoded categorical variables for seamless integration with machine learning models.

3.Exploratory Data Analysis:

Found high correlation between tenure and TotalCharges, indicating that longer tenure leads to higher charges.
Monthly charges showed a near-uniform distribution, while tenure revealed customer retention trends.
Customers with month-to-month contracts and electronic payment methods showed higher churn rates.

4.Machine Learning Models:

Random Forest outperformed Decision Tree and XGBoost with the highest accuracy during cross-validation and hyperparameter tuning.
Models were optimized for better predictions using a robust parameter grid.

5.Performance Metrics:

Random Forest achieved best-in-class accuracy on test data.
Detailed classification reports highlighted precision and recall improvements, especially for the minority churn class.

6.Actionable Insights:

Customers with short tenures, high monthly charges, and month-to-month contracts are more likely to churn.
Recommendations include offering long-term contracts or discounts for customers with these profiles.

7.Predictive System:

Deployed a predictive system that provides churn probabilities for individual customers.
Results help businesses make informed decisions to enhance customer retention.
