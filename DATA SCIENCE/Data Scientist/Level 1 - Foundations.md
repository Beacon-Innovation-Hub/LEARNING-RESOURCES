<!--
Beacon Innovation Hub — Data Scientist Learning Path
This TXT file contains GitHub Markdown source. Copy the contents into a .md file to render on GitHub.
-->

# Level 1 --- Data Science Foundations

> Build the programming, mathematical and problem-framing foundations
> required before serious modelling begins.

**Prerequisite:** [Python For Data.md](Python%20For%20Data.md)

[← Back to Data Scientist Roadmap](README.md)

------------------------------------------------------------------------

## 1. Data Science & Problem Framing

**Why it matters:** A model has little value if it solves the wrong
problem.

### Learn

-   [ ] Data Scientist vs Data Analyst vs Data Engineer
-   [ ] Descriptive, diagnostic, predictive and experimental questions
-   [ ] Problem statements
-   [ ] Population and unit of analysis
-   [ ] Features and targets
-   [ ] Prediction time
-   [ ] Constraints
-   [ ] Baselines
-   [ ] Success metrics
-   [ ] When machine learning is unnecessary

### Resources

-   [Google --- Introduction to Machine
    Learning](https://developers.google.com/machine-learning/intro-to-ml)
-   [Google --- Problem
    Framing](https://developers.google.com/machine-learning/problem-framing)

### BIH Practice

BIH wants to improve project completion. Classify each question as
descriptive, diagnostic, predictive, experimental, or unsuitable for ML:

1.  Which project categories have the lowest completion rates?
2.  Which factors are associated with delayed projects?
3.  Can delay risk be estimated before a project deadline?
4.  Does additional mentoring improve completion?
5.  Which team had the highest average review score?

For one predictive problem, define the target, prediction time, possible
features, baseline, metric, risks and limitations.

------------------------------------------------------------------------

## 2. SQL for Data Science

**Why it matters:** Data Scientists often need to obtain, combine and
validate data before modelling.

### Learn

-   [ ] `SELECT`, `WHERE`, `ORDER BY`
-   [ ] `GROUP BY`
-   [ ] Aggregations
-   [ ] `CASE WHEN`
-   [ ] `JOIN`
-   [ ] Subqueries
-   [ ] CTEs
-   [ ] Window functions
-   [ ] Null handling
-   [ ] Date operations
-   [ ] Query validation

### Video

[![SQL
Tutorial](https://img.youtube.com/vi/7mz73uXD9DA/maxresdefault.jpg)](https://youtu.be/7mz73uXD9DA)

[Watch SQL Tutorial](https://youtu.be/7mz73uXD9DA)

### Documentation

-   [PostgreSQL Documentation](https://www.postgresql.org/docs/)

### BIH Practice

Using fictional `participants`, `projects`, `attendance`, and `reviews`
tables:

-   Calculate project counts by team.
-   Calculate average review score by project category.
-   Join participant and attendance data.
-   Identify participants below an agreed attendance threshold.
-   Validate that joins have not duplicated records.

------------------------------------------------------------------------

## 3. Data Structures & Algorithms

**Why it matters:** Data Scientists do not need competitive-programming
mastery, but they should understand how common structures and operations
affect correctness and efficiency.

### Learn

-   [ ] Lists and arrays
-   [ ] Dictionaries / hash maps
-   [ ] Sets
-   [ ] Tuples
-   [ ] Stacks and queues
-   [ ] Searching
-   [ ] Sorting
-   [ ] Big-O intuition
-   [ ] Time complexity
-   [ ] Space complexity
-   [ ] Vectorized operations

### Practice

Compare a Python loop with a vectorized NumPy/Pandas operation on a
large practice dataset. Explain why performance differs.

------------------------------------------------------------------------

## 4. Mathematics for Data Science

### Algebra

-   [ ] Functions
-   [ ] Exponents
-   [ ] Logarithms
-   [ ] Equations
-   [ ] Summation notation

### Linear Algebra

-   [ ] Scalars
-   [ ] Vectors
-   [ ] Matrices
-   [ ] Matrix dimensions
-   [ ] Dot products
-   [ ] Matrix multiplication
-   [ ] Transpose
-   [ ] Linear transformations
-   [ ] Eigenvalue/eigenvector intuition

### Calculus

-   [ ] Derivatives
-   [ ] Partial derivatives
-   [ ] Gradients
-   [ ] Chain-rule intuition
-   [ ] Optimization
-   [ ] Gradient descent

### Video

[![Linear
Algebra](https://img.youtube.com/vi/QCPJ0VdpM00/maxresdefault.jpg)](https://www.youtube.com/watch?v=QCPJ0VdpM00)

[Watch: Linear Algebra for Machine
Learning](https://www.youtube.com/watch?v=QCPJ0VdpM00)

Additional visual explanation:

[3Blue1Brown --- Eigenvectors and
Eigenvalues](https://www.youtube.com/watch?v=PFDu9oVAE-g)

### BIH Practice

Explain:

1.  How a vector can represent one project.
2.  How a matrix can represent a dataset.
3.  What a loss function measures.
4.  What optimization attempts to achieve.
5.  Why gradient descent is useful.

------------------------------------------------------------------------

## 5. Probability Foundations

-   [ ] Sample spaces
-   [ ] Events
-   [ ] Conditional probability
-   [ ] Independence
-   [ ] Bayes' theorem
-   [ ] Random variables
-   [ ] Expected value
-   [ ] Variance
-   [ ] Bernoulli distribution
-   [ ] Binomial distribution
-   [ ] Normal distribution
-   [ ] Poisson distribution

### Video

[![Probability Distributions](https://img.youtube.com/vi/oI3hZJqXJuc/hqdefault.jpg)](https://www.youtube.com/watch?v=oI3hZJqXJuc)

**[Watch: Probability Distributions](https://www.youtube.com/watch?v=oI3hZJqXJuc)**


------------------------------------------------------------------------

## Level 1 Completion Standard

To qualify for level 2 for data science complete [Challenge](DATA%20SCIENCE/Data%20Scientist/CHALLENGE.md)

Before moving to Level 2, the learner should be able to:

-   [ ] Frame a Data Science problem clearly.
-   [ ] Query relational data using SQL.
-   [ ] Explain common data structures and basic complexity.
-   [ ] Work with vectors and matrices conceptually.
-   [ ] Explain gradients and optimization at a basic level.
-   [ ] Reason about probability and common distributions.
-   [ ] Complete the BIH exercises independently.

**Next:** [Level 2 --- Statistics &
EDA](Level%202%20-%20Statistics%20and%20EDA.md)
