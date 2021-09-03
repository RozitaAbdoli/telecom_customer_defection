# Customer Loss Prediction for a Telecommunications Company Using Machine Learning
It costs more for businesses such as telecommunication companies to acquire new customers compared to retaining existing ones. This impacts the operating costs within the company. The aim of this report is to take a sample set of customer churn data and produce an optimal model for predicting whether or not a customer will leave the company. The chosen dataset has 3333 rows and 21 features, one of which is the class attribute “Churn”. Python’s Scikit-learn library was used to produce a Multinomial Naive Bayes classifier and a Decision Tree classifier. 
## Exploratory Data Analysis

![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/dd4621b7ef4dbc2d2a26430c9c61a40f76427b09/img/heatMap.png)
---
![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/abdae7ac0fdaed85cd128e1ad4268da04dc73748/img/min_charge_corr.png)
---
![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/a91e3e074de455cadd3d5f7f6d96006e58013ede/img/Phi_correlation.png)
---
![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/75756c250bfa6cd8ff4e91086a4c139c5e3b39da/img/box_plots.png)
---
![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/0e3f15958e2cee8e7f03de3772e1bcb128ab749a/img/histograms.png)
---
![alt text](https://github.com/RozitaAbdoli/telecom_customer_defection/blob/56210097d1f20ee09cb6597188f29fa252e116b5/img/top_4_features.png)

Based on Figure 6, it is observed that:
* Customers who used 260 minutes or more during daytime were more likely to churn. Conversely, the number of customers that churned is considerably lower for those with 160 to 200 day minutes.
* Customers were more likely to churn if they made 4 or more calls to the customer service.
* Customers that had an international plan were more likely to churn.
* Customers that did not have a voicemail plan were more likely to churn.
---

