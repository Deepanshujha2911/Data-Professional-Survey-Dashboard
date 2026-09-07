# Data Professional Survey — Power BI Dashboard

An interactive Power BI dashboard built from a global survey of **630 data
professionals**. The dashboard turns raw survey responses into clear visuals
that answer practical questions for anyone entering or working in the data field:
how much do different roles earn, which tools people actually use, and how happy
they are in their jobs.

## Key Insights

- **Data Scientists earn the most** among all roles, followed by Data Architects
  and Data Engineers; Database Developers sit at the lower end.
- **Python is by far the most popular language**, used across every role and far
  ahead of R, SQL, and others.
- **The United States dominates the respondent base**, followed by India and Canada.
- **Salary satisfaction is low (4.27 / 10)** while **work-life balance is
  noticeably higher (5.74 / 10)** — people are happier with their hours than their pay.
- Most respondents found it **moderately-to-very difficult to break into the data
  field**, and the average respondent is **~30 years old**.

## Tools Used

- **Power BI Desktop** — data modeling, DAX measures, and visualization
- **Microsoft Excel** — raw survey data source

## Dataset

The dataset (`data/Power BI - Final Project.xlsx`) contains anonymous survey
responses covering job title, salary range, programming language, industry,
satisfaction ratings (salary, work/life, coworkers, management, mobility,
learning), demographics, and country.

## How to Use

1. Download the `.pbix` file from the `dashboard/` folder.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Interact with the slicers and visuals to explore the data.

## Data Cleaning Steps

- Removed unused/blank columns (Browser, OS, City, Country tracking fields).
- Standardized the salary ranges into a numeric **average salary** column for
  calculations.
- Cleaned inconsistent free-text entries (e.g. job titles and programming
  languages listed under "Other").
- Handled missing values in the satisfaction-rating questions.

---
*Created as a data analytics portfolio project.*
