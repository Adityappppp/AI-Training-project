Project: Customer Churn Prediction using Machine Learning
Dataset: Telco Customer Churn Dataset
This project focuses on predicting whether a telecom customer will leave the company (Churn) or stay, using various supervised machine learning classification algorithms.

Customer churn prediction helps telecom companies reduce revenue loss by identifying customers who are likely to leave.
The dataset used is the Telco Customer Churn Dataset, which contains customer details such as:

Gender

SeniorCitizen

Tenure

MonthlyCharges

TotalCharges

Contract Type

Payment Method

Internet Service

Churn (Target Variable)

Target Variable:

Churn = Yes/No

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔄 Project Workflow
1️⃣ Data Understanding

Checked shape, info, and statistical summary

Identified missing values

Analyzed churn distribution

2️⃣ Data Preprocessing

Removed unnecessary column (CustomerID)

Converted TotalCharges to numeric

Filled missing values using median

Encoded categorical variables using LabelEncoder

Split dataset into training (80%) and testing (20%)

3️⃣ Model Building

The following classification algorithms were applied:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

Gradient Boosting

4️⃣ Model Evaluation

Models were evaluated using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)
