# Level 1 Gateway Challenge

## BIH Technical Project Data Investigation

**Pathway:** Data Scientist  
**Level:** 1 — Foundations  
**Challenge Type:** Level Advancement  
**Next Level:** Statistics & Exploratory Data Analysis

---

## Challenge Brief

Beacon Innovation Hub manages participants working across technical
projects. BIH wants to better understand project participation,
attendance, training activity and early project performance.

You have been assigned as a developing Data Scientist to investigate
the available data.

Your task is to transform the supplied raw data into reliable,
evidence-supported findings that BIH could use to determine what
questions should be investigated further.

> This is a foundation challenge. Machine Learning is not required
> and should not be used.

---

## The Challenge

### 1. Frame the Problem

Before analysing the data:

- [ ] Define the problem being investigated
- [ ] Identify the population
- [ ] Define the unit of analysis
- [ ] Identify important variables
- [ ] Identify possible limitations
- [ ] Write at least 3 questions that can be answered using the data

---

### 2. Work With the Data

Inspect and prepare the supplied datasets.

You must:

- [ ] Identify data types
- [ ] Identify missing values
- [ ] Identify duplicate records
- [ ] Check invalid values
- [ ] Document any transformations

Do not silently modify the data.

---

### 3. SQL Challenge

Use SQL to investigate the data.

Your solution must demonstrate:

- [ ] SELECT
- [ ] WHERE
- [ ] GROUP BY
- [ ] Aggregation
- [ ] CASE WHEN
- [ ] JOIN
- [ ] CTE
- [ ] At least one window function

You must also demonstrate that your joins did not incorrectly
duplicate records.

---

### 4. Python Challenge

Use Python to continue the investigation.

Demonstrate appropriate use of:

- [ ] Pandas
- [ ] NumPy
- [ ] Lists
- [ ] Dictionaries
- [ ] Sets where appropriate
- [ ] Vectorized operations

Compare at least one loop-based calculation with a vectorized
alternative.

Explain which approach is more suitable and why.

---

### 5. Mathematics Challenge

Select suitable numerical project variables and represent them
mathematically.

Demonstrate at least one:

- Vector operation
- Dot product
- Matrix operation

Do not only show the calculation.

Explain what the operation represents in the context of the BIH data.

---

### 6. Probability Challenge

Define at least three events from the dataset.

For example:

P(Project Completed)

P(High Attendance)

P(Project Completed | High Attendance)

Calculate:

- [ ] Simple probabilities
- [ ] Conditional probabilities

Interpret each result using the BIH scenario.

> Do not interpret association as causation.

---

## Final Investigation

Use everything you have learned to answer:

### What does the available evidence tell BIH about its projects?

Present:

- [ ] At least 5 evidence-supported findings
- [ ] Important data-quality problems
- [ ] Important limitations
- [ ] Questions that cannot yet be answered
- [ ] At least 3 questions BIH should investigate next

---

# Deliverables

Submit one GitHub repository:

```text
BIH-level-1-gateway/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── sql/
│   ├── schema.sql
│   └── analysis.sql
│
├── notebooks/
│   └── investigation.ipynb
│
└── report/
    └── findings.md
