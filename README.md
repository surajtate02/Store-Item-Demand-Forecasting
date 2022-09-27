# Store-Item-Demand-Forecasting
Building a forecasting model to estimate store item demand is difficult due to numerous external factors such as the store’s location, seasonality, changes in the store’s neighborhood or competitive position, a considerable variance in the number of consumers and goods, and so on. With such a large volume of data, no human planner could possibly examine all of the possible elements. Deep learning, on the other hand, makes it easier by taking these characteristics into account at a finer level, by individual store or fulfillment channel.


# Dataset Description
1)You are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores

2)The objective of this competition is to predict 3 months of item-level sales data at different store locations.


#File descriptions
train.csv - Training data
test.csv - Test data (Note: the Public/Private split is time based)
sample_submission.csv - a sample submission file in the correct format

#Data fields
date - Date of the sale data. There are no holiday effects or store closures.
store - Store ID
item - Item ID
sales - Number of items sold at a particular store on a particular date.
