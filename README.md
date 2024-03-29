# Predict Customer Churn
## Problem Statement
<p align="center"><img src="https://github.com/dgitts/predict-customer-churn/blob/feature/problem_statement/assets/images/istockphoto-913722522-170667a2.jpg" alt="Predict Customer Churn Cover" title="Predict Customer Churn Cover" style="max-width:100%;"></p>

Customer churn is the percentage of customers that stop using a company service or product during a time period.
To calculate the churn rate, divide the number of customers the business lost during a time period by the number of customers the business had at the beginning of that time period. Customer churn rate is an important metric for any business to evaluate because it costs more to acquire new customers than it does to retain existing ones. Returning customers are likely to spend more on various company products and services because they do not need convincing to become a customer.

A bank wants to identify their credit card customers who are likely to churn and the factors that affect their decision to leave in order to mitigate the churn and improve their customer retention strategies. The bank has supplied this dataset containing about 10,000 customer records and 20 different variables that were tracked over a period of time. The dataset columns include demographic data such as age, gender, dependents, education level, marital status & income. The dataset also includes customer financial data such as how many bank services/products a customer uses, card category, relationship length, transaction counts & amounts. We also have a target column called the attrition flag which tracks whether a customer record is currently existing or attrited.

We aim to help improve the banks' customer retention strategies by identifying the biggest factors that lead to customer churn. We will do this by analyzing each feature against the target column to determine what features have the strongest impact on the target.
The data is structured into several data points that the bank tracks for each customer. We will only use a single dataset for this project.

## Data Acquisition
We obtained this dataset from <a href="https://leapsapp.analyttica.com/cases/11" target="_blank">LEAPS</a>.

The dataset contains 10,127 records. There are 20 features and 1 target (Attrition Flag).

The data is structured and we will use supervised learning models to make the predictions.
## Data Dictionary
| Column Name              | Data Type   | Description                                                                                                                         |
|--------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Clientnum                | Int         | Client number. Unique identifier for the customer holding the account                                                               |
| Attrition_Flag           | Categorical | Customer status variable - Existing Customer, Attrited Customer                                                                     |
| Customer_Age             | Int         | Demographic variable - Customer's Age in Years                                                                                      |
| Gender                   | Categorical | Demographic variable - M=Male, F=Female                                                                                             |
| Dependent_count          | Int         | Demographic variable - Number of dependents                                                                                         |
| Education_Level          | Categorical | Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)               |
| Marital_Status           | Categorical | Demographic variable - Married, Single, Unknown                                                                                     |
| Income_Category          | Categorical | Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown) |
| Card_Category            | Categorical | Product Variable - Type of Card (Blue, Silver, Gold, Platinum)                                                                      |
| Months_on_book           | Int         | Months on book (Time of Relationship)                                                                                               |
| Total_Relationship_Count | Int         | Total no. of products held by the customer                                                                                          |
| Months_Inactive_12_mon   | Int         | No. of months inactive in the last 12 months                                                                                        |
| Contacts_Count_12_mon    | Int         | No. of Contacts in the last 12 months                                                                                               |
| Credit_Limit             | Float       | Credit Limit on the Credit Card                                                                                                     |
| Total_Revolving_Bal      | Int         | Total Revolving Balance on the Credit Card                                                                                          |
| Avg_Open_To_Buy          | Float       | Open to Buy Credit Line (Average of last 12 months)                                                                                 |
| Total_Amt_Chng_Q4_Q1     | Float       | Change in Transaction Amount (Q4 over Q1)                                                                                           |
| Total_Trans_Amt          | Int         | Total Transaction Amount (Last 12 months)                                                                                           |
| Total_Trans_Ct           | Int         | Total Transaction Count (Last 12 months)                                                                                            |
| Total_Ct_Chng_Q4_Q1      | Float       | Change in Transaction Count (Q4 over Q1)                                                                                            |
| Avg_Utilization_Ratio    | Float       | Average Card Utilization Ratio                                                                                                      |
