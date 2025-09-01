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
git clone https://github.com/yourusername/data-center-grid-mapping.git
cd data-center-grid-mapping
pip install -r requirements.txt
jupyter notebook grid_mapping_analysis.ipynb

Insights & Recommendations

Mapped 30 operational data centers in Virginia, Pennsylvania, and Ohio with detailed grid connection data.
Built a 16-column dataset capturing MW capacity, coordinates, ISO/RTO region, nearest substations, transmission lines, and grid connection visibility.
Verified proximity using GIS tools and OpenInfraMap overlays, with Python (geopy, pandas) for ETL workflows and automated distance calculations.
Findings highlight that ~80% of facilities are within 1 mile of a substation, supporting site selection, infrastructure planning, and investment prioritization.

Skills

Python, pandas, geopy, GIS, ETL, data analysis, spreadsheet modeling, geospatial mapping, infrastructure research, energy market analysis, data validation, Excel

Author

Tomiwa Ayanwale
