# 🐍 Python for Data

> ### 📊 Data Science • Data Analytics • Data Engineering
>
> Build a strong Python foundation by learning through documentation, interactive practice, and realistic Beacon Innovation Hub data problems.

---

![Level](https://img.shields.io/badge/Level-Beginner-success)
![Python](https://img.shields.io/badge/Python-Data%20Fundamentals-blue)
![Practice](https://img.shields.io/badge/Approach-Project%20Based-orange)
![BIH](https://img.shields.io/badge/Case%20Studies-Beacon%20Innovation%20Hub-purple)

### 🧭 Learning Model

**🎥 Watch → 📚 Read → 🎮 Play → 🧩 Practice → 📊 Analyse → 🧠 Explain → 🏗️ Build**

---

## 🚀 Start Here

[![Python for Data Analytics](https://img.youtube.com/vi/wUSDVGivd-8/maxresdefault.jpg)](https://youtu.be/wUSDVGivd-8)

### 🎥 Python for Data Analytics

**[▶ Watch the Full Beginner Course](https://youtu.be/wUSDVGivd-8)**

Use the course as your main guided resource, but avoid passive watching.

> **Recommended workflow**
>
> Watch a concept → pause → reproduce it → change the example → solve a BIH problem → consult documentation when stuck.

---

# 🗺️ Beginner Roadmap

| Stage | Topic                  | Practice                     |
| ----- | ---------------------- | ---------------------------- |
| 01    | 🐍 Python Fundamentals | BIH participant data         |
| 02    | 🧠 Functions & Logic   | BIH project scoring          |
| 03    | 🔢 NumPy               | Project evaluation scores    |
| 04    | 🐼 Pandas              | Community datasets           |
| 05    | 🧹 Data Cleaning       | Messy participant data       |
| 06    | 🔗 Data Joins          | Projects + members + reviews |
| 07    | 📊 Visualization       | BIH dashboard analysis       |
| 08    | 🔎 EDA                 | Community performance        |
| 09    | 🏗️ Project            | BIH data investigation       |

---

# 01 — 🐍 Python Fundamentals

### What You Will Learn

`variables` • `strings` • `numbers` • `booleans` • `lists` • `tuples` • `sets` • `dictionaries` • `conditions` • `loops` • `functions` • `exceptions`

### 📚 Documentation

| Resource                                                                            | Use                         |
| ----------------------------------------------------------------------------------- | --------------------------- |
| [Python Documentation](https://docs.python.org/3/)                                  | Main reference              |
| [Python Tutorial](https://docs.python.org/3/tutorial/)                              | Beginner learning           |
| [Data Structures](https://docs.python.org/3/tutorial/datastructures.html)           | Lists, dictionaries, tuples |
| [Control Flow](https://docs.python.org/3/tutorial/controlflow.html)                 | Conditions and loops        |
| [Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) | Reusable logic              |
| [Errors & Exceptions](https://docs.python.org/3/tutorial/errors.html)               | Handling problems           |

---

## 🎮 Learn by Playing

### 🏝️ CheckiO

**[Play Python Missions →](https://py.checkio.org/)**

Best for:

`conditions` • `loops` • `functions` • `strings` • `problem solving`

### ⚔️ CodeCombat

**[Learn Python Through Gameplay →](https://codecombat.com/)**

Best when first learning programming logic.

### 🕹️ CodinGame

**[Solve Coding Challenges →](https://www.codingame.com/)**

Use after becoming comfortable with the basics.

---

## 🏢 BIH Lab 01 — Participant Registration

### Scenario

Beacon Innovation Hub has received a new participant registration.

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
* [ ] Check whether a GitHub account exists
* [ ] Increase `projects_completed`
* [ ] Add a LinkedIn field
* [ ] Add a list of skills
* [ ] Display every skill

### ⭐ Bonus

Create a list containing **five participants** and determine how many belong to each BIH technical team.

---

# 02 — 🧠 Functions & Logic

## 🏢 BIH Lab 02 — Project Evaluation Engine

### Scenario

BIH evaluates proposed innovation projects using four criteria:

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

### Your Mission

* [ ] Calculate the weighted result
* [ ] Evaluate one project
* [ ] Evaluate five projects
* [ ] Store results in a list
* [ ] Find the highest-scoring project
* [ ] Calculate the overall project average

---

# 03 — 🔢 NumPy

> NumPy is used for efficient numerical operations on structured arrays.

### 📚 Documentation

**[NumPy Beginner Guide →](https://numpy.org/doc/stable/user/absolute_beginners.html)**

**[NumPy User Guide →](https://numpy.org/doc/stable/user/)**

### Learn

`arrays` • `shape` • `dtype` • `indexing` • `slicing` • `filtering` • `aggregation` • `broadcasting`

---

## 🏢 BIH Lab 03 — Technical Review Scores

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

The columns represent:

**Technical • Market • Impact • Presentation**

### Analyse

* [ ] Array shape
* [ ] Number of projects
* [ ] Average score per project
* [ ] Average score per criterion
* [ ] Highest technical score
* [ ] Lowest presentation score
* [ ] Standard deviation
* [ ] Best-performing project
* [ ] Projects averaging above 75%

> 💡 Try to solve these using NumPy operations instead of Python loops.

---

# 04 — 🐼 Pandas

> Pandas is the core tool in this pathway for working with structured tabular data.

### 📚 Documentation

| Topic           | Documentation                                                                             |
| --------------- | ----------------------------------------------------------------------------------------- |
| Getting Started | [Pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)       |
| User Guide      | [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)                 |
| DataFrame       | [DataFrame Reference](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) |
| Missing Data    | [Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)               |
| GroupBy         | [GroupBy](https://pandas.pydata.org/docs/user_guide/groupby.html)                         |
| Merge / Join    | [Merge & Join](https://pandas.pydata.org/docs/user_guide/merging.html)                    |

---

## 🏢 BIH Lab 04 — Community Dataset

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

Deliberately insert:

> ⚠️ Missing values
> ⚠️ Duplicate rows
> ⚠️ Incorrect dates
> ⚠️ Incorrect data types
> ⚠️ Inconsistent capitalization
> ⚠️ Inconsistent team names

Example:

```text
Data Science
data science
DATA SCIENCE
DataScience
```

---

## 🔎 Data Investigation

Before cleaning anything:

* [ ] `head()`
* [ ] `shape`
* [ ] `info()`
* [ ] `describe()`
* [ ] Missing-value counts
* [ ] Duplicate counts
* [ ] Unique team values
* [ ] Data-type inspection

---

# 05 — 🧹 Data Cleaning

## 🏢 BIH Lab 05 — Clean the Community Dataset

Use this process for every major transformation:

```text
🔍 Detect
   ↓
📋 Document
   ↓
🧠 Decide
   ↓
🛠️ Transform
   ↓
✅ Validate
```

### Example

> **Problem:** `"Data Science"` appears under several spellings.
> **Decision:** Standardize the category.
> **Transformation:** Convert all valid variations to `"Data Science"`.
> **Validation:** Check unique values after transformation.

### Clean

* [ ] Missing values
* [ ] Duplicate rows
* [ ] Team names
* [ ] Dates
* [ ] Numeric values
* [ ] Invalid records
* [ ] Final dataset

> **Rule:** Never silently clean data. Be able to explain every important transformation.

---

# 06 — 🔗 Multiple Tables & Joins

Real-world data rarely arrives in one perfect CSV.

Create:

```text
participants.csv
projects.csv
project_members.csv
reviews.csv
```

### Data Relationships

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

### Your Mission

* [ ] Load all datasets
* [ ] Identify primary and foreign keys
* [ ] Validate data types
* [ ] Join participants to project memberships
* [ ] Join project information
* [ ] Join review data
* [ ] Identify unmatched records
* [ ] Check unexpected row duplication
* [ ] Validate the final joined dataset

### Questions

1. Which project has the largest team?
2. Which BIH team contributes to the most projects?
3. Which project has the highest review score?
4. Which participants contribute to several projects?
5. What is the average project score by category?
6. Is participant experience associated with project performance?

---

# 07 — 📊 Data Visualization

### 📚 Matplotlib

**[Getting Started →](https://matplotlib.org/stable/users/getting_started/)**

**[Quick Start →](https://matplotlib.org/stable/users/explain/quick_start.html)**

**[Plot Types →](https://matplotlib.org/stable/plot_types/index.html)**

### Learn

`bar charts` • `line charts` • `scatter plots` • `histograms` • `labels` • `titles` • `legends`

---

## 🏢 BIH Lab 06 — Community Insights

Visualize:

* [ ] Participants by team
* [ ] Projects by category
* [ ] Projects by status
* [ ] Project scores
* [ ] Attendance distribution
* [ ] Projects completed per participant
* [ ] Average project score by category
* [ ] Attendance vs project completion

For every chart, provide:

### 👀 Observation

What does the visualization show?

### 🧠 Interpretation

What might explain the pattern?

### 🎯 Decision

What could BIH investigate or do next?

---

# 08 — 🔎 Exploratory Data Analysis

## 🏢 Case Study — BIH Community Performance

### Management Question

> **Is the Beacon Innovation Hub community model effectively developing participants and producing successful projects?**

You have access to:

```text
Participants
Teams
Attendance
Projects
Project Membership
Project Reviews
Project Completion
```

### Investigate

* [ ] Which teams are growing fastest?
* [ ] Which teams have the strongest participation?
* [ ] Which teams have low attendance?
* [ ] Which projects attract the most participants?
* [ ] Which project categories perform best?
* [ ] Does attendance relate to project completion?
* [ ] Do experienced participants complete more projects?
* [ ] Which projects may require intervention?
* [ ] Are some teams underrepresented?
* [ ] Which participants appear most engaged?

---

## 🧠 Analysis Framework

For every major finding:

```text
📊 DATA
What happened?
      ↓
🔎 ANALYSIS
What pattern exists?
      ↓
🧠 INTERPRETATION
What might explain it?
      ↓
🎯 DECISION
What should be investigated or done next?
```

> ⚠️ Correlation does not automatically establish causation.

---

# 09 — 🏗️ Beginner Project

# BIH Community Data Analysis

### Scenario

You have joined the Beacon Innovation Hub data team.

Management provides several messy datasets and asks:

> **What does the available evidence reveal about community participation, project performance, and areas requiring intervention?**

---

## 📋 Project Requirements

### 1️⃣ Understand the Data

* [ ] Dataset descriptions
* [ ] Columns
* [ ] Data types
* [ ] Primary keys
* [ ] Relationships

### 2️⃣ Assess Data Quality

* [ ] Missingness
* [ ] Duplicates
* [ ] Invalid values
* [ ] Inconsistent categories
* [ ] Incorrect types

### 3️⃣ Transform

* [ ] Document important transformations
* [ ] Preserve raw data
* [ ] Validate cleaned data

### 4️⃣ Integrate

* [ ] Join tables
* [ ] Explain join types
* [ ] Validate joins

### 5️⃣ Analyse

* [ ] Filtering
* [ ] Grouping
* [ ] Aggregation
* [ ] Descriptive statistics

### 6️⃣ Visualize

* [ ] Select appropriate chart types
* [ ] Label charts clearly
* [ ] Explain what each chart contributes

### 7️⃣ Findings

Identify at least **five meaningful findings**.

### 8️⃣ Recommendations

Translate findings into actionable recommendations.

---

## 📁 Recommended Project Structure

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

> 🔒 **Never overwrite the original raw datasets.**

---

# 📈 Your Progress

### 🐍 Python

* [ ] Variables & data types
* [ ] Conditions
* [ ] Loops
* [ ] Lists
* [ ] Dictionaries
* [ ] Functions
* [ ] Exceptions

### 🔢 NumPy

* [ ] Arrays
* [ ] Indexing
* [ ] Filtering
* [ ] Aggregations
* [ ] Vectorized operations

### 🐼 Pandas

* [ ] DataFrames
* [ ] CSV files
* [ ] Data inspection
* [ ] Data types
* [ ] Missing values
* [ ] Duplicates
* [ ] Filtering
* [ ] Sorting
* [ ] GroupBy
* [ ] Aggregation
* [ ] Merge / Join

### 📊 Visualization

* [ ] Matplotlib
* [ ] Bar charts
* [ ] Scatter plots
* [ ] Histograms
* [ ] Interpretation

### 🏢 BIH Activities

* [ ] Participant Registration
* [ ] Project Evaluation Engine
* [ ] NumPy Project Scores
* [ ] Community Dataset
* [ ] Data Cleaning
* [ ] Multiple-Table Analysis
* [ ] Visualization
* [ ] Community EDA
* [ ] Beginner Data Project

---

# 🚀 What Comes Next?

```text
                  🐍 Python for Data
                         │
                         ▼
                 📊 Data Foundations
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
   📊 Data Analyst  🧠 Data Scientist  ⚙️ Data Engineer
```

The next shared stage should cover:

**SQL → Statistics → Excel → Data Quality → Visualization → Git/GitHub**

before choosing a specialization.

---

# 💡 Core Principle

> **Do not measure progress by how many hours of tutorials you watched.**

Measure it by whether you can receive unfamiliar data and:

**Understand it → Clean it → Validate it → Analyse it → Visualize it → Explain it → Recommend an action**

That is the beginning of professional data work.
