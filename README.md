# Credit-Card-Approval
Here I tried to do an Analysis of Credit Card Approval. This project can be used to know the characteristics of the client  and whether the credit card approval was received or not

# Data Understanding
The dataset is about the Credit  and personal information dataset by Seanny from Kaggle and is licensed for its author to use publicly. The goal of this project is to know whether the credit approval was received or not. Personal information of the client load in the applicatio_record dataset and credit in the credit_record dataset.

# Outline
The following are a few steps in the modeling technique used on this project:
  1. Import dataset
  2. Data Understanding
  3. DataCleaning and Preprocessing
  4. EDA
  5. Modelling
  6. Conclusion and Recommendation

# Load Dataset
The raw dataset must be combined before proceeding with the process. For the dataset with the personal information of each client, There are a total of 438,557 rows and 18 columns. Each column is labeled with a description of its own. For the dataset with the credit record of each client, There are a total of 1,0485,75 rows and 3 columns.

# Data Understanding
Below is the description for each column or feature:

1. ID: Client's ID
2. CODE_GENDER: Gender of Clients
3. FLAG_OWN_CAR: Does the client own a car?
4. CNT_CHILDREN: Client's children count
5. AMT_INCOME_TOTAL: Client's annual income
6. NAME_INCOME_TYPE: Client's income type
7. NAME_EDUCATION_TYPE: Client's education level
8. NAME_FAMILY_STATUS: Client's family status
9. NAME_HOUSING_TYPE : Client's housing type
10. DAYS_BIRTH: The days the client was born, counts backwards (-1000 means client was born 1000 days ago)
11. DAYS_EMPLOYED: The days the client was employed, counts backwards (-1000 means client was employed 1000 days ago, 0 means unemployed)
12. FLAG_MOBIL: Does client have mobile phone?
13. FLAG_WORK_PHONE: Does client have work phone?
14. FLAG_PHONE: Does client have phone?
15. FLAG_EMAIL: Does client have email?
16. OCCUPATION_TYPE: Client's occupation
17. CNT_FAM_MEMBERS: Client's family members count
18. MONTHS_BALANCE: Client's record month
19. STATUS: Default or not.

# Data Cleaning and Preprocessing

Cleaning data is used to see whether there is a NaN value or not so that it can be used later in the machine learning modeling process. in the process there is a NaN value in the Occupation_type column, and to overcome this an adjustment is made. NaN value data will be made "not Specific".
Apart from that, two data are combined, namely application_record and credit_record, using ID as the key value. The results of combining this data produce 36457 rows of data.

# Exploratory Data Analysis (EDA)
