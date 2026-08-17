<!--
Beacon Innovation Hub — Data Scientist Learning Path
This TXT file contains GitHub Markdown source. Copy the contents into a .md file to render on GitHub.
-->

# Level 2 --- Statistics & Exploratory Data Analysis

> Learn to investigate data scientifically before attempting to build
> predictive models.

[← Back to Data Scientist Roadmap](README.md)

------------------------------------------------------------------------

## 1. Descriptive Statistics

-   [ ] Mean
-   [ ] Median
-   [ ] Mode
-   [ ] Variance
-   [ ] Standard deviation
-   [ ] Quartiles
-   [ ] Percentiles
-   [ ] Interquartile range
-   [ ] Skewness
-   [ ] Outliers

### Documentation

-   [SciPy
    Statistics](https://docs.scipy.org/doc/scipy/reference/stats.html)

### BIH Practice

Summarize attendance, project completion time and review scores. Compare
teams and explain which statistics are most informative for each
variable.

------------------------------------------------------------------------

## 2. Sampling & Statistical Inference

-   [ ] Population vs sample
-   [ ] Sampling methods
-   [ ] Sampling bias
-   [ ] Sampling distributions
-   [ ] Central Limit Theorem
-   [ ] Standard error
-   [ ] Confidence intervals
-   [ ] Statistical vs practical significance

------------------------------------------------------------------------

## 3. Hypothesis Testing

-   [ ] Null hypothesis
-   [ ] Alternative hypothesis
-   [ ] p-values
-   [ ] Type I error
-   [ ] Type II error
-   [ ] Statistical power
-   [ ] Effect size
-   [ ] t-tests
-   [ ] Chi-square tests
-   [ ] ANOVA concepts
-   [ ] Non-parametric alternatives
-   [ ] Multiple-testing awareness

### Video

[![Hypothesis
Testing](https://img.youtube.com/vi/1g3pCE_B12E/maxresdefault.jpg)](https://www.youtube.com/watch?v=1g3pCE_B12E)

[Watch: Hypothesis Testing
Explained](https://www.youtube.com/watch?v=1g3pCE_B12E)

------------------------------------------------------------------------

## 4. Experimental Design & A/B Testing

-   [ ] Treatment and control groups
-   [ ] Randomization
-   [ ] Experimental units
-   [ ] Confounding
-   [ ] Selection bias
-   [ ] A/B testing
-   [ ] Outcome measures
-   [ ] Power considerations
-   [ ] Causal claims vs associations

### BIH Practice

Question:

> Does additional technical mentoring improve assessment performance?

Design an investigation specifying:

-   Population
-   Treatment
-   Comparison
-   Outcome
-   Hypotheses
-   Potential confounders
-   Statistical method
-   Limitations

------------------------------------------------------------------------

## 5. Econometrics Foundations

**Why it matters:** Econometric thinking strengthens understanding of
observational data, confounding and relationships between variables.

### Learn

-   [ ] Simple and multiple regression
-   [ ] Coefficient interpretation
-   [ ] Omitted-variable bias
-   [ ] Confounding
-   [ ] Multicollinearity
-   [ ] Heteroskedasticity concepts
-   [ ] Dummy variables
-   [ ] Interaction terms
-   [ ] Causal interpretation limits
-   [ ] Panel/time concepts at an introductory level

> The purpose here is not to turn the pathway into an Economics degree.
> Focus on reasoning about observational data and model assumptions.

------------------------------------------------------------------------

## 6. Exploratory Data Analysis

### Video

[![EDA in
Pandas](https://img.youtube.com/vi/Liv6eeb1VfE/maxresdefault.jpg)](https://www.youtube.com/watch?v=Liv6eeb1VfE)

[Watch: Exploratory Data Analysis in
Pandas](https://www.youtube.com/watch?v=Liv6eeb1VfE)

### Documentation

-   [Pandas User
    Guide](https://pandas.pydata.org/docs/user_guide/index.html)

### Learn

-   [ ] Dataset dimensions
-   [ ] Data types
-   [ ] Missingness
-   [ ] Duplicate records
-   [ ] Invalid values
-   [ ] Univariate analysis
-   [ ] Bivariate analysis
-   [ ] Multivariate exploration
-   [ ] Distribution analysis
-   [ ] Group comparisons
-   [ ] Correlation analysis
-   [ ] Outlier investigation
-   [ ] Target imbalance
-   [ ] Potential leakage

### Workflow

``` text
Understand Question
      ↓
Inspect Data
      ↓
Assess Quality
      ↓
Explore Variables
      ↓
Explore Relationships
      ↓
Investigate Target
      ↓
Identify Risks
      ↓
Form Hypotheses
```

### BIH Lab

Perform EDA on a fictional BIH project-performance dataset.

Your notebook must include:

-   [ ] Data dictionary
-   [ ] Missingness analysis
-   [ ] Duplicate analysis
-   [ ] Distribution plots
-   [ ] Group comparisons
-   [ ] Correlation investigation
-   [ ] Target analysis
-   [ ] Leakage investigation
-   [ ] Five evidence-supported findings
-   [ ] Three limitations

------------------------------------------------------------------------

## 7. Statistical Communication

A Data Scientist should be able to distinguish:

``` text
Observed Pattern
≠
Statistical Association
≠
Causal Effect
```

Practise explaining:

-   Uncertainty
-   Effect sizes
-   Confidence intervals
-   Assumptions
-   Limitations
-   Alternative explanations

------------------------------------------------------------------------

## Level 2 Completion Standard

-   [ ] Perform defensible descriptive analysis.
-   [ ] Explain sampling and uncertainty.
-   [ ] Select basic statistical tests appropriately.
-   [ ] Design a simple experiment.
-   [ ] Recognize common observational-data problems.
-   [ ] Conduct a structured EDA.
-   [ ] Avoid unsupported causal claims.
-   [ ] Communicate findings and limitations clearly.

**Next:** [Level 3 --- Machine
Learning](Level%203%20-%20Machine%20Learning.md)
