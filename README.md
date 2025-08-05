# task3-web-scraper
# News Headlines Web Scraper

## Objective
A simple Python script to scrape top news headlines from a website and save them into a text file.

## Tools Used
- Python
- requests
- BeautifulSoup4

## How It Works
1. Fetches the HTML content of the news website using `requests`.
2. Parses the HTML to find all `<h2>` tags (or change based on site structure).
3. Extracts and cleans headline text.
4. Saves all headlines into a `headlines.txt` file.

## Usage
1. Install required libraries:
   ```bash
   pip install requests beautifulsoup4
python news_scraper.py
