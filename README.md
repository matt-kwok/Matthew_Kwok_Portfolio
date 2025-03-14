# Data Science Projects

## [Target Marketing for Canadian Bank](https://github.com/matt-kwok/Bank_Target_Marketing)
* Created a machine learning model to predict whether a bank customer will respond to a banks campaign to boost banking activity
* Utilized GridSearchCV to fine tune the hyperparameters of an XGBoost model to make the predictions 
* Also implemented an Ensemble Stacking which included classifier models like Random Forest, ADA Boost, Extra Trees and Gradient Boost
* Overall models had around a 60% accuracy whereas XGBoost had a 64% accuracy score
* Hyperparamter tuning with GridSearchCV on XGBoost gave an AUC of 69% and a F1 score of 63%

![](images/XGBoost_ROC_Curve.png)
![](images/Feature_Importance.png)

## [Impact of COVID-19 on Global Airport Traffic](https://github.com/matt-kwok/covid_airport_impact_proj)
* Utilized GeoPandas, Contextily, and Folium to leverage geospatial data and airport traffic data to create GIS maps of how COVID has influenced global airport traffic 
* Encoded categorical variables using Label-Encoding and One-Hot-Encoding methods to create correlation heatmaps to see if there were any relationships between the variables
* Implemented data wrangling and string RegEx techniques to clean, transform and manipulate a dataset of 7247 airport traffic entries from 27 airports 
* Analyzed time series data of airport traffic to analyze the change in airport traffic during the year of 2020

![](images/corr_matr.png)
![](images/Chloro_map.png)

# Data Analysis Projects

## [How does Infectious Disease Propagate?](https://github.com/matt-kwok/Disease_Project)

## [Toronto Climate Change Impact Assessment (1980 - 2080)](https://github.com/matt-kwok/Toronto_Climate_Analysis)

# Other Data Projects

## [Creating an OLS Regression Model](https://github.com/matt-kwok/OLS_Regression_proj/blob/main/OLS_Regression_Modelling_Project.ipynb)
* Created an OLS regression model on an Excel file with multiple excel sheets
* Checked for linearity in the dataset by plotting correlation matrices 
* Optimized non-linear datasets by applying Box-Cox transformations to the datasets
* Utilized boxplots to find outliers affecting the performance of regression model

## [Creating MongoDB Queries](https://github.com/matt-kwok/MongoDB-Project)
* Created MongoDB data pipelines to run aggregate queries on a company’s employee list
* Employed MongoDB CRUD operations to perform queries that create, read, update, and delete documents in the database

## [Creating a data model in Apache Cassandra](https://github.com/matt-kwok/Apache_Cassandra_Project)
* Designed a data model for a database which stores information about all universities that offer a data course
* Created Cassandra tables based on a Chebotko Diagram’s data model, in Windows PowerShell

## [Machine Learning with Apache Spark](https://github.com/matt-kwok/ApacheSpark-Project)
* Built a random forest model and optimize it to predict if a farmers market is more likely to be in rich zip code 
* Created a model to predict the price of a diamond, using Apache Spark ML Pipeline



