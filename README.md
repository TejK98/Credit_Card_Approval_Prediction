# Credit_Card_Approval_Prediction
Credit gives one access to spend with "future" money. Credit risk is loss by borrower failing to make full and timely payments. Responsible users can benefit from cash backs, reward points, purchase safety, travel convenience and others. People tend to apply for credit cards to build their credit, and in turn take out a loan with a competitive interest rate. Overall, this project of Credit approval analysis helps us in determining these various factors which contribute to approval from the lenders.

# Dataset
There are 2 files:
1. application_record.csv
2. cred_record.csv

# Data Description
We perform our prediction models on two datasets that are connected by "customer ID". Application record dataset contains customer's personal and financial information which we would use as independent variables for prediction. And Credit card record dataset consists of customer's status of previous credit history. 

• Dataset Characteristics: Univariate
• Attribute characteristics: Categorical, Integer, Real
• Associated Tasks: Logistic Regression, KNN, Random Forest
• Records – 438558 instances; 1million instances
• Columns – 18 variables; 3 variables

# Project Flow
1. Import the data
2. Data Cleaning
3. Feature Engineering
4. Upsmapling to handle imbalanced dataset
5. Hyperparameter Tuning using GridSearchCV
6. Predictive Modelling: Logistic Regression, K Nearest Neighbors, and Random Forest
