# WQD7005-AA1-s2175268

# Description
E-commerce customer behaviour case study helps in building the understanding of customers, such as their preferences, spending patterns, favourite products, and churn rate. The analysis can generate insights and helps e-commerce businesses to tailor their strategies to fulfil their customer needs, leading to increased satisfaction, loyalty while increasing return rate and reducing churn rate. 
# Attached file
Customer Info.csv - first dataset with customer info such as ID, name, age, gender, membership level, return, churn and location.
Customer Purchase Info.csv - second dataset with customer purchase info such as ID, purchase date, product category, product price, total amount purchased, total spent and payment method.
customer_data.csv - Integrated data from Talend Data Integration
customer_data_cleaned.csv - Cleaned data from Talend Data Prep
AA1_dataint.zip - Talend Data integration zip
7005 Model.spk - DT, RF and gradient boosting model in SAS E-Miner

# Objective
1.	To understand key demographic segments in e-commerce
2.	To identify key features that lead to customer churn
3.	To predict churn using machine learning model

# Talend Data Integretion
Talend Data Integration is a powerful data integration tool that allows users to connect, transform and manage data from various sources. In this case study, Talend Data Integration was used to integrate the two datasets ‘customer info’ and ‘customer purchase info’ by the common column which is customer ID. 

# Talend Data Prep
Talend Data Preparation is a user-friendly data preparation tools that is specifically designed for data processing, such as data cleaning, transformation and normalization of the data. In this case study, Talend Data Preparation was used to handle the inconsistencies in the dataset. Specifically, the location, which has UK and United Kingdom, US and United States which referred to the same country. Talend Data Preparation was used to convert UK to United Kingdom and US to United States.

# SAS E-MINER
SAS Enterprise Miner offers a wide range of advanced analytics and machine learning techniques that can be used to model and predict the trends and hidden relationships which can provide insights into ecommerce business. SEMMA (Sample, explore, modify, model and access) methodology was applied in this case study. Random sampling was applied to the dataset to obtain a sample that is 10% of the original dataset. Then, data analysis and exploration were performed to inspect the distribution, presence of outliers or missing values in the dataset. In the modify step, missing column (return rate) which was a binary column was imputed with mode. The model that was used to predict churn in this case study was decision trees, random forest and gradient boosting. Lastly, the performance of the 3 models were compared and analysed.
