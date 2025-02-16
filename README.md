# Zomato Data Analysis
# Overview
This project analyzes a Zomato dataset to derive insights into restaurant ratings, online orders, table booking trends, and cost distribution. Various exploratory data analysis (EDA) techniques and visualizations have been used to understand the data better.

# Dataset Description
The dataset consists of 148 records and 7 columns, as described below:

# Column Name	Description
name	                      Name of the restaurant
online_order	              Indicates if the restaurant accepts online orders (Yes/No)
book_table	                Indicates if table booking is available (Yes/No)
rate	                      Customer rating of the restaurant
votes	                      Number of votes received
approx_cost(for two people)	Approximate cost for two people (in currency units)
listed_in(type)	            Category/type of restaurant

# Data Analysis & Visualizations
The following visualizations were performed to explore patterns in the dataset:

# Countplot: 
Displays the distribution of restaurant types based on their category (listed_in(type)).
# Histogram: 
Visualizes the frequency distribution of restaurant ratings.
# Boxplot: 
Compares online order availability (online_order) against customer ratings (rate) to analyze trends.
# Heatmap: 
Displays the correlation between numerical variables to identify patterns.
# Frequency Plot:
Analyzes the frequency of different types of restaurants and their corresponding number of votes.


# Technologies Used
Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook

# Conclusion
This analysis provides insights into customer preferences, restaurant popularity, and cost patterns, which can be useful for business decision-making in the food industry.

