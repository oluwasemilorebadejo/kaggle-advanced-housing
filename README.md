# Project Overview

![image](https://user-images.githubusercontent.com/85442734/156748571-fb165076-be07-4b74-81d2-c1f4c2b14845.png)

* Project Statement: 
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home

In this project I built a regressions model capable of predicting house price of given instance with high variety of Independent variables.

Tree based algorithms were used for model building starting with a Random Forest Regressor, then SVR, Linear Regressor, XGBoost Regressor and in last Decision Tree Regressor. Total five models were made.

# Data

The dataset for this project is from kaggle's advanced housing price prediction v9. This can be found at: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

# Tools Overview
The following are the tools that are covered in the notebooks. They are popular tools that machine learning engineers and data scientists need in one way or another and day to day.

Python is a high level programming language that has got a lot of popularity in the data community and with the rapid growth of the libraries and frameworks, this is a right programming language to do ML.

NumPy is a scientific computing tool used for array or matrix operations.

Pandas is a great and simple tool for analyzing and manipulating data from a variety of different sources.

Matplotlib is a comprehensive data visualization tool used to create static, animated, and interactive visualizations in Python.

Scikit-Learn: Instead of building machine learning models from scratch, Scikit-Learn makes it easy to use classical models in a few lines of code. This tool is adapted by almost the whole of the ML community and industries, from the startups to the big techs.

# Observations:

1) By taking a look at the data description, I noticed that the NA value for most of the variables actually means that variable isn’t present for that particular observation. For example, an observation which has it’s PoolQC variable as NA, actually means there is no Pool. Hence, I correctly replaced the NA values with None.

2) Also some categorical variables were actually represented with numbers which most machine learning models would have struggled with so I also replaced these variables such as the MSSubClass variable.

#  Project Steps
1. Loading training and test data 
2. Data Wrangling
3. Exploratory Data Analysis
4. Train- Test Split
5. Feature Selection
6. Model Selection And Evaluation
7. Final model building
8. Inference 
9. Submission for competition 
