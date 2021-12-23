## Data analysis of sales data of an electronic store
This is a beginner's project in data analysis, using Pandas, Numpy, Matplotlib and Seaborn libraries in Python.

### Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup and Data Preparation](#setup)
* [Analysis Approach](#analysis)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)

#### General Information
- The purpose of this project is to conduct exploratory data analysis to find sales pattern with respect to different attributes such as product type, region, month, etc. 
- The problem present here is that the data is not clean and not compatible for data analysis.
- I undertook this project basically as a part of my online course for learning data analysis using Python, as done independently.

#### Technologies Used
- Python - version 3.8
- Jupyter Notebook

#### Setup and Data Preparation
The process starts by importing the required libraries: Pandas, Numpy, Matplotlib and Seaborn.
Next, we load the data by reading the dataset set, which is in the form of a csv file.
This follows with cleaning the dataset by removing null values and changing the data types of columns, such as from string to numeric type for numerical values.
Finally, we concate all the csv files of 12 months data sales to obtain a single csv file to conduct data analysis

#### Analysis Approach
For analysis, we start with data exploration to answer the following business questions:
- How much is the maximum sales in a day and for what?
- What is the trend of sales monthwise and by city?
- When is the busiest time for sales in the store?
- Which products are most often sold together?
- How can the price of products be optimized to increase sales?

The approach is to first extract the specific information required, in a newly added column, for example calculating total sales value from unit price, city from purchase address, order hour and month, etc.
This involves using groupby, slicing, .apply() methods commonly.
Then the visualization techniques of barplot, lineplot are used to interpret the results graphically. 

#### Project Status
Project is: complete.

#### Room for Improvement
Area for future work:
- Optimizing the inventory based on sales
