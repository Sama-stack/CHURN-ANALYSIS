# CHURN-ANALYSIS
SYRIATEL CUSTOMER CHURN ANALYSIS
This project aims to predict customer churn for SyriaTel using machine learning models, particularly focusing on Random Forest Classifier. The model helps identify key factors contributing to churn and provides actionable insights for customer retention.
# Dataset Overview
The dataset contains customer information with features such as:

Service usage (number of calls, minutes used, etc.)

Customer service interactions

International plan activation

Churn status (Target Variable)

# Project Goals
 Identifying key factors leading to customer churn
 
 Build a predictive model to classify customers as churners or non-churners
 
 Optimize model performance through hyperparameter tuning
 
 Provide business recommendations to reduce churn


Customers with higher customer service calls are more likely to churn
![image](https://github.com/user-attachments/assets/b4db4a5a-14d1-4d93-8cb7-43623fe7e9e9)

Having an international plan increases the risk of churn
![image](https://github.com/user-attachments/assets/fba09c0c-b421-492b-83fb-1aeb25e6dc29)

# Model Building & Evaluation
The main steps included:
 Feature Encoding & Scaling
 
 Splitting data into training & testing sets
 
 Training the baseline Random Forest model
 
 Hyperparameter tuning using GridSearchCV
 
 Evaluating model performance using accuracy, precision, recall, and F1-score

 The best-performing model was a Random Forest Classifier with:
 ![image](https://github.com/user-attachments/assets/89c0a5b6-c38f-453f-995b-0ac906f2b9dc)

 Accuracy: 96.4%
 Recall: 76.24%
 Precision: 86.52%
 Best Parameters: {n_estimators: 200, max_depth: None, min_samples_split: 2, min_samples_leaf: 1}

 # Conclusion & Recommendations
To reduce customer churn, SyriaTel should:

Improve customer service quality

Offer discounts or incentives for customers with international plans

Identify and engage high-risk customers early

