# 🕷 Web Scraping Projects

This repository contains real-world web scraping projects built using Python and Selenium to extract structured data from dynamic websites.

Each project demonstrates:
- Browser automation
- Handling dynamic content
- Data cleaning and transformation
- Structured data export

---

# 📌 Projects

---

## 1️⃣ Nykaa Scraper

Automates product data extraction from **Nykaa.com** using the search query *"korean skin care"*.

### 🔍 Features

- Uses Selenium WebDriver for automation
- Searches products using a keyword
- Extracts:
  - Product Name
  - Price
  - Review Count
- Handles dynamic content using the **"Load More"** button
- Exports data into CSV format

👉 `./Nykaa_Scrape`

---

## 2️⃣ Yahoo Finance Scraper

Scrapes stock data from **Yahoo Finance – Most Active Stocks** section.

### 🔍 Features

- Uses Selenium with explicit waits
- Handles dynamic page loading
- Extracts:
  - Stock Symbol
  - Company Name
  - Current Price
  - Price Change
  - Trading Volume
  - Market Capitalization
  - P/E Ratio
- Handles pagination
- Cleans and formats data
- Exports structured CSV file

👉 `./Yahoo_Scrape`

---

## 3️⃣ 99acres Chennai Property Scraper 🏠

This project scrapes real estate listings from **99acres.com** (Chennai properties).

### 🔍 What This Project Does

- Uses Selenium to:
  - Navigate listing pages
  - Handle pagination
  - Extract property cards dynamically

- Extracts:
  - Property Name
  - Location
  - Price
  - Area (sqft)
  - BHK
  - Starred listing indicator

---

### 🧹 Data Cleaning & Feature Engineering

After scraping, the dataset is processed using Pandas:

- Removed duplicates
- Trimmed and standardized text (lowercase, strip spaces)
- Extracted numeric price values:
  - Converted Crore → Lakhs
- Converted:
  - Area → numeric sqft
  - BHK → numeric
- Removed unnecessary text like:
  - "chennai"
  - commas
  - special characters
- Created new feature:
  - `is_starred` (1 if featured listing, else 0)

---

### 📊 Final Output

The cleaned dataset is exported to:
