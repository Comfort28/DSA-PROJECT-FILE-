# DSA-PROJECT (CASE STUDY 1)-
This repository contains my work on a data analysis project as part of my coursework in the (Digital Skill-up Africa program by the incubator hub). As a data analyst in training, i am excited to apply my skills and knowledge to real-world problems and contribute to the success of @incubator hub. This project will be graded by the organization, and i look forward to receiving feedback and improving my skills. Thank you and GOD bless you.
## PROJECT TOPIC: Amazon Product Review Analysis (CASE STUDY 1)
### PROJECT OVERVEW 
This project contains one repository and it aims to analyse product and customer review data to generate insights that can guide product improvement, and customer engagement. I will be making use of various data analysis techniques and tools to deliver insights and recommendations.
### SKILLS DEMONSTRATED 
- Data analysis and visualization
- Data cleaning and preprocessing
- Data storytelling and communication
### DATA SOURCES
The primary source of data used here is scraped from Amazon product pages which is an XLSX worksheet(xlsx) and this file is an open source data that can be freely downloaded from an open source such as kaggle or any other data repository site.
### TOOLS USED 
- WPS office for data cleaning [download here] (https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChsSEwjR5Ynru5mOAxWJllAGHRZeENoYACICCAEQABoCZGc&ae=2&aspm=1&co=1&ase=5&gclid=EAIaIQobChMI0eWJ67uZjgMViZZQBh0WXhDaEAAYASAAEgLrR_D_BwE&ohost=www.google.com&cid=CAASJeRocrII6hmlQe5hirSKMiJPtkYevfnATsihcK-kr4E9mMVjPa8&category=acrcp_v1_43&sig=AOD64_0zy9O8vyE1SLGK8h_zacofd_hNyw&q&adurl&ved=2ahUKEwjN_IXru5mOAxWVVEEAHUPMFzYQ0Qx6BAgIEAE)
  1. For data cleaning
  2. For data manipulation
  3. For data munging
  4. For data visualization
