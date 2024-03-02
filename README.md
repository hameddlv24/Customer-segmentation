# :dart: Customer segmentation by clustering algorithms
![Alt text](Customers.JPG)


### :scroll: overview
---
About 9000 customer usage behavior from their credit card, gathered in a dataset which i want to do a clustering for them.

There are 18 features for every sample and what i want to do is using these informations and labeling customers for a marketing strategy purposes.

In the notebook file, after preprocessing and EDA part i tried 8 different clustering algorithms such as : K-Means - Affinity propagation - Mean-shift - DBSCAN - Gaussian mixtures - BIRCH - MiniBatchKMeans - Hierarchical clustering.

At last i compared best models, their metrics and scores, and customer labels.


### :pencil: Dataset Description
---
This case requires to develop a customer segmentation to define marketing strategy. 
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. 
The file is at a customer level with 18 behavioral variables.
Following is the Data Dictionary for Credit Card dataset :

| columns | Description |
| ------ | ----------- |
| CUST_ID | Identification of Credit Card holder (Categorical) |
| BALANCE | Balance amount left in their account to make purchases |
| BALANCE_FREQUENCY | How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated) |
| PURCHASES | Amount of purchases made from account |
| ONEOFF_PURCHASES | Maximum purchase amount done in one-go |
| INSTALLMENTS_PURCHASES | Amount of purchase done in installment |
| CASH_ADVANCE | Cash in advance given by the user |
| PURCHASES_FREQUENCY | How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased) |
| ONEOFFPURCHASESFREQUENCY | How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased) |
| PURCHASESINSTALLMENTSFREQUENCY | How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done) |
| CASHADVANCEFREQUENCY | How frequently the cash in advance being paid |
| CASHADVANCETRX | Number of Transactions made with "Cash in Advanced" |
| PURCHASES_TRX | Numbe of purchase transactions made |
| CREDIT_LIMIT | Limit of Credit Card for user |
| PAYMENTS | Amount of Payment done by user |
| MINIMUM_PAYMENTS | Minimum amount of payments made by user |
| PRCFULLPAYMENT | Percent of full payment paid by user |
| TENURE | Tenure of credit card service for user |


### :open_file_folder: File Descriptions
---
+ notebook / clustering project : ipynb file which includes all codes and clustering algorithms.
+ dataset / Customer_Data : csv file which is the dataset i worked on it for clustering the customers.


### :paperclip: Additional Links
---
+ Kaggle : You can follow me on kaggle to check my works and outputs in easier way. [My kaggle profile](https://www.kaggle.com/hameddelavar)
+ Linkedin : Also you can contact me on linkedin by [My linkedin profile](https://www.linkedin.com/in/hamed-delavar-b030172a4)
