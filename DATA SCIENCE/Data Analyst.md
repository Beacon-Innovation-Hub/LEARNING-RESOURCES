# 📊 Data Analyst Learning Path

> Transform raw data into reliable insights, clear visualizations, useful dashboards, and evidence-based recommendations.

![Path](https://img.shields.io/badge/Path-Data%20Analyst-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Advanced-success)
![Practice](https://img.shields.io/badge/Learning-Hands--On-orange)
![BIH](https://img.shields.io/badge/Case%20Studies-Beacon%20Innovation%20Hub-purple)

**Learning Model:**  
🎥 Learn → 📚 Read → 🧩 Practice → 🔎 Analyse → 📊 Visualize → 🧠 Interpret → 🎯 Recommend

---

# ⚠️ Prerequisite

Before starting this pathway, complete:

**[📊 Common Data Foundations](data-foundations.md)**

You should already understand:

- [ ] Python fundamentals
- [ ] NumPy fundamentals
- [ ] Pandas
- [ ] DataFrames
- [ ] CSV/Excel data
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

Before learning more tools, understand what a Data Analyst actually does.

[![Introduction to Data Analysis](https://img.youtube.com/vi/37x5dKW-X5U/maxresdefault.jpg)](https://youtu.be/37x5dKW-X5U)

## 🎥 Introduction Resource

**[▶ Watch: Introduction to Data Analysis](https://youtu.be/37x5dKW-X5U)**

---

## 🎯 Understand

- [ ] What data analysis is
- [ ] What Data Analysts do
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

A Data Analyst should be able to move from:

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

> A chart is not the final product.

The analyst should be able to explain:

> **What happened, why does it matter, and what should decision-makers investigate or do next?**

---

# 02 — 🔎 Practical Data Analysis

**Level:** 🟢 Beginner → 🟡 Intermediate

[![Data Analysis](https://img.youtube.com/vi/qrbf9DtR3_c/maxresdefault.jpg)](https://www.youtube.com/watch?v=qrbf9DtR3_c)

## 🎥 Continuing Resource

**[▶ Continue Data Analysis Learning](https://www.youtube.com/watch?v=qrbf9DtR3_c)**

Use this resource to strengthen your practical analytical workflow.

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

Before cleaning or analysing anything:

- [ ] Determine dataset dimensions
- [ ] Identify all variables
- [ ] Inspect data types
- [ ] Identify categorical variables
- [ ] Identify numerical variables
- [ ] Count missing values
- [ ] Check duplicate records
- [ ] Inspect unique categories
- [ ] Generate descriptive statistics

Ask:

> **What does each row represent?**

> **What does each column measure?**

> **What limitations might this dataset have?**

---

# 🧹 BIH Lab 02 — Data Quality

Investigate:

- [ ] Missing values
- [ ] Duplicate records
- [ ] Incorrect types
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

Maintain a cleaning record.

| Problem | Evidence | Decision | Transformation | Validation |
|---|---|---|---|---|
| Inconsistent team names | Unique values | Standardize | Replace variations | Recheck categories |
| Missing attendance | Null check | Investigate | Appropriate treatment | Recheck missingness |

> Never silently alter important data.

---

# 🏢 BIH Lab 03 — Community Overview

Answer:

- [ ] How many participants are represented?
- [ ] How many belong to each technical team?
- [ ] What percentage belongs to each team?
- [ ] What is the experience-level distribution?
- [ ] What is average attendance?
- [ ] What is median attendance?
- [ ] What is average task completion?
- [ ] What is average review performance?
- [ ] What is the average number of completed projects?

---

# 🏢 BIH Lab 04 — Team Analysis

Compare technical teams using:

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

### Questions

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

Data Analysts should be comfortable analysing structured data using spreadsheet tools.

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

## 📊 Build a PivotTable

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

SQL is a core Data Analyst skill because organisational data commonly lives inside relational databases.

## 🎯 Learn

- [ ] `SELECT`
- [ ] `FROM`
- [ ] `WHERE`
- [ ] `ORDER BY`
- [ ] `DISTINCT`
- [ ] `LIMIT`
- [ ] Aliases
- [ ] `CASE`
- [ ] `COUNT`
- [ ] `SUM`
- [ ] `AVG`
- [ ] `MIN`
- [ ] `MAX`
- [ ] `GROUP BY`
- [ ] `HAVING`
- [ ] `INNER JOIN`
- [ ] `LEFT JOIN`
- [ ] Subqueries
- [ ] CTEs
- [ ] Window functions

---

## 📚 Documentation

**[📘 PostgreSQL Documentation](https://www.postgresql.org/docs/)**

**[📘 SQLBolt Interactive Lessons](https://sqlbolt.com/)**

**[🎮 SQL Murder Mystery](https://mystery.knightlab.com/)**

---

# 🎮 Interactive SQL Practice

Use **SQLBolt** to learn queries interactively.

Then attempt **SQL Murder Mystery** to apply SQL as an investigation.

The objective is to become comfortable asking questions directly from relational data.

---

# 🏢 BIH Lab 07 — BIH Database

Imagine BIH maintains:

```text
participants
projects
project_members
reviews
attendance
```

Write SQL queries to determine:

- [ ] Number of participants
- [ ] Participants per team
- [ ] Average attendance
- [ ] Average attendance by team
- [ ] Number of active projects
- [ ] Participants working on multiple projects
- [ ] Average review score by project
- [ ] Highest-performing projects
- [ ] Participants without project assignments
- [ ] Most active technical team

---

# ⭐ SQL Challenge

Answer:

> **Who are the five most active participants?**

But first define what **active** means.

Your definition may consider:

```text
Attendance
+
Project Participation
+
Task Completion
+
Training Activity
```

Explain your metric.

---

# 05 — 📐 Statistics for Data Analysts

**Level:** 🟡 Intermediate

Statistics helps analysts determine whether observed patterns are meaningful.

## 🎯 Learn

### Descriptive Statistics

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

### Distributions

- [ ] Distribution shape
- [ ] Skewness
- [ ] Outliers
- [ ] Normal distribution

### Relationships

- [ ] Covariance
- [ ] Correlation
- [ ] Scatter plots

### Statistical Reasoning

- [ ] Population vs sample
- [ ] Sampling
- [ ] Sampling bias
- [ ] Confidence intervals
- [ ] Hypothesis testing fundamentals
- [ ] Statistical significance
- [ ] Practical significance

---

# 🏢 BIH Lab 08 — Statistical Investigation

Investigate:

### Attendance

Calculate:

- [ ] Mean
- [ ] Median
- [ ] Standard deviation
- [ ] Quartiles
- [ ] Minimum
- [ ] Maximum

Then compare attendance across technical teams.

---

### Engagement

Investigate correlations between:

```text
Attendance ↔ Projects Completed

Training Hours ↔ Review Score

Task Completion ↔ Review Score
```

Explain what the correlations do **and do not** tell you.

---

# 06 — 📊 Power BI

**Level:** 🟡 Intermediate

Power BI allows analysts to transform analysis into interactive reports and dashboards.

[![Learn Power BI](https://img.youtube.com/vi/I0vQ_VLZTWg/maxresdefault.jpg)](https://www.youtube.com/watch?v=I0vQ_VLZTWg)

## 🎥 Main Power BI Course

**[▶ Learn Power BI in Under 3 Hours](https://www.youtube.com/watch?v=I0vQ_VLZTWg)**

---

## 📚 Official Documentation

**[📘 Microsoft Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)**

**[📘 Power BI Fundamentals](https://learn.microsoft.com/en-us/power-bi/fundamentals/)**

**[📘 Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)**

**[📘 Power BI Visualizations](https://learn.microsoft.com/en-us/power-bi/visuals/)**

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
- [ ] Charts
- [ ] Reports
- [ ] Dashboards

---

# 🏢 BIH Lab 09 — Community Dashboard

Import:

```text
bih_data_analyst_practice.csv
```

---

## KPI Cards

Create:

```text
👥 Total Participants

📋 Projects Completed

📅 Average Attendance

✅ Average Task Completion

⭐ Average Review Score

⏱️ Training Hours
```

---

## Visualizations

Create:

- [ ] Participants by team
- [ ] Participants by experience
- [ ] Attendance by team
- [ ] Projects completed by team
- [ ] Review score by team
- [ ] Project categories
- [ ] Project status
- [ ] Participants joining over time

---

## 🎛️ Filters

Add slicers for:

- [ ] Technical Team
- [ ] Experience Level
- [ ] Project Category
- [ ] Project Status

---

# 07 — 🧮 Data Modelling & DAX

**Level:** 🟡 Intermediate → 🔴 Advanced

Building professional Power BI reports requires more than dragging fields onto charts.

## 🎯 Learn

### Data Modelling

- [ ] Fact tables
- [ ] Dimension tables
- [ ] Relationships
- [ ] Cardinality
- [ ] Filter direction
- [ ] Star schema

### DAX

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

## 📚 Documentation

**[📘 DAX Documentation](https://learn.microsoft.com/en-us/dax/)**

---

# 🏢 BIH Lab 10 — Create BIH Measures

Create measures for:

```text
Total Participants

Total Projects

Average Attendance

Average Review Score

Project Completion Rate

Average Training Hours

Active Participant Rate
```

Do not create unnecessary calculated columns when a measure is more appropriate.

---

# 08 — 🎯 KPIs & Business Metrics

A Data Analyst should understand that not every number deserves to become a KPI.

## Understand

- [ ] Metric vs KPI
- [ ] Leading indicators
- [ ] Lagging indicators
- [ ] Targets
- [ ] Benchmarks
- [ ] Rates
- [ ] Ratios
- [ ] Percent change
- [ ] KPI context

---

# 🏢 BIH Lab 11 — Design BIH KPIs

Suppose BIH wants to monitor:

```text
Community Growth
Engagement
Skills Development
Project Participation
Project Completion
Technical Performance
```

Design appropriate KPIs.

For every KPI explain:

### Definition

What exactly does it measure?

### Formula

How is it calculated?

### Purpose

Why does BIH need it?

### Limitation

How could the metric be misleading?

---

# 🧠 BIH Engagement Score Challenge

Design:

```text
Attendance          30%
Task Completion     30%
Training Activity   20%
Projects Completed  20%
```

Then classify:

```text
80–100     Highly Engaged
65–79      Engaged
50–64      Moderate
Below 50   Requires Attention
```

But answer:

> **Why could this metric be unfair or misleading?**

Consider:

- Arbitrary weighting
- Different roles
- Project difficulty
- Missing data
- Quality vs quantity
- Availability differences

---

# 09 — 📈 Dashboard Design

A dashboard should reduce complexity rather than create more of it.

## Recommended Structure

```text
┌─────────────────────────────────────────┐
│       BIH COMMUNITY PERFORMANCE         │
├────────┬────────┬────────┬──────────────┤
│Members │Projects│Attend. │Review Score  │
├────────┴────────┴────────┴──────────────┤
│                                         │
│          PRIMARY ANALYSIS               │
│                                         │
├───────────────────┬─────────────────────┤
│ Team Performance  │ Engagement Trends   │
├───────────────────┴─────────────────────┤
│          SUPPORTING ANALYSIS            │
├─────────────────────────────────────────┤
│              FILTERS                    │
└─────────────────────────────────────────┘
```

---

## Dashboard Principles

- [ ] Clear visual hierarchy
- [ ] Important KPIs first
- [ ] Appropriate chart types
- [ ] Consistent labels
- [ ] Minimal unnecessary decoration
- [ ] Useful filters
- [ ] Context for metrics
- [ ] Readable titles
- [ ] Logical grouping

Before adding a chart ask:

> **What decision does this visualization help someone make?**

---

# 10 — 🧠 Data Storytelling

Data analysis becomes valuable when findings can be communicated clearly.

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

# 🏢 BIH Lab 12 — Management Brief

Imagine you have **five minutes** to brief BIH leadership.

Present:

### 3 Key Findings

What should leadership know?

### 2 Risks

What requires attention?

### 3 Recommendations

What should be investigated or changed?

### 1 Limitation

What important question cannot be answered from the available dataset?

---

# 11 — 🏗️ Final Data Analyst Project

# BIH Community Performance Analysis

## Business Question

> **How effectively is the Beacon Innovation Hub community engaging participants, developing technical skills, and supporting project activity?**

---

## Phase 1 — Business Understanding

Define:

- [ ] Main question
- [ ] Stakeholders
- [ ] Relevant metrics
- [ ] Scope
- [ ] Limitations

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

Investigate:

- [ ] Community composition
- [ ] Technical teams
- [ ] Attendance
- [ ] Training activity
- [ ] Project participation
- [ ] Project completion
- [ ] Review performance
- [ ] Engagement
- [ ] Trends
- [ ] Potential areas requiring intervention

---

## Phase 4 — Statistics

Include:

- [ ] Descriptive statistics
- [ ] Distribution analysis
- [ ] Group comparisons
- [ ] Correlation analysis
- [ ] Appropriate interpretation

---

## Phase 5 — Power BI

Create:

### Page 1 — Executive Overview

KPIs and major trends.

### Page 2 — Team Performance

Technical-team comparisons.

### Page 3 — Participant Engagement

Attendance, training and project activity.

### Page 4 — Project Analysis

Project categories, status and performance.

---

## Phase 6 — Findings

Provide at least **five meaningful findings**.

Each finding must include evidence.

---

## Phase 7 — Recommendations

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

- [ ] SELECT
- [ ] Filtering
- [ ] Aggregations
- [ ] GROUP BY
- [ ] HAVING
- [ ] JOINs
- [ ] CASE
- [ ] Subqueries
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
- [ ] CALCULATE
- [ ] DIVIDE
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

Each project repository should explain:

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

A recruiter or reviewer should be able to understand:

> **What problem did you solve?**

> **How did you solve it?**

> **What did you discover?**

> **Why does the result matter?**

---

# 🚀 Completion

When you can independently receive unfamiliar organisational data and:

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

you are moving beyond simply learning analytics tools and toward **professional analytical problem-solving**.

> **A Data Analyst's value is not determined by how many tools they know. It is determined by their ability to turn reliable evidence into information that helps people make better decisions.**
