# Web Scraping on Amazon - Tim Horton's Coffee

- Built a Python-based web scraper to extract Amazon product details, including titles, prices, and timestamps.

- Used Beautiful Soup and Requests libraries to fetch and parse HTML content from static product pages.

- Identified specific HTML elements (id="product-title" and id="price-block_ourprice") to extract key product data.

- Cleaned and formatted scraped data by removing whitespace and special characters for usability.

- Created a CSV file to store product details, including headers for Title, Price, and Date.

- Automated data collection with a while loop and time.sleep() to append new data entries at regular intervals.

- Included an optional email alert feature using smtplib to notify users of price drops below a set threshold.

- Validated and structured the data for downstream analysis, enabling time-series tracking of price changes.

- Designed the script to run continuously in the background for long-term data collection.

- Highlighted the project as an introduction to web scraping, with potential for scaling to scrape multiple pages or complex datasets.
