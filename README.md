📊 Call Center Performance Dashboard - Excel Project

📌 Overview
This project is a Call Center Performance Dashboard built using Microsoft Excel. The dashboard integrates various data analysis and visualization techniques, including:
- Power Pivot for data modeling
- Slicers for interactivity
- Pivot Tables & Charts for dynamic reports
- Conditional Formatting for insights

This project is ideal for Excel users who want to enhance their data analytics skills and build a portfolio-worthy dashboard.

🎯 Features
- Dynamic Report: View performance metrics for individual representatives.
- Data Modeling: Combines call data and customer data.
- Interactivity: Use slicers to filter results dynamically.
- Trend Analysis: Monthly and weekly breakdown of calls.
- Performance Metrics:
  - Total calls & call duration
  - Average satisfaction ratings
  - Number of 5-star rated calls
  - Call trends and breakdown by city & gender
  - Representative performance rankings
- Custom Formatting & Theming:
  - Custom color themes & fonts for professional design.
  - Icons & images for better visualization.

🛠️ Technologies Used
- Microsoft Excel 365
- Power Pivot (Data Model & DAX Measures)
- Pivot Tables & Charts
- Conditional Formatting
- Excel Slicers

📂 Dataset
The dataset consists of:
1. Call Data: Call number, representative, customer details, call duration, satisfaction rating, and purchase amount.
2. Customer Data: Customer ID, gender, age, and city.

📌 Step-by-Step Guide
### 1️⃣ Data Preparation
- Load call data and customer data into Excel.
- Format data types correctly (dates, numbers, text).
- Create a relationship between `Customer ID` in both datasets.

2️⃣ Setting Up the Dashboard
- Create a new worksheet for the dashboard layout.
- Apply custom colors & fonts.
- Insert a pivot table for overall summary calculations.
- Create a pivot table for representative-level performance.
- Add slicers to filter by representative dynamically.

3️⃣ Calculations & DAX Measures
Create DAX measures using Power Pivot, including:
```DAX
Call Count = COUNTROWS(Calls)
Total Amount = SUM(Calls[Purchase Amount])
Avg Rating = AVERAGE(Calls[Satisfaction Rating])
5-Star Calls = CALCULATE([Call Count], Calls[Rating Rounded] = 5)
```

4️⃣ Interactive Charts
- Monthly Call Trends (Line Chart)
- Weekly Call Trends (Bar Chart)
- Representative Comparison (Bar Chart with Data Overlays)
- Customer Demographics (Stacked Bar Chart for Gender & City)
- Satisfaction Ratings (Column Chart)

5️⃣ Conditional Formatting
- Highlight top-performing representatives.
- Use data bars to show revenue distribution.
- Apply color coding for easier visualization.

📸 Screenshots
*(Include dashboard screenshots here)*



