# **Churn / Repeat Purchase Prediction**



## Problem



Predict whether a customer will make a repeat purchase after their first order.

Understanding repeat behavior is critical for:

&#x09;improving customer retention

&#x09;reducing acquisition costs

&#x09;identifying high-value users early



## Approach



Defined target variable:

&#x09;repeat\_purchase = 1 if user has ≥2 completed orders

Built user-level dataset using:

&#x09;first purchase data

&#x09;user attributes

&#x09;behavioral signals from event logs

Avoided data leakage by using only features available after the first purchase

Trained models:

&#x09;Logistic Regression (baseline)

&#x09;Random Forest (non-linear model)



## Key Insights



Behavioral features (e.g., add-to-cart activity) are more predictive than static user attributes

Users with higher first purchase revenue are more likely to return

Acquisition channel influences repeat behavior, suggesting differences in user intent

Browsing activity alone (views) is less predictive than active engagement (add-to-cart)



## Results



Baseline accuracy: \~55%

Logistic Regression: \~55% (no improvement over baseline with weak features)

Random Forest: \~58% after adding behavioral features

Feature engineering significantly improved performance, while model choice had a smaller impact.



## Business Impact



Enables early identification of high-retention customers

Supports targeted marketing campaigns (e.g., email, promotions)

Helps prioritize users with higher likelihood of repeat purchase

Suggests focusing on improving engagement actions (add-to-cart) to drive retention



## Tech Stack



Python

Pandas (data manipulation)

DuckDB (SQL queries)

Scikit-learn (modeling)

Matplotlib (visualization)

