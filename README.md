# IMDB Data Analysis Project

## Overview
This project involves a comprehensive analysis of movie data from IMDB. Our team has focused on various aspects such as trend analysis, genre analysis, performance metrics, director success metrics, actor and actress film records, seasonal analysis, release regions, and a special matrix for 9 box office movies.

## Objectives
- Perform detailed data profiling and analysis to derive meaningful insights.
- Develop ETL mappings and processes using Talend.
- Create interactive dashboards in Power BI and Tableau for visual analysis.
- Write SQL queries to validate the data shown in the dashboards.

## Data Sources
1. **MySQL Database**: imdb_Tables_Backup.sql - Contains the primary movie data.
2. **Revenue Data**: TSV files for 9 Movie box office numbers.
3. **SCD2 Data**: JSON files for movie title and actor name changes.
   
## Data source files link : 
https://northeastern-my.sharepoint.com/personal/naveenhks_northeastern_edu/_layouts/15/onedrive.aspx?csf=1&web=1&e=tgtZqp&cid=f54f53fb%2D9f4f%2D46c1%2Dbf67%2Dfce96f4321d1&id=%2Fpersonal%2Fnaveenhks%5Fnortheastern%5Fedu%2FDocuments%2FDAMG7370%5FFALL2023%2FIMDB&FolderCTID=0x012000050E74E63D77D24EAC181D0723FA1928&view=0
## Components
- **Alteryx**: For data profiling and analysis.
- **Talend**: To design and implement ETL processes.
- **Power BI and Tableau**: For dashboard creation.
- **SQL**: For data validation and additional analysis.

## Setup Instructions
1. **MySQL Database Setup**:
   - Import `imdb_Tables_Backup.sql` into a local MySQL database.
2. **Data Loading**:
   - Load the TSV and JSON files into the appropriate data structures.
3. **Talend Setup**:
   - Configure metadata-based connections, contexts, and environments in Talend.
4. **Alteryx, Power BI, and Tableau**:
   - Set up Alteryx for data profiling.
   - Develop dashboards in Power BI and Tableau.

## Analysis and Insights
### Trend Analysis
- Average movie runtime over the years.
- Correlation between average movie rating and release year.
- Distribution of movie releases per year.

### Genre Analysis
- Popularity trends of different genres.
- Top 5 genres compared to gross earnings.

### Performance Metrics
- Correlation between movie runtime, average rating, and gross earnings.
- Relationship between the number of votes and average rating.

### Director Success Metrics
- Directors with most films rated above 7.
- Directors with highest number of films and their gross earnings trends.

### Actor and Actress Film Records
- Top 10 actors/actresses with films rated between 4 and 7.
- Comparison of top 5 actors and actresses based on ratings.

### Seasonal Analysis
- Movie performance across different seasons.
- Top 3 movies in spring, summer, and fall seasons.

### Release Regions
- Movies with the widest release across multiple regions.

### Matrix for Box Office Movies
- Dashboard showcasing various metrics for 9 box office movies.

## SQL Queries
SQL queries for each analysis are provided to validate the dashboard data.
