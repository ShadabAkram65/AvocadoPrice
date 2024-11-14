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

## Conclusions
* It is noted that the average price of the avocados is higher in the second half of the year than the fist half.
* The correlation is medium negative correlation between 'TotalVolume' and 'AveragePrice'.
  * Because the correlation is medium, so may be other factors at play influencing the relationship between 'TotalVolume' and 'AveragePrice'.
* The average price for the conventional avocados is 1.158445.
* The average price varies significantly across regions. For instance, HartfordSpringfield and SanFrancisco have the highest average prices, while
  Houston and PhoenixTucson have the lowest.
* There is a rise in avocado sales, and this rise began in 2017.
* From the average price data, it appears that prices are highest in October and lowest in February. This could suggest a seasonal trend where avocado prices increase in the autumn and decrease in the winter.While sales are highest in February and lowest in November and October, this is expected because the correlation between them is inverse.

