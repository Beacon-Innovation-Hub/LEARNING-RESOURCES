# Level 4 Gateway Challenge

## BIH Data Consistency & Reliable Machine Learning Challenge

**Pathway:** Data Scientist  
**Level:** 4 — Advanced Machine Learning  
**Challenge Type:** Level Advancement  
**Next Level:** Deep Learning & AI

---

# Scenario

Mr S.G. Mbhamali is a **Data Engineer at Beacon Innovation Hub (BIH)**.

He is responsible for preparing and maintaining data used by BIH's analytical and Machine Learning systems.

Recently, Mr Mbhamali has identified a serious problem:

> **The data arriving from different BIH systems is not always consistent.**

Different systems and data pipelines sometimes represent the same information differently.

Examples include inconsistent categories, missing values, duplicate records, changing date formats, unexpected numerical ranges, different units, new categories, changing data types, repeated IDs, missing or unexpected columns, and changes in feature distributions.

A model may work correctly during development but fail or generate unreliable predictions when new data enters the system.

Mr Mbhamali has therefore asked the BIH Data Science team:

> **Can we design a Machine Learning workflow that remains reliable when incoming data is imperfect or changes over time?**

---

# Your Role

You are working as an **Advanced Data Scientist at BIH**.

Your task is to investigate how inconsistent data affects a Machine Learning system and design a more reliable modelling workflow.

You must apply:

- Reproducible pipelines
- Advanced cross-validation
- Hyperparameter optimization
- Regularization
- Ensemble learning
- Gradient boosting
- Imbalanced data handling
- Feature selection
- Model interpretation
- Time-aware analysis

---

# The Main Challenge

You will receive historical BIH data such as:

```text
participants.csv
projects.csv
training.csv
attendance.csv
tasks.csv
reviews.csv
```

You will also receive:

```text
incoming_data.csv
```

Determine:

> **Can the Machine Learning system continue producing reliable predictions when the characteristics of incoming data change?**

---

# Part 1 — Define Data Consistency

Distinguish between:

```text
Data Quality
     vs
Data Consistency
     vs
Data Drift
     vs
Concept Drift
```

Provide BIH-based examples of each.

---

# Part 2 — Establish the Expected Data Contract

Create a **Data Contract** based on the supplied dataset.

| Feature | Expected Type | Required? | Allowed Values / Range | Missing Allowed? |
|---|---|---:|---|---:|
| participant_id | String | Yes | Unique valid ID | No |
| technical_field | Category | Yes | Approved BIH fields | No |
| attendance_rate | Float | Yes | 0–100 | Yes |
| training_hours | Float | Yes | ≥ 0 | Yes |
| project_count | Integer | Yes | ≥ 0 | No |

---

# Part 3 — Build a Data Validation System

Your system should detect:

- [ ] Missing required columns
- [ ] Unexpected columns
- [ ] Incorrect data types
- [ ] Missing values
- [ ] Duplicate records
- [ ] Duplicate identifiers
- [ ] Invalid categories
- [ ] Impossible numerical values
- [ ] Unexpected date formats
- [ ] Out-of-range values

Produce a validation report and document every action taken.

---

# Part 4 — Investigate Category Inconsistency

Investigate variations such as:

```text
Cybersecurity
cybersecurity
Cyber Security
CYBERSECURITY
cyber-security
```

Develop a reproducible standardization method and explain when automatic standardization would be dangerous.

---

# Part 5 — Establish a Baseline Model

Select a BIH prediction problem such as project completion risk, participant assessment outcome, project review performance, or project delay risk.

Define:

- [ ] Business problem
- [ ] Target
- [ ] Unit of analysis
- [ ] Prediction time
- [ ] Features
- [ ] Primary metric

Establish a simple baseline.

---

# Part 6 — Build a Reproducible Pipeline

Build:

```text
Raw Data
    ↓
Validation
    ↓
Cleaning
    ↓
Feature Processing
    ↓
Feature Selection
    ↓
Model
    ↓
Prediction
```

