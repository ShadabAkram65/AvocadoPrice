# Exploratory Data Analysis (EDA) on Avocado Sales

This project involves performing an exploratory data analysis (EDA) on a dataset containing historical data on avocado prices and sales volume in multiple US markets.

## Project Description

The goal of this project is to understand the factors influencing avocado prices and sales volume. The dataset includes information such as the date of observation, average price, type of avocado (conventional or organic), total volume of avocados sold, sales volume of small, large, and extra large avocados, total bags sold, and the region of the observation.

## Dataset Resource
[Avocado Prices Dataset on Kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices)


## Key Questions

Some of the key questions that this project aims to answer are:
Q1: How has the 'AveragePrice' changed over time (Date)?<br>
Q2: What is the correlation between 'TotalVolume' and 'AveragePrice'?<br>
Q3: How does the 'AveragePrice' vary by 'Type' of avocado?<br>
Q4: How does the 'AveragePrice' vary across different 'Regions'?<br>
Q5: How has the sales volume ('TotalVolume') changed year over year ('Year')?<br>
Q6: Are there any seasonal trends in avocado prices or sales volume?<br>

## Methodology

The EDA process in this project involves the following steps:
- **Data Cleaning**: Checking for missing or null values, handling outliers, and ensuring data types are correct.
- **Data Visualization**: Creating plots using plotly to understand the distribution of variables, trends over time, and relationships between variables.

## Conclusion

1. **Seasonal Price Variation**: The average price of avocados is higher in the second half of the year than the first half.

2. **Correlation between Volume and Price**: There is a medium negative correlation between 'TotalVolume' and 'AveragePrice'. This suggests that as the total volume of avocados sold increases, the average price decreases. However, because the correlation is medium, there may be other factors influencing the relationship between 'TotalVolume' and 'AveragePrice'.

3. **Price Difference between Conventional and Organic Avocados**: The average price for conventional avocados is 1.158040, while the average price for organic avocados is 1.649377. This suggests that on average, organic avocados are priced higher than conventional avocados. This is generally expected as organic farming practices are often more costly due to stricter regulations and lower yields.

4. **Regional Price Variation**: The average price varies significantly across regions. For instance, HartfordSpringfield and SanFrancisco have the highest average prices, while DallasFtWorth and Houston have the lowest.

5. **Sales Trend**: There is a decline in avocado sales, and this decline began in 2017.

6. **Seasonal Sales Variation**: From the average price data, it appears that prices are highest in October and lowest in February. This could suggest a seasonal trend where avocado prices increase in the autumn and decrease in the winter. Sales are highest in February and lowest in November and October, which is expected because the correlation between price and sales volume is inverse.
