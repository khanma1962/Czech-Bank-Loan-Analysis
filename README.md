# Czech-Bank-Loan-Analysis

### 

https://webpages.uncc.edu/mirsad/itcs6265/group1/index.html

Project Goal
The Berka dataset, from the 1999 PKDD Discovery Challenge, provides information on the clients, accounts, and transactions of a Czech bank. The original task description of the Discovery Challenge states:

The bank wants to improve their services. For instance, the bank managers have only vague idea, who is a good client (whom to offer some additional services) and who is a bad client (whom to watch carefully to minimize the bank loses). Fortunately, the bank stores data about their clients, the accounts (transactions within several months), the loans already granted, the credit cards issued The bank managers hope to improve their understanding of customers and seek specific actions to improve services. A mere application of a discovery tool will not be convincing for them.
In keeping with the original task description, our project goal is to mine and analyze this bank data in order to extrapolate from it the type of customer who makes a good candidate for a credit card.

### Business Objectives:

(1)	In data-driven world, what is the definition of a good loan? What features effects bad loans?

(2)	Which loan accounts are likely to default and why?

(3)	Using Machine Learning techniques, analyze the credit worthiness (credit scoring model) of bank’s customer based on income, expenses, balance, demographical location, transaction, credit cards, etc.

(4)	Find out ‘Customer lifetime value’ based on their transactions by data-driven approach.

(5)	Based on their transaction history, credit card info, geographical location, recommend a marketable bank’s product.

(6)	What are the characteristics of a good bank branch?


Models
Acc (Train) 
Acc (Test)
F1 Score (Test)
AUC (Test)
Comment
Logistic Regression
0.90
0.90
0.95
0.45

Random Forest
0.90
0.91
0.95
0.72
Best Model
Logistic Regression
With SMOTE
0.99
0.99
0.74
0.58

Random Forest
With SMOTE
0.90
0.91
0.93
0.67

Decision Tree
0.90
0.91
.095
0.63

![image](https://user-images.githubusercontent.com/66092829/114090566-71ea4300-986c-11eb-808e-883b6ba3f7e1.png)


