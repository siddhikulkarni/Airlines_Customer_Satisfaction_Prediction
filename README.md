# Airlines_Customer_Satisfaction_Prediction
The original dataset contains about 130,000 survey entries from passenger/flight details from a US airline. 
In total, there are 22 feature columns and 1 binary target column. 
Feature Engineering performed : 
Log transform
Use logarithmic to create a new feature “Delay in Minutes logged”
Features selection
Drop “Departure Delay” and “Arrival Delay”
Encoding the categorical features
Standardize all features
Model Accuracy and Performance 
The confusion matrix resulted in an accuracy of 95.6% 
The sensitivity value is better at 96.2% compared to the specificity value of 95.43% — which means that the true positive rate is better than the true negative rate. This means that the model can predict when a customer is satisfied slightly better than when they aren’t.
