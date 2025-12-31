# Business Analysis and Valuation: Dabur India Ltd.

Financial analysis and valuation project for Dabur India Limited (DABUR.NS) covering fiscal years 2022-2024.

## Project Overview

This project performs DCF valuation and relative valuation analysis for Dabur India.

## Methodology

### Historical Financial Analysis
- Downloaded three years of financial statements from Yahoo Finance (Balance Sheet, Income Statement, Cash Flow)
- Performed horizontal analysis to calculate year-over-year growth rates
- Performed vertical analysis using common-size statements
- Analyzed key metrics including revenue, operating income, net income, CAPEX, and accumulated depreciation

### Financial Projections
- Projected financial statements for 5-year planning period (2025-2029)
- Calculated projected revenue, operating income, net income, capital expenditure, and interest expense
- Computed Free Cash Flow to Firm (FCFF) and Free Cash Flow to Equity (FCFE) for each projection year

### Cost of Capital Calculation
- Performed regression analysis to calculate Beta using daily returns against NIFTY 50 index
- Calculated Cost of Equity using CAPM model with risk-free rate and market risk premium
- Determined Cost of Debt using interest coverage ratio and credit rating approach
- Computed Weighted Average Cost of Capital (WACC)

### DCF Valuation
- Discounted projected free cash flows using WACC
- Calculated terminal value using two methods: Reinvestment Rate approach and PEG ratio approach
- Computed Enterprise Value and Equity Value

### Relative Valuation
- Analyzed peer companies: Hindustan Unilever, ITC, and Nestlé India
- Calculated EV/EBITDA multiples for comparable companies
- Applied industry average multiple to Dabur's EBITDA

## Technologies

Python libraries used: numpy, pandas, matplotlib, seaborn, yfinance, scipy, statsmodels [file:1]

## File Structure

