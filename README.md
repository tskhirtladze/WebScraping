# Web Scraping and Data Analysis

This script demonstrates how to scrape data from a webpage, process it, and visualize it using Python. Specifically, it extracts population and wedding statistics from the website Geostat.ge, processes the data into a DataFrame, and creates visualizations.

## Overview

The script performs the following tasks:

### 1. Fetch HTML Content
- Retrieves the HTML content of the Geostat.ge homepage.

### 2. Extract Links and Data
- Extracts links, headings, and statistics from the homepage.

### 3. Fetch Detailed Data
- Retrieves and parses additional data from the provided links.

### 4. Data Cleaning and Processing
- Cleans and processes the data, including handling Georgian text and converting values.

### 5. Visualization
- Generates line and bar plots to visualize population and wedding statistics over the years.

## Requirements

Ensure you have the following Python packages installed:
- **requests**
- **beautifulsoup4**
- **pandas**
- **matplotlib**

You can install these packages using pip if they are not already installed:

```bash
pip install requests beautifulsoup4 pandas matplotlib

## Notes

The script assumes that the webpage structure and the table format remain consistent. If the structure changes, adjustments to the parsing logic may be required.

Georgian characters are handled specifically to ensure that text extraction and processing are accurate.
