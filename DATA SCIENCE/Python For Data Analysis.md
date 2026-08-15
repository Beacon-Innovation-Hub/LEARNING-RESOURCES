# 📊 Common Data Foundations

> Build the shared technical foundation required for Data Analytics, Data Science, and Data Engineering.

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-success)
![Python](https://img.shields.io/badge/Python-Data%20Fundamentals-blue)
![Practice](https://img.shields.io/badge/Approach-Project%20Based-orange)
![BIH](https://img.shields.io/badge/Case%20Studies-Beacon%20Innovation%20Hub-purple)

**Learning Model:** 🎥 Watch → 📚 Read → 🎮 Play → 🧩 Practice → 📊 Analyse → 🧠 Explain → 🏗️ Build

---

# 🗺️ Shared Learning Roadmap

```text
🐍 Python Fundamentals
        ↓
🔢 NumPy
        ↓
🐼 Pandas
        ↓
🧹 Data Cleaning
        ↓
🔗 Multiple Tables & Joins
        ↓
📊 Data Visualization
        ↓
🔎 Exploratory Data Analysis
        ↓
✅ Validation & Documentation
        ↓
🏗️ BIH Common Data Project
```

This file contains **only the shared foundation**.

Specialisation begins after this stage.

---

# 🚀 Main Beginner Course

[![Python for Data Analytics](https://img.youtube.com/vi/wUSDVGivd-8/maxresdefault.jpg)](https://youtu.be/wUSDVGivd-8)

## 🎥 Python for Data Analytics

**[▶ Watch the Full Course](https://youtu.be/wUSDVGivd-8)**

Use this as the main guided resource.

Do not watch passively.

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

Python is the common programming foundation for modern data work.

## 🎥 Additional Beginner Resource

[![Python for Beginners](https://img.youtube.com/vi/b093aqAZiPU/maxresdefault.jpg)](https://youtu.be/b093aqAZiPU)

**[▶ Watch Python for Beginners](https://youtu.be/b093aqAZiPU)**

Use this resource if you need extra help with Python fundamentals.

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

## ⚔️ CodeCombat

**[🎮 Learn Python Through Gameplay](https://codecombat.com/)**

Recommended for basic programming logic.

## 🕹️ CodinGame

**[🎮 Solve Programming Challenges](https://www.codingame.com/)**

Use after becoming comfortable with basic Python.

---

# 🏢 BIH Lab 01 — Participant Registration

```python
participant = {
    "name": "Ayanda",
    "team": "Data Science",
    "experience": "Beginner",
    "github": True,
    "projects_completed": 2
}
```

### Tasks

* [ ] Display the participant's name
* [ ] Display the team
* [ ] Check whether GitHub exists
* [ ] Increase `projects_completed`
* [ ] Add a LinkedIn field
* [ ] Add technical skills
* [ ] Display every skill
* [ ] Create at least five fictional participants

### Extension

Determine:

* [ ] Total number of participants
* [ ] Number per technical team
* [ ] Most common team
* [ ] Average projects completed

---

# 🏢 BIH Lab 02 — Project Evaluation Engine

Suppose BIH evaluates projects using:

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

Classify results:

```text
80–100    High Potential
65–79     Promising
50–64     Requires Development
Below 50  Major Revision Required
```

### Tasks

* [ ] Calculate a weighted result
* [ ] Evaluate one project
* [ ] Evaluate five projects
* [ ] Find the highest score
* [ ] Calculate the average
* [ ] Assign classifications automatically

---

# 2. NumPy

**Level:** 🟢 Beginner → 🟡 Intermediate

NumPy provides efficient numerical operations for structured numeric data.

---

## 🎥 NumPy Resource 1

[![NumPy Tutorial](https://img.youtube.com/vi/zI5ducyfyNc/maxresdefault.jpg)](https://youtu.be/zI5ducyfyNc)

**[▶ Watch NumPy Resource 1](https://youtu.be/zI5ducyfyNc)**

## 🎥 NumPy Resource 2

[![Python NumPy Tutorial](https://img.youtube.com/vi/QUT1VHiLmmI/maxresdefault.jpg)](https://youtu.be/QUT1VHiLmmI)

**[▶ Watch NumPy Resource 2](https://youtu.be/QUT1VHiLmmI)**

---

## 📚 Documentation

* **[NumPy Beginner Guide](https://numpy.org/doc/stable/user/absolute_beginners.html)**
* **[NumPy User Guide](https://numpy.org/doc/stable/user/)**
* **[NumPy API Reference](https://numpy.org/doc/stable/reference/)**

---

## 🎯 Learn

* [ ] Arrays
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

* [ ] Array shape
* [ ] Number of projects
* [ ] Mean score per project
* [ ] Mean per criterion
* [ ] Highest technical score
* [ ] Lowest presentation score
* [ ] Standard deviation
* [ ] Highest-performing project
* [ ] Projects averaging above 75

> Try to use NumPy operations instead of loops.

---

# 3. Pandas

**Level:** 🟢 Beginner → 🟡 Intermediate

Pandas is the main shared tool for tabular data manipulation.

---

## 🎥 Pandas Resource

[![Pandas Tutorial](https://img.youtube.com/vi/EXIgjIBu4EU/maxresdefault.jpg)](https://youtu.be/EXIgjIBu4EU)

**[▶ Watch Pandas Tutorial](https://youtu.be/EXIgjIBu4EU)**

## 🎥 Additional Resource

[![Additional Data Resource](https://img.youtube.com/vi/2uvysYbKdjM/maxresdefault.jpg)](https://youtu.be/2uvysYbKdjM)

**[▶ Watch Additional Data Resource](https://youtu.be/2uvysYbKdjM)**

---

## 📚 Pandas Documentation

| Topic           | Documentation                                                                             |
| --------------- | ----------------------------------------------------------------------------------------- |
| Getting Started | [Pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)       |
| User Guide      | [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)                 |
| DataFrame       | [DataFrame Reference](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) |
| Missing Data    | [Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)  |
| GroupBy         | [GroupBy](https://pandas.pydata.org/docs/user_guide/groupby.html)                         |
| Joining         | [Merge, Join & Concatenate](https://pandas.pydata.org/docs/user_guide/merging.html)       |

---

## 🎯 Learn

* [ ] Series
* [ ] DataFrames
* [ ] CSV files
* [ ] Excel files
* [ ] `head()`
* [ ] `tail()`
* [ ] `info()`
* [ ] `describe()`
* [ ] Selecting columns
* [ ] Filtering
* [ ] Sorting
* [ ] Missing values
* [ ] Duplicate records
* [ ] Grouping
* [ ] Aggregation
* [ ] Merging
* [ ] Joining
* [ ] Column transformations

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

Create at least **30 fictional participants**.

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

* [ ] Dataset shape
* [ ] Data types
* [ ] Descriptive statistics
* [ ] Missing-value counts
* [ ] Duplicate counts
* [ ] Unique categories
* [ ] Suspicious values

---

# 4. Data Cleaning

**Level:** 🟡 Intermediate

Use the following workflow:

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

# 🏢 BIH Lab 05 — Clean the Dataset

For every important transformation, record:

### Problem

What is wrong?

### Evidence

How was it identified?

### Decision

What should be done?

### Transformation

How was it changed?

### Validation

How was the result verified?

---

### Clean

* [ ] Missing values
* [ ] Duplicates
* [ ] Inconsistent categories
* [ ] Dates
* [ ] Numeric values
* [ ] Invalid values
* [ ] Text inconsistencies
* [ ] Final dataset

> Never silently clean important data.

---

# 5. Multiple Tables & Joins

**Level:** 🟡 Intermediate

Create:

```text
participants.csv
projects.csv
project_members.csv
reviews.csv
```

---

## Relationships

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

# 🏢 BIH Lab 06 — Joining Data

### Tasks

* [ ] Load all tables
* [ ] Identify primary keys
* [ ] Identify foreign keys
* [ ] Validate key data types
* [ ] Join participant and project data
* [ ] Join project reviews
* [ ] Detect unmatched records
* [ ] Compare row counts
* [ ] Detect accidental duplication
* [ ] Validate the final dataset

### Questions

1. Which project has the largest team?
2. Which technical team contributes to the most projects?
3. Which project has the highest review score?
4. Which participants work on multiple projects?
5. What is the average score by project category?
6. Which categories have the most participants?

---

# 6. Data Visualization

**Level:** 🟡 Intermediate

Visualization helps communicate patterns clearly.

---

## 🎥 Visualization Resource

[![Data Visualization](https://img.youtube.com/vi/OZOOLe2imFo/maxresdefault.jpg)](https://www.youtube.com/watch?v=OZOOLe2imFo)

**[▶ Watch Visualization Resource](https://www.youtube.com/watch?v=OZOOLe2imFo)**

---

## 📚 Matplotlib Documentation

* **[Getting Started](https://matplotlib.org/stable/users/getting_started/)**
* **[Quick Start](https://matplotlib.org/stable/users/explain/quick_start.html)**
* **[Plot Types](https://matplotlib.org/stable/plot_types/index.html)**

---

## 🎯 Learn

* [ ] Bar charts
* [ ] Line charts
* [ ] Scatter plots
* [ ] Histograms
* [ ] Titles
* [ ] Labels
* [ ] Legends
* [ ] Axes
* [ ] Appropriate chart selection

---

# 🏢 BIH Lab 07 — Community Insights

Visualize:

* [ ] Participants by team
* [ ] Projects by category
* [ ] Projects by status
* [ ] Attendance distribution
* [ ] Review scores
* [ ] Projects completed
* [ ] Average project score by category
* [ ] Attendance vs projects completed

For each chart provide:

### 👀 Observation

What does it show?

### 🔎 Analysis

What pattern exists?

### 🧠 Interpretation

What might explain it?

### 🎯 Action

What should BIH investigate?

---

# 7. Exploratory Data Analysis

**Level:** 🟡 Intermediate

EDA is used to understand the structure, patterns, anomalies, and relationships in unfamiliar data.

---

# 🏢 BIH Case Study — Community Performance

Investigate:

* [ ] Which teams are growing?
* [ ] Which teams have high participation?
* [ ] Which teams have low attendance?
* [ ] Which projects attract more participants?
* [ ] Which categories perform best?
* [ ] Is attendance associated with completion?
* [ ] Which projects may require intervention?
* [ ] Are some technical teams underrepresented?
* [ ] Which participants appear highly engaged?

---

# 🧠 Analysis Framework

```text
📊 DATA
What happened?
     ↓
🔎 PATTERN
What trend or relationship exists?
     ↓
🧠 INTERPRETATION
What might explain it?
     ↓
🎯 DECISION
What should be investigated or done?
```

> Correlation does not automatically imply causation.

---

# 8. Validation & Documentation

**Level:** 🟡 Intermediate

A result is not trustworthy merely because the code ran successfully.

---

## ✅ Validate

* [ ] Row counts
* [ ] Column counts
* [ ] Data types
* [ ] Missingness
* [ ] Unique keys
* [ ] Join results
* [ ] Aggregations
* [ ] Transformation outputs
* [ ] Unexpected outliers
* [ ] Impossible values

---

## 📝 Document

Record:

* Data source
* Dataset purpose
* Data types
* Missingness
* Cleaning decisions
* Transformations
* Joins
* Aggregations
* Validation checks
* Assumptions
* Known limitations

---

# 9. BIH Common Data Project

# 🏗️ BIH Community Data Investigation

### Scenario

Beacon Innovation Hub provides multiple messy datasets and asks:

> **What does the data reveal about participant engagement, project activity, and areas that may require further investigation?**

---

## Project Requirements

### 1. Data Understanding

* [ ] Describe every dataset
* [ ] Identify columns
* [ ] Identify types
* [ ] Identify keys
* [ ] Map relationships

### 2. Data Quality

* [ ] Missingness
* [ ] Duplicates
* [ ] Invalid values
* [ ] Inconsistent categories
* [ ] Incorrect types

### 3. Cleaning

* [ ] Preserve raw data
* [ ] Document changes
* [ ] Validate transformations

### 4. Integration

* [ ] Join tables
* [ ] Explain join types
* [ ] Validate joins

### 5. Analysis

* [ ] Filtering
* [ ] Sorting
* [ ] Grouping
* [ ] Aggregation
* [ ] Descriptive statistics

### 6. Visualization

* [ ] Appropriate chart choice
* [ ] Clear labels
* [ ] Interpretation

### 7. Findings

Identify at least five meaningful findings.

### 8. Recommendations

Provide evidence-based recommendations or areas for further investigation.

---

# 📁 Recommended Project Structure

```text
BIH-data-foundations/
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

> 🔒 Never overwrite the original raw datasets.

---

# 10. Progress Checklist

## 🐍 Python

* [ ] Main Python for Data course
* [ ] Beginner Python tutorial
* [ ] Data types
* [ ] Conditions
* [ ] Loops
* [ ] Collections
* [ ] Functions
* [ ] Exceptions

## 🔢 NumPy

* [ ] NumPy tutorial 1
* [ ] NumPy tutorial 2
* [ ] Arrays
* [ ] Indexing
* [ ] Filtering
* [ ] Aggregation
* [ ] Broadcasting

## 🐼 Pandas

* [ ] Pandas tutorial
* [ ] DataFrames
* [ ] Data inspection
* [ ] Missing data
* [ ] Duplicates
* [ ] Filtering
* [ ] Sorting
* [ ] GroupBy
* [ ] Aggregation
* [ ] Merge / Join

## 🧹 Data Quality

* [ ] Missing-value analysis
* [ ] Duplicate detection
* [ ] Category standardisation
* [ ] Type conversion
* [ ] Transformation documentation
* [ ] Validation

## 📊 Visualization

* [ ] Visualization resource
* [ ] Matplotlib
* [ ] Bar charts
* [ ] Scatter plots
* [ ] Histograms
* [ ] Appropriate chart selection
* [ ] Interpretation

## 🏢 BIH Labs

* [ ] Participant Registration
* [ ] Project Evaluation
* [ ] NumPy Project Scores
* [ ] Community Dataset
* [ ] Data Cleaning
* [ ] Multi-Table Analysis
* [ ] Community Visualization
* [ ] EDA Case Study
* [ ] Common Data Project



# 💡 Learning Principle

Do not measure progress by tutorial hours.

Measure whether you can receive unfamiliar data and:

```text
📥 Understand
     ↓
🔎 Inspect
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
```

> **The shared goal is to become capable of turning raw data into reliable, understandable information. Specialisation comes after this foundation.**
