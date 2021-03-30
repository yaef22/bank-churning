# bank-churning
Goal: To improve on the recall score when predicting customer who most probably going to churn their credit card services.

Description:-
A manager at the bank is disturbed with more and more customers leaving their credit card services. 
They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide 
them better services and turn customers' decisions in the opposite direction

I got this dataset from a website with the URL as https://www.kaggle.com/sakshigoyal7/credit-card-customers. 
I have been using this for a while to get datasets and accordingly work on them to produce fruitful results. 
The site explains how to solve a particular business problem.

Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

We have only 16.07% of customers who have churned. Thus, it's a bit difficult to train our model to predict churning customers.

Results: I able to get 99% AUC, 91% recall, and 96% accuracy using XGBoost and resampling the dataset using SMOTE.
