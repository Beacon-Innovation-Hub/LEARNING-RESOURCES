# 🐍 Python for Data — Beginner

> Learn Python by working with realistic data problems inspired by the
> Beacon Innovation Hub.

**Level:** 🟢 Beginner  
**Path:** Data Analyst • Data Scientist • Data Engineer  
**Learning Model:** Watch → Read → Play → Practice → Analyse → Build

---

# 🎯 Learning Objectives

By the end of this section, you should be able to:

- [ ] Understand basic Python syntax
- [ ] Work with variables and data types
- [ ] Use conditions and loops
- [ ] Write reusable functions
- [ ] Work with lists, dictionaries, sets and tuples
- [ ] Read data from files
- [ ] Use NumPy for numerical data
- [ ] Use Pandas to work with tabular data
- [ ] Clean messy datasets
- [ ] Join multiple datasets
- [ ] Aggregate data
- [ ] Create basic visualizations
- [ ] Perform a basic exploratory data analysis
- [ ] Explain and document data transformations

---

# 1. Python for Data Analytics

[![Python for Data Analytics](https://img.youtube.com/vi/wUSDVGivd-8/maxresdefault.jpg)](https://youtu.be/wUSDVGivd-8)

## 🎥 Main Course

**[▶ Python for Data Analytics — Full Course](https://youtu.be/wUSDVGivd-8)**

Do not watch the entire course passively.

Use:

```text
Watch
  ↓
Pause
  ↓
Recreate the example
  ↓
Change the data
  ↓
Predict the output
  ↓
Run the code
  ↓
Solve a BIH problem
```

---

# 2. Python Fundamentals

## 🎯 Learn

- [ ] Variables
- [ ] Numbers
- [ ] Strings
- [ ] Booleans
- [ ] `None`
- [ ] Lists
- [ ] Tuples
- [ ] Sets
- [ ] Dictionaries
- [ ] Operators
- [ ] Comparisons
- [ ] Conditional statements
- [ ] Loops
- [ ] Functions
- [ ] List comprehensions
- [ ] Modules
- [ ] Basic classes
- [ ] Exception handling

---

# 📚 Python Documentation

Use the official Python documentation whenever you need to understand
how the language actually works.

### Python Documentation

**[📘 Python Documentation](https://docs.python.org/3/)**

### Python Tutorial

**[📘 Official Python Tutorial](https://docs.python.org/3/tutorial/)**

### Data Structures

**[📘 Python Data Structures](https://docs.python.org/3/tutorial/datastructures.html)**

### Control Flow

**[📘 Python Control Flow](https://docs.python.org/3/tutorial/controlflow.html)**

### Functions

**[📘 Defining Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)**

### Classes

**[📘 Python Classes](https://docs.python.org/3/tutorial/classes.html)**

### Errors & Exceptions

**[📘 Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html)**

---

# 🎮 Learn Python Through Games

Programming should not only be learned through lectures.

Use coding games to reinforce logic, conditions, loops and functions.

## 🏝️ CheckiO — Python

**[🎮 Play CheckiO Python](https://py.checkio.org/)**

Solve programming missions using Python.

Recommended for:

- Conditions
- Loops
- Functions
- Strings
- Lists
- Dictionaries
- Problem solving

---

## ⚔️ CodeCombat

**[🎮 CodeCombat](https://codecombat.com/)**

Control characters by writing code.

Use it when learning:

- Variables
- Conditions
- Loops
- Functions

---

## 🧩 CodinGame

**[🎮 CodinGame](https://www.codingame.com/)**

Use this after becoming comfortable with basic Python.

It is useful for developing:

- Programming logic
- Algorithms
- Debugging
- Problem-solving

---

# 🏢 BIH PRACTICE 1 — Participant Registration

Beacon Innovation Hub has received registrations from new community
participants.

Represent one participant using a dictionary:

```python
participant = {
    "name": "Ayanda",
    "team": "Data Science",
    "experience": "Beginner",
    "github": True,
    "projects_completed": 2
}
```

## Tasks

- [ ] Print the participant's name
- [ ] Print their team
- [ ] Determine whether they have GitHub
- [ ] Increase `projects_completed` by one
- [ ] Add a `linkedin` field
- [ ] Add a list of technical skills
- [ ] Print every skill

Then create at least five participants.

---

# 🏢 BIH PRACTICE 2 — Team Assignment

BIH participants can work in areas such as:

```text
Software Development
Data Science
Cybersecurity
Data Engineering
Research
Project Management
```

Create:

```python
participants = [
    {"name": "Ayanda", "team": "Data Science"},
    {"name": "Thando", "team": "Cybersecurity"},
    {"name": "Lwazi", "team": "Software Development"},
    {"name": "Zanele", "team": "Data Science"},
]
```

Determine:

- [ ] How many participants there are
- [ ] How many belong to Data Science
- [ ] How many belong to Cybersecurity
- [ ] How many belong to Software Development
- [ ] Which team has the most participants

Do not manually count the participants.

Use Python.

---

# 3. Functions

Functions allow data practitioners to create reusable transformations
and calculations.

---

# 🏢 BIH PRACTICE 3 — Project Evaluation

Suppose BIH scores projects using:

```text
Technical Feasibility → 40%
Market Potential       → 30%
Impact                 → 20%
Presentation           → 10%
```

Create:

```python
def calculate_project_score(
    technical,
    market,
    impact,
    presentation
):
    # Your solution
    pass
```

The function should calculate the weighted project score.

Then classify projects:

```text
80–100 → High Potential
65–79  → Promising
50–64  → Requires Development
Below 50 → Major Revision Required
```

## Tasks

- [ ] Write the function
- [ ] Test one project
- [ ] Test five projects
- [ ] Store projects inside a list
- [ ] Determine the highest-scoring project
- [ ] Calculate the average score

---

# 4. NumPy

NumPy provides efficient tools for working with numerical data.

---

# 📚 NumPy Documentation

### Beginner Guide

**[📘 NumPy — Absolute Beginner's Guide](https://numpy.org/doc/stable/user/absolute_beginners.html)**

### User Guide

**[📘 NumPy User Guide](https://numpy.org/doc/stable/user/)**

---

## 🎯 Learn

- [ ] NumPy arrays
- [ ] Array dimensions
- [ ] Shape
- [ ] Data types
- [ ] Indexing
- [ ] Slicing
- [ ] Filtering
- [ ] Vectorized operations
- [ ] Aggregation
- [ ] Broadcasting

---

# 🏢 BIH PRACTICE 4 — Project Scores

Suppose the technical review scores for BIH projects are:

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

Each row represents a project.

The columns represent:

```text
Technical
Market
Impact
Presentation
```

Determine:

- [ ] Shape of the array
- [ ] Number of projects
- [ ] Average score for every project
- [ ] Average technical score
- [ ] Average market score
- [ ] Highest technical score
- [ ] Lowest presentation score
- [ ] Standard deviation for each category
- [ ] Highest-performing project
- [ ] Projects with an average above 75

Try solving these using NumPy operations rather than loops.

---

# 5. Pandas

Pandas is one of the most important Python libraries for working with
tabular data.

---

# 📚 Pandas Documentation

### Getting Started

**[📘 Pandas — Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)**

### User Guide

**[📘 Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)**

### DataFrame

**[📘 Pandas DataFrame](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)**

### Missing Data

**[📘 Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)**

### Merge / Join

**[📘 Merge, Join & Concatenate](https://pandas.pydata.org/docs/user_guide/merging.html)**

### GroupBy

**[📘 GroupBy](https://pandas.pydata.org/docs/user_guide/groupby.html)**

---

## 🎯 Learn

- [ ] Series
- [ ] DataFrames
- [ ] Reading CSV files
- [ ] Reading Excel files
- [ ] `head()`
- [ ] `tail()`
- [ ] `info()`
- [ ] `describe()`
- [ ] Data types
- [ ] Selecting columns
- [ ] Filtering
- [ ] Sorting
- [ ] Missing values
- [ ] Duplicates
- [ ] Grouping
- [ ] Aggregation
- [ ] Merging
- [ ] Joining
- [ ] Transforming columns

---

# 🏢 BIH PRACTICE 5 — Community Dataset

Create:

```text
participants.csv
```

with columns:

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

Include at least **30 fictional participants**.

Deliberately introduce:

- Missing values
- Duplicate records
- Inconsistent team names
- Incorrect dates
- Incorrect data types
- Different capitalization

Examples:

```text
Data Science
data science
DATA SCIENCE
DataScience
```

---

## 🔍 Investigate

Before cleaning anything:

- [ ] Display the first rows
- [ ] Determine the dataset shape
- [ ] Inspect column types
- [ ] Count missing values
- [ ] Identify duplicate records
- [ ] Inspect unique team values
- [ ] Generate descriptive statistics

---

# 🧹 BIH PRACTICE 6 — Data Cleaning

Clean the participant dataset.

For every transformation, document:

```text
Problem
   ↓
Evidence
   ↓
Decision
   ↓
Transformation
   ↓
Validation
```

Example:

```text
Problem:
"Data Science" appears using four different spellings.

Decision:
Standardize team names.

Transformation:
Convert all variations to "Data Science".

Validation:
Check unique values again.
```

Complete:

- [ ] Missing-value investigation
- [ ] Duplicate removal
- [ ] Team-name standardization
- [ ] Date conversion
- [ ] Numeric-type correction
- [ ] Invalid-value investigation
- [ ] Final validation

---

# 6. Working With Multiple Tables

Real data rarely exists in one perfect table.

Create:

```text
participants.csv
projects.csv
project_members.csv
reviews.csv
```

---

## participants.csv

```text
participant_id
name
team
experience
```

## projects.csv

```text
project_id
project_name
category
status
start_date
```

## project_members.csv

```text
project_id
participant_id
role
```

## reviews.csv

```text
project_id
technical_score
market_score
impact_score
review_date
```

---

# 🏢 BIH PRACTICE 7 — Joining Data

Using Pandas:

- [ ] Load all four datasets
- [ ] Inspect their keys
- [ ] Validate data types
- [ ] Join participants to project membership
- [ ] Join project information
- [ ] Join project reviews
- [ ] Check unmatched records
- [ ] Check whether joins unexpectedly increased row counts
- [ ] Validate the final dataset

Then answer:

1. Which project has the largest team?
2. Which team contributes to the most projects?
3. Which project has the highest review score?
4. Which participants contribute to multiple projects?
5. What is the average project score by category?
6. Are more experienced participants associated with higher project scores?

---

# 7. Matplotlib

Data analysis is incomplete if findings cannot be communicated.

---

# 📚 Matplotlib Documentation

### Getting Started

**[📘 Matplotlib — Getting Started](https://matplotlib.org/stable/users/getting_started/)**

### Quick Start

**[📘 Matplotlib Quick Start](https://matplotlib.org/stable/users/explain/quick_start.html)**

### Plot Types

**[📘 Matplotlib Plot Types](https://matplotlib.org/stable/plot_types/index.html)**

---

## 🎯 Learn

- [ ] Line charts
- [ ] Bar charts
- [ ] Horizontal bars
- [ ] Scatter plots
- [ ] Histograms
- [ ] Labels
- [ ] Titles
- [ ] Legends
- [ ] Axes
- [ ] Figure sizing

---

# 📊 BIH PRACTICE 8 — Community Dashboard Analysis

Using your BIH datasets, visualize:

- [ ] Participants by team
- [ ] Projects by category
- [ ] Projects by status
- [ ] Average project score
- [ ] Attendance distribution
- [ ] Projects completed per participant
- [ ] Average project score by category
- [ ] Relationship between attendance and projects completed

For every visualization, write:

### Observation

What does the chart show?

### Interpretation

Why might this pattern exist?

### Decision

What could BIH do with this information?

---

# 8. Exploratory Data Analysis

You are now acting as a junior BIH data practitioner.

Your task is not merely to generate charts.

You must discover useful information.

---

# 🏢 BIH CASE STUDY — Community Performance

## Scenario

Beacon Innovation Hub wants to understand whether its community
development model is effectively developing participants and producing
successful projects.

You have been given data covering:

```text
Participants
Teams
Attendance
Projects
Project membership
Project reviews
Project completion
```

Management wants evidence-based answers.

---

## 🔍 Questions

Investigate:

- [ ] Which technical teams are growing fastest?
- [ ] Which teams have the highest participation?
- [ ] Which teams have the lowest attendance?
- [ ] Which projects attract the most participants?
- [ ] Which project categories perform best?
- [ ] Is attendance associated with project completion?
- [ ] Are experienced participants completing more projects?
- [ ] Which projects appear to require intervention?
- [ ] Are certain teams underrepresented in projects?
- [ ] Which participants appear highly engaged?

---

# 🧠 Go Beyond the Numbers

For every important finding, distinguish between:

```text
DATA
"What happened?"

ANALYSIS
"What pattern exists?"

INTERPRETATION
"What might explain it?"

DECISION
"What should BIH investigate or do next?"
```

Do not claim causation merely because two variables are correlated.

---

# 🏁 FINAL BEGINNER PROJECT

## BIH Community Data Analysis

You have joined the Beacon Innovation Hub data team.

Management gives you several messy datasets and asks:

> **What can the available data tell us about community participation,
> project performance and areas requiring intervention?**

---

## Your Analysis Must Include

### 1. Data Understanding

- [ ] Dataset descriptions
- [ ] Columns
- [ ] Data types
- [ ] Primary keys
- [ ] Relationships

### 2. Data Quality

- [ ] Missingness
- [ ] Duplicates
- [ ] Invalid values
- [ ] Inconsistent categories
- [ ] Incorrect types

### 3. Transformation

Document every important transformation.

### 4. Data Integration

- [ ] Join datasets
- [ ] Explain join types
- [ ] Validate joins

### 5. Analysis

Use:

- [ ] Filtering
- [ ] Grouping
- [ ] Aggregation
- [ ] Descriptive statistics

### 6. Visualization

Produce appropriate charts.

### 7. Findings

Identify at least **five meaningful findings**.

### 8. Recommendations

Convert the findings into actionable recommendations for BIH.

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

Never overwrite your original raw dataset.

---

# 📊 Progress Checklist

## Python

- [ ] Variables
- [ ] Data types
- [ ] Conditions
- [ ] Loops
- [ ] Lists
- [ ] Dictionaries
- [ ] Functions
- [ ] Exceptions

## NumPy

- [ ] Arrays
- [ ] Indexing
- [ ] Filtering
- [ ] Aggregation
- [ ] Vectorized operations

## Pandas

- [ ] Series
- [ ] DataFrames
- [ ] CSV files
- [ ] Data inspection
- [ ] Data types
- [ ] Missing data
- [ ] Duplicates
- [ ] Filtering
- [ ] Sorting
- [ ] GroupBy
- [ ] Aggregation
- [ ] Merge / Join

## Visualization

- [ ] Matplotlib
- [ ] Bar charts
- [ ] Line charts
- [ ] Scatter plots
- [ ] Histograms
- [ ] Chart interpretation

## Practical Work

- [ ] Participant registration exercise
- [ ] Team analysis
- [ ] Project evaluation
- [ ] NumPy project analysis
- [ ] Data cleaning
- [ ] Multi-table joins
- [ ] Community visualization
- [ ] BIH Community Data Analysis project

---

# 🚀 Where This Leads

Completing this section establishes the shared Python foundation for:

```text
                    Python for Data
                          │
             Data Cleaning & Analysis
                          │
              ┌───────────┼───────────┐
              │           │           │
              ▼           ▼           ▼
        📊 Analyst   🧠 Scientist   ⚙️ Engineer
```

Do not specialize too early.

First become comfortable understanding, cleaning, manipulating and
explaining data.

---

# 💡 Learning Principle

Do not measure progress by:

> "I watched 10 hours of Python."

Measure progress by:

> "I was given unfamiliar data, investigated it, cleaned it, validated
> my transformations, analysed it and explained what I discovered."

Use this cycle:

```text
🎥 LEARN
    ↓
🎮 PLAY
    ↓
🧩 PRACTICE
    ↓
🏢 SOLVE A BIH PROBLEM
    ↓
🐛 DEBUG
    ↓
📚 CONSULT DOCUMENTATION
    ↓
📊 ANALYSE
    ↓
🧠 EXPLAIN
    ↓
🔁 IMPROVE
```

> **A data professional does not simply produce numbers. They must be able
> to explain where the data came from, what was done to it, whether the
> result can be trusted, what the result means, and what decisions the
> evidence supports.**
