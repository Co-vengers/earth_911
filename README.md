# Earth911 Electronics Recycling Data Scraper

This project scrapes electronics recycling center data from Earth911 for New York, NY, and saves it to a CSV file.

## Features
- Scrapes business name, last update time, address, and materials accepted for each recycling center.
- Handles multiple pages of search results.
- Cleans and formats the extracted data.
- Outputs results to `earth911_recycling_data.csv`.

## Requirements
- Python 3.x
- Required packages:
  - requests
  - beautifulsoup4
  - lxml

Install dependencies with:
```bash
pip install requests beautifulsoup4 lxml
```

## Usage
1. Open the `earth911.ipynb` notebook and run the code cell, or run the script as a Python file if you convert it to `.py`.
2. The script will fetch data from Earth911 and write it to `earth911_recycling_data.csv` in the same directory.

## Notes
- The script is configured to scrape the first 20 pages of search results for electronics recycling in New York, NY (postal code 10001).
- The script uses a custom User-Agent header to avoid being blocked by the website.
- Data fields collected:
  - Business Name
  - Last Update Time
  - Address
  - Materials Accepted


