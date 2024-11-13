# Amazon Product Data Scraper

This project is a Python-based web scraper that extracts information from Amazon product pages. It uses the `requests` and `Beautiful Soup` libraries to fetch and parse HTML content, extracting data such as product title, price, ratings, number of reviews, and availability.

## How it Works

1. **Import Libraries:**
   - Import necessary libraries: `requests`, `BeautifulSoup`, `time`, `datetime`, and `pandas`.

2. **Define Extraction Functions:**
   - Define functions (`get_title`, `get_price`, etc.) to extract specific product information from a BeautifulSoup object using HTML tags and attributes.

3. **Fetch Product Data:**
   - Set up URL and headers for the request to an Amazon product page.
   - Fetch webpage content using `requests.get`.
   - Create a BeautifulSoup object to parse the content using the `lxml` parser.

4. **Extract and Display Data:**
   - Call extraction functions to extract the desired information from the BeautifulSoup object.
   - Print the extracted data to the console.

5. **Scrape Multiple Products (Optional):**
   - Define header for scraper identification.
   - Fetch product links from an Amazon search results page.
   - Iterate through links, fetch product pages, and extract data using extraction functions.
   - Print extracted data for each product to the console.

## Usage

1. **Install Dependencies:**
   - Make sure you have `requests` and `Beautiful Soup` installed:
  
 2. **Run the Code:**
   - Execute the Python script in your Colab environment.

## Output

The script will print the extracted product data to the console. You can modify the code to store the data in a structured format like CSV or Excel for further analysis.

## Disclaimer

This project is for educational purposes only. Web scraping may be subject to terms of service restrictions on websites like Amazon. Please use this code responsibly and respect website policies.
