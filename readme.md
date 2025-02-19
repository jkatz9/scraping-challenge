# Mars Weather and News Scraping Project

## Description

This project involves scraping Mars weather data and news articles using Python libraries such as BeautifulSoup, Splinter, Pandas, and Matplotlib. The project is divided into two parts:

1. Scraping Titles and Preview Text from Mars News
2. Scraping and Analyzing Mars Weather Data

## Table of Contents

- [Mars Weather and News Scraping Project](#mars-weather-and-news-scraping-project)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Part 1: Scraping Titles and Preview Text from Mars News](#part-1-scraping-titles-and-preview-text-from-mars-news)
    - [Part 2: Scrape and Analyze Mars Weather Data](#part-2-scrape-and-analyze-mars-weather-data)
  - [Project Structure](#project-structure)

## Installation

Make sure you have the following libraries installed:

- beautifulsoup4==4.13.3
- matplotlib==3.10.0
- pandas==2.2.3
- splinter==0.21.0

You can install these dependencies using the following command:

```sh
pip install -r requirements.txt
```

## Usage

### Part 1: Scraping Titles and Preview Text from Mars News
1. Visit the Website: Use automated browsing to visit the Mars news site.
2. Scrape the Website: Create a BeautifulSoup object and use it to extract text elements from the website.
3. Store the Results: Extract the titles and preview text of the news articles and store them in a Python list of dictionaries. Save the results to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data
1. Visit the Website: Use automated browsing to visit the Mars Temperature Data Site.
2. Scrape the Table: Create a BeautifulSoup object and use it to scrape the data in the HTML table.
3. Store the Data: Assemble the scraped data into a Pandas DataFrame.
4. Prepare Data for Analysis: Cast the data to the appropriate datetime, int, or float data types.
5. Analyze the Data: Use Pandas functions to answer questions about the dataset.
6. Save the Data: Export the DataFrame to a CSV file.

## Project Structure

```plaintext
scraping-challenge/
├── part_1_mars_news.ipynb
├── part_2_mars_weather.ipynb
├── requirements.txt
├── mars_news.json
├── mars_data.csv
└── README.md
```
