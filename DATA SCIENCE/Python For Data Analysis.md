# 📊 Data Science, Data Analytics & Data Engineering Learning Path

> Learn how to understand, clean, transform, analyse, visualize, and engineer data before specialising as a **Data Analyst**, **Data Scientist**, or **Data Engineer**.

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-success)
![Python](https://img.shields.io/badge/Python-Data%20Fundamentals-blue)
![Practice](https://img.shields.io/badge/Approach-Project%20Based-orange)
![BIH](https://img.shields.io/badge/Case%20Studies-Beacon%20Innovation%20Hub-purple)

**Learning Model:** 🎥 Watch → 📚 Read → 🎮 Play → 🧩 Practice → 📊 Analyse → 🧠 Explain → 🏗️ Build

---

# 🗺️ Learning Roadmap

```text
                           📊 DATA
                              │
                              ▼
                    COMMON DATA FOUNDATION
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
      📊 DATA ANALYST   🧠 DATA SCIENTIST   ⚙️ DATA ENGINEER
             │                │                │
           Excel          Statistics      Advanced SQL
            SQL          Probability       Databases
          Python           Python         Data Modeling
          Pandas           NumPy            ETL / ELT
        Power BI       Visualization       Pipelines
        Tableau       Machine Learning   Warehousing
             │                │            Cloud / Spark
             ▼                ▼                ▼
       Dashboards         ML Models      Data Platforms
       & Insights         & Research      & Pipelines
```

---

# 📍 Common Foundation

1. [Python Fundamentals](#1-python-fundamentals)
2. [NumPy](#2-numpy)
3. [Pandas](#3-pandas)
4. [Data Cleaning](#4-data-cleaning)
5. [Multiple Tables & Joins](#5-multiple-tables--joins)
6. [Data Visualization](#6-data-visualization)
7. [Exploratory Data Analysis](#7-exploratory-data-analysis)
8. [Beginner BIH Project](#8-beginner-bih-project)
9. [Progress Checklist](#9-progress-checklist)
10. [Specialisation Paths](#10-specialisation-paths)

---

# 🚀 Main Beginner Course

[![Python for Data Analytics](https://img.youtube.com/vi/wUSDVGivd-8/maxresdefault.jpg)](https://youtu.be/wUSDVGivd-8)

## 🎥 Python for Data Analytics

**[▶ Watch the Full Course](https://youtu.be/wUSDVGivd-8)**

Use this as the main guided resource for the beginner data pathway.

Do not watch the course passively.

```text
🎥 Watch
   ↓
⏸️ Pause
   ↓
⌨️ Recreate
   ↓
🔧 Modify
   ↓
🧩 Solve a BIH Problem
   ↓
📚 Consult Documentation
```

---

# 1. Python Fundamentals

**Level:** 🟢 Beginner

Python provides the programming foundation for all three data pathways.

---

## 🎥 Beginner Python Resource

[![Python for Beginners](https://img.youtube.com/vi/b093aqAZiPU/maxresdefault.jpg)](https://youtu.be/b093aqAZiPU)

**[▶ Watch Python for Beginners](https://youtu.be/b093aqAZiPU)**

Use this resource if you need additional support with basic Python before working with data libraries.

---

## 🎯 Learn

* [ ] Variables
* [ ] Numbers
* [ ] Strings
* [ ] Booleans
* [ ] `None`
* [ ] Lists
* [ ] Tuples
* [ ] Sets
* [ ] Dictionaries
* [ ] Operators
* [ ] Comparisons
* [ ] Conditional statements
* [ ] Loops
* [ ] Functions
* [ ] List comprehensions
* [ ] Modules
* [ ] Basic classes
* [ ] Exception handling

---

## 📚 Official Python Documentation

| Topic              | Documentation                                                                                |
| ------------------ | -------------------------------------------------------------------------------------------- |
| Main Reference     | [Python Documentation](https://docs.python.org/3/)                                           |
| Beginner Tutorial  | [Official Python Tutorial](https://docs.python.org/3/tutorial/)                              |
| Data Structures    | [Python Data Structures](https://docs.python.org/3/tutorial/datastructures.html)             |
| Conditions & Loops | [Control Flow](https://docs.python.org/3/tutorial/controlflow.html)                          |
| Functions          | [Defining Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) |
| Classes            | [Python Classes](https://docs.python.org/3/tutorial/classes.html)                            |
| Errors             | [Errors & Exceptions](https://docs.python.org/3/tutorial/errors.html)                        |

---

# 🎮 Interactive Python Learning

## 🏝️ CheckiO

**[🎮 Play Python Coding Missions](https://py.checkio.org/)**

Useful for:

`conditions` • `loops` • `functions` • `strings` • `lists` • `problem solving`

---

## ⚔️ CodeCombat

**[🎮 Learn Python Through Gameplay](https://codecombat.com/)**

Recommended when learning:

* Variables
* Conditions
* Loops
* Functions
* Programming logic

---

## 🕹️ CodinGame

**[🎮 Solve Programming Challenges](https://www.codingame.com/)**

Use after becoming comfortable with basic Python.

---

# 🏢 BIH Lab 01 — Participant Registration

### Scenario

Beacon Innovation Hub receives a new participant registration.

```python
participant = {
    "name": "Ayanda",
    "team": "Data Science",
    "experience": "Beginner",
    "github": True,
    "projects_completed": 2
}
```

### Your Mission

* [ ] Display the participant's name
* [ ] Display the technical team
* [ ] Determine whether the participant has GitHub
* [ ] Increase `projects_completed`
* [ ] Add a LinkedIn field
* [ ] Add a list of technical skills
* [ ] Display every technical skill

### ⭐ Extension

Create at least **five fictional participants**.

Then determine:

* [ ] Total participants
* [ ] Number in Data Science
* [ ] Number in Cybersecurity
* [ ] Number in Software Development
* [ ] Most common team

Do not manually count the data.

---

# 🏢 BIH Lab 02 — Project Evaluation Engine

BIH evaluates innovation projects using:

| Criterion             | Weight |
| --------------------- | -----: |
| Technical Feasibility |    40% |
| Market Potential      |    30% |
| Impact                |    20% |
| Presentation          |    10% |

Create:

```python
def calculate_project_score(
    technical,
    market,
    impact,
    presentation
):
    pass
```

### Classification

```text
80–100    High Potential
65–79     Promising
50–64     Requires Development
Below 50  Major Revision Required
```

### Tasks

* [ ] Calculate the weighted score
* [ ] Evaluate one project
* [ ] Evaluate five projects
* [ ] Store project results
* [ ] Find the highest-scoring project
* [ ] Calculate the average project score
* [ ] Assign a classification automatically

---

# 2. NumPy

**Level:** 🟢 Beginner → 🟡 Intermediate

NumPy provides efficient numerical operations and is foundational for scientific computing and data science.

---

## 🎥 NumPy Resource 1

[![NumPy Tutorial](https://img.youtube.com/vi/zI5ducyfyNc/maxresdefault.jpg)](https://youtu.be/zI5ducyfyNc)

**[▶ Watch NumPy Resource 1](https://youtu.be/zI5ducyfyNc)**

---

## 🎥 NumPy Resource 2

[![Python NumPy Tutorial](https://img.youtube.com/vi/QUT1VHiLmmI/maxresdefault.jpg)](https://youtu.be/QUT1VHiLmmI)

**[▶ Watch NumPy Resource 2](https://youtu.be/QUT1VHiLmmI)**

Use the second resource when you need another explanation or additional examples.

---

## 📚 NumPy Documentation

* **[NumPy Beginner Guide](https://numpy.org/doc/stable/user/absolute_beginners.html)**
* **[NumPy User Guide](https://numpy.org/doc/stable/user/)**
* **[NumPy API Reference](https://numpy.org/doc/stable/reference/)**

---

## 🎯 Learn

* [ ] NumPy arrays
* [ ] Dimensions
* [ ] Shape
* [ ] Data types
* [ ] Indexing
* [ ] Slicing
* [ ] Filtering
* [ ] Vectorized operations
* [ ] Aggregation
* [ ] Broadcasting
* [ ] Statistical operations

---

# 🏢 BIH Lab 03 — Innovation Project Scores

```python
import numpy as np

scores = np.array([
    [78, 82, 75, 80],
    [91, 88, 84, 90],
    [65, 71, 69, 74],
    [84, 79, 88, 86],
    [58, 64, 61, 67]
])
```

Columns represent:

```text
Technical | Market | Impact | Presentation
```

### Analyse

* [ ] Determine the array shape
* [ ] Determine the number of projects
* [ ] Calculate mean score per project
* [ ] Calculate mean score per criterion
* [ ] Find the highest technical score
* [ ] Find the lowest presentation score
* [ ] Calculate standard deviation
* [ ] Identify the best-performing project
* [ ] Identify projects averaging above 75

> ⭐ Try to solve these using NumPy operations instead of Python loops.

---

# 3. Pandas

**Level:** 🟢 Beginner → 🟡 Intermediate

Pandas is one of the most important tools in this pathway for working with structured and tabular data.

---

## 🎥 Pandas Tutorial

[![Pandas Tutorial](https://img.youtube.com/vi/EXIgjIBu4EU/maxresdefault.jpg)](https://youtu.be/EXIgjIBu4EU)

**[▶ Watch the Pandas Tutorial](https://youtu.be/EXIgjIBu4EU)**

---

## 🎥 Additional Data Resource

[![Additional Data Resource](https://img.youtube.com/vi/2uvysYbKdjM/maxresdefault.jpg)](https://youtu.be/2uvysYbKdjM)

**[▶ Watch Additional Data Resource](https://youtu.be/2uvysYbKdjM)**

Use this resource as additional reinforcement.

---

## 📚 Pandas Documentation

| Topic           | Documentation                                                                             |
| --------------- | ----------------------------------------------------------------------------------------- |
| Getting Started | [Pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)       |
| User Guide      | [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)                 |
| DataFrame       | [DataFrame Reference](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) |
| Missing Data    | [Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)  |
| Grouping        | [GroupBy](https://pandas.pydata.org/docs/user_guide/groupby.html)                         |
| Joining         | [Merge, Join & Concatenate](https://pandas.pydata.org/docs/user_guide/merging.html)       |

---

## 🎯 Learn

* [ ] Series
* [ ] DataFrames
* [ ] Reading CSV files
* [ ] Reading Excel files
* [ ] `head()`
* [ ] `tail()`
* [ ] `info()`
* [ ] `describe()`
* [ ] Data types
* [ ] Selecting columns
* [ ] Filtering rows
* [ ] Sorting
* [ ] Missing values
* [ ] Duplicate rows
* [ ] Grouping
* [ ] Aggregation
* [ ] Merging
* [ ] Joining
* [ ] Transforming columns

---

# 🏢 BIH Lab 04 — Community Participant Dataset

Create:

```text
participants.csv
```

with:

```text
participant_id
name
team
experience_level
join_date
github_username
projects_completed
attendance_rate
```

Create at least **30 fictional participant records**.

Deliberately introduce:

* [ ] Missing values
* [ ] Duplicate records
* [ ] Incorrect dates
* [ ] Incorrect data types
* [ ] Invalid numeric values
* [ ] Inconsistent capitalization
* [ ] Inconsistent team names

Example:

```text
Data Science
data science
DATA SCIENCE
DataScience
```

---

## 🔎 Investigate Before Cleaning

* [ ] Display first rows
* [ ] Determine dataset shape
* [ ] Inspect data types
* [ ] Generate descriptive statistics
* [ ] Count missing values
* [ ] Count duplicate records
* [ ] Inspect unique team values
* [ ] Identify suspicious values

---

# 4. Data Cleaning

**Level:** 🟡 Intermediate

Professional data work requires understanding **why** a transformation was applied, not merely producing a clean dataset.

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

# 🏢 BIH Lab 05 — Clean the Community Dataset

For every important transformation, document:

### Problem

What is wrong?

### Evidence

How was the problem discovered?

### Decision

What will be done?

### Transformation

How was the data changed?

### Validation

How do you know the transformation worked?

---

### Example

> **Problem:** `"Data Science"` appears using multiple spellings.
> **Evidence:** Inspection of unique values revealed inconsistent labels.
> **Decision:** Standardise valid variations.
> **Transformation:** Convert variations to `"Data Science"`.
> **Validation:** Inspect unique team values again.

---

## Clean

* [ ] Missing values
* [ ] Duplicate records
* [ ] Team names
* [ ] Dates
* [ ] Numeric fields
* [ ] Invalid values
* [ ] Inconsistent text
* [ ] Final dataset

> **Rule:** Never silently clean important data.

---

# 5. Multiple Tables & Joins

**Level:** 🟡 Intermediate

Real-world data is usually distributed across multiple tables.

Create:

```text
participants.csv
projects.csv
project_members.csv
reviews.csv
```

---

## `participants.csv`

```text
participant_id
name
team
experience
```

## `projects.csv`

```text
project_id
project_name
category
status
start_date
```

## `project_members.csv`

```text
project_id
participant_id
role
```

## `reviews.csv`

```text
project_id
technical_score
market_score
impact_score
review_date
```

---

## 🗂️ Relationships

```text
Participants
     │
     ▼
Project Members
     │
     ▼
Projects
     │
     ▼
Reviews
```

---

# 🏢 BIH Lab 06 — Joining Community Data

### Tasks

* [ ] Load all tables
* [ ] Identify primary keys
* [ ] Identify foreign keys
* [ ] Validate key data types
* [ ] Join participants with project membership
* [ ] Join project information
* [ ] Join reviews
* [ ] Detect unmatched records
* [ ] Compare row counts before and after joins
* [ ] Detect accidental duplication
* [ ] Validate the final dataset

---

## Answer

1. Which project has the largest team?
2. Which BIH team contributes to the most projects?
3. Which project has the highest review score?
4. Which participants work across multiple projects?
5. What is the average project score by category?
6. Which project categories have the most participants?
7. Are more experienced participants associated with higher project scores?

---

# 6. Data Visualization

**Level:** 🟡 Intermediate

A good analysis should communicate information clearly, not just calculate it.

---

## 🎥 Visualization Resource

[![Data Visualization](https://img.youtube.com/vi/OZOOLe2imFo/maxresdefault.jpg)](https://www.youtube.com/watch?v=OZOOLe2imFo)

**[▶ Watch Data Visualization Resource](https://www.youtube.com/watch?v=OZOOLe2imFo)**

---

## 📚 Matplotlib Documentation

* **[Getting Started](https://matplotlib.org/stable/users/getting_started/)**
* **[Quick Start](https://matplotlib.org/stable/users/explain/quick_start.html)**
* **[Plot Types](https://matplotlib.org/stable/plot_types/index.html)**

---

## 🎯 Learn

* [ ] Line charts
* [ ] Bar charts
* [ ] Horizontal bar charts
* [ ] Scatter plots
* [ ] Histograms
* [ ] Labels
* [ ] Titles
* [ ] Legends
* [ ] Axes
* [ ] Appropriate chart selection

---

# 🏢 BIH Lab 07 — Community Insights

Visualize:

* [ ] Participants by technical team
* [ ] Projects by category
* [ ] Projects by status
* [ ] Attendance distribution
* [ ] Review scores
* [ ] Projects completed per participant
* [ ] Average project score by category
* [ ] Attendance vs projects completed

---

## For Every Visualization

### 👀 Observation

What does the chart show?

### 🔎 Analysis

What pattern is visible?

### 🧠 Interpretation

What might explain that pattern?

### 🎯 Action

What could BIH investigate or do?

---

# 7. Exploratory Data Analysis

**Level:** 🟡 Intermediate

Exploratory Data Analysis is about discovering meaningful patterns, anomalies, relationships, and questions in data.

---

# 🏢 BIH Case Study — Community Performance

### Scenario

Beacon Innovation Hub wants to understand whether its community model is effectively developing participants and producing successful technology projects.

Available data includes:

```text
Participants
Teams
Attendance
Projects
Project Membership
Project Reviews
Project Completion
```

---

## 🔍 Investigate

* [ ] Which technical teams are growing fastest?
* [ ] Which teams have the strongest participation?
* [ ] Which teams have the lowest attendance?
* [ ] Which projects attract the most participants?
* [ ] Which project categories perform best?
* [ ] Is attendance associated with project completion?
* [ ] Are more experienced participants completing more projects?
* [ ] Which projects appear to require intervention?
* [ ] Are particular technical teams underrepresented?
* [ ] Which participants appear highly engaged?

---

# 🧠 Analysis Framework

For every major finding:

```text
📊 DATA
What happened?
     ↓
🔎 PATTERN
What relationship or trend exists?
     ↓
🧠 INTERPRETATION
What might explain it?
     ↓
🎯 DECISION
What should be investigated or done next?
```

> ⚠️ Correlation does not prove causation.

---

# 8. Beginner BIH Project

# 🏗️ BIH Community Data Analysis

### Scenario

You have joined the Beacon Innovation Hub data team.

Management provides multiple messy datasets and asks:

> **What does the available evidence reveal about community participation, project performance, participant engagement, and areas requiring intervention?**

---

## 1️⃣ Understand the Data

* [ ] Describe each dataset
* [ ] Explain every important column
* [ ] Identify data types
* [ ] Identify primary keys
* [ ] Identify foreign keys
* [ ] Map table relationships

---

## 2️⃣ Assess Data Quality

* [ ] Missing values
* [ ] Duplicate records
* [ ] Invalid values
* [ ] Incorrect data types
* [ ] Inconsistent categories
* [ ] Suspicious values

---

## 3️⃣ Clean & Transform

* [ ] Preserve raw data
* [ ] Document transformations
* [ ] Standardise categories
* [ ] Correct types
* [ ] Handle missing values
* [ ] Validate cleaned data

---

## 4️⃣ Integrate Data

* [ ] Join tables
* [ ] Explain join types
* [ ] Identify unmatched records
* [ ] Check row counts
* [ ] Validate joins

---

## 5️⃣ Analyse

Use:

* [ ] Filtering
* [ ] Sorting
* [ ] Grouping
* [ ] Aggregation
* [ ] Descriptive statistics
* [ ] Comparative analysis

---

## 6️⃣ Visualize

* [ ] Select suitable chart types
* [ ] Label charts properly
* [ ] Avoid misleading visualisations
* [ ] Explain what each chart contributes

---

## 7️⃣ Findings

Identify at least **five meaningful findings** supported by data.

---

## 8️⃣ Recommendations

Translate your findings into evidence-based recommendations for BIH.

---

# 📁 Recommended Project Structure

```text
BIH-data-analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── figures/
│   └── cleaned-data/
│
├── src/
│   └── cleaning.py
│
├── README.md
└── requirements.txt
```

> 🔒 **Never overwrite your original raw datasets.**

---

# 9. Progress Checklist

## 🐍 Python

* [ ] Main Python for Data course
* [ ] Beginner Python resource
* [ ] Variables
* [ ] Data types
* [ ] Conditions
* [ ] Loops
* [ ] Lists
* [ ] Dictionaries
* [ ] Functions
* [ ] Exceptions

---

## 🔢 NumPy

* [ ] NumPy Resource 1
* [ ] NumPy Resource 2
* [ ] Arrays
* [ ] Shape
* [ ] Indexing
* [ ] Filtering
* [ ] Aggregation
* [ ] Vectorized operations
* [ ] Broadcasting

---

## 🐼 Pandas

* [ ] Pandas tutorial
* [ ] DataFrames
* [ ] Data inspection
* [ ] CSV files
* [ ] Excel files
* [ ] Data types
* [ ] Missing data
* [ ] Duplicates
* [ ] Filtering
* [ ] Sorting
* [ ] GroupBy
* [ ] Aggregation
* [ ] Merge / Join

---

## 🧹 Data Quality

* [ ] Missing-value analysis
* [ ] Duplicate detection
* [ ] Category standardisation
* [ ] Type conversion
* [ ] Validation
* [ ] Transformation documentation

---

## 📊 Visualization

* [ ] Visualization resource
* [ ] Matplotlib
* [ ] Bar charts
* [ ] Scatter plots
* [ ] Histograms
* [ ] Appropriate chart selection
* [ ] Interpretation

---

## 🏢 BIH Labs

* [ ] Participant Registration
* [ ] Project Evaluation Engine
* [ ] NumPy Innovation Scores
* [ ] Community Participant Dataset
* [ ] Data Cleaning
* [ ] Multi-Table Analysis
* [ ] Community Visualizations
* [ ] EDA Case Study
* [ ] BIH Beginner Data Project

---

# 10. Specialisation Paths

After completing the common foundation, choose a path.

---

# 📊 Data Analyst

Focus on turning data into understandable business information and decisions.

### Continue With

```text
Excel
  ↓
SQL
  ↓
Advanced Pandas
  ↓
Statistics
  ↓
Power BI
  ↓
Tableau
  ↓
Dashboard Design
  ↓
Business Analysis
  ↓
Data Storytelling
```

### Core Skills

* [ ] Excel
* [ ] Advanced spreadsheets
* [ ] SQL
* [ ] Data cleaning
* [ ] Statistical summaries
* [ ] Dashboard design
* [ ] Power BI
* [ ] Tableau
* [ ] KPI design
* [ ] Data storytelling
* [ ] Business recommendations

---

# 🧠 Data Scientist

Focus on statistical reasoning, predictive models, experimentation, and machine learning.

### Continue With

```text
Statistics
   ↓
Probability
   ↓
Advanced Python
   ↓
NumPy / Pandas
   ↓
Data Visualization
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Feature Engineering
   ↓
Experiments
   ↓
ML Projects
```

### Core Skills

* [ ] Probability
* [ ] Statistics
* [ ] Hypothesis testing
* [ ] Regression
* [ ] Classification
* [ ] Feature engineering
* [ ] Machine learning
* [ ] Model evaluation
* [ ] Experiment design
* [ ] Scientific communication

---

# ⚙️ Data Engineer

Focus on building reliable systems for collecting, transforming, storing, and serving data.

### Continue With

```text
Advanced SQL
     ↓
Database Design
     ↓
Linux / Bash
     ↓
Python
     ↓
ETL / ELT
     ↓
Data Modeling
     ↓
Data Warehousing
     ↓
Airflow
     ↓
Spark
     ↓
Cloud Platforms
     ↓
Production Pipelines
```

### Core Skills

* [ ] Advanced SQL
* [ ] Relational databases
* [ ] Database design
* [ ] Linux
* [ ] Bash
* [ ] Python
* [ ] ETL / ELT
* [ ] Data modelling
* [ ] Data warehouses
* [ ] Data lakes
* [ ] Airflow
* [ ] Spark
* [ ] Cloud data platforms
* [ ] Pipeline monitoring
* [ ] Data quality

---

# 🎮 Recommended Interactive Learning

Use these resources throughout the programme.

### 🐍 CheckiO

**[Python Missions →](https://py.checkio.org/)**

### ⚔️ CodeCombat

**[Learn Through Gameplay →](https://codecombat.com/)**

### 🕹️ CodinGame

**[Programming Challenges →](https://www.codingame.com/)**

### 📓 Google Colab

**[Open Google Colab →](https://colab.research.google.com/)**

Use Colab to practise Python and data analysis without installing a local environment.

### 🧪 Kaggle

**[Kaggle Learn & Datasets →](https://www.kaggle.com/)**

Use Kaggle later for:

* Real datasets
* Notebooks
* Data-cleaning practice
* Visualization
* Machine learning
* Portfolio projects

---

# 🚀 Complete Data Progression

```text
🐍 Python Fundamentals
          ↓
🔢 NumPy
          ↓
🐼 Pandas
          ↓
🧹 Data Cleaning
          ↓
🔗 Multiple Tables
          ↓
📊 Visualization
          ↓
🔎 Exploratory Data Analysis
          ↓
🏗️ BIH Data Project
          ↓
      SHARED FOUNDATION
          │
 ┌────────┼─────────┐
 │        │         │
 ▼        ▼         ▼
📊       🧠        ⚙️
Analyst Scientist Engineer
```

---

# 💡 Learning Principle

Do not measure progress by:

> **"I watched ten hours of Python tutorials."**

Measure progress by whether you can receive unfamiliar data and:

```text
📥 Understand
     ↓
🧹 Clean
     ↓
✅ Validate
     ↓
🔗 Integrate
     ↓
📊 Analyse
     ↓
📈 Visualize
     ↓
🧠 Explain
     ↓
🎯 Recommend
```

A professional data practitioner should be able to explain:

* Where the data came from
* What its limitations are
* What transformations were performed
* Why those transformations were necessary
* Whether the results can be trusted
* What patterns were discovered
* What conclusions are justified
* What decisions the evidence supports

> **The objective is not simply to produce numbers. The objective is to transform data into trustworthy evidence that supports better decisions.**
