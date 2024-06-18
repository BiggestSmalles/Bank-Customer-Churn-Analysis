# Bank-Customer-Churn-Analysis
#Introduction
The dataset I worked on is from Kaggle titled “Credit Card Customers”. This dataset is made of 23 columns and 10,127 rows with 0 missing values. It consists of data related to bank customers, focusing on the churning aspect where customers leave or stop using the bank's service. It has various pieces of information about customers from demographic details such as age, gender, education level, income category, and dependent count, to bank account characteristics and transaction behaviors such as card category, months on book, credit limit, total revolving balance, total transaction amount, and total transaction count. All of these columns and its values in each row are possible indicators of future customer churnings, so the driving question behind our analysis is, what factors influence a bank customer’s likelihood of churning?
#Dataset Cleaning
To prepare the dataset for analysis, I did the following:
Loaded the dataset using pandas
Handled Missing Value: Filled or dropped missing values as appropriate. For instance, filling missing numerical values with the mean or median and categorical values with the mode.
Dropped columns that are not necessary for the analysis, such as identifiers or highly redundant information.
Created new columns that might be useful for analysis. For example, generating age groups from continuous age data or categorizing income levels.
We standardized or normalized values where it was necessary. This could include numerical data or converting categorical data to a consistent format. 
