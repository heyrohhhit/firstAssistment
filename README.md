::: {align="center"}
# 📊 HR Analytics Dashboard

### Turning workforce data into clear, actionable HR insights

An Excel-based HR analytics dashboard designed to explore employee
headcount, attrition, demographics, job roles, departments, education,
and marital status through an interactive, visual report.

```{=html}
<p>
```
`<img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>`{=html}
`<img src="https://img.shields.io/badge/Project-HR%20Analytics-0F6CBD?style=for-the-badge" alt="HR Analytics"/>`{=html}
`<img src="https://img.shields.io/badge/Focus-Data%20Visualization-7B61FF?style=for-the-badge" alt="Data Visualization"/>`{=html}
`<img src="https://img.shields.io/badge/Status-Portfolio%20Project-2EA44F?style=for-the-badge" alt="Portfolio Project"/>`{=html}
```{=html}
</p>
```
:::🖼️ Dashboard Preview
The screenshots below show the dashboard layout and its visual
components. The dashboard is designed around a blue theme, KPI cards,
charts, and Excel slicers.

::: {align="center"}
### Main dashboard

`<img src="assets/hr-analytics-dashboard.png" alt="HR Analytics Dashboard showing KPIs, employee charts, and slicers" width="100%"/>`{=html}

### Alternate layout / comparison view

`<img src="assets/hr-analytics-dashboard-layout.png" alt="Alternate HR Analytics Dashboard layout showing KPI cards, charts, and slicers" width="100%"/>`{=html}
:::🎯 Project Overview
The HR Analytics Dashboard presents key workforce metrics in one
place to make HR data easier to understand. Instead of reviewing rows of
employee records individually, a viewer can use summary indicators and
charts to identify patterns in employee attrition, department
distribution, job roles, age groups, gender, and marital status.

This project demonstrates practical skills in Excel reporting, data
summarization, dashboard layout, chart design, and interactive
filtering.
Business questions this dashboard helps explore
- 👥 How many employees are in the workforce?
- 🚪 How many employees have left, and how many remain active?
- 📉 What is the overall attrition rate?
- 🧑‍🤝‍🧑 How is the workforce distributed by gender?
- 🏢 How many employees work across departments and job roles?
- 🎂 Which age groups contain the most employees?
- 💍 How is the workforce distributed by marital status?
- 🎓 How can the education category and attrition status be explored
  together?
- 🔎 How do the displayed metrics change when slicers are used?
📌 Key Metrics at a Glance
The values below are the figures displayed in the supplied dashboard
screenshots.
  KPI                                Displayed value What it represents
  Total Employees                          1,470 Total employee
                                                     records represented
                                                     in the dashboard

  Attrition                                  237 Employees recorded as
                                                     having left

  Active Employees                         1,233 Employees remaining
                                                     active

  Attrition Rate                           16.1% Share of employees
                                                     recorded as attrition

  Average Age                               36.9 Average employee age
                                                     displayed
  Job Satisfaction                           2.6 Average rating shown
  Rating                                             in the dashboard
Metric note: These values are transcribed from the screenshots.
Confirm the formulas and source data in the workbook before using the
figures for formal business reporting.
📊 Dashboard Components
  Component                           Purpose
  KPI cards                       Provide a quick overview of
                                      employee count, attrition, active
                                      employees, attrition rate, and
                                      average age

  Job Satisfaction indicator      Highlights the displayed average
                                      job satisfaction rating

  Gender view                     Compares the employee counts shown
                                      for female and male employees

  Department-wise employee status Shows the employee distribution
                                      across HR, R&D, and Sales

  Job area / role chart           Compares employee counts across job
                                      roles

  Age-group chart                 Displays the employee distribution
                                      across age brackets

  Marital status report           Compares the counts shown for
                                      Divorced, Married, and Single
                                      employees

  Attrition slicer                Filters the report by attrition
                                      status, such as Yes or No

  Education slicer                Allows exploration by education
                                      category

  Department slicer               Allows exploration by department

  Marital status slicer           Allows exploration by marital
                                      status
  Gender slicer                   Allows exploration by gender
