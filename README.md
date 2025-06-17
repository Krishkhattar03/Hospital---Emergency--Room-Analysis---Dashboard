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

✅ Created a clean dashboard layout with KPI cards, donut charts, and bar charts

✅ Added slicers for month and year interactivity.

✅ Saved and exported the final dashboard screenshot and file. (https://github.com/Krishkhattar03/Hospital---Emergency--Room-Analysis---Dashboard/blob/main/Screenshot.jpg)

# Dashboard Interaction 
![WhatsApp Image 2025-06-16 at 12 21 45_a4c25130](https://github.com/user-attachments/assets/839f5c5d-74ce-4e5f-9313-6694535ea085)



# Final Conclusion & Key Insights

This project successfully demonstrates how a well-structured Excel dashboard can transform raw hospital data into actionable insights for healthcare administrators. The dashboard provides a real-time, interactive overview of ER performance across critical dimensions such as wait time, admission rates, patient satisfaction, and demographic distribution.

Key Takeaways:

The average wait time (35.5 mins) is reasonable, but there is room to reduce delays further, especially for the 39% of patients who arrived late or were delayed.

The patient satisfaction score of 4.71/5 indicates a generally positive experience, suggesting strong operational efficiency and staff responsiveness.

Age group 70–79 had the highest patient volume, signaling the need for geriatric-friendly care and staffing in the ER.

While most referrals came without a department tag (291), General Practice and Orthopedics contribute significantly to ER traffic and should be monitored closely.

Gender distribution is nearly equal, with 51% female and 49% male patients, indicating balanced healthcare access.

The admission rate of 52% vs. 48% discharged suggests that the ER is functioning as both a triage and care point — an indicator of efficient decision-making.

The dashboard is not only a reporting tool but also a strategic asset that helps prioritize improvements in ER logistics, patient flow, and resource planning.

