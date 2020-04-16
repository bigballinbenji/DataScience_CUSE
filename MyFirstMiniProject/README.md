# My_First_Mini_Project
 IST 652 Spring 2020 Mini Project

## Data Source
[House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
Predict sales prices and practice feature engineering

## Analysis
Compute the average sale price for houses that have 3 bedrooms and 2 full baths.
What is median sale price of a house for each year?


## Data Exploration and Cleaning Steps
In my initial exploration of the data, I uncovered that the files for training and test had missing values. I started with importing these two into my notebook and then merging them together. Now, the interesting part was to start cleaning. The data cleaning started with identifying what type of data was contained in the entire set. Then, looking at each column to determine what were the amount and percent of data missing. When looking at these values, the threshold I set for removing columns was 80 percent. After this step, I was able to produce summary statistics for each column and conduct unit analysis test that was not displayed in the data.

## Description of program
In my analysis I am using the pandas library to compute some basis statistics. In doing this, I am able to output the type of data that I am working with. I also have to do some cleaning to exclude some observations in my data from being calculated. This does not affect the statistics I am doing before I try to run a regression model. 

## Description of output files

q1.csv goal was to get the mean value of a house with 3 bedrooms and 2 baths

q2.csv goal was to get the median prices of houses across each year


#### Later on I will perform my preprocessing of this data to prepare it for a regression model.
In cleaning the data for my regression, there are values that should be none, because they are truly missing. This means that the observation are not able to be captured. Also there are values that are NA because they are  Leaving these as blanks would affect my predictions, so I choose to impute the columns in the data as the mode. 
