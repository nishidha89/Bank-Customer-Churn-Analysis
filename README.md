# Bank-Customer-Churn-Analysis  

Customer churn, also referred to as customer attrition, happens when customers end their association with a business.In the context of banking, customer attrition occurs when customers close their accounts or discontinue utilizing services of a particular bank. Effectively understanding and managing customer attrition are crucial for banks to maintain financial stability and safeguard their reputation.
# Objective
* To understand and analyse the factors that contribute to customer churn from bank.
* To find insights to understand relationships and trends in bank customer churn data.
* To provide recommendations to bank in order to mitigate churn.

# Data Source
Data is from RBC bank(Royal Bank of Canada)  
Link of files: https://drive.google.com/drive/folders/1WlPwjiQe0AsjB0KF-HrFyK5ukJgfGYGT?usp=drive_link

# Data Cleaning/Preparation
* Removed irrelevant columns that are not related to customer churn.
* Done date formatting for consistency.

# Data Modelling
* The relationship between the tables refers to star schema
* There are 7 Dimension tables and 1 Fact table
* Dimension tables includes:
1. ActiveCustomer  
2. CreditCard  
3. CustomerInfo  
4. ExitCustomer  
5. Gender  
6. Geography  
Primary key from each dimension table is mapped to foreign key from fact table    
![Screenshot (230)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/1f663c7f-9eb0-402e-8546-c49cb5dcf47d)


# Data Analysis and visuals
![Screenshot (238)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/98715ce5-aa8c-4a0e-bf7a-b7d322c038ff)

From above visuals we could discover the following insights:    
* The joining of customers increases from 2016 to 2019  
* The number of exit customers are more in September and November  
* 69.91% of exit customers holds credit card and 30.09% of exit customers are non credit card holders  
* 55.92% of exit customers comprises of females and 44.08% of exit customers comprises of males  
 

![Screenshot (240)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/fab91f2a-6158-4ff4-b70a-93473d7884eb)

![Screenshot (246)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/6c6961ee-ab11-47ef-b315-c44b961378a5)


* 30% churn rate happened in January 2017 which is highest than other years.    
* Exit customers with Fair credit type are more i.e 685.  
* Churned rate of inactive members are more i.e 65.3%.  
* There are more number of exit customers in 2019 i.e 658 as more number of customers join bank in 2019.  
* Most of the customers belong to France country.
* The percentage of active customers are more than inactive customers.  


![Screenshot (242)](https://github.com/nishidha89/Bank-Customer-Churn-Analysis-using-PowerBI/assets/78490621/88add2a3-0a79-471d-8b7a-89050b88e8aa)

* Germany contains more number of exit customers i.e 814 followed by France which contains 810 exit customers.  

# Conclusion  
* In 2019, the bank had the highest number of customers, with 3.3K joining.  
* In September and November, there were a higher number of exiting customers.  
* Womens are more likely to churn than males.  
* In March 2017 there was 30% churn rate which was highest than other years.    
* InActive members are more likely to churn.    
* Customers with higher credit score are less likely to leave bank.    
* The percentage of active customers are more than inactive customers.   
* In Germany, there are a higher number of exiting customers.    

# Recommendations
* Provide financial advice and investment solutions for diverse customer groups.  
* Increase customer awareness about the benefits of keeping a good credit score.  
* Introduce digital products and use schemes to attract customers of various ages.  


