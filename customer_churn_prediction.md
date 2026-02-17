# Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn in a telecom dataset using supervised machine learning techniques. The objective is to help businesses identify customers who are likely to discontinue services, enabling proactive retention strategies.

##  Problem Statement

Build a classification model that predicts whether a customer will churn based on factors such as tenure, services opted, payment method, contract type, monthly charges, and customer demographics.

##  Methods Used

- Data Cleaning and Preprocessing
  - Handling missing values in `TotalCharges`
  - Removing irrelevant columns like `customerID`
- Encoding Categorical Variables using LabelEncoder
- Feature Scaling using StandardScaler
- Train-Test Split
- Model Building:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- Model Evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix

##  Libraries & Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

##  Results & Insights

- Random Forest outperformed other models in terms of accuracy and generalization.
- Key drivers of churn: Contract type, Tenure, Monthly charges, and Payment method.
- Recommendation: Prioritize customer engagement for users with month-to-month contracts and high monthly charges.

##  Files Included

- `customer_churn_prediction.ipynb`: Jupyter Notebook with the complete end-to-end implementation
- `README.md`: Project documentation

---

> This project was done for educational and demonstrative purposes.
