# workforce-scheduling-analysis

## Overview
This project analyses workforce scheduling data to assess whether staffing levels are aligned with workload demand across shifts and demand periods. The analysis combines Excel-based exploration with SQL-style aggregation logic to identify staffing pressure and misalignment.

---

## Business Question
- Are staffing elvels appropriately aligned with workload demand?
- Which shifts experience the highest workload per staff?
- Do demand classification accurately reflect staffing pressure?

---

## Dataset
The dataset represents four weeks of workforce scheduling data. Each record corresponds to a single shift and includes staffing levels, workload indicators, shift timing, and demand classification.

A derived KPI, workload per staff, was used to quantify staffing pressure.

--- 

## Methodology
- Validated and structured workforce scheduling data in excel
- Defined workload per staff as the primary efficiency KPI
- Used PivotTables to analyse staffing pressure by shift and demand level
- Performed cross-analysis of shift timing and demand classification
- Translated Excel-based logic into SQL-style GROUP BY queries

---

## Key Findings
- Night shifts experience the highest average workload per staff (12.6), indicating elevated but manageable staffing pressure
- Low-demand periods consistently exhibit the highest workload per staff
- Afternoon low-demand shifts show the greatest staffing pressure, with an average workload per staff of 16.4
- High-demand periods appear better buffered through staffing allocation

---

## Recommendations
- Review minimum staffing levels during low-demand periods
- Refine demand classification to better reflect actual workload intensity
- Implement workload-per-staff thresholds as an early-warning KPI

---

## Tools Used
- Microsoft Excel (Tables, PivotTables, calculated fields)
- SQL (conceptual query translation using GROUP BY)

---

## Notes
This project uses simulated but realistic workforce data for portfolio demonstration purposes.
