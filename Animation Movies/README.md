# Animation Movies

This was a Code Jam **Competition** project that I worked on after the TripleTen Business Intelligence Analytics Program. It was a light-hearted team project designed to showcase my Tableau and Collaboration skills.  
The purpose was to create a visually compelling story from a provided dataset **in 4 days with Tableau and collaboration**.

This project highlights my strengths in:  
Data Analysis & Exploration (understanding and manipulating data)  
Data Visualization (creating clear and informative visuals)  
Communication & Teamwork (conveying insights and collaborating effectively)  

**Original YouTube LIVE recording of entire competition with host Q&A** can be found [HERE](https://www.youtube.com/live/rWTYgq_3ER4?si=fNs4AeeffGvZo9k8)  

## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | [Animation Movies.pdf](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Animation%20Movies/Animation%20Movies.pdf) | The PDF of the Tableau Workbook including Visualizations, Dashboards, and Story. |
| 2 | [AnimationMovies.V2.twbx](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Animation%20Movies/AnimationMovies.V2.twbx) | The downloadable Tableau Workbook includes interactive Visualizations, Dashboards, and Story. |
| 3 | [Animation_Movies.csv](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Animation%20Movies/Animation_Movies.csv) | Original spreadsheet file in CSV format provided at the start of the competition. |
| 4 | [March_Code_Pudding_Data_Cleaning_..ipynb](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Animation%20Movies/March_Code_Pudding_Data_Cleaning_.ipynb) | Jupiter Notebook file using Python for Data cleaning and EDA performed at the start of the analysis. |
| 5 | README.md | This current page, with all relevant information about the project, just past the Table of contents. |
| 6 | [Requirements.txt](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/blob/main/Animation%20Movies/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen and The Pudding. |

---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#process) | Describes the process, including the tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#assumptions) | Describes assumptions to include those given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#findings) | Insights learned from the data analysis. |
| [Results](https://github.com/Tiffany-Bergett/BI_Analytic_Projects/tree/main/Animation%20Movies#results) | What was gained from the competition |

### Description:
- 1 Tableau Story made from 6 Dashboards and 12 visuals
- Includes Sets, Visualizations, Filters, Dashboards, Story, and a final presentation of the Tableau Story.  
**Reworked and Updated Tableau Public** can be found [HERE](https://public.tableau.com/views/AnimationMovies_17352673342840/AnimatedMoviesBringingtheWorldTogether?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Process:
1) Held a *Google Meet* to organize our team details and technical details on how to best seamlessly share the work between time zones and workstations.  
2) Team member Michelle explored, filtered, and cleaned the data using *Jupyter Notebook* and *Python*.  
3) Took turns passing the Tableau Workbook between members via *Discord Chat* based on availability. While we kept in constant connection and collaboration about our live edits through the same chat.  
4) Simultaneously, we prepared the presentation requirements, outline, and details using the same collaborative method via *Discord* and .txt file.  
5) Recorded our assigned portions of the presentation and used video manipulation to make it one seamless video presentation.  

### Data
The data was one .csv file provided by TripleTen
- `'Animation_Movies.csv'`: Original data. 1 Table with 23 Fields. Fields kept after data cleaning:
    - `'id'`: Unique Identifier
    - `'title'`: Movie Title
    - `'vote_average'`: Average voter score
    - `'vote_count'`: Total number of votes
    - `'status'`: Boolean stat- released for viewing or still in production
    - `'release_date'`: The date the movie was released to the public
    - `'revenue'`: Money earned after release
    - `'runtime'`: Length of movie in time
    - `'adult'`: Boolean stat to tag if it was made for adults
    - `'budget'`: Money reserved for the creation of the movie
    - `'original_language'`: Primary language spoken upon first release
    - `'popularity'`: Numerical value comparing demand for a movie compared to other movies
    - `'genres'`: List of all genre tags for each movie
    - `'production_companies'`: List of all production companies involved in each movie
    - `'production_countries'`: Country of origin

### Assumptions:
1) The main genre was the 1st one listed; analysis was based on the main genre.  
2) Missing values or inconsistencies in the data are minimal and can be ignored.  
3) The provided data was mostly clean when provided to us.  

### Findings:
- The United States produces the most animated movies, but production is happening far and wide across the globe.
- The most produced genre was Comedy until the 1970s, when Family films took over. Except for a brief period at the beginning of the pandemic when Documentaries were Top.
- English is the primary language of animated movies.
- Original Language had a positive correlation with film runtime.
- Animated movies have been steadily getting longer over time until the 2008 recession, and have steadily declined since.
- Pixar, when in conjunction with Disney, had the highest revenue at 7.9 billion.
- Frozen 2 made the highest revenue at 1.45 billion.
- There is a direct correlation between budget size and revenue.
- Sequels bring more money in than their original titles.
- Disney was the most popular production company.
- Spider-Man: Across the Spider-Verse had the highest average vote scores.
- Elemental had the highest Popularity scores

### Results:  
**Original Team Chart-cuteri's recorded presentation** can be found [HERE](https://drive.google.com/file/d/1hCgHvyS8QK4xuK0Vba_DeCW6dX-BBXlA/view?usp=drive_link)  
**Collaborative Brainstorming**: I effectively worked with a team to identify interesting stories within the provided datasets.  
**Data-Driven Storytelling**: I focused on insights supported by data, ensuring clear and ethical use of information.  
**Visual Storytelling**: I created unique data visualizations that complemented the narrative and communicated key points effectively.  
**Presentation Skills**: I participated in crafting a clear and concise presentation that showcased our project's findings within a limited timeframe. 