Use appropriate tools such as `Pipeline`, `ColumnTransformer`, `SimpleImputer`, `OneHotEncoder`, and `StandardScaler` where justified.

---

# Part 7 — Advanced Cross-Validation

Consider K-Fold, Stratified K-Fold, Grouped Cross-Validation and time-aware validation.

Compare at least **two validation strategies** and investigate leakage from repeated participants or projects.

---

# Part 8 — Hyperparameter Optimization

Select at least two candidate models.

Use `GridSearchCV` and/or `RandomizedSearchCV`.

Document:

- Search space
- Validation method
- Evaluation metric
- Best parameters
- Cross-validation performance
- Computational cost

Keep the final test set untouched.

---

# Part 9 — Regularization Investigation

Where appropriate, compare:

```text
Unregularized Model
        ↓
Ridge / L2
        ↓
Lasso / L1
```

Investigate performance, coefficient size, feature reduction, overfitting and generalization.

---

# Part 10 — Ensemble Learning

Compare a simple model with ensemble approaches such as:

```text
Decision Tree
      vs
Random Forest
      vs
Gradient Boosting
```

Use the same validation strategy and explain whether added complexity produces meaningful improvement.

---

# Part 11 — Imbalanced Data

If the outcome is imbalanced, investigate Precision, Recall, F1, Precision-Recall behaviour and ROC-AUC where appropriate.

Where justified, investigate class weighting, threshold adjustment and resampling.

Do not modify the test distribution merely to improve reported performance.

---

# Part 12 — Feature Selection

Compare:

```text
All Features
      vs
Selected Features
```

Consider permutation importance, L1-based selection, tree-based importance, Recursive Feature Elimination and suitable statistical methods.

Compare performance, training time, complexity, stability and interpretability.

---

# Part 13 — Model Interpretation

Use suitable techniques such as:

- Model coefficients
- Permutation importance
- Tree feature importance
- Partial dependence
- SHAP where appropriate

Determine which variables the model relies on most and whether those variables will remain consistently available.

---

# Part 14 — Introduce Controlled Data Problems

Create separate stress-test datasets containing problems such as:

```text
10% additional missing values
Unknown categories
Category capitalization changes
Extreme numerical values
Missing optional features
Changed feature distributions
```

Do not corrupt the original dataset.

---

# Part 15 — Stress Test the Pipeline

| Scenario | Validation Result | Pipeline Runs? | Model Performance | Main Problem |
|---|---|---:|---:|---|
| Original data | | | | |
| Missing values | | | | |
| New categories | | | | |
| Extreme values | | | | |
| Distribution change | | | | |

Determine which data problems have the greatest effect on model reliability.

---

# Part 16 — Distribution Shift Investigation

Compare historical training data with incoming data using:

- Means
- Medians
- Standard deviations
- Category proportions
- Missingness rates
- Distributions
- Prediction distributions

Identify features showing meaningful changes.

---

# Part 17 — Time-Aware Investigation

If timestamps are available, investigate changing category proportions, missingness, target rates, numerical distributions and model performance over time.

Explain why randomly mixing historical and recent records may hide these changes.

---

# Part 18 — Model Stability

Evaluate model performance across different periods or data segments.

| Period | Primary Metric |
|---|---:|
| Period 1 | |
| Period 2 | |
| Period 3 | |
| Period 4 | |

Determine whether performance is stable and investigate significant changes.

---

# Part 19 — Failure Handling

Design rules for:

```text
ACCEPT
WARN
REJECT
```

Example:

```text
Incoming Dataset
       ↓
Validation
       ↓
 ┌─────┼─────┐
 ↓     ↓     ↓
PASS  WARN   FAIL
 ↓     ↓      ↓
Predict Review Reject
```

Define what should trigger each outcome.

---

# Part 20 — Recommendation to Mr S.G. Mbhamali

Prepare a technical report addressed to:

## Mr S.G. Mbhamali
**Data Engineer — Beacon Innovation Hub**

Explain:

