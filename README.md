# CoinMarketCap-API-Project-
Developed a Python-based pipeline integrating the CoinMarketCap API to fetch, parse, and analyze real-time cryptocurrency market data.
Real-Time Cryptocurrency Data Pipeline & Analysis
Overview
Engineered an automated data extraction script in Python to pull live cryptocurrency pricing, market capitalization, and volume metrics from the CoinMarketCap API for market analysis.
Technical Stack
Language: Python
Environment: Jupyter Notebook
Libraries: Requests (API integration), JSON (data parsing)
API Authentication: Header-based API key validation
Architecture & Workflow
API Integration: Established secure communication with the CoinMarketCap endpoint using authenticated HTTP GET requests via the Python requests library.
Data Extraction & Parsing: Processed complex nested JSON responses to isolate targeted financial attributes, including current asset valuation, 24-hour trading volumes, market capitalizations, and percentage shifts.
Robust Error Handling: Implemented exception handling structures to gracefully manage connectivity disruptions (ConnectionError) and request timeouts (Timeout).
Key Insights & Outcomes
Successfully established a reliable workflow for querying live market data across major digital assets (Bitcoin, Ethereum).
Standardized raw JSON outputs into structured, analysis-ready formats for ongoing financial trend evaluation.

Getting Started
Obtain an API key from https://coinmarketcap.com/api/
Clone the repository and insert your credentials into the designated variable: YOUR_API_HERE
Install the required dependency:
pip install requests
Execute the Jupyter Notebook to run the pipeline.
Project by George Abasiumoh 
-Data Analyst
