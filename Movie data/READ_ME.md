### Movie data analysis project

This project in data analysis uses Pandas, Numpy, Matplotlib, Wordcloud and Seaborn libraries in Python.

#### General Information
- The purpose of this project is to present an analysis of movie features in order to estimate the trend of gross revenue with movie production.
- The approach is to conduct exploratory data analysis to find pattern and correlation between different attributes such as budget, gross revenue, movie genres, etc., 
- The data here contains a few incorrect entries (semantic error) and incompatible data format.

#### Technologies Used
- Python - version 3.8
- Jupyter Notebook

#### Setup and Data Preparation
The process starts by importing the required libraries: Pandas, Numpy, Matplotlib and Seaborn.
Next, we load the dataset from a csv file.
This follows with investigating the dataset by checking null values and changing the data types of columns, such as from string to numeric type for numerical values.

#### Analysis Approach
For analysis, we start with data exploration to answer the following questions:
- What are the most popular type of movies by genre?
- Who are the most popular movie directors?
- How is movie budget correlated with gross revenue?

The approach is to first extract the specific information required, for example, year from released information of movies, since the released year column contains incorrect values.
To analyze the data with respect to different attributes involves using groupby, slicing and categorizing class with numeric values through cat.codes for correlation purpose.
Further, we use visualization techniques of barplot, pieplot, heatmap, regression plots for presentation of the results.

#### Project Status
Project is: complete.

#### Room for Improvement
Area for future work:
- Investigating the data for syntactic accuracy, identifying outliers.
