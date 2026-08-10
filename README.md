# LA County Education & Health Analysis

< 🔄 Status: In Progress: SQL analysis is currently underway. A Power BI dashboard will be added in a later phase of the project.

## Table of Contents
1. Project Background and Overview
2. Data & Methodology
3. Next Steps
4. Project Background and Overview

This project analyzes the relationship between educational attainment and self-reported poor health across communities in Los Angeles County.

The analysis is motivated by Los Angeles County Public Health reporting that highlights social and economic disparities in life expectancy, obesity, disability, and overall health outcomes across the county.

The goal is to explore how educational attainment relates to poor health and how other socioeconomic factors, such as income and poverty, may help explain differences between communities.

Data Context: [County of Los Angeles Public Health — Social Determinants of Health and Health Outcomes in Los Angeles County](http://publichealth.lacounty.gov/epi/docs/SocialD_Final_Web.pdf)

## Data and Methodology

- **Primary Tool:**
  - SQL
- **Data Exploration:**
  - Use `COUNT()`, `AVG()`, `MIN()`, and `MAX()` to understand the overall dataset
  - Examine distributions across socioeconomic and health-related variables
  - Identify communities with the highest and lowest values
  - Check for missing or incomplete records
- **Analysis Questions:**
  - Which communities have the highest percentages of self-reported poor health?
  - How does poor health vary across levels of educational attainment?
  - Which communities experience both high poverty and low life expectancy?
  - How do income and mortality patterns differ across communities?
- **SQL Analysis:**
  - Use `WHERE`, `GROUP BY`, and `ORDER BY` to filter, summarize, and rank results
  - Create calculated fields where needed
  - Use CTEs or views to organize more complex analysis
  - Incorporate joins if additional datasets are added
- **Analysis Approach:**
  - Compare community-level socioeconomic conditions with health outcomes
  - Identify patterns and disparities associated with education, income, and poverty
  - Interpret query results in the context of social determinants of health

Status: The following analyses are planned and reflect work that is still in progress.

Exploratory Analysis:
Profile the dataset and identify notable distributions, missing values, and outliers.
Community Comparisons:
Rank and compare Los Angeles County communities based on poor health, educational attainment, poverty, income, life expectancy, and mortality.
Relationship Analysis:
Examine whether communities with lower educational attainment also tend to report poorer health outcomes and how income and poverty relate to those patterns.
Analysis-Ready Outputs:
Create reusable SQL queries, CTEs, or views that summarize the most important findings for visualization.
Interpretation:
Translate SQL results into clear findings about socioeconomic and health disparities without treating observed associations as proof of causation.
Dashboard:
Present the most important findings in Power BI through KPIs, community rankings, comparison charts, and interactive filters.

<!--
# la-county-SDOH-analysis
Python analysis of LA County health data exploring the relationship between education levels and community health outcomes.

Research Question:
How is educational attainment associated with health outcomes across Los Angeles County communities, and how do income and poverty relate to those patterns?
-->
