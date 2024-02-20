# Bank Churn  
This project dives into a dataset that relates to customers in a bank. This dataset attempts to capture the relationship between a customer and the bank and provides us with a target variable that states whether the customer is still an active member of the bank or if the customer left the bank. I have analysed the variables that describe the customers relationship with the bank in great detail in the analysis.ipynb file that can be found in the above code folder. In this analysis, each variables importance with respect to each other and the its significance to the target variable is explored and analysed. Based on the analysis an interesting pattern was noticed in the dataset. It was seen in the data that any customer that had raised a complaint had ended up leaving the bank. Since I had no way of verifying whether this was a sampling error of some sort, we have removed the variable as a factor in the final model as including it lead to bias in the model.  

# The Model
Due to the complex relationship among variables, the XGBClassifier was used along with the Bayes Search Hyperparameter tuning method.
