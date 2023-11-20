# Webpage Reviews Scraper

This Python script uses Selenium to scrape reviews from a list of URLs and compiles the data into a dataset. The dataset includes information such as title, reviews, date, rating, and names.

## How It Works

1. **Provide URLs:**
   - Create a CSV file (`Property_Names_Links.csv`) with columns including property names and their corresponding URLs.

2. **Run the Script:**
   - Execute the `main_scraper.py` script to scrape reviews from the provided URLs.

3. **Collected Data:**
   - The script will collect data such as title, reviews, date, rating, and names and store it in memory.

4. **Save to CSV:**
   - The script will save the collected data to a CSV file (`reviews_dataset.csv`).

## Prerequisites

- Ensure you have Python installed.
- Install required packages using:

```bash
pip install selenium
