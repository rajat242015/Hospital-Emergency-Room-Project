# Hospital-Emergency-Room-Project
I have created a Hospital Emergency Room Analysis Dashboard in Excel to improve efficiency and provide useful insights. This dashboard will help stakeholders monitor, analyze, and make better decisions for managing patients and improving services.
# Transforming Raw Data into Actionable Insights: Emergency Room Dashboard

## Project Overview
I’m thrilled to share a dashboard project I developed from scratch using raw operational and patient data from a hospital Emergency Room (ER). The goal was to move beyond static reports and craft a dynamic, intuitive visual tool that clearly answers pressing questions around patient volumes, wait times, satisfaction and referral patterns — enabling the ER leadership and clinical team to make data-driven decisions.

## Dataset source: 
<a href="https://www.kaggle.com/datasets/xavierberge/hospital-emergency-dataset">Dataset</a> 


## Dashboard Purpose & Scope
This dashboard addresses the core operational and quality-of-care challenges within an ER environment:
- How many patients are arriving each day, and how does that change over time?
-	How long are patients waiting before being seen — and which days or conditions cause delays?
-	How satisfied are patients with their ER experience, and do trends in satisfaction correlate with operational pressures?
-	Which age groups and genders are being seen, and what referral patterns (to other departments) are emerging?
-	What proportion of patients are admitted versus not admitted, and what does that indicate about throughput, capacity and referral decisions?

## Dashboard Image:
![Hospital Emergency Room Final Dashboard](https://github.com/user-attachments/assets/d7dac311-be68-4a16-bcf9-95ec1370fd7a)



## Key Metrics & Visualisations
Here are the primary metrics tracked, how I visualised them, and why they matter:
1.	Number of Patients (Daily Count & Trend)
-	Metric: Total number of patients visiting the ER each day.
-	Visualisation: Daily trend displayed via an area chart so that peaks, troughs and seasonal patterns become obvious at a glance.
-	Why it matters: Understanding daily volume helps detect busy days, seasonal surges or unusual drops — enabling staffing adjustment, resource allocation and process optimisation.

2.	Average Wait Time
o	Metric: The average time patients wait from arrival to seeing a medical professional.
o	Visualisation: A daily sparkline/area trend, with high-wait days highlighted for further investigation.
o	Why it matters: Wait time is a key operational indicator — prolonged waits can degrade patient experience, increase risk and signal bottlenecks in triage or staffing. According to industry guidance, wait time is among the most critical process-time indicators in an ER setting. 

4.	Patient Satisfaction Score
o	Metric: The average daily satisfaction score reported by patients (via surveys/feedback).
o	Visualisation: Daily trend line or sparkline to display how satisfaction evolves, and to link dips with high volume or long waits.
o	Why it matters: Satisfaction is both a quality and a reputational metric. It helps link operational performance (volume, wait time) with patient experience and quality outcomes. When satisfaction drops, it often correlates with pressures elsewhere.

6.	Patient Admission Status
o	Metric: The number and percentage of patients admitted versus not admitted (e.g., discharged or treated and sent home).
o	Visualisation: A simple table or bar/pie chart showing admitted vs not admitted + grand total, plus % of each.
o	Why it matters: Admission status gives insight into hospital throughput, bed demand, severity of presenting patients and resource utilisation.

7.	Patient Age Distribution
o	Metric: Count of patients by age group (0-9, 10-19, …, 70-79, etc).
o	Visualisation: Bar chart by age group to show which segments dominate the volume.
o	Why it matters: Age distribution helps identify which cohorts the ER serves most, enabling targeted staffing, equipment readiness and service planning.

9.	Gender Analysis
o	Metric: Number/percentage of patients by gender (Male, Female).
o	Visualisation: Pie chart or doughnut showing male vs female share.
o	Why it matters: Demographic context helps in understanding patient mix, potential equity/representation issues, or service tailoring by gender.

10.	Department Referrals
o	Metric: Count of patients referred from the ER to various departments (General Practice, Orthopaedics, Cardiology, Neurology, Gastroenterology, etc).
o	Visualisation: Horizontal bar chart ranked by the number of referrals to each department.
o	Why it matters: Referral patterns can spotlight which downstream specialties are most utilized, where bottlenecks may exist, and where cross-department coordination can be improved.

## What This Dashboard Enables
•	Operational Monitoring: With daily counts and wait-time trends, ER leadership can anticipate high-load days and proactively allocate resources.
•	Quality Linkage: By showing satisfaction in parallel with operational metrics, the dashboard builds a bridge between process performance and patient-experience.
•	Strategic Insights: Age distribution and referral patterns guide long-term planning — e.g., if older age bands are increasing, orthopaedics or cardiology demand may rise.
•	Actionable Visibility: The visual design is built for clarity — anyone on the team can see: “Here’s a day when volume peaked, wait times climbed, satisfaction dropped and referrals to neurology increased” — leading to questions, root-cause investigation and corrective action.
•	Continuous Improvement: The dashboard is designed not just for one snapshot, but for ongoing monitoring and iterative improvement — trending month-to-month, benchmarking targets (for example: 80% of patients seen within 30 minutes), and enabling drill-downs.

## Technical & Process Highlights
•	Data extracted from raw ER logs: patient arrival timestamps, triage/reporting, wait time measurements, satisfaction feedback, gender, age, referral department, admission status.
•	Data transformation: Created age bands, measured daily averages and counts, calculated percentage of patients seen within target time window.
•	Visualisation design: Selected clean, intuitive charts (area charts for trend, pie/doughnut for gender, bar charts for age distribution and referrals, tables for admission status) to ensure quick comprehension and minimal clutter.
•	Dashboard layout: Designed for leadership, clinicians and operational staff — with a top-line summary (number of patients, average wait, satisfaction), and supporting visuals (age, gender, referrals) all on a single page.

## The Outcome & Next Steps
I’m proud of this work because it turns previously raw, unstructured data into a dashboard framework that speaks directly to key operational, quality-and-experience questions in the ER.
Going forward, the roadmap includes:
•	Adding trend-over-time (monthly or quarterly) views to detect longer-term shifts or seasonality.
•	Enabling drill-downs (e.g., click on an age band to see wait times by referral department).
•	Incorporating targets & alerts (e.g., flag days where wait time exceeds target, or satisfaction falls below threshold).
•	Deploying the dashboard for live/near-real-time use, enabling staff to monitor as events unfold.
•	Engaging stakeholders (ER directors, triage nurses, department heads) to refine visuals, define action-workflow links, and embed the dashboard into regular review meetings.

Dashboard link
<a href="https://github.com/rajat242015/Hospital-Emergency-Room-Project/blob/main/Hospital%20Emergency%20Room%20Final%20Dashboard.JPG">Dashboard</a>
