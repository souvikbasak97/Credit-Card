# Credit-Card
Detect credit card fraudulent transactions


This project samples a credit card dataset from Kaggle(https://www.kaggle.com/mlg-ulb/creditcardfraud/download).
In this project the credit card dataset was imported and preprocessed.The data was explored and described in the form of histograms
to check if there was any anomaly in the data.The data was grouped into 2 main categories: Fradulent and Valid and Outlier Fraction was determined which was less than 1%.Correlation Matrix was represented in the form of heatmap using Python's seaborn library function.Our target parameter was Class.We used two different methods to do anomaly detection on this dataset which are Isolation Forest and Local Outlier Factor.

By using Local Outlier Factor we have an overall accuracy of 99.69 percentage.However the accuracy of False Positives and False 
Negatives using Local Outlier Fraction is around 1% which is very low.
By using Isolation Forest we have an overall accuracy of 99.77%. However the accuracy of False Positives and Negatives is 
around 26% which is better than Outlier Fraction Method.
The accuracy percentage can be improved by using a larger fraction of dataset or the whole dataset however due to computational
requirements the dataframe has been scaled down.
