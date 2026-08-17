<!--
Beacon Innovation Hub — Data Scientist Learning Path
This TXT file contains GitHub Markdown source. Copy the contents into a .md file to render on GitHub.
-->

# Level 3 --- Machine Learning

> Build, evaluate and interpret core supervised and unsupervised
> machine-learning models.

[← Back to Data Scientist Roadmap](README.md)

------------------------------------------------------------------------

## 1. Machine Learning Fundamentals

### Video

[![Machine Learning
Introduction](https://img.youtube.com/vi/Gv9_4yMHFhI/maxresdefault.jpg)](https://www.youtube.com/watch?v=Gv9_4yMHFhI)

[Watch: A Gentle Introduction to Machine
Learning](https://www.youtube.com/watch?v=Gv9_4yMHFhI)

### Interactive Course

-   [Google Machine Learning Crash
    Course](https://developers.google.com/machine-learning/crash-course)
-   [scikit-learn Getting
    Started](https://scikit-learn.org/stable/getting_started.html)

### Learn

-   [ ] Features
-   [ ] Targets
-   [ ] Parameters
-   [ ] Hyperparameters
-   [ ] Loss functions
-   [ ] Training and inference
-   [ ] Generalization
-   [ ] Overfitting
-   [ ] Underfitting
-   [ ] Bias-variance intuition
-   [ ] Supervised learning
-   [ ] Unsupervised learning

------------------------------------------------------------------------

## 2. Feature Engineering & Preprocessing

### Video

[![Feature
Engineering](https://img.youtube.com/vi/uu8um0JmYA8/maxresdefault.jpg)](https://www.youtube.com/watch?v=uu8um0JmYA8)

[Watch: Feature Engineering Full
Course](https://www.youtube.com/watch?v=uu8um0JmYA8)

### Documentation

-   [scikit-learn
    Preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)

### Learn

-   [ ] Missing-value imputation
-   [ ] Standardization
-   [ ] Normalization
-   [ ] One-hot encoding
-   [ ] Ordinal encoding
-   [ ] Date/time features
-   [ ] Interaction features
-   [ ] Binning
-   [ ] Feature selection
-   [ ] High-cardinality categories
-   [ ] Leakage prevention

### Rule

``` text
Training Data
     ↓
Learn Preprocessing
     ↓
Apply to Training Data
     +
Apply Same Transformation to Test Data
```

Never learn preprocessing parameters from the test set.

------------------------------------------------------------------------

## 3. Train / Validation / Test Strategy

-   [ ] Training set
-   [ ] Validation strategy
-   [ ] Test set
-   [ ] Random state
-   [ ] Stratification
-   [ ] Baselines
-   [ ] Leakage prevention

------------------------------------------------------------------------

## 4. Regression

### Video

[![Linear
Regression](https://img.youtube.com/vi/nk2CQITm_eo/maxresdefault.jpg)](https://www.youtube.com/watch?v=nk2CQITm_eo)

[Watch: Linear Regression, Clearly
Explained](https://www.youtube.com/watch?v=nk2CQITm_eo)

### Learn

-   [ ] Linear regression
-   [ ] Multiple regression
-   [ ] Coefficients
-   [ ] Intercepts
-   [ ] Residuals
-   [ ] Regression assumptions
-   [ ] Ridge
-   [ ] Lasso
-   [ ] Tree-based regression

### Metrics

-   [ ] MAE
-   [ ] MSE
-   [ ] RMSE
-   [ ] R²

### BIH Lab

Estimate final project review scores. Compare a baseline and at least
two models. Investigate residuals and explain whether improvement is
practically useful.

------------------------------------------------------------------------

## 5. Classification

### Video

[![Logistic
Regression](https://img.youtube.com/vi/yIYKR4sgzI8/maxresdefault.jpg)](https://www.youtube.com/watch?v=yIYKR4sgzI8)

[Watch: Logistic Regression ---
StatQuest](https://www.youtube.com/watch?v=yIYKR4sgzI8)

### Learn

-   [ ] Binary classification
-   [ ] Multiclass classification
-   [ ] Logistic regression
-   [ ] Decision trees
-   [ ] Random forests
-   [ ] k-nearest neighbours concepts
-   [ ] Support-vector-machine concepts
-   [ ] Probability estimates
-   [ ] Decision thresholds
-   [ ] Class imbalance

### Metrics

-   [ ] Confusion matrix
-   [ ] Accuracy
-   [ ] Precision
-   [ ] Recall
-   [ ] F1
-   [ ] Specificity
-   [ ] ROC-AUC
-   [ ] Precision-recall curves

### BIH Lab

Build a project-risk classifier. Define what "at risk" means and explain
the costs of false positives and false negatives before selecting the
main evaluation metric.

------------------------------------------------------------------------

## 6. Model Evaluation

### Video

[![Cross
Validation](https://img.youtube.com/vi/fSytzGwwBVw/maxresdefault.jpg)](https://www.youtube.com/watch?v=fSytzGwwBVw)

[Watch: Cross Validation ---
StatQuest](https://www.youtube.com/watch?v=fSytzGwwBVw)

### Documentation

-   [scikit-learn Model Selection &
    Evaluation](https://scikit-learn.org/stable/model_selection.html)

### Learn

-   [ ] Baselines
-   [ ] Holdout evaluation
-   [ ] Cross-validation
-   [ ] Stratified cross-validation
-   [ ] Metric selection
-   [ ] Data leakage
-   [ ] Error analysis
-   [ ] Learning curves
-   [ ] Calibration concepts
-   [ ] Subgroup performance

### Model Evaluation Checklist

``` text
Baseline?
   ↓
Protected Test Data?
   ↓
Leakage-free Preprocessing?
   ↓
Appropriate Metric?
   ↓
Cross-validation?
   ↓
Error Analysis?
   ↓
Subgroup Checks?
   ↓
Practically Useful?
```

------------------------------------------------------------------------

## 7. Unsupervised Learning

### Video

[![K-Means](https://img.youtube.com/vi/4b5d3muPQmA/maxresdefault.jpg)](https://www.youtube.com/watch?v=4b5d3muPQmA)

[Watch: K-means Clustering ---
StatQuest](https://www.youtube.com/watch?v=4b5d3muPQmA)

Additional:

-   [PCA Step-by-Step ---
    StatQuest](https://www.youtube.com/watch?v=FgakZw6K1QQ)
-   [scikit-learn
    Clustering](https://scikit-learn.org/stable/modules/clustering.html)

### Learn

-   [ ] K-means
-   [ ] Hierarchical clustering concepts
-   [ ] DBSCAN concepts
-   [ ] Distance metrics
-   [ ] Feature scaling
-   [ ] Silhouette score
-   [ ] PCA
-   [ ] Dimensionality reduction
-   [ ] Cluster interpretation

### BIH Lab

Explore participant engagement patterns using attendance, training
hours, task completion, projects completed and review performance. Do
not assign unsupported labels such as "good" or "bad" participants.

------------------------------------------------------------------------

## Level 3 Completion Standard

To progress to the next level attempt and pass [CHALLENGE 3](Challenges/CHALLENGE3), submit the project under Beacon Innovation Hub's Data Science Repository.
A learner should independently be able to:

-   [ ] Prepare modelling data without leakage.
-   [ ] Establish a baseline.
-   [ ] Build regression and classification models.
-   [ ] Choose appropriate evaluation metrics.
-   [ ] Use cross-validation.
-   [ ] Investigate model errors.
-   [ ] Perform basic clustering and PCA.
-   [ ] Explain model limitations.

**Next:** [Level 4 --- Advanced Machine
Learning](Level%204%20-%20Advanced%20Machine%20Learning.md)
