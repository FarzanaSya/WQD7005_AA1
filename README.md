# WQD7005_AA1
The aim of this case study is to perform an analysis on the behaviour of E-Commerce customers that might help the business to increase profit by planning marketing strategies thoroughly. This analysis also helps to reveal hiddern patterns or trend of the sales. 

Initially, there are three separate datasets collected from different sources. Then, they are combined into one dataset to fulfill the objectives of the case study. The attributes involved along with its descriptions in the final dataset are listed below:
- Customer_ID   : The ID of the customers
- Gender        : Gender of the customers (Male/Female)
- Age           : Age of the customers
- Marital_Status: Marital status of the customers (Single/Married/Divorced)
- City          : The place that the customers live (Cities in USA: Chicago/Houston/Los Angeles/Miami/New York/San Francisco)
- Membership_Type : The type of membership class that the customers have (Gold/Silver/Bronze)
- Total_Spend : The total amount of money spent on the items by the customers
- Items_Purchased: The number of items purchased by the customers
- Category: The category of items that the customers purchased (Furniture/ Office Supplies/ Technology)
- NumWebVisitsMonth: The number of visits on the website's company by each customer
- CustomerEnrollmentDate: The date that the customers enrolled for membership club
- Satisfaction_Level: The level of customer's satisfaction on the buying experience of the items on the website (Satisfied/Unsatisfied/Neutral)

Three tools have been used to complete this project which include Talend Data Integration, Talend Data Preparation and SAS e-Miner. Talend Data Integration was used to merge the three datasets (E-commerce Customer Behavior-Sheet1.csv, superstore_data.csv and train.csv) into one dataset (ecommerceData.csv). The nodes that were involved in this process were "tFileInputDelimited", "tMap" and "tFileOutputDelimited" nodes. Next, Talend Data Preparation was used to clean the data. This involves standardizing the date format, rename certain columns and replacing certain values that have similar context within a column. The last tools used were SAS e-Miner. Sas e-Miner helps to detect and missing values as well as handle them by using mean imputation for continuous variables. Then, selections of machine learning such as Decision Tree, Random Forest and Gradient Boosting in SAS e-Miner were used to have a comprehensive analysis of the E-commerce customers behaviours.
