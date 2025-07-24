📊 Corporate Financial Insights Dashboard :

A professional Power BI dashboard providing detailed insights into corporate financial health and efficiency. Designed to showcase data analytics capabilities relevant to real-world business scenarios.

🔍 Overview :

This project focuses on delivering actionable financial insights across key business areas:

--> Summary KPIs

--> Revenue & Sales Trends

--> HR Efficiency Metrics

--> Expense Breakdown

--> Budget vs Actual Performance


🧰 Tech Stack :

--> Microsoft Excel

--> Power BI Desktop

--> DAX (Data Analysis Expressions)

--> Data Modeling

--> Interactive Slicers


📁 Pages in the Report and their key elements :


| Page                 | Key Elements                             |
| -------------------- | ---------------------------------------- |
| Summary              | KPI Cards, Monthly Trends, Navigation    |
| Sales                | Avg Deal Size, Profit Margin             |
| HR                   | Headcount Trends, Avg Monthly Headcount  |
| Expense              | Category-wise Expense Visuals            |
| Budget vs Actual     | Variance Analysis, KPI Comparison        |


📌 Key Measures (DAX)
Some of the key DAX calculations include:

Total Revenue = SUM(SalesData[Revenue])

Net Profit = SUM(SalesData[Net_Profit])

Profit Margin (%) = DIVIDE([Net Profit], [Total Revenue], 0)

Average Deal Size = DIVIDE([Total Revenue], DISTINCTCOUNT(SalesData[InvoiceID]), 0)

Revenue Variance (%) =
DIVIDE(
    [Total Actual Revenue] - [Total Budgeted Revenue],
    [Total Budgeted Revenue],
    0
)


📎 File :
Corporate_Financial_Insights.pbix — Main dashboard file
