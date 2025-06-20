# VentureInsight

This was an optional project with TripleTen. It involved performing a series of SQL-based data analysis tasks for VentureInsight, a research firm providing insights to venture capital firms. The goal was to understand the overall startup landscape, analyze funding patterns, identify industry influencers, and evaluate factors affecting startup success to help shape a quarterly investment report.

<!--
🎥 **[Video Overview – Click Here](#)**
-->

##  Table of Contents for Repository Artifacts

| File Number | Title         | Description                                           |
|-------------|---------------|-------------------------------------------------------|
| 1 | README.md | This current page, with all relevant information about the project. |
| 2 | [Exploring Startup Trends with SQL.pdf](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/VentureInsight/Exploring%20Startup%20Trends%20with%20SQL.pdf) | Prompt with SQL code containing all queries of the analysis in PDF format. |

---

##  Table of Contents for README

| Section Title   | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| [Description]() | Describes the project's purpose, software, and analytical focus.            |
| [Data]() | Describes the data source, including tables and key fields.                 |
| [Process]() | Describes the data analysis process and SQL techniques used.                |
| [Assumptions]() | Describes assumptions made during the analysis.                             |
| [Findings]() | Key insights learned from the data analysis.                                |
| [Recommendations]() | Actionable recommendations for investment strategies.                       |

### Description:

This project involves a comprehensive **Startup Landscape Analysis using SQL**, designed for VentureInsight, a research firm specializing in venture capital and startup investments. The analysis aims to provide **data-driven recommendations** for clients, focusing on:

- Understanding the success rate of startups (closed vs. operating/acquired).
- Benchmarking funding for specific sectors (e.g., US news companies).
- Analyzing acquisition trends (cash-based deals).
- Identifying industry influencers based on social media presence.
- Evaluating geographic investment patterns.
- Assessing funding round volatility and fund activity levels.
- Investigating the correlation between employee education and startup success.

**Software/Tools:**  
- SQL (for querying and analysis)  
- Database Management System (implicit)  
- ER Diagram (for data understanding)

<!--
Original Work can be found [HERE](URL).
-->

###  Data:

The analysis uses a comprehensive database tracking venture funds, startups, acquisitions, and key people in the industry. The structure is visualized via an ER Diagram.

**Key Tables and Fields:**

`company`:  
- `id`, `name`, `category_code`, `status`, `funding_total`, `country_code`

`fund`:  
- `id`, `name`, `invested_companies`, `investment_rounds`
  
`funding_round`:  
- `id`, `company_id`, `raised_amount`, `funded_at`, `is_first_round`, `is_last_round`
  
`acquisition`:  
- `id`, `acquiring_company_id`, `acquired_company_id`, `price_amount`, `term_code`, `acquired_at`
  
`people`:  
- `id`, `first_name`, `last_name`, `company_id`, `twitter_username`
  
`education`:  
- `id`, `person_id`, `degree_type`, `institution`

<!--
Raw Data can be found [HERE](URL).
-->

###  Process:

The project followed a structured analytical process, primarily utilizing SQL queries to extract, transform, and aggregate data from a relational database.

Key steps included:

- **Data Exploration**: Initial queries to understand overall startup statuses.
- **Filtering and Sorting**: `WHERE` clauses for criteria (e.g., `country_code`, `category_code`, date ranges) and `ORDER BY` for presentation.
- **Aggregation**: Using `COUNT`, `SUM`, `MAX`, `MIN`, and `AVG` with `GROUP BY` to summarize data.
- **Conditional Logic**: `CASE` statements for data categorization (e.g., fund activity levels).
- **Subqueries and Joins**: `IN` subqueries and `INNER JOIN` operations across tables (`company`, `funding_round`, `acquisition`, `people`, `education`, `fund`).
- **Data Validation**: `HAVING` clauses to filter aggregated results.

###  Assumptions:

1) The database structure and content are accurate and reflect real-world venture capital activity.
2) News-related companies are identified by `category_code = 'news'`.
3) Cash-based acquisitions are identified by `term_code = 'cash'`.
4) Twitter handles starting with “Silver” or containing “money” are valid influencer indicators.
5) For education impact, companies with `is_first_round = 1` and `is_last_round = 1` represent startups that closed after limited funding.

###  Findings:

The analysis uncovered the following insights:

- **Startup Landscape**: Total number of companies that have closed.
- **Sector Funding**: Total funding for US news-related companies, sorted by `funding_total`.
- **Acquisition Trends**: Total amount of cash-based acquisitions during 2011–2013.
- **Influencer Identification**: Individuals with specific Twitter patterns for outreach.
- **Geographic Investment**: Total money raised per country; top destinations identified.
- **Funding Round Volatility**: Dates with high variability in funding amounts.
- **Fund Activity**: Categorization of funds as `high_activity`, `middle_activity`, `low_activity`.
- **Strategy by Activity**: Average number of rounds per activity level.
- **Employee Education Impact**: Avg. number of degrees per employee at startups that closed after one funding round.

###  Recommendations:

Based on the findings, the following recommendations were made for VentureInsight’s clients:
-Investment Strategy: Leverage insights on **geographic funding**, **sector trends**, and **fund activity levels** to guide investment and co-investment strategies.
- Market Understanding: Use acquisition trends and volatility insights to understand market dynamics and potential risks.
- Marketing & Outreach: Target industry influencers identified through social media analysis for outreach campaigns.
- Strategic Debates: Use education correlation data to inform internal hiring or team-building strategies.
- Overall Landscape: Establish realistic expectations for startup performance and guide further investigation areas.
