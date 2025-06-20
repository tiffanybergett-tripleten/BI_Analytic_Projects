# SuperStore Consult

This was the fourth project that I worked on in the TripleTen Business Intelligence Analytics Program.  
It was an independent project designed to showcase what I have learned about Tableau Visualization.  
The purpose was to consult the company by reviewing the store’s operations and increasing its profitability to avoid bankruptcy.  

🎥 **The Loom Video Overview** can be found [HERE](https://www.loom.com/share/ce4f7d6c63a4489d9f6d8f430ba3f3d9?sid=55211fb8-68b2-4489-ab4b-e9010cad830b)  

## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | [DataSet - SuperStore.xls](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Consult/DataSet%20-%20SuperStore.xls) | The original data file provided by TripleTen that was used in the analysis of this project. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Consult/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Reviewer Grade.png](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/SuperStore%20Consult/Reviewer%20Grade.png) | This is the comments left by my project reviewer. |

---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#process) | A general outline of how this project formed from start to finish. |
| [Data](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#data) | Describes the source of data, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#assumptions) | Describes assumptions to include those given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/SuperStore%20Consult#recommendations) | Recommended direction for the stakeholders based on the final analysis. |

### Description:
- 7-page Tableau Visualization
- Includes data analysis, charts, and a dashboard.  
**Tableau Public** Share Link can be found [HERE](https://public.tableau.com/views/SuperStoreConsult/ProfitLossbySubcategory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)    

### Process:
1) Left Joined `'returns'` table to `'orders'` table.  
2) Determined profit and loss centers.  
3) Analyzed the worth of advertising during the company's triage phase.
4) Created a Calculated Field  - `IF` formula for a Return Rate Measurement.
5) Briefly examined the contribution returns various dimensions to profits.  

### Data
The data was one Excel spreadsheet file provided by TripleTen:
- `'Superstore.xls'`: Each row corresponds to one product sold
    - `'orders'`: details all fields for each ordered item
    - `'returns'`: details all fields for each returned item

### Assumptions:
- Profits from sales are totaling in the negative.	
- There is one or more causes for negative profits directly related to orders and returns.
- The operations department will need to make changes.
- The advertising department needs recommendations.

### Findings:
1. Subcategories of profit centers are Copiers, Phones, and Accessories, while loss centers are Tables, Bookcases, and Supplies based on profits.
2. Profit Centers are Office Supplies and Technology in the West Region, while loss centers are Office Supplies and Furniture in the Central Region, based on profits.
3. Several products are causing negative profits, some with as high as $20k in losses.
4. Advertising campaigns should be targeted towards Indiana in October, Vermont in November, and Washington in March.
5. Returns are a serious problem, with many products having return rates as high as 100%.
6. There are several customers with return rates as high as 100%.
7. When considering average profits vs return rate, there are a few individual products that are not worth selling, and many products left to consider continuing or not.

### Recommendations:
1. Continue to optimize sales and marketing efforts in profit centers to maintain profitability. Invest in marketing and product development to further capitalize on their success.
2. Conduct a thorough analysis to identify the underlying reasons for losses. Consider product adjustments, pricing strategies, or operational changes to improve performance. If these products consistently generate negative profits, consider discontinuing them.
3. Investigate products with negative profits. If these products consistently generate negative profits, consider discontinuing them.
4. Target advertising campaigns while allocating advertising budgets of 1/5 of the state's monthly profits during their most profitable seasons to maximize returns. Consider regional preferences and market trends when designing advertising campaigns.
5. Investigate high return rates, as this is a significant contributor to negative profits.
6. Analyze customer behavior to identify repeat offenders and take appropriate measures to address their concerns and implement customer loyalty programs.
