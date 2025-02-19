# selenium_project
# Egyptian Premier League Standings Scraper

A Selenium-based web scraper to extract and process the 2023-2024 Egyptian Premier League standings from [jdwel.com](https://jdwel.com/).

## Features
- Scrapes team names, positions, wins, draws, losses, goals for/against, and points.
- Handles data cleaning (e.g., removing penalties from points).
- Saves data to a CSV file.
- Processes data using pandas for analysis.

## Installation
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install selenium webdriver_manager pandas

## Usage
1.Run the Jupyter notebook selenium_project.ipynb.

2.The script will:

-Automatically download ChromeDriver.
   
-Scrape data from the target URL.
   
-Save results to egyptian-premier-league.csv.

-Generate a cleaned DataFrame with a year column.

## Data Source
Scraped from: 2023-2024 Egyptian Premier League Standings

## Notes
The CSV is saved to D:\projects\ by default (modify the path in the notebook if needed).

The scraper assumes the website structure remains consistent. Updates to the site may break the script.
