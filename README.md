## Data-Mining---Credit-Card-Fraud-Detection
### Project Description
In this project, we are going to classify credit card fraud transactions by using multiple classifiers and ensemble learning. Besides, considering the transaction amount and model complexity, cost-sensitive learning will also be performed. 
### Data
The dataset contains transactions made by credit cards in September 2013 by European cardholders, where we have **492 frauds out of 284,807 transactions. The dataset is highly unbalanced, in which the proportion of the fraud transactions is only 0.172%.**
**It contains 30 independent variables including 2 numerical features, ‘Time’ and ‘Amount’, and 28 principal components obtained with PCA.** Feature 'Time' is a timestamp, which means the seconds elapsed between each transaction and the first transaction in the dataset, and it is not included in our analysis. The feature 'Amount' is the transaction Amount, and this feature can be used for example-dependent cost-sensitive learning. **Feature class is the response variable and it takes value 1 for fraud transactions and 0 for normal ones. Finally, 29 independent variables and one dependent variable are included in our research.**

Link: https://www.kaggle.com/mlg-ulb/creditcardfraud
### Implementation Choice
Python Jupyter Notebook
