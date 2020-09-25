# Anomaly-Detection-Models


Credit Card Anomaly Detection Models¶
Brainstation Data Science Capstone | 2019 | Manny Brar
Objective=
The importance of effective and quick detection of fraud events is becoming more and more essential everyday with the rise in fraud activity over the years. For my project I have decided to explore and evaluate a few different machine learning classification models to see which model will have the highest accuracy to detect anomaly transactions. I will utilize both supervised and unsupervised methods and compare overall performance metrics to determine the best option.

Data=
This dataset was downloaded from Kaggle, and consists of european credit card data from September 2013, that occured over a span of 2 days. This dataset contains over 250,000 transactions and contains only numerical values and 31 columns. Among these columns we have columns v1-v28 containing private and sensitive data that has been pre-processed with PCA transformations. Due to confidentiality reasons this data has been transformed into numerical values. We also have a 'Time' column and this data represents the time in seconds from the first transaction to the current. The 'Amount' column provides a monetary value for each transaction and finally we have a 'Class' column which is a binary column with a value of 0 representing a legitimate transaction and a value of 1 to represent a anomaly or 'fraud' event.

Source= (https://www.kaggle.com/mlg-ulb/creditcardfraud)
