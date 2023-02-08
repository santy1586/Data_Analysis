# Telecom_Churn_Analysis
# Introduction
Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation. The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription.
Explore and analyze the data to discover key factors responsible for customer churn and come up with ways/recommendations to ensure customer retention.
# Business Understanding Of A Telecom Industry Customer Churn
In recent years, customer churn prediction has become a hot research topic. Churners are people who leave a company's service for various reasons.
Companies must be able to accurately predict customer behaviour in order to reduce customer churn. Customer churn has emerged as a major issue in all industries. According to studies, acquiring a new customer is more expensive than retaining an existing one.
In order to retain existing customers, service providers need to know the reasons of churn, which can be realised through the knowledge extracted from the data.
we will perform EDA(Exploratory Data Analysis) n order to get actionable insights and convert them into meaningful stories and present it so that the company will take necessary actions to prevent further churning.
# Business Objective
As per the Organization requirements, We need to Explore and Analyze the data by performing Exploratory Data Analysis. And to find out what are the key factors responsible for customer churn. And how we can prevent from further retention.
* Overall Maximizing the company's profit by retaining customer.
* Overall minimizing the customers by identifying the key cause of the problem.
# Data Summary
There are 3333 rows and 20 columns in above dataset.Only one column is in boolean format.8 Variables is of Float Data type.8 Variables is of Interger data Type.3 Variables are in Object format i.e there are categorical values.So far the dataset which was provided by the Organization have CLEAN features without having any MISSING or NULL values.
* STATE: 51 Unique States name
* Account Length: Length of The Account
* International Plan: Yes Indicate International Plan is Present and No Indicates no subscription for Internatinal Plan
* Voice Mail Plan: Yes Indicates Voice Mail Plan is Present and No Indicates no subscription for Voice Mail Plan
* Number vmail messages: Number of Voice Mail Messages ranging from 0 to 50
* Total day minutes: Total Number of Minutes Spent in Morning
* Total day calls: Total Number of Calls made in Morning.
* Total day charge: Total Charge to the Customers in Morning.
* Total eve minutes: Total Number of Minutes Spent in Evening
* Total eve calls: Total Number of Calls made r in Evening.
* Total eve charge: Total Charge to the Customers in Morning.
* Total night minutes: Total Number of Minutes Spent in the Night.
* Total night calls: Total Number of Calls made in Night.
* Total night charge: Total Charge to the Customers in Night.
* Customer service calls Number of customer service calls made by customer
* Churn Customer Churn, True means churned customer, False means retained customer
# Key Findings of the EDA
After performing exploratory data analysis on the data set, this is what we have incurred from data:
* Some states have a higher churn rate than others, which might be due to poor network coverage.
* Because the area code and account length have no influence on the churn rate, they are redundant data columns.
* Customers who have the International plan churn more frequently, and the international calling charges are also high, leaving customers dissatisfied with network issues and high call charges.
* When there are more than 20 voice-mail messages in the voice mail section, there is churn, which basically means that the voice mail quality is poor..
* Total day call minutes, total day calls, Total day charge, Total eve minutes, Total eve calls, Total eve charge, Total night minutes, Total night calls, Total night charge, none of these columns had any bearing on the churn rate.
* Data on international calls shows that the churn rate of those customers who take the international plan is high, implying that international call charges are high as well as a call drop or network issue.
* Data from customer service calls shows that when an unsatisfied customer calls the service centre, the churn rate is high, indicating that the service centre did not resolve the customer's issue.
# Conclusion
* Increase network coverage in the churned state
* Customers can benefit from a discount plan in international plans.
* Improve the voice mail quality or solicit customer feedback
* Improve call centre service by soliciting frequent feedback from customers about their problems and attempting to resolve them as soon as possible.








