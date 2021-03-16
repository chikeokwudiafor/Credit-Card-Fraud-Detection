# Credit-Card-Fraud-Detection Project 
Credit Card Fraud Detection Project for my Artificial Intelligence class at Duquesne University by Chike Okwudiafor, Eric Ato Brown, and Obehi Irekponor

## INTRODUCTION
Credit card fraud happens when a non- owner of a card uses a third parties’ card to transact business without
the knowledge of the person. In many cases, a fraudster can obtain your financial information and use it to
make fraudulent purchases. In view of some of the ways through which credit card fraud occurs, this project is aimed at using the
available machine learning algorithms and techniques to aid financial institutions and clients detect fraudulent
credit card transactions. We hope that, we will be able to establish insights to help both parties to identify
fraudulent transactions thereby saving them from loss of money.

The machine learning algorithms we used are Logistic Regression, Artificial Neural Network, Random
Forest and K-Means Clustering in predicting genuine and fraudulent credit card transactions. In all, we seek
to understand how the various chosen algorithms will be meaningful in establishing weather there is a
higher magnitude of credit card fraud or no fraud. We will use the selected Machine learning Algorithms
to analyze and predict large data looking for patterns and anomaly.

## DESCRIBING THE DATA SET
A dataset of 284,807 sample size of credit card transaction in September 2013 by European cardholders
was used for the analysis. This transaction was carried out in two days and it contains 492 fraud and its
variable include, numerical input variables which are the result of a PCA transformation. Unfortunately,
due to confidentiality issues, we cannot provide the original features and more background information
about the data. The fraudulent transaction makes up only 0.1727% of all the transactions making the dataset
highly unbalanced. This dataset and information was gotten from: (https://www.kaggle.com/mlgulb/creditcardfraud)
## FEATURES
* V1, V2, … V28: are the principal components obtained with PCA, the only features which have not been
transformed with PCA are 'Time' and 'Amount'.
Time: contains the seconds elapsed between each transaction and the first transaction in the dataset.
* Amount: is the transaction amount
* Class: is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Principal Component Analysis:
  PCA transformation has previously been carried out on Features V1, V2,
… V28 in other to manage confidentiality. Through this, we cannot provide the original features and more
background information about the data.

### Standard Scaling/Normalization:
Variables that are measured at different scales do not contribute equally
to the analysis and might end up creating a bias, a normalization was carried out in other to fit all the features
in a particular range as it helps in speeding up the calculations in the algorithms.

### Data Cleaning: 
Fortunately, the dataset had no null values making it unnecessary for data manipulation.
Correlation: Correlation was carried out to check close similarities within the features and to re-confirm
the PCA transformation.

### Training and Testing: 
For the supervised learning algorithms carried out, the data was spilt into test and
training data where the testing data was 30% of the dataset. we decided to split the testing data to 30% in
other to involve or randomly capture as many fraudulent transactions as possible since it represents
0.1727% of the entire dataset.