🧰 Tools & Skills Demonstrated
- Microsoft Excel --- dashboard development and reporting
- PivotTables / summarized data --- aggregating employee records
  for analysis
- PivotCharts / charts --- communicating workforce patterns
  visually
- Slicers --- interactive filtering of dashboard views
- KPI cards --- presenting key metrics prominently
- Dashboard design --- consistent color palette, alignment,
  spacing, and hierarchy
- HR analytics --- employee headcount, demographics, and attrition
  reporting
The exact workbook implementation may vary. The list above describes
the techniques represented by the dashboard design; check the workbook
to confirm which Excel objects and formulas were used.

🔍 How to Explore the Dashboard
1. Open the Excel workbook containing the dashboard.
2. If Excel displays a security or Protected View notice, only enable
   editing if the file is from a trusted source.
3. Use the slicers on the right side of the dashboard to select an
   attrition status, education category, department, or marital status.
4. Use the gender slicer to explore the gender-related view.
5. Observe which connected PivotTables, charts, and KPI values update
   after a selection.
6. Clear a slicer selection to return to the broader view. In Excel,
   the clear-filter icon is usually shown in the slicer's header.
7. Compare the results across categories and look for workforce
   patterns worth investigating.
Interaction note: Slicers only update the PivotTables/charts they
are connected to. If an element does not change when a slicer is
selected, check the workbook's Report Connections / PivotTable
Connections.
📁 Suggested GitHub Repository Structure
Keep the README and dashboard screenshots together so the images display
correctly on GitHub.
hr-analytics-dashboard/
├── README.md
├── assets/
│   ├── hr-analytics-dashboard.png
│   └── hr-analytics-dashboard-layout.png
└── HR-Analytics-Dashboard.xlsx   # Add your workbook here
The Excel workbook is not included in this package because it was not
supplied with the screenshots. Add your .xlsx file to the repository
if you want visitors to download and inspect it.
🚀 Getting Started
View the project
1. Open this repository on GitHub.
2. Review the dashboard screenshots in the Dashboard Preview
   section.
3. If the workbook is included, download HR-Analytics-Dashboard.xlsx.
4. Open the workbook in Microsoft Excel to inspect the data, charts,
   and slicer behavior.
Reproduce or extend the dashboard
1. Prepare a clean employee-level dataset.
2. Check column names, data types, missing values, and inconsistent
   category labels.
3. Create summary tables or PivotTables for the metrics and categories
   you want to report.
4. Insert charts that match the analysis questions.
5. Add slicers and connect them to the relevant PivotTables.
6. Build KPI cards and arrange the visuals into a clear dashboard
   layout.
7. Validate all calculations against the underlying records.
8. Save the workbook and capture updated screenshots for the README.
💡 Possible Future Improvements
- 📈 Add monthly or yearly attrition trends if date fields are
  available.
- 🧭 Add a clear-filter / reset-filters guide for dashboard users.
- 🧮 Add a definitions sheet documenting each KPI and its formula.
- 🧑‍💼 Compare attrition by tenure, age group, department, and job role
  where the data supports it.
- 🎨 Improve accessibility with consistent contrast, readable labels,
  and color-independent indicators.
- 🧪 Add a data-quality check for blanks, duplicates, and inconsistent
  category names.
- 📄 Include a short data dictionary and a note about the dataset's
  source and limitations.
⚠️ Data & Interpretation Notes
- The README documents the dashboard shown in the screenshots; it does
  not independently verify the source dataset or workbook formulas.
- Treat the displayed metrics as descriptive figures, not proof that
  one factor causes employee attrition.
- Avoid publishing employee names, email addresses, IDs, or other
  personal information in a public repository.
- If the workbook uses sample, synthetic, or third-party data, clearly
  identify the source and follow its license or usage terms.
- Validate KPI definitions, filters, and calculations before using
  this dashboard for real HR decisions.
👤 Author
Rohit
Advance Computer & Data Visualization --- portfolio project
- GitHub: @heyrohhit
::: {align="center"}
### ⭐ If this project is useful, consider starring the repository.

Made with 📊, Excel, and a focus on making data easier to understand.
:::