### DATA CLEANING AND PREPARATION
1. Data loading
2. Data Inspection; I inspected the data for quality issues including,missing calues,duplicate and data type inconsistencies.
3. Handling missing values; I first filtered my data and imputed missing values with '0' to represent those that deal with number and 'NA' for those that deal with letters.
4. Removal of duplicates; I used my product ID to filter out duplicates, so that my product ID would be unique.
5. Data normalization; I scaled monetary numeric variables to a common currency (English india).
6. Splitting of columns; I split my category column into 4 different sub-category to make data visualization more readable and easier to use for analysis.
7. Calculated columns; I included calaculated columns into my data set for those that were needed e.g Average discount %, >=50% discount, total potential revenue, price range bucket e.t.c
### EXPLORATORY DATA ANALYSIS (EDA)
Use pivot tables and calculated columns where necessary to answer the following:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual price × rating count) by category?
10. What is the number of unique products per price range bucket (e.g., <$200, F200-5500, >7500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.
Final Task: Dashboard Creation
Using your cleaned dataset and pivot outputs, build an Excel dashboard. Unleash your
Creativity.
### DATA ANALYSIS 
These are some of the DAX expressions used during my analysis;
- =if(discount %) = 50, "yes", "no")
- =if(discounted price (200, "< ₹200 ", if(discounted price (=500, "₹200 - ₹500", ">₹500"))
- =actual price * rating count
### ANALYSIS
- AMAZON STRUCTURED TABLE
![image](https://github.com/user-attachments/assets/84b78860-9d44-4cf8-8476-299f34a0f257)
- PIVOT TABLES
1. What is the average discount percentage by product category?
![image](https://github.com/user-attachments/assets/3b3b1cb1-5a3d-453c-a9e8-b64c64f22998)
2. How many products are listed under each category?
![image](https://github.com/user-attachments/assets/36e6d30a-2655-4a8c-806e-e20cc877111a)
3. What is the total number of reviews per category?
![image](https://github.com/user-attachments/assets/322d8e39-c541-4e3d-909f-470b33b955f5)
4. Which products have the highest average ratings?
![image](https://github.com/user-attachments/assets/717ee74b-eb9a-42d9-96ec-307d1fe2a5b0)
5. What is the average actual price vs the discounted price by category?
![image](https://github.com/user-attachments/assets/763282de-4f66-415f-9f4e-8bcc7d31f816)
6. Which products have the highest number of reviews?
![image](https://github.com/user-attachments/assets/98bab68a-a6ec-43c0-9723-3345ff4bc3cd)
7. How many products have a discount of 50% or more?
![image](https://github.com/user-attachments/assets/35a6fba5-a93d-481e-aad3-40b662aa41d8)
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
![image](https://github.com/user-attachments/assets/b685ae9a-1450-4365-8c66-bcc77d7de512)
9. What is the total potential revenue (actual price × rating count) by category?
![image](https://github.com/user-attachments/assets/ed521c4c-9e40-4eb2-8f33-03bd66909da1)
10. What is the number of unique products per price range bucket (e.g., <$200,F200-5500, >7500)?
![image](https://github.com/user-attachments/assets/16339901-3536-43c8-aa01-870f1b21bc07)
11. How does the rating relate to the level of discount?
![image](https://github.com/user-attachments/assets/e806b743-3873-4dbf-a093-62d0b42b6025)
![image](https://github.com/user-attachments/assets/1900a02e-c324-4fff-99ef-a721cd9e8d80)
12. How many products have fewer than 1,000 reviews?
![image](https://github.com/user-attachments/assets/866da385-e6d7-4914-a682-786450b2f133)
13. Which categories have products with the highest discounts?
![image](https://github.com/user-attachments/assets/133ed336-ffe9-4273-951b-bfe2a8048f77)
14. Identify the top 5 products in terms of rating and number of reviews combined.
![image](https://github.com/user-attachments/assets/bbdb8a7b-5b41-4a9f-b9a0-810763abe516)
- DASHBOARD
![Screenshot 2025-07-03 115524](https://github.com/user-attachments/assets/664b69b2-33c2-4b5b-a9e2-1ce51fe702b8)

### RESULTS AND RECOMMENDATIONS 
- Based on the insights generated from our pivot tables and dashboard our analysis of total potential revenue across categories reveals that Electronics emerges as the top-performing category, generating the highest revenue potential. This is followed closely by Computer and Accessories, which also demonstrates significant revenue potential. Homes and Kitchen ranks third, showing moderate revenue potential. In contrast the remaining categoreis exhibit relatively low revenue potential, indicating opportunities for growth and optimization. Based on this findings we recommend focusing on the top-performign categories to maximize revenue potential and we suggest exploring strategies to boost revenue the Homes and Kitchen category and investigating opportunities to grow the low-performing categories.
- Based on the insights generated from our pivot tables and dashboard our analysis of average discount percentage reveals variations across categories. Home improvement stands out with the highest avaerage discount percentage of 58% indicating a strong promotional strategy in this category. In contrast, Toys and Games has the lowest at 0%, suggesting opportunities for price adjustments or promotional activities to drive sales.
- Based on the insights generated from our pivot tables and dashboard our analysis reveals significant differences in average actual prices and average discounted prices across categories for example, Car and Motorbike - average actual price which is at 4,000 and its average discounted price whhic is at 2,339. These findings varying pricing strategies and discounting practices across categories. Another insight generated indicates that Toys and games shows no price difference, potentially indicating a fixed pricng strategy or limited discounting opportunities.
- Based on the insights generated from our pivot tables and dashboard our analysis revelas that fire-bolt ninja call pro plus 1.83 smart watch stands out with the highest number of reviews, boasting a rating count of 5. This products high review count suggests strong customer engagement and interest.   



  
