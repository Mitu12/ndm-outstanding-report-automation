# NDM-Wise Outstanding Report Automation

## Overview
This project automates the generation of **National District Manager (NDM)-wise outstanding reports** using Python. It transforms raw financial/operational data into structured reports for tracking credit outstanding, aging analysis, and branch performance.

## Business Problem
Manual reporting of outstanding balances and aging analysis is time-consuming and error-prone.  
This project solves that by:
- Automating report generation
- Standardizing KPI calculations
- Providing clear insights into credit and operational performance

## Key Features
- NDM-wise credit outstanding analysis
- Matured & non-matured credit aging
- Branch-level performance tracking
- Cash drop aging analysis
- Top-performing branches and delivery personnel identification
- Automated CSV report generation

## Tools & Technologies
- Python (Pandas, NumPy)
- Data Cleaning & Transformation
- CSV Report Generation
- KPI Calculation

## Project Structure
- `Generate_all_csv.py` – Generates report outputs
- `generate_all_kpi.py` – Calculates KPIs
- `branch_wise_cash_drop_aging.csv` – Sample output
- `Images/` – Visual report outputs

---

## Sample Outputs

### Dashboard Summary
![Dashboard Summary](images/img1_2.png)

### NDM Credit Outstanding
![NDM Credit Outstanding](images/3.ndm_credit_outstanding.png)

### Matured Credit Aging
![Matured Credit Aging](images/4.matured_credit_aging.png)

### NDM Matured Credit Aging
![NDM Matured Credit Aging](images/5.ndm_matured_credit_aging.png)

### Branch-Wise Matured Credit Aging
![Branch Wise Matured Credit Aging](images/6.Branch_wise_matured_credit_aging.png)

### Non-Matured Credit Aging
![Non Matured Credit Aging](images/7.non_matured_credit_aging.png)

### NDM Non-Matured Credit Aging
![NDM Non Matured Credit Aging](images/8.ndm_non_matured_credit_aging.png)

### Branch Non-Matured Analysis
![Branch Non Matured](images/9.branch_non_matured.png)

### Cash Drop Aging
![Cash Drop Aging](images/10.cashdrop_aging.png)

### NDM Cash Drop Aging
![NDM Cash Drop Aging](images/11.ndm_cash_drop_aging.png)

### Branch Cash Drop Aging
![Branch Cash Drop Aging](images/12.branch_wise_cash_drop_aging.png)

### Return Summary
![Return Summary](images/img13_14.png)

### Top 5 Branch Return
![Top 5 Branch Return](images/15.top5_branch_return.png)

### Top 5 Delivery Performance
![Top 5 Delivery](images/16.top5_delivery_persons_return.png)

---

## Skills Demonstrated
- Data Analysis & Reporting
- Python Automation
- Business KPI Development
- Data Visualization (via reports)
- Financial/Operational Data Analysis

---

## Future Improvements
- Convert reports into interactive dashboard (Power BI/Tableau)
- Add automated data pipeline
- Deploy as a reporting tool or web app
