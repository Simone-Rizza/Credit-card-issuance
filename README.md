# Credit card issuance
 
In this project, I built a model capable of estimating a customer's creditworthiness in order to understand whether or not to accept an application for the issuance of a credit card.
The dataset used contains the information of current account holders who have applied for a line of credit.
- ID: customer identification number
- CODE_GENDER: gender of the cleinte
- FLAG_OWN_CAR: indicator of car ownership
- FLAG_OWN_REALTY: indicator of home ownership
- CNT_CHILDREN: number of children
- AMT_INCOME_TOTAL: annual income
- NAME_INCOME_TYPE: type of income
- NAME_EDUCATION_TYPE: level of education
- NAME_FAMILY_STATUS: marital status
- NAME_HOUSING_TYPE: 
- DAYS_BIRTH: Number of days elapsed since birth
- DAYS_EMPLOYED: Number of days elapsed since date of employment, if positive indicates number of days since unemployed
- FLAG_MOBIL: Indicator of the presence of a cell phone number
- FLAG_WORK_PHONE: indicator of the presence of a work phone number
- FLAG_PHONE: indicator of the presence of a phone number
- FLAG_EMAIL: indicator of the presence of an email address
- OCCUPATION_TYPE: type of occupation
- CNT_FAM_MEMBERS: number of family members
- TARGET: a variable that is worth 1 if the customer has high creditworthiness given by consistent payment of installments and 0 otherwise.

The model predicts the target customer.
In the end, we analyze through LIME why a customer obtained a certain target value