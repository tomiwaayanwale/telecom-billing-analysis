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

## Repository Structure

telecom-billing-analysis/ │ ├── avoxi_analysis_results.xlsx   # Final Excel report ├── billing_analysis.ipynb        # Full analysis notebook ├── README.md                     # Project documentation └── requirements.txt              # Python dependencies

## Tools & Libraries
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- openpyxl  

## How to Run
```bash
git clone https://github.com/yourusername/telecom-billing-analysis.git
cd telecom-billing-analysis
pip install -r requirements.txt
jupyter notebook billing_analysis.ipynb

Insights & Recommendations

Total billing per client calculated and available in Excel output.

Low-margin clients identified — recommend targeted rate adjustments.

High-cost vendors impact profitability — vendor renegotiation suggested.

Automated dashboards could simplify recalculation for pricing changes.


Author

Tomiwa Ayanwale
