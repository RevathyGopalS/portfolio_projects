# Web Scraping Amazon Bestselling Books for Rating Analysis

This project scrapes the Amazon Bestselling Books page, extracts details about books, and visualizes the top-rated books with a focus on their ratings and the number of customer reviews.

## Features

- **Web Scraping**: Extracts book titles, authors, ratings, prices, and the number of customer reviews from Amazon's Bestselling Books page.
- **Data Cleaning**: Processes and structures the scraped data, handles missing values, and converts textual ratings into numerical values.
- **Data Filtering**: Filters out books with fewer than 1000 customer ratings and sorts books by their ratings.
- **Visualization**: Creates bar and scatter plots to visualize book ratings and the number of customer reviews.

## Project Setup

### Prerequisites

Ensure the following Python libraries are installed:
- `requests`: For sending HTTP requests.
- `BeautifulSoup`: For parsing HTML pages.
- `pandas`: For data manipulation.
- `matplotlib`: For creating visualizations.

Install the libraries via pip:
```bash
pip install requests beautifulsoup4 pandas matplotlib

