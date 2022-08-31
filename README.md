# Housing-Dataset-Data-Cleaning

The purpose of this project was to showcase my data wrangling (data cleaning) skills in Python utilising the Pandas library to clean an un-tidy dataset on the Nashville Housing Market.

My primary objective for this project was to clean the dataset by transforming features/data by:

1) Correcting the data types of each feature
2) Dealing with missing values (most of which were MNAR)
3) Factorising categorical data to reduce the complexity of certain categorical variables
4) Eliminating any features which will not be useful for EDA or Machine Learning models (such as the name of the owner and parcel ID of a property)


The programming concepts I applied using Pandas to clean the dataset were the following:

1) Utilised lambda functions for feature manipulation and implemented them using .apply()
2) Utilised functions and implemented them using .apply()
3) Utilised string methods such as .title() and .split() to make data for certain features neater 
4) Corrected the data types of features using dtypes and astype()
5) Investigated the cause of missing data using .isnull().sum() and dealt with them using .dropna()


**NOTE** 
This project only focuses on the cleaning of the dataset. Any Data Exploration (EDA) and Data Visualisation was conducted on a seperate GitHub project repo named 'Real-Estate-Dataset-EDA-and-Data-Visualisation'.
