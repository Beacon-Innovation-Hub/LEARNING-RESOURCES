# Beacon Innovation Hub — Data Analyst Pathway

**Pathway:** Data Analyst  
**Stage:** Level 2 of 5  
**Prerequisite:** Data Analyst Level 1 and its competence assessment

---

# Level 2 — SQL & Statistical Analysis

**Classification:** Developing Analyst  
**Goal:** Move from single-file analysis to relational data and use statistical reasoning to support analytical conclusions.

## Level 2 Outcomes

By the end of this level, the participant should be able to:

- [ ] Query relational databases using SQL
- [ ] Filter, aggregate and group records correctly
- [ ] Join multiple tables while validating row counts and keys
- [ ] Use `CASE`, subqueries, CTEs and window functions
- [ ] Calculate and interpret descriptive statistics
- [ ] Identify distributions, skewness and outliers
- [ ] Measure relationships using covariance and correlation
- [ ] Explain population, sample, sampling bias and confidence intervals
- [ ] Distinguish statistical association from causation
- [ ] Combine SQL outputs with statistical reasoning

---

## 04 — 🗄️ SQL for Data Analysts

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

## 📚 SQL Documentation

**[PostgreSQL Documentation](https://www.postgresql.org/docs/)**

---

## 🎮 Interactive SQL Practice

## SQLBolt

**[🚀 Learn SQL Interactively](https://sqlbolt.com/)**

## SQL Murder Mystery

**[🕵️ Solve the SQL Murder Mystery](https://mystery.knightlab.com/)**

---

## 🏢 BIH SQL Database

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

## 🏢 BIH SQL Lab 01 — Basic Queries

- [ ] Display all participants
- [ ] Display participant names
- [ ] Display unique experience levels
- [ ] Find Data Science participants
- [ ] Find participants who joined after a date
- [ ] Sort by joining date
- [ ] Display the first 10 participants

---

## 🏢 BIH SQL Lab 02 — Aggregation

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

## 🏢 BIH SQL Lab 03 — JOINs

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

## 🏢 BIH SQL Lab 04 — Advanced Analytics

Practice:

- [ ] Performance categories with `CASE`
- [ ] Participant summaries with CTEs
- [ ] Overall participant ranking
- [ ] Ranking within teams
- [ ] Running totals
- [ ] Window functions

---

---

## 05 — 📐 Statistics for Data Analysts

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

## 🏢 BIH Lab 07 — Statistical Investigation

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

---

## Level 2 Competence Assessment

Using a multi-table BIH-style database, the participant should:

1. Write queries that answer management questions.
2. Demonstrate correct joins and document join validation.
3. Use aggregation, `CASE`, CTEs and at least one window function.
4. Produce descriptive statistical summaries.
5. Investigate at least two relationships between variables.
6. Explain what the results support and what they do not support.
7. Submit reproducible SQL and an analytical summary.

**Progression rule:** The participant must show that they can obtain trustworthy evidence from relational data before moving into business-intelligence tooling.

---vvv
