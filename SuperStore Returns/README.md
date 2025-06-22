# SuperStore Returns

This was the fifth project that I worked on in the TripleTen Business Intelligence Analytics Program.  
It was an independent project designed to showcase what I have learned for Tableau Dashboards and Story Telling.  
The purpose was to prepare an analysis for the CEO of Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.  

🎥 **The Loom Video Overview** can be found [HERE](https://www.loom.com/share/74d93fb0067c4649b51ceb65fc0f221c?sid=57e2a8a3-db62-4f12-af46-50030f1b1dd2)  

## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | [DataSet - SuperStore.xls](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Returns/DataSet%20-%20SuperStore.xls) | The original data file provided by TripleTen that was used in this project's analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Returns/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Reviewer Grade.png](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Returns/Reviewer%20Grade.png) | This is the comments left by my project reviewer. |
| 5 | [SuperStore Returns.pdf](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Returns/SuperStore%20Returns.pdf) | This is a PDF version of my project for easy viewing. |
---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Returns#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Returns#process) | Describes the process, including the tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Returns#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Returns#assumptions) | Describes assumptions to include those given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Returns#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Returns/README.md#recommendations) | Recommended direction for the stakeholders based on the final analysis. |

### Description:
- 7 Tableau Visualizations, 1 Dashboard, and a 10-page Story Presentation
- Includes data analysis, charts, dashboard, and Tableau story  
**Tableau Public** Share Link can be found [HERE](https://public.tableau.com/views/SuperStoreReturns_17275522394170/Presentation?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
  
### Process:
1) Left Joined `'returns'` table to `'orders'` table.
2) Created a Calculated Field  - `IF` formula for a Return Rate Measurement.
3) Examined the in-depth contribution of returns for various dimensions using visualizations to determine what is causing returns.  
4) Built a dashboard for monitoring returns.  
5) Created a Tableau story to present my findings.
6) Created a video presentation for Asynchronous Stakeholders.

### Data
The data was one Excel spreadsheet file provided by TripleTen:
- `'Superstore.xls'`: Each row corresponds to one product sold
    - `'orders'`: details all fields for each ordered item
    - `'returns'`: details all fields for each returned item

### Assumptions:
1) Profits from sales are totaling in the negative.	
2) There is one or more causes for negative profits directly related to orders and returns.
3) The operations department will need to make changes.

### Findings:
- There are several customers with unusually high return rates; Several customers have a return rate of 100%.
- There are several products with unusually high return rates; Several products have a return rate of 100%.
- The location where the order was delivered, Utah being a particular problem.
- Orders are returned significantly more in August, with September close behind, corresponding with increased purchases.

### Recommendations:
1) Employee training in the technology department to better assist customers in choosing the right product.
2) Reach out to customers with a 100% return rate to determine the reasons behind their decision. Implement any changes needed in our website or shipping partners that are causing these returns.
3) As triage, immediately stop selling the problem products.
4) Focus internal efforts on updating product information and size guides and promoting customer reviews via social media collaborations.
5) Consider stricter return policies or charging a return fee for purchases made in problem states.
6) Adjust promotional strategies such as promoting gift cards for holiday peaks, and shifting from discounts to value-added, like free shipping.
