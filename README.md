# Sports Data Collection Using Public APIs

## Project Overview

This project demonstrates sports data collection using a public API. The data was retrieved from TheSportsDB API, processed using Python and Pandas, cleaned to handle missing values and duplicates, and exported into a CSV file for further analysis.

## Objectives

* Connect to a public sports API
* Retrieve sports team data
* Parse JSON responses
* Clean and structure the dataset
* Export data into CSV format
* Demonstrate basic data engineering practices

## API Used

TheSportsDB API

Endpoint:

https://www.thesportsdb.com/api/v1/json/3/search_all_teams.php?l=English%20Premier%20League

## Technologies Used

* Python
* Requests
* Pandas
* Jupyter Notebook
* GitHub

## Data Processing Steps

1. Connected to TheSportsDB API.
2. Retrieved sports team information.
3. Converted JSON response into a Pandas DataFrame.
4. Handled missing values using fillna().
5. Removed duplicate records.
6. Exported the cleaned dataset to CSV.

## Output

Generated file:

sports_teams.csv

Dataset contains:

* Team information
* League information
* Stadium details
* Social media links
* Team images and metadata

## Repository Structure

sports-data-collection/

├── README.md

├── Sports_Data_Collection.ipynb

├── sports_teams.csv

## Conclusion

This project successfully demonstrates the complete workflow of collecting, cleaning, and storing sports data from a public API using Python.
