# 📊 Data Analyst Learning Path

> Transform raw data into reliable insights, useful dashboards, clear reports, and evidence-based recommendations.

![Path](https://img.shields.io/badge/Path-Data%20Analyst-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Advanced-success)
![Practice](https://img.shields.io/badge/Learning-Hands--On-orange)
![BIH](https://img.shields.io/badge/Case%20Studies-Beacon%20Innovation%20Hub-purple)

**Learning Model:**  
🎥 Learn → 📚 Read → 🎮 Practice → 🔎 Analyse → 📊 Visualize → 🧠 Interpret → 🎯 Recommend

---

# ⚠️ Prerequisite

Before starting this pathway, complete:

**[📊 Common Data Foundations](Python-For-Data.md)**

You should already understand:

- [ ] Python fundamentals
- [ ] NumPy
- [ ] Pandas
- [ ] DataFrames
- [ ] Missing values
- [ ] Data cleaning
- [ ] Data types
- [ ] Grouping and aggregation
- [ ] Joins
- [ ] Basic visualization
- [ ] Exploratory Data Analysis
- [ ] Data validation

---

# 🗺️ Data Analyst Roadmap

```text
📊 Introduction to Data Analysis
              ↓
🔎 Practical Data Analysis
              ↓
📑 Excel / Spreadsheets
              ↓
🗄️ SQL
              ↓
📐 Statistics for Analysts
              ↓
📊 Power BI
              ↓
🧮 DAX & Data Modelling
              ↓
🎯 KPIs & Business Metrics
              ↓
📈 Dashboard Design
              ↓
🧠 Data Storytelling
              ↓
🏢 Business Case Studies
              ↓
🏗️ Portfolio Projects
```

---

# 01 — 📊 Introduction to Data Analysis

**Level:** 🟢 Beginner

[![Introduction to Data Analysis](https://img.youtube.com/vi/37x5dKW-X5U/maxresdefault.jpg)](https://youtu.be/37x5dKW-X5U)

## 🎥 Introduction Resource

**[▶ Watch: Introduction to Data Analysis](https://youtu.be/37x5dKW-X5U)**

### 🎯 Understand

- [ ] What data analysis is
- [ ] What a Data Analyst does
- [ ] Types of data
- [ ] Structured vs unstructured data
- [ ] Business questions
- [ ] Data collection
- [ ] Data preparation
- [ ] Data analysis
- [ ] Visualization
- [ ] Reporting
- [ ] Decision support

---

# 🧠 The Analyst Workflow

```text
❓ BUSINESS QUESTION
        ↓
📥 DATA
        ↓
🔎 INVESTIGATION
        ↓
🧹 PREPARATION
        ↓
📊 ANALYSIS
        ↓
📈 VISUALIZATION
        ↓
🧠 INTERPRETATION
        ↓
🎯 RECOMMENDATION
        ↓
📋 DECISION SUPPORT
```

> A chart is not the final product. A Data Analyst should explain what happened, why it matters, and what decision-makers should investigate or do next.

---

# 02 — 🔎 Practical Data Analysis

**Level:** 🟢 Beginner → 🟡 Intermediate

[![Data Analysis](https://img.youtube.com/vi/qrbf9DtR3_c/maxresdefault.jpg)](https://www.youtube.com/watch?v=qrbf9DtR3_c)

## 🎥 Continuing Resource

**[▶ Continue Data Analysis Learning](https://www.youtube.com/watch?v=qrbf9DtR3_c)**

---

# 🧪 Practice Dataset

Use:

```text
bih_data_analyst_practice.csv
```

The fictional dataset represents activity within the Beacon Innovation Hub community.

### Main Variables

| Field | Meaning |
|---|---|
| `participant_id` | Participant identifier |
| `participant_name` | Participant |
| `technical_team` | Technical team |
| `experience_level` | Experience category |
| `join_date` | Joining date |
| `attendance_rate` | Attendance percentage |
| `projects_completed` | Completed projects |
| `training_hours` | Training activity |
| `task_completion_rate` | Assigned-task completion |
| `average_review_score` | Average review performance |
| `project_category` | Project area |
| `project_status` | Current project status |

> ⚠️ The dataset intentionally contains data-quality problems.

---

# 🏢 BIH Lab 01 — Understand the Dataset

Before cleaning or analysing:

- [ ] Determine dataset dimensions
- [ ] Identify variables
- [ ] Inspect data types
- [ ] Identify categorical variables
- [ ] Identify numerical variables
- [ ] Count missing values
- [ ] Check duplicates
- [ ] Inspect unique categories
- [ ] Generate descriptive statistics

Ask:

- What does each row represent?
- What does each column measure?
- What limitations might this dataset have?

---

# 🧹 BIH Lab 02 — Data Quality

Investigate:

- [ ] Missing values
- [ ] Duplicate records
- [ ] Incorrect data types
- [ ] Inconsistent categories
- [ ] Invalid numerical values
- [ ] Suspicious dates
- [ ] Outliers

Use:

```text
🔎 Detect
    ↓
📋 Document
    ↓
🧠 Decide
    ↓
🛠️ Transform
    ↓
✅ Validate
```

---

## 📝 Cleaning Log

| Problem | Evidence | Decision | Transformation | Validation |
|---|---|---|---|---|
| Inconsistent team names | Unique values | Standardize | Replace variations | Recheck categories |
| Missing attendance | Null check | Investigate | Appropriate treatment | Recheck missingness |

> Never silently alter important data.

---

# 🏢 BIH Lab 03 — Community Overview

Answer:

- [ ] How many participants are represented?
- [ ] How many belong to each team?
- [ ] What percentage belongs to each team?
- [ ] What is the experience-level distribution?
- [ ] What is average attendance?
- [ ] What is median attendance?
- [ ] What is average task completion?
- [ ] What is average review performance?
- [ ] What is the average number of completed projects?

---

# 🏢 BIH Lab 04 — Team Analysis

Compare teams using:

- [ ] Participant count
- [ ] Attendance
- [ ] Training hours
- [ ] Task completion
- [ ] Projects completed
- [ ] Review performance

For every comparison ask:

1. Which group performs highest?
2. Which performs lowest?
3. How large is the difference?
4. Could sample size affect the comparison?
5. Are outliers influencing the result?
6. What additional evidence would be needed?

---

# 🏢 BIH Lab 05 — Engagement Analysis

Investigate relationships between:

```text
Attendance
Training Hours
Task Completion
Projects Completed
Review Scores
```

Questions:

- [ ] Is attendance associated with project completion?
- [ ] Are training hours associated with review performance?
- [ ] Does task completion relate to project completion?
- [ ] Which experience group has the highest attendance?
- [ ] Which experience group has the strongest reviews?
- [ ] Are there unusual participants?
- [ ] Which variables appear related?

> ⚠️ Association does not automatically mean causation.

---

# 03 — 📑 Spreadsheet Analysis

**Level:** 🟡 Intermediate

## 🎯 Learn

- [ ] Tables
- [ ] Sorting
- [ ] Filtering
- [ ] Conditional formatting
- [ ] Data validation
- [ ] Text functions
- [ ] Date functions
- [ ] Logical functions
- [ ] Lookup functions
- [ ] `SUMIFS`
- [ ] `COUNTIFS`
- [ ] `AVERAGEIFS`
- [ ] PivotTables
- [ ] PivotCharts
- [ ] Basic dashboards

---

# 🏢 BIH Lab 06 — Spreadsheet Analysis

Import:

```text
bih_data_analyst_practice.csv
```

Create a spreadsheet analysis answering:

- [ ] Participants per team
- [ ] Average attendance
- [ ] Average attendance per team
- [ ] Total projects completed
- [ ] Projects completed per team
- [ ] Average review score
- [ ] Average review score per experience level
- [ ] Participant count by project category

---

## 📊 PivotTable Challenge

Create:

```text
Technical Team
      ↓
Participant Count
Average Attendance
Average Review Score
Projects Completed
```

Then create appropriate PivotCharts.

---

# 04 — 🗄️ SQL for Data Analysts

**Level:** 🟡 Intermediate

SQL is one of the most important tools for analysts because organisational data is commonly stored across relational database tables.

[![SQL for Data Analytics](https://img.youtube.com/vi/7mz73uXD9DA/maxresdefault.jpg)](https://youtu.be/7mz73uXD9DA)

## 🎥 Main SQL Course

**[▶ SQL for Data Analytics — Learn SQL in 4 Hours](https://youtu.be/7mz73uXD9DA)**

Recommended workflow:

```text
🎥 Watch Concept
      ↓
⌨️ Write Query
      ↓
🔧 Modify Query
      ↓
❓ Answer a BIH Question
      ↓
🎮 Complete Interactive Exercise
      ↓
📚 Consult Documentation
```

---

## 🎯 SQL Fundamentals

- [ ] Relational databases
- [ ] Tables
- [ ] Rows
- [ ] Columns
- [ ] Primary keys
- [ ] Foreign keys
- [ ] `SELECT`
- [ ] `FROM`
- [ ] `WHERE`
- [ ] `DISTINCT`
- [ ] `ORDER BY`
- [ ] `LIMIT`
- [ ] Aliases

---

## Filtering

```sql
WHERE
AND
OR
NOT
IN
BETWEEN
LIKE
IS NULL
```

---

## Aggregation

```sql
COUNT()
SUM()
AVG()
MIN()
MAX()
GROUP BY
HAVING
```

---

## Conditional Logic

```sql
CASE
    WHEN ...
    THEN ...
    ELSE ...
END
```

---

## JOINs

- [ ] `INNER JOIN`
- [ ] `LEFT JOIN`
- [ ] Join keys
- [ ] One-to-many relationships
- [ ] Many-to-many relationships
- [ ] Duplicate rows from incorrect joins
- [ ] Unmatched records

---

## Intermediate SQL

- [ ] Subqueries
- [ ] Common Table Expressions
- [ ] `WITH`
- [ ] Date functions
- [ ] String functions
- [ ] Numeric functions
- [ ] Null handling

---

## Analytical SQL

- [ ] Window functions
- [ ] `ROW_NUMBER()`
- [ ] `RANK()`
- [ ] `DENSE_RANK()`
- [ ] `PARTITION BY`
- [ ] Running totals
- [ ] Ranking within groups

---

# 📚 SQL Documentation

**[PostgreSQL Documentation](https://www.postgresql.org/docs/)**

---

# 🎮 Interactive SQL Practice

## SQLBolt

**[🚀 Learn SQL Interactively](https://sqlbolt.com/)**

## SQL Murder Mystery

**[🕵️ Solve the SQL Murder Mystery](https://mystery.knightlab.com/)**

---

# 🏢 BIH SQL Database

Imagine BIH maintains:

```text
participants
teams
projects
project_members
attendance
training
reviews
```

### `participants`

```text
participant_id
participant_name
team_id
experience_level
join_date
```

### `teams`

```text
team_id
team_name
```

### `projects`

```text
project_id
project_name
project_category
project_status
start_date
```

### `project_members`

```text
project_id
participant_id
project_role
```

### `attendance`

```text
attendance_id
participant_id
session_date
attendance_status
```

### `training`

```text
training_id
participant_id
training_name
hours_completed
completion_date
```

### `reviews`

```text
review_id
project_id
participant_id
review_score
review_date
```

---

# 🏢 BIH SQL Lab 01 — Basic Queries

- [ ] Display all participants
- [ ] Display participant names
- [ ] Display unique experience levels
- [ ] Find Data Science participants
- [ ] Find participants who joined after a date
- [ ] Sort by joining date
- [ ] Display the first 10 participants

---

# 🏢 BIH SQL Lab 02 — Aggregation

Answer:

- [ ] Number of participants
- [ ] Participants per experience level
- [ ] Participants per team
- [ ] Number of projects
- [ ] Number of active projects
- [ ] Projects per category
- [ ] Average review score
- [ ] Highest review score
- [ ] Lowest review score

---

# 🏢 BIH SQL Lab 03 — JOINs

Combine:

```text
Participants
      +
Teams
```

Then:

```text
Participants
      +
Project Members
      +
Projects
```

Answer:

- [ ] Which participants have projects?
- [ ] Which participants have no project assignment?
- [ ] Which projects have the largest teams?
- [ ] Which team contributes most participants to projects?
- [ ] Which participants work on multiple projects?

---

## 🧩 JOIN Validation

After every join ask:

```text
How many rows existed before?

How many exist afterwards?

Was the increase expected?

Did records disappear?

Were records duplicated?
```

---

# 🏢 BIH SQL Lab 04 — Advanced Analytics

Practice:

- [ ] Performance categories with `CASE`
- [ ] Participant summaries with CTEs
- [ ] Overall participant ranking
- [ ] Ranking within teams
- [ ] Running totals
- [ ] Window functions

---

# 05 — 📐 Statistics for Data Analysts

**Level:** 🟡 Intermediate

[![Statistics for Data Analysts](https://img.youtube.com/vi/IYVEI1EYfPg/maxresdefault.jpg)](https://youtu.be/IYVEI1EYfPg?si=16Jr0l9XP49_15H5)


## 🎯 Descriptive Statistics

- [ ] Mean
- [ ] Median
- [ ] Mode
- [ ] Minimum
- [ ] Maximum
- [ ] Range
- [ ] Variance
- [ ] Standard deviation
- [ ] Percentiles
- [ ] Quartiles

## Distributions

- [ ] Distribution shape
- [ ] Skewness
- [ ] Outliers
- [ ] Normal distribution

## Relationships

- [ ] Covariance
- [ ] Correlation
- [ ] Scatter plots

## Statistical Reasoning

- [ ] Population vs sample
- [ ] Sampling
- [ ] Sampling bias
- [ ] Confidence intervals
- [ ] Hypothesis-testing fundamentals
- [ ] Statistical significance
- [ ] Practical significance

---

# 🏢 BIH Lab 07 — Statistical Investigation

Calculate for attendance:

- [ ] Mean
- [ ] Median
- [ ] Standard deviation
- [ ] Quartiles
- [ ] Minimum
- [ ] Maximum

Investigate:

```text
Attendance ↔ Projects Completed

Training Hours ↔ Review Score

Task Completion ↔ Review Score
```

Explain what the relationships do and do not imply.

---

# 06 — 📊 Power BI

**Level:** 🟡 Intermediate

[![Learn Power BI](https://img.youtube.com/vi/I0vQ_VLZTWg/maxresdefault.jpg)](https://www.youtube.com/watch?v=I0vQ_VLZTWg)

## 🎥 Main Power BI Course

**[▶ Learn Power BI in Under 3 Hours](https://www.youtube.com/watch?v=I0vQ_VLZTWg)**

---

## 📚 Official Documentation

- **[Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)**
- **[Power BI Fundamentals](https://learn.microsoft.com/en-us/power-bi/fundamentals/)**
- **[Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)**
- **[Power BI Visualizations](https://learn.microsoft.com/en-us/power-bi/visuals/)**

---

## 🎯 Learn

- [ ] Power BI interface
- [ ] Importing data
- [ ] Power Query
- [ ] Data types
- [ ] Relationships
- [ ] Visualizations
- [ ] Formatting
- [ ] Filters
- [ ] Slicers
- [ ] Cards
- [ ] Tables
- [ ] Reports
- [ ] Dashboards

---

# 🏢 BIH Lab 08 — Community Dashboard

Create KPI cards:

```text
👥 Total Participants
📋 Projects Completed
📅 Average Attendance
✅ Average Task Completion
⭐ Average Review Score
⏱️ Training Hours
```

Create visualizations:

- [ ] Participants by team
- [ ] Participants by experience level
- [ ] Attendance by team
- [ ] Projects completed by team
- [ ] Review score by team
- [ ] Project categories
- [ ] Project status
- [ ] Participants joining over time

Add slicers:

- [ ] Technical Team
- [ ] Experience Level
- [ ] Project Category
- [ ] Project Status

---

# 07 — 🧮 Data Modelling & DAX

**Level:** 🟡 Intermediate → 🔴 Advanced


[![Data Modelling](https://img.youtube.com/vi/lD7TvkoQ6rY/maxresdefault.jpg)](https://youtu.be/lD7TvkoQ6rY?si=jHSGMWV2JWTPeAAI)


## 🎯 Data Modelling

- [ ] Fact tables
- [ ] Dimension tables
- [ ] Relationships
- [ ] Cardinality
- [ ] Filter direction
- [ ] Star schema

[![DAX](https://img.youtube.com/vi/4ePNrdxWtY0/maxresdefault.jpg)](https://youtu.be/4ePNrdxWtY0?si=PbEoaDiEgBxuuJuI)


## 🎯 DAX

- [ ] Measures
- [ ] Calculated columns
- [ ] `SUM`
- [ ] `AVERAGE`
- [ ] `COUNTROWS`
- [ ] `DISTINCTCOUNT`
- [ ] `CALCULATE`
- [ ] `DIVIDE`
- [ ] Filter context
- [ ] Basic time intelligence

---

## 📚 DAX Documentation

**[DAX Documentation](https://learn.microsoft.com/en-us/dax/)**

---

# 🏢 BIH Lab 09 — Create Measures

Create:

```text
Total Participants
Total Projects
Average Attendance
Average Review Score
Project Completion Rate
Average Training Hours
Active Participant Rate
```

---

# 08 — 🎯 KPIs & Business Metrics

## 🎥 Video Resource

[![Video Resource](https://img.youtube.com/vi/ItZlTixh6Bs/maxresdefault.jpg)](https://youtu.be/ItZlTixh6Bs?si=hy5ip7hAJKMVMkKC)

**[▶ Watch Video](https://youtu.be/ItZlTixh6Bs?si=hy5ip7hAJKMVMkKC)**



## Learn

- [ ] Metric vs KPI
- [ ] Leading indicators
- [ ] Lagging indicators
- [ ] Targets
- [ ] Benchmarks
- [ ] Rates
- [ ] Ratios
- [ ] Percentage change
- [ ] KPI context




---

# 🏢 BIH Lab 10 — Design KPIs

Design KPIs for:

```text
Community Growth
Engagement
Skills Development
Project Participation
Project Completion
Technical Performance
```

For each KPI explain:

- Definition
- Formula
- Purpose
- Limitation

---

# 🧠 Engagement Score Challenge

Example:

```text
Attendance          30%
Task Completion     30%
Training Activity   20%
Projects Completed  20%
```

Classify:

```text
80–100     Highly Engaged
65–79      Engaged
50–64      Moderate
Below 50   Requires Attention
```

Then explain why the score may be misleading.

---

# 09 — 📈 Dashboard Design

A dashboard should reduce complexity.

```text
┌─────────────────────────────────────────┐
│       BIH COMMUNITY PERFORMANCE         │
├────────┬────────┬────────┬──────────────┤
│Members │Projects│Attend. │Review Score  │
├────────┴────────┴────────┴──────────────┤
│          PRIMARY ANALYSIS               │
├───────────────────┬─────────────────────┤
│ Team Performance  │ Engagement Trends   │
├───────────────────┴─────────────────────┤
│          SUPPORTING ANALYSIS            │
├─────────────────────────────────────────┤
│              FILTERS                    │
└─────────────────────────────────────────┘
```

## Principles

- [ ] Clear visual hierarchy
- [ ] Important KPIs first
- [ ] Appropriate chart types
- [ ] Consistent labels
- [ ] Minimal unnecessary decoration
- [ ] Useful filters
- [ ] Context for metrics
- [ ] Readable titles

Ask:

> What decision does this visualization help someone make?

---

# 10 — 🧠 Data Storytelling

Use:

```text
📊 EVIDENCE
What did the data show?
        ↓
🔎 PATTERN
What happened?
        ↓
🧠 INTERPRETATION
Why might it matter?
        ↓
⚠️ LIMITATION
What can't we conclude?
        ↓
🎯 RECOMMENDATION
What should happen next?
```

---

# 🏢 BIH Lab 11 — Management Brief

Prepare:

### 3 Key Findings

### 2 Risks

### 3 Recommendations

### 1 Major Limitation

The objective is to communicate only the most decision-relevant information.

---

# 11 — 🏗️ Final Data Analyst Project

# BIH Community Performance Analysis

## Business Question

> How effectively is Beacon Innovation Hub engaging participants, developing technical skills, and supporting project activity?

---

## Phase 1 — Business Understanding

- [ ] Define the main question
- [ ] Identify stakeholders
- [ ] Define relevant metrics
- [ ] Define scope
- [ ] Identify limitations

---

## Phase 2 — Data Preparation

- [ ] Import data
- [ ] Profile data
- [ ] Investigate missingness
- [ ] Investigate duplicates
- [ ] Correct types
- [ ] Standardize categories
- [ ] Validate transformations

---

## Phase 3 — Analysis

- [ ] Community composition
- [ ] Technical teams
- [ ] Attendance
- [ ] Training activity
- [ ] Project participation
- [ ] Project completion
- [ ] Review performance
- [ ] Engagement
- [ ] Trends
- [ ] Areas requiring investigation

---

## Phase 4 — Statistics

- [ ] Descriptive statistics
- [ ] Distribution analysis
- [ ] Group comparisons
- [ ] Correlation analysis
- [ ] Appropriate interpretation

---

## Phase 5 — SQL

Use SQL to answer at least ten management questions.

Include:

- [ ] Aggregation
- [ ] JOINs
- [ ] CASE
- [ ] CTEs
- [ ] Window functions

---

## Phase 6 — Power BI

Create:

### Page 1 — Executive Overview

### Page 2 — Team Performance

### Page 3 — Participant Engagement

### Page 4 — Project Analysis

---

## Phase 7 — Findings

Provide at least **five evidence-supported findings**.

---

## Phase 8 — Recommendations

Provide at least **three actionable recommendations**.

Separate:

```text
What the data proves
        ≠
What the analyst suspects
        ≠
What management should investigate
```

---

# 📁 Recommended Project Structure

```text
BIH-data-analyst/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── excel/
│   └── exploratory-analysis.xlsx
│
├── sql/
│   └── analysis.sql
│
├── notebooks/
│   └── analysis.ipynb
│
├── power-bi/
│   └── BIH-dashboard.pbix
│
├── outputs/
│   ├── charts/
│   └── reports/
│
└── README.md
```

---

# 12 — 📈 Progress Tracker

## 📊 Analysis Fundamentals

- [ ] Introduction video
- [ ] Continuing analysis resource
- [ ] Analyst workflow
- [ ] Business-question development
- [ ] BIH dataset analysis

## 📑 Spreadsheet Analysis

- [ ] Filtering
- [ ] Functions
- [ ] Lookup functions
- [ ] Conditional aggregation
- [ ] PivotTables
- [ ] PivotCharts

## 🗄️ SQL

- [ ] Main SQL course
- [ ] SELECT
- [ ] WHERE
- [ ] GROUP BY
- [ ] HAVING
- [ ] JOINs
- [ ] CASE
- [ ] CTEs
- [ ] Window functions
- [ ] SQLBolt
- [ ] SQL Murder Mystery

## 📐 Statistics

- [ ] Mean / Median
- [ ] Variance
- [ ] Standard deviation
- [ ] Percentiles
- [ ] Distributions
- [ ] Outliers
- [ ] Correlation
- [ ] Sampling
- [ ] Statistical reasoning

## 📊 Power BI

- [ ] Power BI course
- [ ] Power Query
- [ ] Visualizations
- [ ] Filters
- [ ] Slicers
- [ ] KPI cards
- [ ] Data relationships
- [ ] Dashboard

## 🧮 DAX

- [ ] Measures
- [ ] Calculated columns
- [ ] `CALCULATE`
- [ ] `DIVIDE`
- [ ] Filter context
- [ ] Time intelligence fundamentals

## 🎯 Business Analytics

- [ ] KPI design
- [ ] Business metrics
- [ ] Dashboard design
- [ ] Interpretation
- [ ] Data storytelling
- [ ] Recommendations

## 🏢 BIH Projects

- [ ] Dataset investigation
- [ ] Data-quality analysis
- [ ] Community overview
- [ ] Team analysis
- [ ] Engagement analysis
- [ ] Spreadsheet analysis
- [ ] SQL analysis
- [ ] Statistical investigation
- [ ] Power BI dashboard
- [ ] KPI design
- [ ] Management brief
- [ ] Final BIH Data Analyst Project

---

# 🏆 Portfolio Standard

Do not build a portfolio containing only screenshots.

Every project should explain:

```text
❓ Problem
    ↓
📥 Data
    ↓
🧹 Preparation
    ↓
🔎 Analysis
    ↓
📊 Visualization
    ↓
🧠 Findings
    ↓
🎯 Recommendations
    ↓
⚠️ Limitations
```

A reviewer should be able to understand:

- What problem did you solve?
- What data did you use?
- How did you prepare it?
- What did you discover?
- Why does the result matter?
- What are the limitations?

---

# 🚀 Completion

A developing Data Analyst should eventually be able to receive unfamiliar organisational data and independently:

```text
❓ Define the Question
        ↓
📥 Understand the Data
        ↓
🧹 Prepare & Validate
        ↓
🗄️ Query
        ↓
📐 Analyse
        ↓
📊 Visualize
        ↓
🧠 Interpret
        ↓
🎯 Recommend
        ↓
📢 Communicate
```

> **A Data Analyst's value is not determined by how many tools they know. It is determined by their ability to turn trustworthy evidence into information that supports better decisions.**
