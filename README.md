# Predict Customer Churn
## Problem Statement
<p align="center"><img src="https://github.com/dgitts/Data-Science-Projects/raw/feature/problem_statement/Predict-Customer-Churn/assets/images/istockphoto-913722522-170667a2.jpg" alt="Customer Churn Cover" title="Customer Churn Cover" style="max-width:100%;"></p>
Customer churn is the percentage of customers that stop using a company service or product during a time period.
To calculate the churn rate, divide the number of customers the business lost during a time period by the number of customers the business had at the beginning of that time period.

Customer churn rate is an important metric for any business to evaluate because it costs more to acquire new customers than it does to retain existing ones. Returning customers are likely to spend more on various company products and services because they do not need convincing to become a customer. This reduces operating expenses for a business since they do not need to spend as much resources acquiring this business.

In this project, a bank would like to identify customer characteristics for customers who are likely to stop using their credit card services. By identifying this KPI, the bank can quickly identify what features greatly affect customer retention and begin targetting these features to minimize churn rate.

The data is structured into several data points that the bank tracks for each customer. We will only use a single dataset for this project.
## Data Acquisition
We obtained this dataset from [LEAPS](https://leapsapp.analyttica.com/cases/11).
The dataset contains 10,127 records. There are 20 features and 1 target (Attrition Flag).
The data is structured and we will use supervised learning models to make the predictions.
## Data Dictionary
| Original Column Name     | Data Type | Description                                                                                                                         |
|--------------------------|-----------|-------------------------------------------------------------------------------------------------------------------------------------|
| Clientnum                | int64     | Client number. Unique identifier for the customer holding the account                                                               |
| Attrition_Flag           | category  | Internal event (customer activity) variable - if the account is closed then 1 else 0                                                |
| Customer_Age             | int64     | Demographic variable - Customer's Age in Years                                                                                      |
| Gender                   | category  | Demographic variable - M=Male, F=Female                                                                                             |
| Dependent_count          | int64     | Demographic variable - Number of dependents                                                                                         |
| Education_Level          | category  | Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)               |
| Marital_Status           | category  | Demographic variable - Married, Single, Unknown                                                                                     |
| Income_Category          | category  | Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown) |
| Card_Category            | category  | Product Variable - Type of Card (Blue, Silver, Gold, Platinum)                                                                      |
| Months_on_book           | int64     | Months on book (Time of Relationship)                                                                                               |
| Total_Relationship_Count | int64     | Total no. of products held by the customer                                                                                          |
| Months_Inactive_12_mon   | int64     | No. of months inactive in the last 12 months                                                                                        |
| Contacts_Count_12_mon    | int64     | No. of Contacts in the last 12 months                                                                                               |
| Credit_Limit             | float64   | Credit Limit on the Credit Card                                                                                                     |
| Total_Revolving_Bal      | int64     | Total Revolving Balance on the Credit Card                                                                                          |
| Avg_Open_To_Buy          | float64   | Open to Buy Credit Line (Average of last 12 months)                                                                                 |
| Total_Amt_Chng_Q4_Q1     | float64   | Change in Transaction Amount (Q4 over Q1)                                                                                           |
| Total_Trans_Amt          | int64     | Total Transaction Amount (Last 12 months)                                                                                           |
| Total_Trans_Ct           | int64     | Total Transaction Count (Last 12 months)                                                                                            |
| Total_Ct_Chng_Q4_Q1      | float64   | Change in Transaction Count (Q4 over Q1)                                                                                            |
| Avg_Utilization_Ratio    | float64   | Average Card Utilization Ratio                                                                                                      |
    
--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdsprojects</small></p>