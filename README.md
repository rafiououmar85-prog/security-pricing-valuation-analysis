# Security Pricing & Valuation Exception Analysis

## Project Overview
This Excel project analyzes 5,000 simulated securities to identify potential pricing and valuation exceptions. The project demonstrates a rule-based review process similar to workflows used in financial data, pricing, valuation, and investment operations.

All data used in this project is simulated and does not contain confidential or proprietary company information.

## Objectives
- Identify missing or invalid security prices
- Detect stale pricing
- Flag significant daily price movements
- Identify differences between current and vendor prices
- Prioritize exceptions for review
- Build a dashboard to summarize results and key findings

## Exception Rules
- **Missing Price:** Current price is blank or zero
- **Stale Price:** Price age is 3 days or greater
- **Large Move:** Daily price movement is 5% or greater
- **Vendor Difference:** Difference between current and vendor price is 2% or greater

## Key Results
- **5,000** securities reviewed
- **822** total exceptions identified
- **16.44%** exception rate
- **307** high-priority exceptions
- **160** medium-priority exceptions
- **355** low-priority exceptions
- **467** stale-price exceptions — the largest exception category

## Dashboard
The Excel dashboard summarizes:
- Total securities reviewed
- Total exceptions and exception rate
- High, medium, and low priority exceptions
- Exception priority distribution
- Exception type breakdown
- Key analytical insights

## Tools Used
- Microsoft Excel
- Excel formulas and logical functions
- Conditional formatting
- Data validation and reconciliation
- Charts and dashboard reporting

## Skills Demonstrated
Financial data analysis, security pricing, valuation controls, exception management, data quality, analytical problem-solving, Excel reporting, dashboard development, and financial operations.

## Project File
The complete Excel workbook is included in this repository:

`Security_Pricing_Valuation_Exception_Analysis.xlsx`
