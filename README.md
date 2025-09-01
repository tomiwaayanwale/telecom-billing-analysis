# telecom-billing-analysis

# Telecom Billing and Margin Analysis

## Overview
This project analyzes telecom call billing data to calculate costs, revenue, and gross margins across multiple dimensions. It also includes scenario modeling to evaluate how pricing changes affect profitability.  
All work is implemented in **Python (pandas, matplotlib)** with outputs exported to Excel for review.

## Key Features
- **Data consolidation**: Combines three months of call records with client and vendor rate tables.  
- **Billing increments applied correctly**:  
  - Clients billed per minute (e.g., 61 sec → 2 min)  
  - Vendors billed with unique increments (6-sec, per-second, per-minute, 30-sec blocks, etc.)  
- **Gross margin calculations by**:  
  - Client  
  - Country  
  - Carrier  
  - Number Type  
- **Scenario modeling**:  
  - Simulates mobile rate +7% and landline rate +20% impacts  
  - Estimates rate changes required to reach 45% gross margin target  
- **Deliverables**:  
  - Clean Excel report (`avoxi_analysis_results.xlsx`)  
  - Full Python notebook (`billing_analysis.ipynb`) with all formulas and logic  

## Project Files
- `avoxi_analysis_results.xlsx` — Final Excel report with all metrics  
- `avoxi_analysis.ipynb` — Full analysis notebook (Python code and calculations)  
- `README.md` — Project documentation (this file)  
- 

## Tools & Libraries
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- openpyxl  

## Insights & Recommendations
- Total billing per client calculated and included in the Excel output.  
- Low-margin clients identified — targeted rate adjustments recommended.  
- High-cost vendors impact profitability — vendor renegotiation suggested.  
- Automated dashboards could simplify recalculation for pricing changes.  

## Author
Tomiwa Ayanwale 
