# PalmorIa-HR-Gender-Equality-Audit
A Power BI Analysis on PalmorIa Group Gender Equality Crisis


<img width="1098" height="635" alt="palmoria Dashboard" src="https://github.com/user-attachments/assets/022b1dc5-c1e4-4829-828c-0de1d9ba7453" />



---

# Palmoria Group: Gender Equity & Regulatory Compliance Audit

## Project Overview

This project addresses a critical HR crisis at **Palmoria Group**, a manufacturing company in Nigeria recently labeled by the media as a "Manufacturing Patriarchy". As an HR Analytics expert, I analyzed the company's data to identify gender pay gaps, performance evaluation biases, and non-compliance with new minimum wage regulations.

## Key Insights & Solutions

* **Regulatory Compliance**: Identified **653 employees** currently earning below the newly mandated **$90,000** minimum wage.
* **Gender Pay Gap**: Developed DAX measures to expose the average salary disparity between Male and Female employees across all regions.
* **Performance Bias**: Visualized performance ratings by gender to determine if evaluation metrics were skewed.
* **Salary Structure**: Created a distribution analysis using **$10,000 salary bands** to show the concentration of low-income earners.

## Technical Procedures

### 1. Data Cleaning (Power Query)

* **Anonymization & Standardization**: Assigned a generic **"Undisclosed"** status to employees who chose not to reveal their gender.
* **Data Integrity**: Filtered out inactive employees (blank salaries) and removed records with **"NULL"** department labels to ensure an accurate headcount of **945 staff**.

### 2. Advanced Analytics (DAX)

* **Custom Measures**: Created complex measures for **Average Salary by Gender**, **Gender Pay Gap %**, and **Staff Below $90k Minimum Wage**.
* **Conditional Logic**: Built a dynamic **Annual Bonus** system using `SWITCH` logic based on performance ratings (3–5) as requested by management.

## Tools Used

* **Power BI Desktop**: For data modeling and interactive dashboard design.
* **Power Query**: For ETL (Extract, Transform, Load) processes.
* **DAX**: For advanced statistical and financial calculations.

---
