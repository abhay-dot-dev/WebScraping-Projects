Here is your updated **README.md** with the **99acres project added in the exact same format**, without changing anything else:

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

## 3️⃣ 99acres Chennai Property Scraper

This project scrapes real estate listings from **99acres.com** focusing on Chennai properties.

### 🔍 What This Project Does

* Uses **Selenium WebDriver** to automate property listing extraction
* Navigates through multiple property listing pages
* Extracts property details including:

  * Property Name
  * Location
  * Price
  * Area (sqft)
  * BHK
* Identifies featured/starred listings
* Cleans and standardizes extracted data using Pandas
* Converts price values (Crore to Lakhs)
* Converts area and BHK into numeric format
* Exports the cleaned dataset into an Excel file

👉 [Open 99acres Scrape Project](./99Acre.ipynb)

---

## 🛠 Technologies Used

* Python
* Selenium
* BeautifulSoup
* Requests
* Pandas
* NumPy

---
