Got it 👍 — only the **scraping projects**, no data analysis details.

Here is your cleaned and updated **README.md**:

---

# 🕷 Web Scraping Projects

This repository contains web scraping projects built using Python and Selenium to extract structured data from real-world websites.

---

## 📌 Projects

---

## 1️⃣ Nykaa Scraper

This project automates data extraction from **Nykaa.com** based on the search query *"korean skin care"*.

### 🔍 What This Project Does

* Uses **Selenium WebDriver** to automate browser interaction
* Searches for products using a keyword
* Extracts product details including:

  * Product Name
  * Price
  * Review Count
* Handles dynamic content loading using the **"Load More"** button
* Collects data across multiple product listings
* Stores the scraped data into a structured CSV file

👉 [Open Nykaa Scrape Project](./Nykaa_Scrape)

---

## 2️⃣ Yahoo Finance Scraper

This project scrapes stock market data from **Yahoo Finance – Most Active Stocks** section.

### 🔍 What This Project Does

* Uses **Selenium with explicit waits** to handle dynamic pages
* Navigates through Yahoo Finance stock sections automatically
* Extracts stock information including:

  * Stock Symbol
  * Company Name
  * Current Price
  * Price Change
  * Trading Volume
  * Market Capitalization
  * P/E Ratio
* Handles pagination to scrape data from multiple pages
* Cleans and formats extracted data
* Exports the final dataset into a CSV file

👉 [Open Yahoo Scrape Project](./Yahoo_Scrape)

---

## 🛠 Technologies Used

* Python
* Selenium
* BeautifulSoup
* Requests
* Pandas
* NumPy

---