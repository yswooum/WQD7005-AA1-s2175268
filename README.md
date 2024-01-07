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

# Role of Talend Data Integretion
Talend Data Integration is a powerful data integration tool that allows users to connect, transform and manage data from various sources. In this case study, Talend Data Integration was used to integrate the two datasets ‘customer info’ and ‘customer purchase info’ by the common column which is customer ID. 
![image](https://github.com/yswooum/WQD7005-AA1-s2175268/assets/155871715/a97f48ef-8d81-4aac-b4f2-5ed889b928f6)

# Role of Talend Data Prep
Talend Data Preparation is a user-friendly data preparation tools that is specifically designed for data processing, such as data cleaning, transformation and normalization of the data. In this case study, Talend Data Preparation was used to handle the inconsistencies in the dataset. Specifically, the location, which has UK and United Kingdom, US and United States which referred to the same country. Talend Data Preparation was used to convert UK to United Kingdom and US to United States.
![image](https://github.com/yswooum/WQD7005-AA1-s2175268/assets/155871715/14d20220-5c36-4c39-900d-5b4dac7726b8)

# Role of SAS E-MINER
SAS Enterprise Miner offers a wide range of advanced analytics and machine learning techniques that can be used to model and predict the trends and hidden relationships which can provide insights into ecommerce business. SEMMA (Sample, explore, modify, model and access) methodology was applied in this case study. Random sampling was applied to the dataset to obtain a sample that is 10% of the original dataset. Then, data analysis and exploration were performed to inspect the distribution, presence of outliers or missing values in the dataset. In the modify step, missing column (return rate) which was a binary column was imputed with mode. The model that was used to predict churn in this case study was decision trees, random forest and gradient boosting. Lastly, the performance of the 3 models were compared and analysed.
![image](https://github.com/yswooum/WQD7005-AA1-s2175268/assets/155871715/17ee7d51-9ebd-4bbd-89b0-78edacdf631b)

# Methodology
1.	Talend Data Integration
The two datasets had a common key, which is the ID. So, the datasets were integrated by using Talend Data Integration. 

2.	Talend Data Preparation 
Upon inspection, there was inconsistency in the location column. There was UK and United Kingdom as well as US and United States which were representing the same country, but in short form. Replaced UK with United Kingdom and US with United States.

4.	SAS ENTREPRISE MINER
The summary of SEMMA methodology applied in the case study:
Sample: 10% of the dataset was randomly sampled.
Explore: Explored and analysed the dataset, identify outliers and missing values. No outliers were identified in the dataset, but there is a column (Return) that had missing values.
Modify: The column with the missing values (Return) was imputed with mode. No transformation and normalization were done to the dataset. Then, the dataset was split into 60 % training, 20 %validation and 20% testing sets for modelling.
Model: Three models were used to predict the churn, namely decision tree, random forest and gradient boosting. 
Access: The performance of the model was compared.




