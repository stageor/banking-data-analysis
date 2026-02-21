# Banking Data Analysis Project

## Overview

This project performs exploratory data analysis on a synthetic banking dataset and generates automated visual reports in PDF format. The goal is to extract meaningful patterns from customer-level banking data and present results in a structured, reproducible reporting workflow.

---

## Business Objective

Banks need visibility into:

- Customer engagement levels
- Loan distribution patterns
- Transaction behavior by demographic segment
- Risk indicators linked to inactivity or balance levels

This project simulates a reporting pipeline that converts raw banking data into decision-ready visual summaries.

---

## Dataset Description

Synthetic dataset containing:

- `customer_id`
- `age`
- `gender`
- `account_balance`
- `loan_amount`
- `account_status` (active / inactive)
- `transaction_count`

---

## Analysis Performed

1. Active vs Inactive Account Distribution  
2. Average Transactions by Age Group  
3. Account Balance vs Loan Amount Relationship  
4. Loan Ownership Distribution  
5. Account Status Breakdown  

Each analysis includes visualization and summary interpretation.

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Outputs

- Automated chart generation (PNG format)  
- Programmatically generated consolidated PDF report  
- Reproducible Jupyter workflow  

---

## Repository Structure

```
banking-data-analysis/
│
├── Banking_Report.ipynb        # Complete EDA workflow
├── banking_report.pdf          # Final generated report
├── visuals/
│   ├── account_status.png
│   ├── transactions_by_age.png
│   ├── balance_vs_loan.png
│   ├── loan_distribution.png
│   └── activity_distribution.png
└── README.md
```

---

## How to Run

1. Install required libraries:

```
pip install pandas numpy matplotlib seaborn
```

2. Open `Banking_Report.ipynb`
3. Run all cells to regenerate visualizations and PDF output

---

## Key Takeaways

- Account inactivity patterns can indicate engagement issues.
- Transaction volume varies significantly by age segment.
- Loan ownership and balance distribution provide insight into risk segmentation.
- Automated reporting improves repeatability and operational efficiency.

---

## Future Improvements

- Add customer segmentation using clustering
- Build predictive model for account inactivity
- Implement dashboard version using Power BI or Streamlit
- Add statistical testing for deeper inference
