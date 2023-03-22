# bank-customer-churn

This is a project to analyse the factors affecting customer churn for a bank. The data used was obtained online and is for a bank's customer life-cycle. Based on the analysis done on this historical data, a classification model was created to predict the customer churn.

The data used can be found attached in this repository.

This [file](https://github.com/aniket0599/bank-customer-churn/blob/main/Bank%20Customer%20Churn%20-%20EDA.ipynb) contains the Exploratory data analysis and insights obtained. A few of these insights are here and a detailed look can be found by clicking on the link

![image](https://user-images.githubusercontent.com/56698924/226929319-4292001c-c264-47b9-85ca-80ceae1e86f4.png)

![image](https://user-images.githubusercontent.com/56698924/226929969-e4e58f12-6665-46b1-b40f-07779d981ce6.png)
![image](https://user-images.githubusercontent.com/56698924/226930025-c1b89bff-4f51-4cd4-bcf8-3a9abc89494b.png)

Tenure of a customer is duration of time for which they stay with the bank. This is related with the age of the customer. A customer of Age 28 years will have lower tenure than a customer of Age 38 years if both opened their account at the same age. Therefore, lower tenure does not necessarily mean less loyal customer. TenureByAge is better feature in this regard and gives good insights.

Customers with low TenureByAge are more likely to churn. This seems to be feasible and in sync with our general understanding of disloyalty and customer behaviour.

Similarly, CreditScoreByAge is a better feature than CreditScore alone. Credit Score is describes the credit merit of an individual who has taken a loan. Credit scores help to depict the credit and repayment history, utilization of credit, tenures of previous debts, and so on. Age plays an important factor here. I will link articles in the project to help you better understand this. For now, this feature is definetely more promising than CreditScore. https://www.bankbazaar.com/cic/how-credit-score-is-calculated.html

Customers with lower CreditScoreByAge are more likely to churn than those with higher CreditScoreByAge.
