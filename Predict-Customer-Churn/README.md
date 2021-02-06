# Predict Customer Churn
## Problem Statement
<div style='text-align:center'>![Customer Churn Cover](https://github.com/dgitts/Data-Science-Projects/blob/feature/problem_statement/Predict-Customer-Churn/assets/images/istockphoto-913722522-170667a2.jpg "Customer Churn Cover")</div>
Customer churn is the percentage of customers that stop using a company service or product during a time period. To calculate the churn rate, divide the number of customers the business lost during a time period by the number of customers the business had at the beginning of that time period.
Customer churn rate is an important metric for any business to evaluate because it costs more to acquire new customers than it does to retain existing ones. Returning customers are likely to spend more on various company products and services because they do not need convincing to become a customer. This reduces operating expenses for a business since they do not need to spend as much resources acquiring this business.

In this project, a business would like to use data science to predict customers who are likely to stop using their credit card services. 
## Data Acquisition
We obtained this dataset from [LEAPS](https://leapsapp.analyttica.com/cases/11).
The dataset contains 10,127 records. There are 20 features and 1 target (Attrition Flag)
## Data Dictionary
| Original Column Name     | Data Type | Description                                                                                                                         |
|--------------------------|-----------|-------------------------------------------------------------------------------------------------------------------------------------|
| Clientnum                | Num       | Client number. Unique identifier for the customer holding the account                                                               |
| Attrition_Flag           | Char      | Internal event (customer activity) variable - if the account is closed then 1 else 0                                                |
| Customer_Age             | Num       | Demographic variable - Customer's Age in Years                                                                                      |
| Gender                   | Char      | Demographic variable - M=Male, F=Female                                                                                             |
| Dependent_count          | Num       | Demographic variable - Number of dependents                                                                                         |
| Education_Level          | Char      | Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)               |
| Marital_Status           | Char      | Demographic variable - Married, Single, Unknown                                                                                     |
| Income_Category          | Char      | Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown) |
| Card_Category            | Char      | Product Variable - Type of Card (Blue, Silver, Gold, Platinum)                                                                      |
| Months_on_book           | Num       | Months on book (Time of Relationship)                                                                                               |
| Total_Relationship_Count | Num       | Total no. of products held by the customer                                                                                          |
| Months_Inactive_12_mon   | Num       | No. of months inactive in the last 12 months                                                                                        |
| Contacts_Count_12_mon    | Num       | No. of Contacts in the last 12 months                                                                                               |
| Credit_Limit             | Num       | Credit Limit on the Credit Card                                                                                                     |
| Total_Revolving_Bal      | Num       | Total Revolving Balance on the Credit Card                                                                                          |
| Avg_Open_To_Buy          | Num       | Open to Buy Credit Line (Average of last 12 months)                                                                                 |
| Total_Amt_Chng_Q4_Q1     | Num       | Change in Transaction Amount (Q4 over Q1)                                                                                           |
| Total_Trans_Amt          | Num       | Total Transaction Amount (Last 12 months)                                                                                           |
| Total_Trans_Ct           | Num       | Total Transaction Count (Last 12 months)                                                                                            |
| Total_Ct_Chng_Q4_Q1      | Num       | Change in Transaction Count (Q4 over Q1)                                                                                            |
| Avg_Utilization_Ratio    | Num       | Average Card Utilization Ratio                                                                                                      |
    
--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdsprojects</small></p>
