# Project Overview

Supermarkets are big business and they use data on a big scale. Originating in the US in the 1930s, supermarkets have since gradually taken over a bigger and bigger share of the retail and grocery market. Giants like Wal-Mart, Aldi and Carrefour are among the largest retailers in the world with revenues approaching the hundreds of billions. As such many have invested heavily in big data, with analytics and data science forming a core part of their decision making.

The growth of supermarkets in most populated cities are increasing and market competitions are also high. Every product purchased, along with its price, is recorded in gargantuan databases, with tables exceeding hundreds of billions of rows. Loyalty schemes, where customers accumulate points by scanning their loyalty card at each purchase, allow the company to stitch together a customer’s entire history of transactions, gaining more valuable insights.

 

### Dataset


The dataset is one of the historical sales of Supermarket Company which has recorded in 3 different branches for 3 months data. Predictive data analytics methods are easy to apply with this dataset. The following table details the attribute information:


Attribute                                              Description                                  
Invoice id                                      Computer generated sales slip invoice identification number

Branch                                          Branch of supercenter (3 branches are available identified by A, B and C)

City                                            Location of supercenters

Customer type                                   Type of customers, recorded by Members for customers using member card and Normal for without member card

Gender                                          Gender type of customer

Product line                                    General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and                                                             beauty, Home and lifestyle, Sports and travel

Unit price                                       Price of each product in $

Quantity                                         Number of products purchased by customer

Tax                                              5% tax fee for customer buying

Total                                            Total price including tax

Date                                              Date of purchase (Record available from January 2019 to March 2019)

Time                                              Purchase time (10am to 9pm)

Payment                                           Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

COGS                                              Cost of goods sold

Gross margin percentage                           Gross margin percentage

Gross income                                      Gross income

Rating                                            Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)


### Objective


Project teams need to explore & visualize the data to generate insights about supermarket sales transactions of customers and also obtain inference about customer ratings.

### Methodology

The methodology should include the following operations of Exploratory Data Analysis & Clustering Analysis:

a.     Import the dataset

b.     Perform Univariate analysis to address the following queries:

· Question 1: What does the customer rating look like and is it skewed?(Use normal distribution plot)

· Question 2: Is there any difference in aggregate sales across branches?(Use bar graph)

· Question 3: Which is the most popular payment method used by customers?(Use bar graph)

 

c.      Perform Bi-variate analysis to address the following queries:

· Question 4: Does gross income affect the ratings that the customers provide?(Use scatterplot)

· Question 5: Which branch is the most profitable?(Use Boxplot)

· Question 6: Is there any relationship between Gender and Gross income?(Use Boxplot)

· Question 7: Is there any time trend in gross income? (Use line graph)

· Question 8: Which product line generates most income?(Use Bar plot)

 

d.     Prepare pairwise plot (scatterplot matrix) to visualize all the bi-variate relationships in the data.

e.      Perform correlation analysis using heatmap.

f.       Perform additional analysis to address the following queries:

· Question 9: What is the spending pattern of females and males and in which category do they spend a lot?(Use countplot in Seaborn Python package)

·  Question 10: How many products are bought by customers?(Use distribution plot)

· Question 11: Which day of the week has maximum sales?(Use countplot)

· Question 12: Which hour of the day is the busiest?(Use line plot)

· Question 13: Which product line should the supermarket focus on?(Use bar plot)


· Question 14: Which city should be chosen for expansion and which products should it focus on?(Use bar plot)


Use the dataset supermarket_sales.csv for the Project.
