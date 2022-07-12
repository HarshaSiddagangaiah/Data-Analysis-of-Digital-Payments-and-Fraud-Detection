# Fraud-System: Data Analysis of Digital Payments and Fraud Detection
Financial fraud is an ever-increasing threat with far-reaching implications. The quantity of online transactions has increased dramatically, with online credit card transactions accounting for a substantial portion of these. As a result, banks and financial institutions place a high importance on credit card fraud detection software. Fraudulent transactions can take many forms and fall under a variety of categories. This paper examines common types of fraud in real-world transactions. This paper investigates the performance of 5 models: Gradient Boosting Classifier, XGBoost, Support Vector Machine, Random Forest and Logistic Regression on highly skewed credit card fraud data. The results demonstrate that XGBoost performs better than all the other classifiers with F1 Score, Accuracy and Precision of 73% to detect frauds.

# Code description and Specification

# Structure of code
# Loading Data
• Loaded the data of Capital One Transaction dataset.
• Mounted the data through Google Drive in Google Colab for easy access as data is greater than 600 MBs
• Loaded JSON format into Pandas Data Frames which are just like SQL or Excel Tables
• Necessary Python Packages and Libraries are loaded for further analysis

# Structure of the data
• Displayed Both Top and Bottom rows of the data to have a better look on the structure and attributes before doing any data analysis
• Some Basic Information about the dataset which includes the Type of columns it has, number of columns and total number of records
• Checking for Null values and unique values in data 

# Data Visualization and Analysis
• Plots, Histograms, Box Plots, Correlation Matrix and Hypothesis about the Structure of Data, Deep Diving in Fraudulent Aspects to find correlation and causation

# Data Wrangling
• Removing 6 empty columns
• Adding Date Column in the Data Frame to computer Results independent of just Date-Time
• Checking for Duplicate and multiple swipe transactions.
• Removing outlier and plotting graphs.

# Feature Engineering
• Divided the data based on 4 timings and added a separate column for it.
• Transormation from Categorical and Booleans to Numerical
• UnderSampling Technique for balancing data Modeling

# Modeling
• Dividing the data into train and test.
• Ran models Gradient Boosting Classifier, XGBoost, Support Vector Machine, Random Forest and Logistic Regression
 
 # Results
 • XGBoost Classifier which gives highest of 73% accuracy compared to other models

Note: Detailed Code description and Specification is also provided in Google colab file.
Google Colab File link:https://colab.research.google.com/drive/1gBByid9NWLbibJKkGPyGLJs_JDB 33IUP - scrollTo=mxY6z-3rnP8x
    
