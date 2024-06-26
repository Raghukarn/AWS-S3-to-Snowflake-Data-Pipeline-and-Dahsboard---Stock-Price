![Architecture](https://github.com/Raghukarn/AWS-S3-to-Snowflake-Data-Pipeline-and-Dahsboard---Stock-Price/assets/119719960/1254dbbd-012d-4723-841b-de20bd6b5c24)


# AWS-S3-to-Snowflake-Data-Pipeline-and-Dahsboard---Stock-Price

## Project Goal:
Create a data pipeline that integrates and processes stock price data from AWS S3 to Snowflake, automates data loading using Snowpipe and SQS, and enables stock price forecasting and visualization in Power BI.

## Problem Statement: 
The challenge is to establish a robust data pipeline for stock price forecasting, integrating data from AWS S3 into Snowflake efficiently. Additionally, there is a need to automate the data loading process and provide visualization capabilities for analyzing stock price patterns and forecasting future prices.

## Solution:
- Integration Objects in Snowflake: Create integration objects in Snowflake to facilitate easy data fetching from AWS S3 and secure storage of credentials.
- Snowpipe Setup with SQS: Configure Snowpipe with AWS SQS to automatically load data from S3 into Snowflake once it becomes available. Set up event notifications in S3 to trigger Snowpipe for seamless data ingestion.
- Power BI Visualization: Utilize Power BI for data analysis and visualization, establishing a direct connection to Snowflake. Develop visualizations to depict stock price patterns over time and forecast future prices using time series analysis.
- Skills Used: Employ Amazon S3 for data storage, Snowflake for data warehousing and transformation, and Power BI for data analysis and visualization.


![StockPrice Overall](https://github.com/Raghukarn/AWS-S3-to-Snowflake-Data-Pipeline-and-Dahsboard---Stock-Price/assets/119719960/6f738d40-3c65-4e5a-8c60-ab62cda05396)


![Avg StockPrice Forecast](https://github.com/Raghukarn/AWS-S3-to-Snowflake-Data-Pipeline-and-Dahsboard---Stock-Price/assets/119719960/07cc48bf-02b0-4d1d-a39e-7fb0af70908e)
