Analyzing Historical Stock and Revenue Data for Tesla and GameStop
📌 Project Overview
This project extracts, processes, and analyzes historical stock price and revenue data for Tesla (TSLA) and GameStop (GME). By visualizing stock trends alongside revenue streams over time, this project provides insights into financial trends, market volatility, and company performance.

🛠️ Features & Methodology
Stock Data Extraction:

Utilizes the yfinance library to download historical stock prices and trading volumes for TSLA and GME.

Revenue Data Scraping:

Uses BeautifulSoup and requests to scrape historical revenue tables from web sources.

Data Cleaning & Wrangling:

Cleans messy string data (e.g., removing commas, dollar signs) and converts values into appropriate numeric formats (float/int).

Handles missing values and standardizes date formats.

Interactive Visualization & Dashboard:

Builds custom plotting functions using Plotly / Matplotlib to display stock prices alongside revenue trends in a clear, unified view.

📁 Repository Structure
Plaintext
├── README.md                                    # Project documentation
└── Revenue Data and Building a Dashboard.ipy
