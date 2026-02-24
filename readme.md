# Brain Tumor Distribution Analysis Dashboard


**Interactive Power BI dashboard analyzing 10,000 anonymized brain tumor cases (diagnosed 2015–2025)**

This project explores patterns in brain tumor occurrence by grade, patient demographics, tumor characteristics, anatomical location, histological confirmation status, and temporal trends. Built entirely in Power BI with custom DAX measures.

## ✨ Key Insights at a Glance

- **Grade 4 tumors** are the most prevalent (~40.8% of cases), highlighting the heavy burden of aggressive malignancies.
- Tumor size increases dramatically with grade: ~2.0 cm (Grade 1) → ~6.5 cm (Grade 4).
- Lower-grade tumors (Grade 1–2) predominantly affect adults aged **41–60**, while higher-grade tumors show broader age impact — including younger patients (e.g., Grade 3 peaks in 21–30 group).
- **Pituitary region** dominates low-grade tumors (hormonal/vision symptoms); **cerebellum & brainstem** are most affected in high-grade cases (motor/balance issues).
- Histological confirmation rate is high overall (~78%), reaching ~90% in Grade 4 — reflecting urgency in aggressive cases.
- Annual diagnosis counts fluctuate (no clear long-term rise/fall), with peaks in certain years possibly linked to improved imaging access or awareness.

These findings can inform targeted screening, resource allocation, and public health strategies — especially in regions with variable healthcare access.

## 📊 Dashboard Overview

The dashboard includes:

- **KPIs** (cards & indicators):
  - Total patients
  - Avg. annual intake (vs. overall average with ↑/↓ arrows)
  - Average patient age
  - Most affected age group
  - Average tumor size (cm)
  - Most Affected Brain Region (MABR) with %

- **Visuals**:
  - Pie chart: Tumor type distribution
  - Horizontal bar: Top affected brain regions
  - Line chart: Annual patients diagnosed (2016–2025)
  - Bar chart: Top affected age groups by count
  - Slicer: Filter by Confirmed / Unconfirmed histological diagnosis

Separate views created for each tumor grade (1–4).

## Screenshots

### Grade 1 (Low-grade, often benign – meningioma & pituitary dominant)

![Grade 1 Confirmed](/Dashboard%20Screenshots/Grade%201%20Confirmed.png)  
*Grade 1 – Confirmed cases*

![Grade 1 Unconfirmed](/Dashboard%20Screenshots/Grade%201%20Unconfirmed.png)  
*Grade 1 – Unconfirmed cases*

### Grade 2

![Grade 2 Confirmed](/Dashboard%20Screenshots/Grade%202%20Confirmed.png)  
*Grade 2 – Confirmed*

![Grade 2 Unconfirmed](/Dashboard%20Screenshots/Grade%202%20Unconfirmed.png)  
*Grade 2 – Unconfirmed*

### Grade 3 (High malignancy – ependymoma prominent)

![Grade 3 Confirmed](/Dashboard%20Screenshots/Grade%203%20Confirmed.png)  
*Grade 3 – Confirmed*

![Grade 3 Unconfirmed](/Dashboard%20Screenshots/Grade%203%20Unconfirmed.png)  
*Grade 3 – Unconfirmed (rare)*

### Grade 4 (Aggressive – glioma & medulloblastoma / ependymoma variants)

![Grade 4 Confirmed](/Dashboard%20Screenshots/Grade%204%20Confirmed.png)  
*Grade 4 – Confirmed (glioma & medulloblastoma dominant)*

![Grade 4 Unconfirmed](/Dashboard%20Screenshots/Grade%204%20Unconfirmed.png)  
*Grade 4 – Unconfirmed*


## 🛠️ Technical Details

- **Data Source**: `Brain Tumor Data.csv` (10,000 synthetic/anonymized records)
- **Tools**: Power BI Desktop
- **Key DAX Measures** (see `Formula.txt` for full definitions):
  - Avg Intake py — patients per year
  - vs Avg Intake py — comparison with overall average + directional arrow
  - Most Affected Group — top age bracket
  - MABR — most affected brain region + percentage
  - Age Group — binned categories (0-10, 11-20, ..., 60+)


## ⚕️ Health Sector Implications

- **Screening & Early Detection** — Focus on 40–60 age group for low-grade tumors (headaches, vision/hormonal symptoms).
- **Resource Prioritization** — Grade 4 cases (~41%) require significant oncology/radiation capacity.
- **Rehabilitation Focus** — Cerebellum involvement in many high-grade tumors → motor & balance therapy needs.
- **Diagnostic Equity** — Reduce unconfirmed cases (esp. low grades) via better access to biopsy/advanced imaging.
- **Research & Awareness** — Investigate fluctuating trends; support pediatric programs (medulloblastomas) and geriatric care.

## 📄 License/Ceetifications
- **Bsc Human Anatomy**
- **TechCrush Data Analytic Certificate**

## 🙌 Acknowledgments
- Inspired by real-world healthcare analytics needs.
- Built as a portfolio project to demonstrate Power BI, DAX, and medical data visualization skills.

***Analyst: Raji Toluwanimi Samuel***

***Location: Abuja, Nigeria***

***Date: February 2026***

---

Questions, feedback, or collaboration ideas? Feel free to open an issue or reach out!