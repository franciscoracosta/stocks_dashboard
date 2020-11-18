# stocks_dashboard
Vizualization tool for stocks with predictions


## Project

This projects aims to create a Tableau Dashboard to visualize stocks, cryptocurrencies and forex data for investors. There will be different data sources and the objective is to create a fully working platform that extracts the data and loads into Tableau.

# Steps
1. ETL job (extract from yFinance/Alpha Vantage, data cleaning and prepared for modelling, load in a bucket)
2.	Training Pipeline job 
3.	Model Deployment on GCP/Azure
4.	Predictions Pipeline job and results placed in a bucket
5.	Power BI Dashboard with 
  -	Data from bucket (financial historical data + predictions)
  -	API to get news related to ticked companies
  -	Python Script to get data from Currencies (Currency @ RapidAPI
6. Schedule Pipelines with Airflow
7. Fetch news with Kafka


## Data Sources
Stocks, Cryptocurrencies and Forex
Financial News

## Dashboard Features
. Graph with historical data + predictions
- Select with ticks the companies we want to see
- Select the Time Range
- Top 5 Stocks
- Panel with latest news (title + description + link) for each companie
- Panel with currency conversion with the daily rate (calculated in RT)
- Panel with detailed information for a selected companie.
- Others..
