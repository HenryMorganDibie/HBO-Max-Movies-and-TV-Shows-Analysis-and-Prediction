# HBO-Max-Movies-and-TV-Shows-analysis
## Summary of the process:
* Importing the necessary libraries and loading the datasets.
* combine the datasets using python code soo i can gain insights from both datasets
* Performed some basic exploratory data analysis to gain insights into the dataset, 
1; Explore the data: Used pandas functions like head(), info(), and describe() to get a sense of what the data looks like, what columns are present, and what the data types are.

2; Clean the data: Looked for missing values, duplicates, and other inconsistencies in the data. Use pandas functions like isna(), duplicated(), and drop_duplicates() to identify and clean up the data. Impute missing data, i used the fillna() method in pandas, using the median for numerical columns and the mode for categorical columns:

3; Visualize the data: Used libraries like Matplotlib and Seaborn to create visualizations of the data. This can help you identify patterns and trends in the data that may not be obvious from just looking at the numbers.

4; Perform analysis: Use pandas functions and other Python libraries to perform various types of analysis on the data. For example, you could calculate summary statistics, find correlations between columns, or group the data by certain criteria.
* Started by examining the distribution of each variable in the dataset. 
* Look for any outliers or unusual observations in the data. 
* Examine the relationships between variables. 
* Checked for any missing or invalid values in the dataset. 
* Identified patterns or trends in the data. I produced four plots: a histogram of IMDB scores, a barplot of top 10 genres, a barplot of top 10 countries by production, and a lineplot of release year trends. 
* Analyzing the distribution of various numerical variables, such as runtime, release year, and IMDb score.
Investigating the relationships between different variables, such as the correlation between runtime and IMDb score.
* Identified the top-rated movies based on IMDb score or popularity.
* Analyzing the most common genres or production countries in the dataset, Creating visualizations to better understand the data.
* CreateD a regression analysis for the most popular movies
* To perform regression analysis, I first split the dataset into training and testing sets. I used 80% of the data for training and 20% for testing.
* I performed linear regression on the dataset, and calculate the mean squared error, mean absolute error, and r-squared values. 
