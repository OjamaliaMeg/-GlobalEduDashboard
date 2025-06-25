
##  Overview

This Excel dashboard explores the relationship between **literacy rates** and **internet access** across different countries and regions from **2022 to 2024**. It enables users to visually compare trends and identify gaps in digital and educational equity using interactive tools.

##  Data Preparation

- Restructured the dataset to **long format** for PivotTable compatibility.
- Added **Year**, **Country**, and **Region** fields for dynamic filtering.
- Cleaned numerical data:
  - Removed non-numeric characters (e.g., `%`, symbols).
  - Ensured all values are in proper numeric format.
- Added derived fields for easier comparison (e.g., Metric type: Literacy or Internet Access).

## Analysis & Visualizations

- Built PivotTables to analyze key questions:
  - How do literacy rates and internet access change over time?
  - Which countries or regions show the widest education access gaps?
  - Where does high internet penetration not correlate with literacy gains?
- Created a multi-line **PivotChart** to display both metrics over time.
- Enabled **interactive slicers** for:
  - Filtering by **Country**
  - Filtering by **Region**
- Highlighted trends, such as:
  - Strong performers in both metrics.
  - Countries with high internet access but low literacy growth.
  - Regions where investment in digital infrastructure may be needed.

##  How to Use

1. Open the Excel file: `Literacy_Internet_Dashboard.xlsx`
2. Go to the **Dashboard** sheet.
3. Use the **slicers** to filter by:
   - Country
   - Region
4. Hover over the line chart to explore yearly values for Literacy Rate and Internet Access.
