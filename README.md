#  Investment Preference Analysis Dashboard

This Power BI dashboard presents insights into investor behavior based on survey data. It analyzes investment preferences across different durations, age groups, and expectations, using dynamic visuals and KPIs.



##  Dataset Used

**File Name:** `Finance_data.csv`

**Contains:**
- Demographic Fields: `age`, `gender`, `duration`, `expect`
- Investment Types (scored 1–10): 
  - Mutual Funds
  - Equity Market
  - Debentures
  - Government Bonds
  - Fixed Deposits
  - PPF
  - Gold



##  Objectives

- Identify the most **preferred** and **most used** investment options
- Understand patterns based on **investment duration**
- Include interactivity through **slicers** and dynamic visuals
- Simulate **time-series analysis** using the `duration` field



##  Key Features

###  KPI Cards
- **Average Age of Investors**
- **Most Preferred Investment** (by average score)
- **Top Investment Score**
- **Most Used Investment** (by total score)

###  Visuals
- **Bar Chart:** Average Score by Investment Type
- **Bar Chart:** Total Score by Investment Type
- **Line Chart:** Avg. Score by Duration *(Time Series)*

###  Interactivity
- Slicers for `gender`, `duration`, and `expect`
- All visuals update based on selected filters



##  Time-Series Analysis

Although the dataset lacks date fields, time trends were simulated using the **investment `duration`** column. A line chart was used to visualize changes in average preference over different durations (e.g., 1 year, 3 years, 5 years).



##  Tools & Techniques

- **Power BI Desktop**
- Data Cleaning using **Power Query**
- **Unpivoting** investment columns for long-format analysis
- DAX Measures:
  - `Top_Investment_Score`
  - `Most_Preferred_Investment`
  - `Top_Total_Score`
  - `Most_Used_Investment`



##  Design Notes

- Consistent color theme (blue = averages, green = totals)
- Clear titles and formatted slicers for a clean user experience
- Navigation logic grouped by KPI → Insight → Detail



##  Deliverables

| File                          | Description                          |
|-------------------------------|--------------------------------------|
| `Finance_data.csv`            | Raw dataset                          |
| `Investment_Analysis.pbix`    | Power BI dashboard file              |
| `Investment_Preference_Analysis_Summary.pptx` | Summary presentation      |
| `README.md`                   | Project explanation (this file)      |




## ✅ Conclusion

This project demonstrates how survey-based financial data can be transformed into meaningful insights using Power BI. Despite the absence of true time data, the dashboard uses investment duration to simulate trends, ensuring interactivity and value for financial decision-makers.


