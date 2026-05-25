# Zillow BOE Analysis

A Python toolkit for quickly evaluating real estate investment deals using back-of-the-envelope (BOE) calculations. Includes functions for cash flow modeling and a Zillow & RE/MAX listing price scraper.

## What It Does

- **Net Operating Income** — calculates monthly NOI factoring in rent, property management (10%), property tax, repairs (2% annually), and vacancy (2%)
- **Mortgage Calculator** — computes monthly mortgage payment from purchase price, loan term, and interest rate (assumes 20% down)
- **Down Payment Calculator** — returns down payment amount for a given price and percentage
- **Price Scraper** — scrapes listing prices from RE/MAX using BeautifulSoup
- **Deal Pipeline** — runs multiple properties through the BOE functions to compare opportunities

## Stack

- Python
- Jupyter Notebook
- pandas, requests, BeautifulSoup, streamlit

## Files

- `RE BOE Functions.ipynb` — core calculation functions (NOI, mortgage, down payment, price scraper)
- `RE Draft Pipeline.ipynb` — deal pipeline analysis across multiple properties

