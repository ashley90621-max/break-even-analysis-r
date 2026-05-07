# Marketing Analytics — Customer & Profitability Analysis

**Course**: MSIN0094 Marketing Analytics | UCL School of Management  
**Author**: Kuei-Chun Liu  
**Tools**: R · Quarto · dplyr · modelsummary

---

## Overview

This project applies marketing analytics techniques to a real-world business case — a new bubble tea shop in Canary Wharf, London. The analysis covers market strategy, customer segmentation, and financial modelling using R.

## Contents

| File | Description |
|---|---|
| `Assignment 1 Answer Sheet.qmd` | Full analysis in Quarto Markdown |
| `survey_data.csv` | Survey data (1,000 customers, foodie vs non-foodie segments) |

## Key Analyses

**1. Market Analysis (5C Framework)**  
Situation analysis covering Company, Customers, Competitors, Collaborators, and Context (PESTLE) for a bubble tea shop targeting Canary Wharf office workers.

**2. Customer Acquisition Cost (CAC)**  
Compared three acquisition channels:
- Blanket mailing: £30 per customer
- Targeted mailing: £14 per customer  
- Search Engine Marketing (SEM): £2 per customer

**3. Customer Lifetime Value (CLV)**  
Modelled 24-month CLV with retention rates and discount factors:
- Foodie segment CLV: ~£162.65
- Non-foodie segment CLV: ~£26.94

**4. Loyalty Program ROI**  
Evaluated a buy-3-get-1-free loyalty program:
- Foodie CLV increased by ~20% → recommended ✅
- Non-foodie CLV decreased by ~6.6% → not recommended ❌

## How to Run

1. Open `Assignment 1 Answer Sheet.qmd` in RStudio
2. Ensure `survey_data.csv` is in the same directory
3. Install required packages: `pacman::p_load(dplyr, modelsummary)`
4. Click **Render** to generate the HTML report
