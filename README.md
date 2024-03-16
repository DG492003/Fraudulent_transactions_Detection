# Fraudulent_transactions_Detection
This case requires to develop a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan

# 1 . **Data cleaning including missing values, outliers and multi-collinearity.**  
- There is no null values in any columns  
- Most of the datapoints are not correlated  
- Oldbalance is correlated with newbalance of person who intitiated transaction  
- newbalanceDest and oldbalanceDest is also correlated.  

# 2. **Describe your fraud detection model in elaboration.**  
Fraud Detection Model contains following steps:    
   - Loading of dataset and Explore it    
   - Checking the Distribution of transaction datatype    
   - Checking for the need of data cleaning    
   - statistical Analysis of Data
   - Deal with the skewed data with boxcox tranformation and log transformation    
   - Taking features to train the data    
   - Train test split with 80-20 rule
   - use Sampling to balance the dataset.  
   - Fit the model to RandomForestClassifier and Logistic Regression    
   - Analyse the results

# 3. **What are the key factors that predict fraudulent customer?**
'isFraud', 'oldbalanceOrg', 'type_CASH_OUT', 'type_TRANSFER' are fraud causing/predicting features.
