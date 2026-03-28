# Banking Data Analysis Project

## Overview

This project conducts exploratory data analysis on a synthetic banking dataset and produces an automated PDF report.

It shows how raw customer-level banking data can be systematically processed and converted into structured, decision-ready insights through a reproducible analytics workflow.

---

## Business Context

Retail banks require structured visibility into customer behavior and financial exposure. Key monitoring areas include:

- Customer engagement and inactivity  
- Loan distribution patterns  
- Transaction behavior across demographics  
- Risk signals linked to low balances or dormant accounts  

This project simulates a reporting pipeline that converts transactional data into actionable visual summaries.

---

## Dataset

Synthetic customer-level dataset containing:

- `customer_id`  
- `age`  
- `gender`  
- `account_balance`  
- `loan_amount`  
- `account_status` (active, inactive)  
- `transaction_count`  

The dataset mirrors common attributes used in retail banking engagement and risk analysis.

---

## Analysis Performed

1. Active vs Inactive Account Distribution  
2. Average Transaction Count by Age Group  
3. Account Balance vs Loan Amount Relationship  
4. Loan Ownership Distribution  
5. Account Status Breakdown  

Each analysis includes a visualization and concise interpretation.

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
- Fully reproducible Jupyter Notebook workflow  

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
