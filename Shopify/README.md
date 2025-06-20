# Shopify Platform

This was the 6th project that I worked on in the TripleTen Business Intelligence Analytics Program.  
It was an independent project designed to showcase what I have learned about Power BI.  
The purpose was to review the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites, and to figure out what key factors play into the success of a Shopify app.  

🎥 **The Loom Video Overview** can be found [HERE](https://www.loom.com/share/88359c245ed3425aa004cd2e5a1be3b3?sid=6c7a8349-16a9-47d6-a641-b0d51febcb10)  


## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Shopify/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [Shopify Summary.pdf](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Shopify/Shopify%20Summary.pdf) | A PDF file with Data Model, DAX Calculated Fields, and Dashboards. |

---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Shopify#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Shopify#process) | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Shopify#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Shopify#assumptions) | Describes assumptions to include those given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Shopify#findings) | Insights learned from the data analysis. |

### Description:
- 3-page Power BI Dashboard
- Includes data analysis, KPI cards, and Charts

### Process:
1) Connected the data source and created a relationship between tables.
2) Assessed the app store landscape, creating a Dashboard using a KPI card, charts, and text.  
3) Created another Dashboard to catalog review data with cards and charts.  
4) Analyzed app developers across review types on a third dashboard.  

### Data
The Excel file provided by TripleTen was public data scraped from the Shopify App Store.  
**Raw Data** can be found [HERE](https://docs.google.com/spreadsheets/d/1H-Kw1Li9bvq7rvCDOqgdjawhHeRl8SlU/edit?usp=drive_link&ouid=101031187502320177888&rtpof=true&sd=true)  
- `'shopify.xlsx'`: Excel Workbook containing 4 sheets:
    - `'apps'`: Details of the apps on the Shopify apps marketplace
    - `'apps_categories'`: Join tables to connect apps with categories
    - `'categories'`: Categories of the apps. Each app has multiple categories
    - `'reviews'`: Each review (row) contains information on the user's opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

### Assumptions:
1) The scraped data from Shopify websites is accurate and representative of the actual app landscape.
2) The data in the `'shopify.xlsx'` file is complete and consistent, with minimal missing values or inconsistencies.
3) The provided column names and data types in the tables accurately reflect their content.

### Findings:
- New Apps are more likely to be rated early in their deployment.
- Most apps are rated favorably.
- Reviews are higher for an app if a developer answers the review.
- Reviews that have been voted as helpful have a weighted average of 5.48.
- The app developer "Elfsight" has the highest combined ratings at 135.10 stars.
- The app developer "Pictorem" has the highest average helpful reviews at 50.
- The app developer "FireaApps" has responded to the highest number of reviews at 6,008 responses.
