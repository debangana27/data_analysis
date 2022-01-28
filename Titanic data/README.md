### Titanic data analysis project with linear regression model

This project in data analysis uses Pandas, Numpy, Matplotlib, Scikit-Learn and Seaborn libraries in Python.

#### General Information
- The purpose of this project is to present an analysis of the survival rate of the passengers on the Titanic.
- The approach is to first conduct exploratory data analysis to find pattern and correlation between different attributes such as class, age etc. 
- The next step is to set up a linear regression model and estimate its accuracy for the prediction.

#### Technologies Used
- Python - version 3.8
- Jupyter Notebook

#### Setup and Data Preparation
The process starts by importing the required libraries: Pandas, Numpy, Matplotlib and Seaborn.
Next, we load the dataset from a csv file.
This follows with investigating the dataset by checking the missing data and further using imputations to fill those, where necessary.

#### Analysis Approach
For analysis, we start with data exploration to answer the following questions:
- How biased is the survival rate?
- What are the features influencing survival rate?

The approach is to first extract the specific information required, for example, the distribution of passengers class-wise, by gender.
Further, transforming the data involves categorizing class with numeric values for correlation purpose, while setting dummy numeric values as well for regression model.
Further, we use visualization techniques of barplot, heatmap, regression plots for presentation of the results.

#### Project Status
Project is: Complete.

#### Room for Improvement
Area for future work:
- Investigating the data with other machine learning models through random forest regression.
