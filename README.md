# Bank Marketing using different machine learning models
Using Machine Learning to Predict Subscription to Bank Term Deposits for Clients

 In this project on bank marketing with machine learning, it shows how a particular Portuguese bank can use predictive analytics from data science to help prioritize customers which would subscribe to a bank deposit. The data set is based off the direct marketing campaigns of a Portuguese banking institution. These marketing campaigns were based on phone calls. More than one contact to a client was required, in order to know if the product (bank term deposit) was subscribed by a client or not. The classification goal is to predict if a client will subscribe to the bank term deposit (yes/no).

 Dataset:
 Bank dataset

 Dataset Source:
 https://www.kaggle.com/datasets/sahistapatel96/bankadditionalfullcsv

Features:
Input variables:

1 - age (numeric)

2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

5 - default: has credit in default? (categorical: 'no','yes','unknown')

6 - housing: has housing loan? (categorical: 'no','yes','unknown')

7 - loan: has personal loan? (categorical: 'no','yes','unknown')
Related with the last contact of the current campaign:

8 - contact: contact communication type (categorical: 'cellular','telephone')

9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
Other attributes:

12 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

14 - previous: number of contacts performed before this campaign and for this client (numeric)

15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
Social and economic context attributes:

16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)

17 - cons.price.idx: consumer price index - monthly indicator (numeric)

18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)

19 - euribor3m: euribor 3 month rate - daily indicator (numeric)

20 - nr.employed: number of employees - quarterly indicator (numeric)

Output variable (desired target):

21 - y - has the client subscribed a term deposit? (binary: 'yes','no')

The classification goal is to predict if a client will subscribe to the bank term deposit (yes/no).

ML MODEL
Algorithm used :

              -K-nearest neighbors
              
              -Logistic regression
              
              -Stochastic gradient descent
              
              -Naive Bayes
              
              -Decision tree
              
              -Random forest
              
              -Gradient boosting classifier

  EVALUATION METRICS

        AUC
        accuracy
        recall
        precision
        specificity
        prevalence
        f1

  RESULTS

  ![image](https://github.com/user-attachments/assets/07459e0d-6b5c-4ef0-9ff6-e8f594af9b92)
  ![image](https://github.com/user-attachments/assets/fcf3e95d-68ae-4f4b-b2d1-056c154e4f63)

  CONCLUSION

  Through this project, we identified the best machine learning model that is able to predict how likely clients will subscribe to a bank term deposit.The best model was gradient boosting classifier. The model's performance is 75.2%.

  Future scope
  Incorporation of Hypertuning of algorithm parameters and feature selection processes on the above algorithms to observe and analyse model performance efficiency.


 
ML