1. Which data consistency problems were discovered?
2. Which problems can be automatically corrected?
3. Which problems should cause the pipeline to reject data?
4. Which features are most sensitive to inconsistency?
5. How does inconsistent data affect model performance?
6. Which validation rules should be implemented upstream?
7. Which information should the Data Engineering team monitor?
8. How should schema changes be communicated?
9. When should the Data Science team be notified?
10. Is the model reliable enough for continued use?

---

# Final Architecture

```text
BIH Data Sources
       ↓
Data Engineering
Mr S.G. Mbhamali
       ↓
Schema Validation
       ↓
Quality Checks
       ↓
Consistency Checks
       ↓
Validated Dataset
       ↓
ML Preprocessing Pipeline
       ↓
Feature Selection
       ↓
Model
       ↓
Prediction
       ↓
Performance Monitoring
       ↓
Data / Model Issues
       ↓
Engineering + Data Science Review
```

---

# Required Repository

```text
BIH-data-consistency-ml/
│
├── README.md
├── data/
│   ├── raw/
│   ├── incoming/
│   ├── processed/
│   └── stress-tests/
├── notebooks/
│   ├── 01-data-audit.ipynb
│   ├── 02-validation.ipynb
│   ├── 03-modelling.ipynb
│   ├── 04-model-optimization.ipynb
│   ├── 05-feature-selection.ipynb
│   ├── 06-model-interpretation.ipynb
│   └── 07-robustness-testing.ipynb
├── src/
│   ├── validation.py
│   ├── preprocessing.py
│   ├── features.py
│   ├── train.py
│   └── evaluate.py
├── reports/
│   ├── data-contract.md
│   ├── validation-report.md
│   └── technical-recommendation.md
├── models/
├── tests/
│   ├── test_validation.py
│   └── test_preprocessing.py
└── requirements.txt
```

---

# Assessment

| Area | Weight |
|---|---:|
| Data Consistency Investigation | 10% |
| Data Contract & Validation | 15% |
| Reproducible ML Pipeline | 15% |
| Cross-Validation Strategy | 10% |
| Hyperparameter Optimization | 10% |
| Ensemble / Advanced Modelling | 10% |
| Feature Selection & Interpretation | 10% |
| Robustness & Distribution-Shift Testing | 10% |
| Technical Recommendation | 10% |
| **Total** | **100%** |

---

# Critical Competencies

- [ ] Data validation
- [ ] Leakage-safe preprocessing
- [ ] Reproducible pipelines
- [ ] Appropriate cross-validation
- [ ] Hyperparameter optimization
- [ ] Model comparison
- [ ] Feature selection
- [ ] Model interpretation
- [ ] Robustness testing
- [ ] Understanding of distribution shift

A high overall mark should not compensate for failure in these critical areas.

---

# Important Boundary

The learner is **not expected to redesign Mr Mbhamali's entire Data Engineering infrastructure**.

```text
DATA ENGINEERING
Reliable Data
       ↓
DATA SCIENCE
Reliable Model
```

The Data Scientist should define what the model requires from the data.

The Data Engineer should understand what must be delivered consistently.

Reliable Machine Learning requires both.

---

# Gateway Decision

Successful completion demonstrates readiness for:

# Level 5 — Deep Learning & AI

The learner should be able to move through:

```text
Data Contract
      ↓
Validation
      ↓
Reliable Preprocessing
      ↓
Feature Engineering
      ↓
Cross-Validation
      ↓
Model Optimization
      ↓
Interpretation
      ↓
Robustness Testing
      ↓
Reliable Prediction
```

---

# SUBMISSION

Submit the given task on your GitHub's repository for Beacon Innovation Hub's Data Scientist Programme Repository. The deadline for the task will be set upon receiving the challenge.


# Final Transition Question

Mr S.G. Mbhamali's data pipeline has now been made significantly more consistent.

BIH now has access to larger and more complex datasets, including images and unstructured text.

The Data Science team asks:

> **Can more advanced learning architectures extract useful patterns from data that classical Machine Learning methods struggle to represent?**

Do not solve this problem yet.

This becomes the starting point for:

## Level 5 — Deep Learning & AI
