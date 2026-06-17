# Craigslist Vehicle Listing Analysis

A web scraping and data analysis project examining Toyota Camry listings collected from Craigslist.

## Project Overview

This project collects information from online vehicle listings and converts the results into a structured dataset for analysis. The goal was to examine the relationship between a vehicle’s model year and its listed price while practicing web scraping, data cleaning, and exploratory analysis.

## Data Collected

The dataset includes information such as:

* Listing description
* Location
* Listed price
* Model year

## Methods

* Scraped Craigslist listings using Python and BeautifulSoup
* Parsed listing information into a structured pandas DataFrame
* Reviewed and cleaned missing or inconsistent values
* Used median imputation for missing model-year values
* Visualized the relationship between model year and price
* Calculated Pearson correlation to measure the relationship between the two variables

## Tools and Libraries

* Python
* BeautifulSoup
* pandas
* NumPy
* matplotlib
* SciPy
* Jupyter Notebook

## Repository Contents

* `craigslist_vehicle_listing_analysis.ipynb` — Complete web scraping, data cleaning, visualization, and analysis notebook

## Key Skills Demonstrated

* Web scraping
* Internet data collection
* Data cleaning
* Missing-value handling
* Exploratory data analysis
* Data visualization
* Correlation analysis

## Notes

Craigslist page structures and access restrictions may change over time, so the scraping portion of the notebook may require updates if rerun. Saved outputs in the notebook show the results produced when the project was completed.
