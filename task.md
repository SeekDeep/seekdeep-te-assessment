# Technical Task: Web Scraping for Product Data

## Objective
Develop a Python-based web scraping script to collect and store product page HTML from a store website. The goal is to scrape at least 500 unique product URLs and save their HTML files in a local directory. The scraped HTML content will be used to extract product information, and our main mission is to get as many products from the website as possible.

https://zoommer.ge/

## Requirements

### 1. Scraping Process
- The script should visit each product URL and download the entire HTML page.
- Ensure that each URL is unique and not duplicated in the scraping process.
- Implement basic error handling to retry or skip failed requests.

### 2. URL Collection
- Identify and extract product URLs from the store website.
- The script should be able to crawl category pages or a sitemap if available.
- Store collected URLs in a structured format (e.g., JSON, CSV, or a database).

### 3. Storage
- Save the raw HTML content of each page into a local directory.
- Each file should be named uniquely (e.g., based on product ID or URL hash).
- Maintain a log of successfully scraped URLs and any errors encountered.

### 4. Performance Optimization
- Use asynchronous or multi-threaded requests to speed up scraping.
- Implement request delays or respect robots.txt to avoid IP bans.

### 5. Technology Stack
- Python (Requests, BeautifulSoup, Scrapy, or Selenium as needed).
- JSON/CSV for URL storage.
- Local file system for HTML storage.

## Deliverables
- A working Python script that scrapes and stores at least 500 unique product pages.
- A log file containing processed URLs and errors.
- A directory with saved HTML files.
- A brief README explaining how to run the script.
