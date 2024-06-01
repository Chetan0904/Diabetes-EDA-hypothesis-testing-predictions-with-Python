Project title:
# Diabetes-EDA-hypothesis-testing-predictions-with-Python
Project Overview:
This project focuses on the analysis of diabetes medical data and building predictive models to predict diabetes status. It includes exploratory data analysis (EDA), hypothesis testing, observations, and the development of various models to predict the presence or absence of diabetes.
Steps involved:
Importing important Libraries.
Loading Dataset.
Data exploration and Missing Data Handling: Dealing with missing values by either imputing them or making informed decisions on how to handle gaps in the dataset..
Checking and fixing data types, Looking for null and duplicates values.
Columns which contain missing text data like 'name' and 'hostname' was replaced with the mode of the name/hostname on the basis of their neighbourhood_group and neighbourhood.
Replacing the null values on 'reviews_per_month' with zero and using ffill on datetime column 'last_review' to fill the null values.
Standardization: Consistent formatting and units across the dataset for accurate analysis.
Outlier Detection: Identifying and addressing outliers that may skew analysis or model performance.
Using Boxplot and IQR method to indentify and remove or either replace the outliers with the lower and upper range.
