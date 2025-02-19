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
