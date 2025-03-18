
# Web Scraping Project - Quotes Scraper

## Overview
This project is a simple web scraper that extracts quotes and their authors from [Quotes to Scrape](http://quotes.toscrape.com) using Python. The extracted data is stored in a CSV file.

## Features
- Extracts quotes and their corresponding authors from the website.
- Parses HTML content using BeautifulSoup.
- Stores the extracted data in a CSV file.
- Simple and beginner-friendly implementation.

## Technologies Used
- Python
- Requests
- BeautifulSoup4
- Pandas

## Installation
### Prerequisites
Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).



### Step 2: Install Required Libraries
Run the following command to install the required dependencies:
```bash
pip install requests beautifulsoup4 pandas
```

## Usage
1. Navigate to the project directory.
2. Run the Python script:
```bash
python scraper.py

```
- Sends an HTTP request to the website and retrieves the HTML content.
- Parses the HTML using BeautifulSoup to extract quotes and authors.
- Stores the data in a structured format using Pandas.
- Saves the extracted data in `quotes.csv`.

## Example Output (quotes.csv)
| Quote | Author |
|---------------------------|----------------|
| "The greatest glory in living lies not in never falling, but in rising every time we fall." | Nelson Mandela |
| "The way to get started is to quit talking and begin doing." | Walt Disney |
| "Life is what happens when you're busy making other plans." | John Lennon |




