# Massachusetts General Hospital Analytics Report  
> Comprehensive Data Summary on Deaths, Insurance, and Patients  
> April Data Challenge of DataSense Analytics PH

---

## Table of Contents  
[1. Background](#background)  <br>  
[2. Objective](#objective)  <br>  
[3. Hospital Deaths Report](#deaths-report)  <br>  
[4. Hospital Insurances Report](#insurances-report)  <br>  
[5. Hospital Patients Report](#patients-report)  <br>  
[6. Key Takeaways](#key-takeaways)  <br>  
[7. Recommendations](#recommendations)

---

## 1. Background <a name="background"></a>

<p align="justify">
Massachusetts General Hospital (MGH) is one of the leading academic medical centers in the U.S. This project presents a data-driven analysis of mortality, patient demographics, and insurance claims. It aims to support hospital leaders in making operational, clinical, and financial decisions through actionable insights derived from real-world dashboards.
</p>

---

## 2. Objective <a name="objective"></a>

<p align="justify">
To uncover key trends in hospital deaths, insurance claim distribution, and patient encounters using integrated dashboard analytics. The project highlights performance gaps, cost drivers, and demographic impacts, with the goal of recommending practical improvements in care delivery, resource utilization, and data accuracy.
</p>

---

## 3. Hospital Deaths Report <a name="deaths-report"></a>

<div align="center">  
  <img src="https://github.com/RielRoque/MGH-Analysis-PowerBI/blob/main/MGH%20Death%20Dashboard.png?raw=true" width="95%">  
</div>  

### Summary & Key Metrics:
- **Mortality Rate:** 15.81%  
- **Survival Rate:** 84.19%  
- **Top Cause of Death:** Chronic Congestive Heart Failure – 1,197 cases

### Trends:
- Deaths peaked in 2018 and declined by 2022 — potentially due to improved care or incomplete post-COVID data.

### Demographics:
- Most deaths involved **seniors**, with **non-Hispanic males** the most affected group.

### Geography:
- Highest death concentrations occurred in the **Boston–Cambridge–Quincy** region.

### Marital Status:
- **Married males**: 77.6% of deaths  
- **Single females**: 17.4%

---

## 4. Hospital Insurances Report <a name="insurances-report"></a>

<div align="center">  
  <img src="https://github.com/RielRoque/MGH-Analysis-PowerBI/blob/main/MGH%20Insurances%20Dashboard.png?raw=true" width="95%">  
</div>  

### Financial Overview:
- **Total Claim Cost:** $101.51M  
- **Avg. Claim Cost:** $3.64K  
- **Top Insurance:** Medicare ($19M)

### Gender Disparity:
- **Female patients** incur higher total claim costs.

### Notable Case:
- **Gail Glover** appears as the highest-cost patient — across all dashboards.

### Coverage Trends:
- Coverage peaked around 2020, followed by a notable decline.

---

## 5. Hospital Patients Report <a name="patients-report"></a>

<div align="center">  
  <img src="https://github.com/RielRoque/MGH-Analysis-PowerBI/blob/main/MGH%20Patients%20Dashboard.png?raw=true" width="95%">  
</div>  

### Admission Trends:
- Sharp drop after 2022 likely due to data loss or changes in reporting and care delivery.

### Common Diagnoses:
- Small Cell Lung Cancer  
- Metastatic Neoplasm  
- PTSD

### Encounter Classes:
- Most common: **Ambulatory, Outpatient, Urgentcare**

### Top Claimants:
- **Gail Glover:** $9.93M  
- Others: Eugene Abernathy, Columbus Wolf

### County & Race:
- Most patients from **Suffolk County (17.9%)**  
- Predominantly **White (880 patients)**

---

## 6. Key Takeaways <a name="key-takeaways"></a>

- <p align="justify"><strong>Heart disease (CHF)</strong> is the leading cause of death, concentrated among <strong>seniors</strong>, especially <strong>married males</strong>.</p>

- <p align="justify"><strong>Medicare</strong> dominates insurance coverage, making it the most impactful on hospital revenue and care delivery.</p>

- <p align="justify"><strong>Female patients</strong> consistently account for higher total claims, possibly due to higher care utilization or chronic illness burden.</p>

- <p align="justify"><strong>Gail Glover</strong> is a recurring high-cost patient across all dashboards, indicating the need for patient-level financial and clinical audits.</p>

- <p align="justify"><strong>Ambulatory and outpatient care</strong> represent the bulk of patient encounters, reinforcing the hospital's shift toward cost-effective treatment models.</p>

- <p align="justify">There is a <strong>significant drop in patient admission data post-2022</strong>, which limits trend reliability and requires data governance intervention.</p>

---

## 7. Recommendations <a name="recommendations"></a>

### 🩺 Clinical Action
- <p align="justify">Launch <strong>preventive programs</strong> for cardiovascular disease, targeting high-risk senior populations.</p>
- <p align="justify">Expand <strong>mental health services</strong> to address PTSD and chronic psychological conditions identified in top diagnoses.</p>
- <p align="justify">Strengthen <strong>oncology care coordination</strong> for patients with recurring or high-cost cancer profiles (e.g., small cell lung cancer).</p>

### Cost Management
- <p align="justify">Audit high-cost patients like <strong>Gail Glover</strong> to reduce duplicative services and optimize care plans.</p>
- <p align="justify">Investigate <strong>gender-based claim discrepancies</strong> to determine whether resource allocation is equitable and clinically justified.</p>
- <p align="justify">Monitor <strong>Medicare-driven outpatient services</strong> for inefficiencies and potential overutilization.</p>

### Operational Monitoring
- <p align="justify">Create a <strong>weekly KPI dashboard</strong> to track: mortality rate, claim cost per encounter, top diagnoses, and encounter volumes.</p>
- <p align="justify">Use <strong>real-time alerting systems</strong> for cost outliers and patient admission spikes.</p>
- <p align="justify">Evaluate and manage <strong>average length of stay</strong> and <strong>inflation rate variance</strong> across departments.</p>

### Data Integrity & Governance
- <p align="justify">Resolve <strong>data discontinuity post-2022</strong> to restore longitudinal accuracy.</p>
- <p align="justify">Strengthen <strong>data validation protocols</strong> and introduce real-time encounter logging across departments.</p>
- <p align="justify">Conduct <strong>routine audits</strong> of EHR, billing, and encounter-class datasets.</p>

### Equity & Access
- <p align="justify">Target underserved groups and counties with lower representation for outreach and screening.</p>
- <p align="justify">Monitor KPIs by race, gender, and geography to ensure equitable care delivery and funding allocation.</p>

---

### Tools & Technologies Used

The project was built using Excel for preliminary data quality inspection, Power BI for interactive dashboard creation, and Power Query for efficient data transformation and normalization.

**DAPH April Data Challenge by Riel Roque** 🚀
