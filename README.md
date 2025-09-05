# Australian-Hospital-Performance-Dashboard
analysis
🏥 Australian Hospital Performance Dashboard (2021–2025)

A Power BI project analyzing hospital performance across Australia using synthetic + publicly available data. The dashboard evaluates efficiency, patient outcomes, healthcare access, and financial performance to provide actionable insights for policymakers, recruiters, and healthcare leaders.

🎯 Project Purpose

Healthcare is one of Australia’s largest and most critical sectors. Hospital performance directly impacts patient care, public health outcomes, and system sustainability.

This project aims to:

Monitor Emergency Department (ED) efficiency using wait times and triage compliance.

Assess quality of care via readmission and mortality rates.

Compare public vs private hospitals in terms of admissions, satisfaction, and profit.

Provide recruiters and managers with a clear, interactive dashboard for decision-making.

📊 Dashboard Overview

The dashboard consists of three main sections:

🔹 1. KPI Summary (Top Row)

Quick performance snapshot:

Avg ED Wait Time (Minutes)

% Seen On Time (patients seen within recommended triage time)

Readmission Rate (%) (within 30 days)

Mortality Rate (per 1000 admissions)

Patient Satisfaction (%)

Profit (Million AUD)

👉 These KPIs give recruiters and managers an instant view of system health.

🔹 2. Trends & Comparisons (Middle Section)

Line Chart: ED Wait Time by Year & State → shows system pressure rising over time.

Clustered Bar Chart: Admissions by State & Hospital Type → highlights state-by-state demand and public/private differences.

🔹 3. Performance Breakdown (Bottom Section)

Heatmap/Matrix: Mortality Rate by State & Year → benchmarks performance across regions.

Donut Chart: Public vs Private Hospital Share → shows proportional service usage.

🔍 Key Insights

From the dataset (2021–2025), several insights stand out:

Admissions

NSW and VIC dominate admissions, matching their population.

Smaller states (TAS, NT) show fewer admissions but higher mortality rates.

Profitability vs Satisfaction

Private hospitals are more profitable but show lower patient satisfaction.

Public hospitals remain essential for equitable access and trust.

Emergency Department Pressure

ED wait times worsened in 2024–2025, with some states exceeding 25+ minutes average wait.

Indicates staffing shortages and higher patient load.

Readmission Rates

Chronic diseases (diabetes, heart conditions) drive repeat admissions.

Suggests need for better preventive care and follow-up systems.

Mortality Gaps

Rural states show 10–15% higher mortality rates per 1,000 admissions.

Signals disparities in healthcare access and resources.

⚒️ Tools & Skills Demonstrated

Power BI Desktop: Dashboard creation, slicers, interactive visuals.

Power Query: Data cleaning, transformation, removing nulls.

DAX Measures: Calculated KPIs (e.g., Avg Wait Time, Readmission %).

Data Modeling: Fact table with dimension tables (State, Hospital Type).

Storytelling with Data: Translating raw data → meaningful insights.

📂 Repository Contents

AU_Healthcare_1500_Rows.csv → Clean dataset (2021–2025).

Australian_Hospital_Dashboard.pbix → Power BI dashboard file.

README.md → Project description (this file).

/assets → Dashboard screenshots & sample insights.

🚀 How to Use

Download this repo → open .pbix file in Power BI Desktop.

Explore slicers: Year, State, Hospital Type.

Hover over visuals for tooltips & drill-through insights.

Use with real datasets (AIHW, ABS) by replacing the CSV.

📈 Future Enhancements

Add forecasting for admissions & wait times.

Integrate staffing & resource data (doctor/nurse ratios, ICU capacity).

Include cost per admission (IHACPA data).

Build patient-level drill-down reports for deeper insights.
