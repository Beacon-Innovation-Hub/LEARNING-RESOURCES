# Beacon Innovation Hub — Data Analyst Pathway

**Pathway:** Data Analyst  
**Stage:** Level 1 of 5  
**Prerequisite:** BIH Common Data Foundation (Python for Data)

---

# Level 1 — Data Analytics Foundations

**Classification:** Foundational Specialisation  
**Goal:** Learn how analysts frame questions, inspect data, correct quality problems, perform exploratory analysis, and use spreadsheets to produce reliable summaries.

## Level 1 Outcomes

By the end of this level, the participant should be able to:

- [ ] Explain the role and workflow of a Data Analyst
- [ ] Translate a basic organisational problem into analytical questions
- [ ] Inspect an unfamiliar dataset before analysis
- [ ] Identify missingness, duplicates, invalid types and inconsistent categories
- [ ] Document cleaning decisions and validate transformations
- [ ] Produce descriptive summaries and group comparisons
- [ ] Use Excel or another spreadsheet tool for practical analysis
- [ ] Build PivotTables, PivotCharts and a basic analytical dashboard
- [ ] Distinguish observations from unsupported conclusions

---

## 01 — 📊 Introduction to Data Analysis

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

## 🧠 The Analyst Workflow

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

## 02 — 🔎 Practical Data Analysis

**Level:** 🟢 Beginner → 🟡 Intermediate

[![Data Analysis](https://img.youtube.com/vi/qrbf9DtR3_c/maxresdefault.jpg)](https://www.youtube.com/watch?v=qrbf9DtR3_c)

## 🎥 Continuing Resource

**[▶ Continue Data Analysis Learning](https://www.youtube.com/watch?v=qrbf9DtR3_c)**

---

## 🧪 Practice Dataset

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

## 🏢 BIH Lab 01 — Understand the Dataset

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

## 🧹 BIH Lab 02 — Data Quality

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

## 🏢 BIH Lab 03 — Community Overview

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

## 🏢 BIH Lab 04 — Team Analysis

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

## 🏢 BIH Lab 05 — Engagement Analysis

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

---

## 03 — Spreadsheet Analysis

**Level:** Beginner → Intermediate

Spreadsheets remain an important tool for Data Analysts because they allow
rapid data exploration, validation, calculation, reporting, and communication
with business stakeholders.

[![Excel for Data Analytics](https://img.youtube.com/vi/pCJ15nGFgVg/maxresdefault.jpg)](https://www.youtube.com/watch?v=pCJ15nGFgVg)

## Main Course

**[Watch: Excel for Data Analytics — Full Course for Beginners](https://www.youtube.com/watch?v=pCJ15nGFgVg)**

## Skills to Develop

- [ ] Excel tables
- [ ] Sorting and filtering
- [ ] Data cleaning
- [ ] Conditional formatting
- [ ] Data validation
- [ ] Text functions
- [ ] Date functions
- [ ] Logical functions
- [ ] XLOOKUP
- [ ] SUMIFS
- [ ] COUNTIFS
- [ ] AVERAGEIFS
- [ ] PivotTables
- [ ] PivotCharts
- [ ] Charts
- [ ] Basic dashboard development

---

## 🏢 BIH Lab 06 — Spreadsheet Analysis

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

---

## Level 1 Competence Assessment

The participant should receive an unfamiliar structured dataset and independently:

1. Profile and document the dataset.
2. Identify and correct data-quality problems.
3. Produce a cleaning log.
4. Answer a set of business questions.
5. Build a spreadsheet summary using formulas and PivotTables.
6. Present at least three evidence-supported findings.
7. State limitations and validation checks.

**Progression rule:** Level 2 should begin only after the participant demonstrates reliable foundational analysis rather than simply completing the learning resources.

---
