# Movie Industry Correlation Project

This project consists of finding correlations using movie industry data from [kaggle.com](https://www.kaggle.com/danielgrijalvas/movies). I wanted to explore is if there is a high correlation between a movie's gross revenue and their budget.

![](https://github.com/darienlizano/movies/blob/main/Graphs/budget_gross_reg.png)

## Python Version and Packages
Python Version: Python 3.8 
Packages Used: pandas, numpy, matplotlib, seaborn, sklearn

## Cleaning Data 
It was important to convert the budget and gross variables from float64 data types into integer data types for my analysis. I also created a corrected year column derived from the released column as a string data type. 

## Exploratory Data Analysis 
I performed exploratory data analysis including regression plots, correlation plots, strip plots, and scatterplots. Below are a few highlights of my visualizations.

## Findings
Gross and Budget had the highest correlation (pearson score of 0.71). Paramount Pictures production company has the highest gross in comparison to all other companies. Movies rated PG-13 earned more gross revenue than any other ratings.

