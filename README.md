# Web Scraping Pipeline for Eyewear Product Data

## Overview
This project implements a web scraping pipeline to extract product data from e-commerce platforms and transform it into structured datasets for analysis.

The pipeline targets:
- Glasses
- FramesDirect
- GlassesUSA

## Objectives
- Extract product data from dynamic web pages
- Handle JavaScript-rendered content using Selenium
- Parse and structure data using BeautifulSoup
- Store clean data in CSV and JSON formats

## Data Extracted
- Brand Name
- Product Name
- Original Price
- Discounted Price

## Pipeline Workflow
1. Initialize Selenium WebDriver in headless mode
2. Load and render dynamic content
3. Parse HTML using BeautifulSoup
4. Extract and clean product data
5. Store data in structured formats (CSV/JSON)

## Tech Stack
- Python
- Selenium
- BeautifulSoup
- Pandas

## Challenges
- Handling dynamic content loading
- Managing page delays and timeouts
- Extracting nested HTML elements
- Ensuring clean and consistent data

## Solutions
- Used WebDriverWait for proper page loading
- Combined Selenium + BeautifulSoup for efficiency
- Implemented structured parsing logic
- Cleaned and validated extracted data before storage

## Output
Structured datasets ready for analysis and further processing.

## Author
