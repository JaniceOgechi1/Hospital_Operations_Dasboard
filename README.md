# Hospital Operations Analysis Dashboard — City General Hospital

**Author:** Okoye Ogechi Janice (JaniceOgechi)
**Date:** 2026-07-11

---

## Project Background
City General Hospital is experiencing severe operational issues: ER overcrowding, bed
misallocation, staff burnout, medication mismanagement, financial losses, and high lab retest
rates. This project analyzes available hospital data and produces an interactive Excel dashboard
with actionable recommendations.

---

## Project Objective
- Identify root causes of ER congestion and resource waste
- Analyze patient flow, staff workload, medication stock, lab efficiency, and finance data
- Build an interactive Excel dashboard to inform board-level decisions
- Recommend prioritized actions to stabilize hospital operations

---

## Datasets

- **Patients.csv / Patients.xlsx** — patient_id, age, gender, visit_date, department,

---

## Dashboard Features
- Key KPIs: Total Patients, Total Hospitals,Total doctors
- Visuals: Patient Volume by Hospital, Age Group Distribution, Hospital Workload, Medication Demand, Lab test result breakdown, Revenue by Hospital
- Interactivity: Hospital slicers connected across pivot tables for live filtering 

---

## Key Findings 
- Houston Methodist Hospital handles 37% of all patients ; indicating a real workload imbalance
- Bed allocation was misaligned with actual demographics.
- Medication demand is evenly balanced across all 5 drugs; stock imbalance is due to procurement issues.
- Lab test inconclusive rate is 35%; more than the reported rate of 15%
- Revenue scales directly with patient volume, not hospital-specific pricing  or insurer underpayment.
- Doctor pool is highly fragmented (40,341 unique doctors for 55,000 patients)
---
## Data Linmitations
- No cost or paid-vs-billed data; true profit/loss cannot be calculated.
- No distinct doctor-per-hospital workload metric available
- No ER wait-time or ambulance data to verify reported congestion 
- Insurance data shows no payer-specific shortfall.
## Recommendations
1. Redistribute patients/resources from Houston Mthodist to underutilized hospitals
2. Rebuild bed-allocation model using actual demographic data, not assumptions
3. Implement automated stock monitoring & FIFO for medications
4. Tighten lab QC processes to reduce retests (target <5%)
5. Audit billing and implement a claims follow-up workflow to reduce unpaid claims
6. Monitor KPIs weekly and run a monthly operational review with stakeholders

---

## Tools & Techniques
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers)
- Data cleaning and transformation in Excel
- Dashboard layout and visualization best practices
- Basic descriptive analytics and KPI design
- Microsoft Powerpoint for presentation

---

## Project Files (included)
- City Hospital Dashboard.xlsx — interactive dashboard file
- City Hospital Dataset.xlsx — raw data files used for analysis (CSV / XLSX)
- HOSPITAL OPERATIONS ANALYSIS_JaniceOgechi — boardroom slide deck (10–12 slides)
- `README.md` — this documentation

---

## How to Run / View
1. Open `Dashboard.xlsx` in Excel (desktop recommended)
2. Enable content (if prompted) to allow Pivot Tables and slicers to work
3. Use slicers to filter by Department, Date, Age group, etc.
4. Refer to `Presentation.pdf` for a summary of insights and recommended actions

---

## Contact
Okoye Ogechi Janice
Email: _okoyejanice65@gmail.com_
LinkedIn: _Janice Ogechi Okoye_
