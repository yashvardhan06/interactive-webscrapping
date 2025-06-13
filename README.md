\# Interactive Web Scraper

This is a Python-based interactive web scraping program that allows users to scrape specific data types (headlines or prices) from a website URL they provide. It uses the `requests` and `BeautifulSoup` libraries to extract data and presents it in a user-friendly format.
## Features
- Accepts user input for website URL and data type to scrape (headlines or prices).
- Scrapes headlines from `<h1>` and `<h2>` tags.
- Scrapes prices from elements with the CSS class `price`.
- Displays scraped data in a numbered list.
- Handles errors for invalid URLs, network issues, and unexpected HTTP responses.
- Supports multiple scraping sessions until the user chooses to exit.
## Prerequisites
Make sure you have Python 3 installed. The program requires the following Python libraries:
- `requests`
- `beautifulsoup4`
You can install them via pip:
```bash
pip install requests beautifulsoup4
