# Star Wars API Data Analysis

This project involves fetching data from the Star Wars API, cleaning and transforming the data, and storing it in an SQLite database. The data is then analyzed using SQL queries to derive insights about the characters, vehicles, and films from the Star Wars universe.

## Project Structure

The project comprises the following main components:

1. Data Extraction: Data is fetched from the Star Wars API using the `requests` library in Python.
2. Data Cleaning and Transformation: The fetched data is cleaned and transformed using various data manipulation techniques in Python, including Pandas and NumPy.
3. Data Storage: The cleaned data is stored in an SQLite database for efficient querying and analysis.
4. Data Analysis: SQL queries are performed on the stored data to gain insights about various aspects of the Star Wars universe.

## Installation

To run the project, you need to have Python 3.x installed. Additionally, you need to install the following libraries:

- requests
- pandas
- numpy
- sqlite3

You can install the required libraries using pip:

pip install requests pandas numpy

## Usage

The project involves data extraction, cleaning, transformation, and analysis. Make sure you have the necessary data files and libraries installed before running the scripts.

To fetch data from the Star Wars API and store it as JSON, run the `fetch_data.py` script. After fetching the data, run the `clean_data.py` script to clean and transform the data. Finally, run the `analyze_data.sql` script to perform various analyses using SQL queries.



