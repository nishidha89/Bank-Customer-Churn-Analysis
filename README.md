# Bank-Customer-Churn-Analysis  

Customer churn, also referred to as customer attrition, happens when customers end their association with a business.In the context of banking, customer attrition occurs when customers close their accounts or discontinue utilizing services of a particular bank. Effectively understanding and managing customer attrition are crucial for banks to maintain financial stability and safeguard their reputation.
# Objective
To understand and analyse the factors that contribute to customer churn from bank

# Data Source
Data is from RYC bank(Royal Bank of Canada)  
Link of files: https://drive.google.com/drive/folders/1WlPwjiQe0AsjB0KF-HrFyK5ukJgfGYGT?usp=drive_link

# Data Modelling
The relationship between the tables refers to star schema
There are 7 Dimension tables and 1 Fact table
Dimension tables includes:
ActiveCustomer  
CreditCard  
CustomerInfo  
ExitCustomer  
Gender  
Geography  
Primary key from each dimension table is mapped to foreign key from fact table  
![Screenshot (208)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/a1369636-d870-455b-9a12-fb45caafde29)  

# Data Analysis and visuals
![Screenshot (214)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/4707847b-0823-4313-ab1b-4edc5040377a)  
From above visuals we could discover the following insights:    
The joining of customers increases from 2016 to 2019  
The number of exit customers are more in September and November  
69.91% of exit customers holds credit card and 30.09% of exit customers are non credit card holders  
55.92% of exit customers comprises of females and 44.08% of exit customers comprises of males  
Customers whose credit type is Fair buys more products  





