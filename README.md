# scrapping-challange

## Part 1: Mars News
This Python script scrapes the latest Mars news using `splinter` and `BeautifulSoup` libraries for parsing the HTML content. It's designed to extract news titles and their previews from a static web page.

## Overview
The script preforms various functions:
  - **Step 1:** Visit the Mars news website using `splinter`.
  - **Step 2:** Create a `BeautifulSoup` object and parse the webpage to find news elements.
  - **Step 3:** Extract titles and previews, store them in dictionaries, and collect all dictionaries in a list.

## Prerequisites
Ensure you have the following installed:
- Splinter
- BeautifulSoup4

You can install the necessary libraries using pip:
```bash
pip install splinter beautifulsoup4
```

## Execution 
**1. Import Dependencies**
- from splinter import Browser
- from bs4 import BeautifulSoup

**2. Execute the Python script**

**3. The script will:**
- Launch a Chrome browser window.
- Navigate to the Mars news website.
- Scrape the news titles and previews.
- Print each item as a dictionary in a list.
- Close the Browser.

**4.View Results**

## Stopping the Script
The script will automatically close the browser once it has completed scraping. 

# Part 2: Mars Weather

This script automates the browsing and scraping of Martian temperature data from a specified URL. It uses Python's `splinter` and `BeautifulSoup` libraries for web scraping, `pandas` for data analysis, and `matplotlib` for plotting. The script extracts temperature and pressure data by month and day. After some data manipulations, it provides insights such as average temperatures, pressure variations, and the duration of a Martian year in terrestrial days. Finally, the script saves the resulted data into .csv format in current working directory (cwd).

## Prerequisites

Before running this script, ensure you have the following installed:
- pandas
- matplotlib
- splinter
- BeautifulSoup4

You can install the necessary libraries using pip:
```bash
pip install pandas matplotlib splinter beautifulsoup4
```
## Overview

- **Automated Web Scraping**: Visit the Mars website using `splinter`.
- **Data Extraction with BeautifulSoup**: Parses HTML to retrieve temperature data.
- **Data Analysis with pandas**: Manipulates and analyzes data to extract meaningful statistics like average temperature and pressure.
- **Visualization with matplotlib**: Plots data to provide visual insights into Martian temperatures and pressures.
- **Data Export**: Outputs processed data to a CSV file for further use in current working directory.

## Execution 
**1. Import Dependencies**
- from splinter import Browser
- from bs4 import BeautifulSoup
- import matplotlib.pyplot as plt
- import pandas as pd

**2. Execute the Python script**

**3. The script will:**
- Open the Web Browser
- Navigate to the Specified URL
- Scrape the Data
- Process and Analize the Data
- Visualize the Data
- Export the Data
- Close the Browser

**4.View Results**:
- Check the resulted graphs.
- Visit cwd to ensure exisitance of .csv file.

## Stopping the Script
The script will automatically close the browser once it has completed scraping, analyzes and saving data to .csv file. 

