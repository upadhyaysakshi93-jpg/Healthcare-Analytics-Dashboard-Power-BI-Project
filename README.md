 /># Healthcare-Analytics-Dashboard-Power-BI-Project
Power BI dashboard analyzing hospital patient flow, bed utilization &amp; billing (PDF &amp; screenshots) as my learning project

**Overview**  
Interactive Power BI dashboard analyzing hospital patient flow, diagnosis mix, bed utilization and billing vs insurance. Built from an instructor sample dataset (7,157 records) and enhanced with custom theme, DAX measures and UX-focused layout.

**Key insights**
- **Avg Length of Stay:** ≈ 8.25 days  
- **Total billing:** ₹190M+ (Insurance covers ≈ 90%)  
- **Top diagnoses:** Viral Infection (2,004), Flu (1,717), Malaria (1,431)  
- **Bed occupancy:** Private 3,579 | General 2,385 | ICU 1,193  
- **Top revenue contributors:** Viral Infection (₹53.4M), Flu (₹45.8M)

**Files included**
- `screenshots/01_overview.png` — Full dashboard overview  
- `screenshots/02_bed_occupancy.png` — Bed occupancy insight  
- `screenshots/03_diagnosis_funnel.png` — Diagnosis distribution  
- `screenshots/04_billing_vs_insurance.png` — Billing vs Insurance trend  
- `screenshots/05_kpis.png` — KPI tiles

**Dashboard PDF**
[Download PDF](./Healthcare_Analytics.pdf)

**Insights**
- Insurance covers approx **90%** of all billing, reducing direct out-of-pocket patient burden
- Viral Infection & Flu together contribute **~52%+** of total revenue volume
- Private beds have the highest occupancy (3,579) compared to General (2,385) and ICU (1,193)
- Avg length of stay ~8.25 days indicates moderate recovery window with consistent treatment cycles



**How it was built**
- Tools: Power BI Desktop, Excel (data cleaning)  
- Data cleaning steps: normalized date columns, corrected invalid follow-up dates (replaced follow up year  values), handled nulls and trimmed diagnosis strings.

**Usage**
Open `Healthcare_Analytics.pbix` in Power BI Desktop to explore interactive visuals. Use the slicer for Patient_ID to drill into patient-level records. Screenshots & PDF included for quick preview.

**Contact**
Sakshi Upadhyay  
LinkedIn:https://www.linkedin.com/in/sakshiupadhyayofficial
Email: <upadhyaysakshi93@gmail.com>

---
