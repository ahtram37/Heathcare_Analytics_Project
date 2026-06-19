# 💼 Delhi Hospital - Power BI Dashboard | Healthcare Analytics Project


An end-to-end healthcare analytics project built using **Excel** and **Power BI**, analysing real hospital operational data across patient admissions, diagnosis types, billing, and bed occupancy over a 15-month period.

---

## 📌 Project Overview

Hospitals generate large volumes of operational data — patient records, billing, ward usage, doctor workload — that often go unanalysed. This project transforms raw hospital data into an interactive Power BI dashboard that gives hospital administrators a single view of clinical and financial performance.

**Period covered:** December 2022 – March 2024  
**Total billing tracked:** ₹190.43 Million  
**Tools used:** Microsoft Excel (data cleaning), Power BI (visualisation, DAX)

---

## 🎯 Business Problem

Hospital administrators at Delhi Hospital needed answers to four key operational questions:

1. Which ward types are under the most occupancy pressure?
2. Which diagnosis categories are driving the highest patient volume and billing?
3. Where is the gap between what patients are billed and what insurance covers?
4. How is doctor feedback distributed across the team?

This dashboard was built to answer all four in a single, filterable interface.

---

## 🗂️ Dataset

- **Source:** GitHub (open-source hospital dataset)
- **Cleaning done in:** Microsoft Excel
  - Removed duplicate patient records
  - Standardised date formats across Admit Date, Discharge Date, and Follow Up Date columns
  - Handled null/missing values in billing and insurance fields
  - Verified ward type categorisation (Private / General / ICU)

---

## 📊 Dashboard Features

| Feature | Description |
|---|---|
| **KPI Cards** | Admit Date, Discharge Date, Follow Up Date, Total Billing Amount |
| **Date Range Slicer** | Filter all visuals dynamically by date (Dec 2022 – Mar 2024) |
| **Patient ID Filter** | Drill into individual patient records |
| **Bed Occupancy Chart** | Bar chart comparing occupancy across Private, General, and ICU wards |
| **Diagnosis Type Chart** | Horizontal bar ranking 6 diagnosis categories by patient volume |
| **Feedback Volume (Donut)** | Doctor-wise feedback distribution across 7 physicians |
| **Billing vs Insurance Line Chart** | Dual-line comparison of billed amount vs. insurance coverage by diagnosis |

---

## 🔍 Key Insights & Findings

### 1. Private wards carry the highest occupancy load
Private ward bed occupancy (~3,500) is significantly higher than General (~2,500) and ICU (~1,100). This suggests either a demand preference for private care or a structural undersupply of general ward beds — both worth flagging for resource planning.

### 2. Viral infections dominate diagnosis volume
Viral Infection is the most common diagnosis at 2.00K cases, followed by Flu (1.72K) and Malaria (1.43K). The top three diagnoses together account for approximately 58% of all recorded cases — suggesting the hospital's clinical resources should be heavily weighted toward infectious disease management.

### 3. A widening insurance coverage gap as case severity decreases
Billing drops steeply from ₹48M (Viral Infection) to ₹7M (Fracture). However, health insurance coverage drops at a faster rate in lower-volume categories like Pneumonia (₹15M billed, ₹14M insured — small gap) and Fracture (₹8M billed, ₹7M insured). The largest absolute gap exists for high-volume categories like Viral Infection and Flu, where the billing-insurance difference is the most significant. This represents a structural out-of-pocket burden on patients with common illnesses.

### 4. Doctor feedback volume is uniformly distributed
All 7 doctors show near-identical feedback volume at approximately 1.02K each. This uniformity could indicate either a well-balanced patient load or a data collection limitation (e.g. a fixed feedback cap per doctor). Either way, it signals an opportunity to introduce a weighted feedback scoring system to better differentiate doctor performance.

### 5. Average patient stay spans ~38 days
With an admit date of 05-12-2022 and discharge date of 12-01-2023 shown as the headline values, the data suggests extended patient stays are common — likely skewed by chronic or complex cases. Tracking average length of stay per diagnosis would help isolate outlier cases driving up ward costs.

---

## 💡 Recommendations

- **Resource allocation:** Increase general ward capacity or introduce overflow protocols given the private ward pressure.
- **Insurance awareness programme:** Patients with Viral Infection and Flu diagnoses face the largest insurance shortfalls. A pre-admission insurance advisory could reduce billing disputes.
- **Feedback system overhaul:** Introduce weighted ratings and category-wise feedback (e.g. bedside manner, wait time) to generate more actionable doctor performance data.
- **Follow-up tracking:** With follow-up dates logged, the hospital could analyse how many follow-ups convert to readmissions — a key metric for care quality.

---


## 👤 Author

**Sayed Ahtramul Haque**  
BBA Graduate 
[GitHub](https://github.com/ahtram37)

---

## 📄 License

This project uses an open-source dataset for educational and portfolio purposes only.
---
