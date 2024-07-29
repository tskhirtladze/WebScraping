# WebScraping and Data Analysis
This script demonstrates how to scrape data from a webpage, process it, and visualize it using Python. Specifically, it extracts population and wedding statistics from the website Geostat.ge, processes the data into a DataFrame, and creates visualizations.

Overview

The script performs the following tasks:


Fetch HTML Content:
 
Retrieve the HTML content of the Geostat.ge homepage.


Extract Links and Data:

Extract links, headings, and statistics from the homepage.


Fetch Detailed Data:

Retrieve and parse additional data from the provided links.


Data Cleaning and Processing:

Clean and process the data, including handling Georgian text and converting values.


Visualization:

Generate line and bar plots to visualize population and wedding statistics over the years.


Requirements

Ensure you have the following Python packages installed:

requests

beautifulsoup4

pandas

matplotlib

You can install these packages using pip if they are not already installed:

pip install requests beautifulsoup4 pandas matplotlib



Notes

The script assumes that the webpage structure and the table format remain consistent. If the structure changes, adjustments to the parsing logic may be required.

Georgian characters are handled specifically to ensure that text extraction and processing are accurate.
