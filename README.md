# Data Analytics Internship - Task 1: Web Scraping

## 📌 Project Overview
This project was completed as part of the **CodeAlpha Data Analytics Internship** program. The objective of this task is to perform web scraping to extract data from public web pages, handle HTML structure, and generate a clean, custom dataset for further analysis.

## 🛠️ Tools & Libraries Used
* **Programming Language:** Python 3.x
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:** 
  * `requests` - To send HTTP requests to target web pages
  * `BeautifulSoup` (`bs4`) - To parse HTML structure and extract elements
  * `pandas` - To structure, clean, and export data into CSV format

## 🌐 Target Website & Scraped Data
* **Source:** [Books to Scrape](http://books.toscrape.com/)[cite: 3, 4]
* **Extracted Fields:**
  * Book Title
  * Price

## 🚀 How to Run the Code
1. Clone this repository:
   ```bash
   git clone [https://github.com/VARSHITHA-1707/CodeAlpha_WebScraping.git](https://github.com/VARSHITHA-1707/CodeAlpha_WebScraping.git)
   Open web_scraping_py.ipynb in Google Colab or Jupyter Notebook.

Install the required dependencies (if not already installed):

Bash
pip install requests beautifulsoup4 pandas

Run all notebook cells sequentially to execute the web scraper and generate codealpha_scraped_books.csv

📁 Repository StructurePlaintext
├── web_scraping_py.ipynb            # Main Jupyter/Colab scraping notebook
├── codealpha_scraped_books.csv      # Generated custom dataset
└── README.md                        # Project documentation

👤 AuthorIntern: Varshitha   Program: Data Analytics Internship at CodeAlpha
