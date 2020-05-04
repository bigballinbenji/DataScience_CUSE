# My_Second_Mini_Project
 IST 652 Spring 2020 Mini Project 2

## Data Source
[Amazon Cellphone Reviews](https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews)
Create a sentiment analysis of product review.

## Analysis
Analyze the data and create questions that help you to explore the data even more.

## Data Exploration and Cleaning Steps
In my initial exploration of the data, I uncovered that the files the missing values was concentrated for in the reviews helpfulVotes column. For my analyis, this column is not useful, so I did not have to do any cleaning there. Also, I had data information in my data, so I changed to format to datetime, and used the cleaned-up information to make some plots. 

To last clean up involved making sure I get my data into a format where I can I begin sentiment analysis. Using two packages nltk and scipy I was able to process reviews from Amazon products and learn what features are good and bad for a cell phone. The steps that I conducted included removing stopwords, making all the words lower case, and tokenizing the data points. 

## Description of program

### Question 1. What are features of the product are consumers discussing for each amazon product review?

In the first part of this sentiment analysis I wanted to look at nouns in the product reviews. This is necessary beacuse I care to know what features people discuss and compare them to the ratings in the dataset, thus understanding opinions about a certain feature of a product.

### Question 2. How many reviews do consumers give by month and year?

In this part of the data I was able to use find out the products reviewed by month and by year. I plotted this infromation using matplotlib. My results yielded that around the major holidays like black Friday and Christmas customers wrote more reviews for products. For my yearly data, the reviews increase year over year.

### Question 3. What are the best products and their respective brand?

In this analysis I combined two data frames based on the unique product serial number. The tables that were joined was the product rating and item information. The combination of this join with sorting by the mean gave me an average product rating. From this data frame you can look at what products were rated (rating_x) the best and how many people reviewed the product. You can also see the price information for each product and the brand.

## Description of output files

q1.csv goal was to get aspect-based sentiments for each product review.

totalMonthsReview.pdf displays how many reviews are in the dataset by month
totalYearReview.pdf displays how many reviews are in the dataset by year

q3.csv goal was to get the median prices of houses across each year
