# Capstone Project

## [00-data](https://github.com/typaint/capstone/tree/main/00-data) 
### [gdelt-data]()
- contains the raw data files from the [GDELT Database]()
### [stock-data]() 
- contains historical stock information for the S&P 500 from [Yahoo]()

## [10-data_wrangling]()
### clean_data
- reads in the raw monthly GDELT files and removes bad rows 
### load_data_accre
- compiles data between two date ranges from GDELT

## [20-eda]()
### count_eda
- produces website, keyword, topic counts in an output file for a specified (monthly) dataset
### example-data 
- initial EDA, removes columns and converts time stamps

## [30-web_scraping]()
### [gdelt_websites]
- contains Jupyter Notebooks with templates for specified websites to scrape article contents from a URL
### sp500_history
- produces a table containing the [S&P 500 company transaction history](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies) 
### stock_scraping
- scrapes the historical price data for each company in the S&P 500 index

## [documents]()
- contains any relevant course deliverables

### [updates]()
- contains any relevant information for update meetings
