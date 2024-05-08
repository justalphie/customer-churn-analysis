## Description

<img align="right" height="200" src="https://loanscanada.ca/wp-content/uploads/2016/05/credit_card_churning-1.png" />

Credit institutions are one of the most important establishments of the modern economy. Credit cards are a highly profitable product of these institutions. 

In some situations, however, certain groups of clients tend to close their accounts and discontinue the credit cards. 

This project is aimed at the prediction of those clients with more propensity to close their bank account with the financial institution using the available data and machine learning tools.
Another goal is finding possible groups of clients and define their characteristics to help the marketing team to design custom-made campaigns to increase customer retention.

## Project files

The project contains the following files:
```eda.ipynb``` The file includes basic information about the dataset obtained by using  ```pandas``` library.
```preprocessing.ipynb``` The file contains the preprocessing steps before the model training.
```models.ipynb``` The file contains the training of the models.
```visuals.ipynb``` The file contains visualizations of the dataset and the predictions. 

## Installation

To use the files of the project, please install the libraries from the ```requirements.txt``` file.

## Usage

To get the perdictions of the model, pass the dataframe of the corresponding format to ```rf_classifier.predict()```. 

##   Data sources

The source of the dataset is Kaggle.com.
The dataset can be downloaded on the following link:
[Credit Card Customers](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

In this dataset there are several features that are used as parameters to make predictions, including:

`CLIENTNUM`: customer account number.
`Attrition_Flag`: customer status (Existing and Attrited).
`Customer_Age`: age of the customer.
`Gender`: gender of customer (M for male and F for female).
`Dependent_count`: number of dependents of customers.
`Education_Level`: customer education level (Uneducated, High School, Graduate, College, Post-Graduate, Doctorate, and Unknown).
`Marital_Status`: customer's marital status (Single, Married, Divorced, and Unknown).
`Income_Category`: customer income interval category (Less than $40K, $40K-$60k, $60K-$80K, $80K-$120K, $120K +, and Unknown).
`Card_Category`: type of card used (Blue, Silver, Gold, and Platinum).
`Months_on_Book`: period of being a customer (in months).
`Total_Relationship_Count`: the number of products used by customers in the bank.
`Months_Inactive_12_mon`: period of inactivity for the last 12 months.
`Contacts_Count_12_mon`: the number of interactions between the bank and the customer in the last 12 months.
`Credit_Limit`: credit card transaction nominal limit in one period.
`Total_Revolving_Bal`: total funds used in one period.
`Avg_Open_To_Buy`: the difference between the credit limit set for the cardholder's account and the current balance.
`Total_Amt_Chng_Q4_Q1`: increase in customer transaction nominal between quarter 4 and quarter 1.
`Total_Trans_Amt`: total nominal transaction in the last 12 months.
`Total_Trans_Ct`: the number of transactions in the last 12 months.
`Total_Ct_Chng_Q4_Q1`: the number of customer transactions increased between quarter 4 and quarter 1.
`Avg_Utilization_Ratio`: percentage of credit card usage.

##  Visuals
The visualizations can be found in the ```visuals.ipynb``` file. It should be read the last, as it contains data from the original dataset and the predictions, and the main goal is to study the trends and to compare them with the models predictions.

##  Contributors
The project was developed by [Alfiya Khabibullina](https://github.com/justalphie) under the supervision of the coach [Vanessa Rivera-Quinones](https://github.com/vriveraq)


##  Timeline
The project was carried out in 5 days.
- Day 1-2: studying the classification, preprocessing of the data.
- Day 3: visualization.
- Day 4: Training and evaluation of the models.
- Day 5: Finalizing the project, commenting and formatting.

##  Personal situation
The project was carried out within the framework of Data&AI training by [BeCode](https://becode.org/)