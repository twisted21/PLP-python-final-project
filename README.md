# PLP-python-final-project

This project analyzes COVID-19 data from a dataset named covid_data.csv. The analysis includes loading, cleaning, summarizing, and exploring trends in COVID-19 cases by country.

Dataset
The dataset used is covid_data.csv, which contains the following key information:

date: The date of the record

location: Country or region name

new_cases: Number of new confirmed cases reported that day

total_cases: Cumulative confirmed cases up to that date

Requirements
To run the script, ensure the following are installed:

Python 3.x

pandas (Python library for data analysis)

Install pandas using:

pip install pandas

Project Overview
Load Dataset

Reads covid_data.csv using pandas

Inspect Data

Displays the first few rows (head)

Shows column types and names

Identifies columns with the most missing values

Clean Data

Removes rows with missing values in new_cases and total_cases to ensure accuracy

Summary Statistics

Generates statistics (mean, median, min, max) for numerical columns

Grouped Analysis

Groups data by location and calculates average new_cases per country

Sorts results in descending order to identify countries with the highest average daily cases
