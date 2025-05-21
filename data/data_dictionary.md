# Data Dictionary: Customer Churn Dataset

| Column Name      | Description                                      | Unit         | Expected Range         | Type         | Tag           |
|------------------|--------------------------------------------------|--------------|-----------------------|--------------|---------------|
| CustomerID       | Unique customer identifier                       | N/A          | 0 - 9999              | int          | identifier    |
| Gender           | Customer gender                                  | N/A          | Male, Female          | str          | categorical   |
| SeniorCitizen    | Whether the customer is a senior citizen         | 0 = No, 1 = Yes | 0, 1                | int          | ordinal       |
| Tenure           | Number of months the customer has stayed         | months       | 1 - 72                | int          | numerical     |
| MonthlyCharges   | Monthly billing amount                           | USD          | 20.00 - 120.00        | float        | numerical     |
| TotalCharges     | Total amount charged to the customer             | USD          | 20.00 - 8640.00       | float        | numerical     |
| Contract         | Type of contract                                 | N/A          | Month-to-month, One year, Two year | str | categorical   |
| PaymentMethod    | Customer's payment method                        | N/A          | Electronic check, Mailed check, Bank transfer, Credit card | str | categorical   |
| Churn            | Whether the customer left (target variable)      | 0 = No, 1 = Yes | 0, 1                | int          | ordinal       |

- **numerical**: Quantitative variable (continuous or discrete)
- **categorical**: Qualitative variable (unordered)
- **ordinal**: Qualitative variable (ordered)
- **identifier**: Unique key
