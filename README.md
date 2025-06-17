#    Hospital Emergency Room Dashboard

📋 Project Objective
Provide hospital administrators and clinical staff with a single‐page, at‑a‑glance view of key Emergency Room (ER) performance indicators, enabling data‑driven decisions to improve throughput, resource allocation and patient experience.

Specifically, the dashboard answers the following questions:

How many patients visited the ER this month?
→ The dashboard shows a KPI card displaying the total number of patients, which is 485.

How long did patients wait on average?
→ The average wait time is shown as 35.51 minutes using a KPI and trendline visualization.

What percentage of patients were admitted vs discharged?
→ The dashboard uses a stacked bar and donut chart to indicate that 52% were admitted and 48% were not admitted.

Are patients arriving on time or experiencing delays?
→ A donut chart visualizes that 61% of patients arrived on time while 39% experienced delays.

How does volume break down by age, gender and referral department?
→ Bar and column charts show the distribution of patients across age groups (highest in 70‑79), gender (51% female, 49% male), and department referrals (most referrals are 'None' and General Practice).

What is the overall patient‐satisfaction score?
→ The dashboard displays a satisfaction score of 4.71 out of 5 using a KPI with a trendline.

# 📂 Data Source

https://github.com/Krishkhattar03/Hospital---Emergency--Room-Analysis---Dashboard/blob/main/Hospital%20Emergency%20Room%20Data.csv

# Key Columns

Patient Id — unique hash per encounter 

Patient Admission Date — arrival timestamp (DD‑MM‑YYYY HH:MM) 

Patient Gender — Male | Female | Other | Unknown 

Patient Age — integer years 

Department Referral — source specialty (e.g., Cardiology, Orthopedics) 

Patient Admission Flag — True if admitted; False otherwise 

Patient Satisfaction Score — 1‐5 Likert scale 

Patient Waittime — triage‐to‐doctor minutes 

# Process to Build the Dashboard

✅ Collected synthetic emergency room patient data.

✅ Cleaned the data using Python (pandas).

✅ Performed basic EDA to understand structure and spot missing values.

✅ Calculated KPIs such as average wait time, satisfaction score, and admission rates.

✅ Grouped data by age, gender, and department referrals for segmentation.

✅ Imported clean data into Excel.

✅ Built PivotTables and PivotCharts.

✅ Created a clean dashboard layout with KPI cards, donut charts, and bar charts.

✅ Added slicers for month and year interactivity.

✅ Saved and exported the final dashboard screenshot and file.

