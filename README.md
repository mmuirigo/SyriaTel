**SyriaTel Customer Churn Prediction and Retention Strategies**

**Problem:**

SyriaTel, like most telecom companies, faces challenges with customer retention. A high churn rate can have significant financial implications.

**Objective:**

The goal of this analysis is to understand customer churn and develop strategies to reduce it, enhancing customer retention and minimizing revenue loss.

**How did we handle the problem?**

Data Preparation and Exploration:
Action:Gathered and cleaned customer data, handling missing values, outliers, and encoding categorical variables.

<img width="250" alt="data used" src="https://github.com/user-attachments/assets/1db3eda2-a598-4c2d-8c0f-5d78d2110fb3" />

Model Development and Evaluation:
Action:Tested various machine learning models (e.g., Random Forest, XGBoost) and optimized them using hyperparameter tuning and SMOTE for class imbalance.

Recommendations and Solutions:
Action:Based on model insights, recommended targeted actions to reduce churn.
Outcome:Provided actionable steps to enhance customer retention and minimize churn-related revenue loss.

**Key Features Affecting Churn:**

<img width="619" alt="Feature Importance" src="https://github.com/user-attachments/assets/865ba7fa-3382-4f3c-b756-f8c28b3cdd08" />


**Best Performing Models Confusion Matrix and AUC Evaluation:**

<img width="342" alt="Tuned Random Forest" src="https://github.com/user-attachments/assets/d3b252e3-67e6-4f79-8fb3-867d182f3b3c" />
<img width="305" alt="Tuned XGBoost" src="https://github.com/user-attachments/assets/69c41c2c-ec63-4e7a-ab2e-3e4902bfc162" />
<img width="438" alt="AUC Tuned Random Forest" src="https://github.com/user-attachments/assets/4ad97310-8e32-4b81-a1b8-c1140a17b544" />


**Recommendations:**

Improve Customer Retention Programs:

Proactive Customer Support:

Product Improvement:Customers with specific service plans

Optimize Pricing Models:


**Next Steps:**

Model Deployment

Customer Segmentation

Monitor and Adjust:Monitor churn rates regularly and update models 

**Key Analysis Challenges:**

Imbalanced Dataset:There was a significant data imbalance between churn and non-churn customers. Churn accounted for 14%, while non-churn made up 86%.

Precision-Recall Tradeoff:
