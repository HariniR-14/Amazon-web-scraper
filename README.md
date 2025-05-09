# Amazon Web Scraper

This project is an Amazon web scraper built with Python to extract product information from Amazon product pages. The scraper collects details such as product name, price, rating, and reviews to help with data analysis and decision-making.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Amazon Web Scraper allows you to scrape product details from Amazon by specifying a product URL. The data is then extracted and stored in a structured format, such as a CSV file, for further analysis.

## Features
- Scrapes product name, price, rating, and number of reviews.
- Supports scraping data for multiple products using URLs.
- Saves the extracted data to a CSV file for easy access.
- Handles basic error handling (e.g., missing product details).

## Technologies Used
- **Python**: For scripting the web scraper.
- **BeautifulSoup**: For parsing HTML content.
- **Requests**: For sending HTTP requests to the Amazon page.
- **Pandas**: For storing the extracted data and saving it to CSV.
- **Jupyter Notebook**: For demonstrating and running the scraper interactively.

## Installation

To get started with this project, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/HariniR-14/Amazon-web-scraper.git
    cd Amazon-web-scraper
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

   The `requirements.txt` file includes the necessary libraries such as `beautifulsoup4`, `requests`, and `pandas`.

## Usage

To use the Amazon web scraper, follow these steps:

1. Open the `Amazon web scraping.ipynb` file in Jupyter Notebook.
2. Update the product URL(s) in the notebook to the product page you wish to scrape.
3. Run the cells in the notebook to start scraping.
4. The data will be saved as a CSV file (`amazon_products.csv`) in the working directory.

### Example:
```python
# Example of scraping a product page URL
url = 'https://www.amazon.com/dp/B08N5M7S6K'
scrape_amazon(url)

