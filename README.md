# COVID-19 Data Exploration: SQL Server + Tableau

## Overview
This project explores global COVID-19 data using SQL Server to analyse cases,
deaths, infection rates and vaccination progress. The aim is to identify trends
and generate insights, then present them in an interactive Tableau dashboard.

**Live dashboard:** 

## Questions Answered
- What are the total global cases, deaths and the overall death percentage?
- How do death counts compare across continents?
- Which countries have the highest infection rate relative to their population?
- How has the percentage of the population infected changed over time?
- How has vaccination progressed in each country (rolling totals)?

## Tools and Skills
- **SQL Server (T-SQL):** data exploration and extraction
- **Tableau:** dashboard and visualisations
- **SQL techniques:** aggregate functions, `GROUP BY`, joins, CTEs,
  window functions (`SUM() OVER (PARTITION BY ...)`), type conversion
  (`CAST` / `CONVERT`), and filtering out aggregate rows such as World and
  European Union to keep the totals consistent

## Dataset
COVID-19 data split into two tables, `CovidDeaths` and `CovidVaccinations`,

## Queries
The Tableau queries are in `Tableau_Portfolio_Project_SQL_Queries.sql`:

| # | Purpose | Output |
|---|---------|--------|
| 1 | Global totals and death percentage | Headline figures |
| 2 | Total death count by continent | Bar chart |
| 3 | Highest infection count and % of population infected by country | Map |
| 4 | % of population infected by country over time | Forecast / trend line |

The same file also includes extra queries I left out of the final dashboard,
including a rolling vaccination count using a CTE and a window function.


## Author
Syed: [LinkedIn] | [Portfolio website]
