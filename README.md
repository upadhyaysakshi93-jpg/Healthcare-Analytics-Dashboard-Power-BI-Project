 ## Healthcare-Analytics-Dashboard-Power-BI-Project
 
Power BI dashboard analyzing hospital patient flow, bed utilization &amp; billing (PDF &amp; screenshots) as my learning project

**Overview**  
Interactive Power BI dashboard analyzing hospital patient flow, diagnosis mix, bed utilization and billing vs insurance. Built from an instructor sample dataset (7000+ records) and enhanced with custom theme, DAX measures and UX-focused layout.

## Business Problem / Objective
Hospitals struggle to monitor patient flow, diagnosis mix, billing patterns and bed utilization from a single analytical view.  
This dashboard enables decision makers to track patient admissions, costs, diagnosis trends, length of stay and insurance dependency to support better operational efficiency.  
**Dataset Description**
Contains: Patient ID, Admit/Discharge Dates, Bed Type, Diagnosis, Billing Amount, Insurance Amount, Follow-up Dates etc.  
During cleaning, invalid follow-up year values were corrected and normalized.

## Key Business Questions Answered Through This Dashboard
This dashboard provides actionable insights for multiple operational decision areas:

1) **Patient-Level Snapshot** — Identify clinical journey for individual patient using Patient_ID slicer (admit date, discharge date, follow-up date).  
2) **Billing Intelligence** — Understand total billing generated, insurance dependency and cost burden per diagnosis.  
3) **Bed Occupancy Breakdown** — Evaluate distribution of Private, General & ICU beds for optimizing capacity planning.  
4) **Doctor Feedback Summary** — View patient satisfaction feedback aggregated for doctors to analyze care quality trend.  
5) **Diagnosis Pattern Statistics** — Identify highest occurring diagnoses and their contribution to volume and revenue.  
6) **Billing vs Insurance Pattern** — Compare total billed amount vs insurance coverage trends over time to analyze financial structure and risk exposure.
   
## Key insights
- **Avg Length of Stay:** ≈ 8.25 days  
- **Total billing:** ₹190M+ (Insurance covers ≈ 90%)  
- **Top diagnoses:** Viral Infection (2,004), Flu (1,717), Malaria (1,431)  
- **Bed occupancy:** Private 3,579 > General 2,385 > ICU 1,193  
- **Top revenue contributors:** Viral Infection (₹53.4M), Flu (₹45.8M)
- Insurance covers approx **90%** of all billing, reducing direct out-of-pocket patient burden
 
**Files included(to view click on images folder):**

 (1) Full dashboard overview -
   Gives the full top-level hospital patient performance view at a glance with all major KPIs and visuals in one frame.    
 (2) Bed occupancy insight -
   Shows how beds are utilized across Private, General, and ICU categories highlighting where patient load is highest.  
 (3) Diagnosis distribution -
   Breaks down disease distribution to reveal which diagnoses contribute most to patient volume.  
 (4) Billing vs Insurance trend -
   Displays total billing trends along with insurance share to understand financial impact and cost coverage.  
 (5) KPI tiles -
   Presents the core KPI tiles including average length of stay, billing amount, and follow-up metrics for quick decision     reference.
   


**How it was built**
- Tools: Power BI Desktop, Excel (data cleaning)  
- Data cleaning steps: normalized date columns, corrected invalid follow-up dates (replaced follow up year  values), handled nulls and trimmed diagnosis strings.

**Usage**
Open `Healthcare Project Dashboard.pbix` in Power BI Desktop to explore interactive visuals. Use the slicer for Patient_ID to drill into patient-level records. Screenshots & PDF included for quick preview.

## Conclusions
Insurance providers cover a major share of total billing (~90%), reducing patient OOP expense.  
Viral Infection & Flu together contribute to over 50% of patient volume and majority of revenue impact.  
Private beds are the most utilized suggesting pressure on private bed capacity allocation.

## Future Work
- Add outcome scoring and patient satisfaction metrics layer

## Contact :
Sakshi Upadhyay  
LinkedIn: https://www.linkedin.com/in/sakshiupadhyayofficial

Email: <upadhyaysakshi93@gmail.com>

---
