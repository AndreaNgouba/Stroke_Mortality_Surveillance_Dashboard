# Stroke_Mortality_Surveillance_Dashboard 

Project Overview: 
This project analyzes county-level stroke mortality data from the CDC Atlas of Heart Disease and Stroke (2022-2024) to identify geographic distribution, high-risk states, and counties with elevated stroke mortality rates. The analysis combines data cleaning with Excel and SQL, alongside the use of Power BI to produce an interactive dashboard for descriptive epidemiologic surveillance. 

Objectives:

- Identify states with the highest average stroke mortality rates.
- Identify counties with the highest average stroke mortality rates.
- Assess the geographic burden of high-risk counties across states.
- Visualize spatial patterns in stroke mortality using an interactive dashboard.

Dataset:
Source: CDC Atlas of Heart Disease and Stroke 
- Time period: 2022-2024 (3-year average)
- Geographic level: U.S. counties 
- Coverage: 56 U.S. jurisdictions (50 states + D.C., U.S. Virgin Islands, Guam, American Samoa, Puerto Rico, Northern Mariana Islands ) 

Tools & Technologies: 
- Microsoft Word
- Microsoft Excel 
- Power Query 
- SQLite
- SQL
- Power BI 

Methods:
1. Imported and cleaned the CDC dataset using Excel and Power Query.
2. Removed records that did not meet the inclusion criteria.
3. Imported the cleaned data set into SQLite.
4. Wrote SQL queries to summarize county- and state-level stroke mortality rates.
5. Calculated state-level averages and identified high-risk counties.
6. Developed an interactive Power BI dashboard to visualize geographic distribution and state burden.

## Dashboard preview
! [Stroke_mortality_surveillance_dashboard_scsht](scsht.png)
- Filled map of coverage stroke mortality rates by states 
- KPI cards summarizing key metrics 
- Top 10 states by average stroke mortality rate
- Bottom 10 states by average stroke mortality rate 
- Top 10 counties by stroke mortality rate 
- States with the highest burden of high-risk counties

Key Findings:
- Stroke mortality rates varied substantially across the U.S. states and counties
- Several states showed consistently higher average stroke mortality than the national average
- Geographic burden differed across states when considering both numbers and proportion of high-risk counties.
- County-level analysis highlighted important local variation that may not be apparent from state averages alone.

Skills Demonstrated:
- Data cleaning and processing 
- SQL querying and aggregation 
- Descriptive epidemiology analysis 
- Geographic data visualization 
- Dashboard development in Power BI 
- Public Health Surveillance 

Future improvements:
- Incorporate county-level demographic and socioeconomic variables.
- Explore associations between stroke mortality and risk factors such as diabetes, obesity, smoking, and poverty.
- Perform statistical analyses to identify predictors of elevated stroke mortality.
- Expand the dashboard with additional interactive filtering and trend analyses.



Author:
Piero Andrea Ketura Ngouba Madinda 

Master of Science in Biohazard Threats & Emerging Infectious Diseases
Interest areas: Public Health Data Analytics, Epidemiology, Global Health, and Disease Surveillance. 

