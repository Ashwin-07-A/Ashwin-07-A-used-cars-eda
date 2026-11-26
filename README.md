# Exploratory Data Analysis on a Used Cars Dataset

Minor Project 1 | EDA | AIML Batch (November Batch)
Name: Ashwin Ananth

## About
Cleaning and exploring a US used-car listings dataset to find patterns in car prices, with charts and insights.

## Dataset
Used car listings (vehicles.csv), 295,451 rows and 41 columns.
https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data
(The CSV is not included here because of its size. Download it from Kaggle to re-run the notebook.)

## What I did
- Kept 14 columns and cleaned the data from 295,451 to 182,894 rows
- Removed 82,184 duplicates, rows with missing key values, prices below $500 or above $150,000, years before 1995 and odometer above 500,000 miles
- Created 8 charts: price distribution, fuel type, top manufacturers, age vs price, odometer vs price, price by transmission, correlation heatmap and price box plot

## Key findings
- Prices are right-skewed: mean $16,537 vs median $11,995
- Mileage has the strongest link with price (correlation -0.52), followed by car age (-0.45)
- Gas cars make up about 86.9% of listings and automatic cars about 93.3%
- Ford, Chevrolet and Toyota are the most listed manufacturers (about 38% of all listings)

## Files
- Minor_Project_1_-_EDA_Report.ipynb: the full notebook
- EDA_Report_Ashwin_A_1.pdf: the report
