## Description:
This is a personal project (started at my own initiative).

pf_analysis is a Jupyter Notebook designed to import, clean, and analyze portfolio transactions. Using the Refinitiv Data API and Pandas, the project processes historical and current market data to generate insights into portfolio performance.

## Motivation for the project:
-I want to practise my python skills.

-I use ETFs to ensure cheap and effective diversification across my portfolio while selectively overweighting specific sectors, countries, and market caps. This project allows me to ‘unwrap’ ETFs, providing a clearer view of my underlying exposures.

-I invest through dollar-cost averaging (DCA), which complicates performance tracking. This project adjusts returns to account for reinvestments, allowing comparisons against benchmarks like the S&P 500.

## Key Features:
-**Data Import & Cleaning**: Reads portfolio transaction data from account_activity_seeded.csv (a statement downloaded from my broker, but multiplied to hide true size of portfolio), ensuring structured and clean datasets.

-**Market Data Integration**: Fetches historical price data as well as ETF composition and  via the Refinitiv Data API for enhanced financial analysis.

-**Performance Analysis**: Computes returns, risk metrics, and key performance indicators.

-**Visualization/summary**: Uses Matplotlib (including GridSpec) and Seaborn for effective data visualization, creating a OnePager to view exposures at a glance.
