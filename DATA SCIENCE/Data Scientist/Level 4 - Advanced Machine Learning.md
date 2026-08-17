<!--
Beacon Innovation Hub — Data Scientist Learning Path
This TXT file contains GitHub Markdown source. Copy the contents into a .md file to render on GitHub.
-->

# Level 4 --- Advanced Machine Learning

> Move from running models to building reliable, reproducible and
> carefully validated modelling systems.

[← Back to Data Scientist Roadmap](README.md)

------------------------------------------------------------------------

## 1. Reproducible Pipelines

### Video

[![Scikit-learn
Pipeline](https://img.youtube.com/vi/T9ETsSD1I0w/maxresdefault.jpg)](https://www.youtube.com/watch?v=T9ETsSD1I0w)

[Watch: Building a Machine Learning Pipeline with
Scikit-Learn](https://www.youtube.com/watch?v=T9ETsSD1I0w)

### Documentation

-   [scikit-learn Pipelines and Composite
    Estimators](https://scikit-learn.org/stable/modules/compose.html)

### Learn

-   [ ] `Pipeline`
-   [ ] `ColumnTransformer`
-   [ ] Numeric preprocessing
-   [ ] Categorical preprocessing
-   [ ] Leakage-safe transformations
-   [ ] Reproducibility
-   [ ] Random seeds

------------------------------------------------------------------------

## 2. Advanced Cross-Validation

-   [ ] K-fold cross-validation
-   [ ] Stratified K-fold
-   [ ] Grouped validation concepts
-   [ ] Time-aware validation
-   [ ] Nested-validation concepts
-   [ ] Choosing a validation strategy based on the problem

------------------------------------------------------------------------

## 3. Hyperparameter Optimization

Additional video:

[Hyperparameter Tuning](https://www.youtube.com/watch?v=HdlDYng8g9s)

### Learn

-   [ ] Hyperparameters vs parameters
-   [ ] Grid search
-   [ ] Randomized search
-   [ ] Search spaces
-   [ ] Validation metrics
-   [ ] Avoiding test-set tuning
-   [ ] Computational trade-offs

------------------------------------------------------------------------

## 4. Regularization

-   [ ] L1 regularization
-   [ ] L2 regularization
-   [ ] Ridge
-   [ ] Lasso
-   [ ] Regularization strength
-   [ ] Bias-variance trade-off

------------------------------------------------------------------------

## 5. Ensemble Learning

-   [ ] Bagging
-   [ ] Random forests
-   [ ] Boosting
-   [ ] Gradient boosting
-   [ ] Voting
-   [ ] Stacking concepts
-   [ ] When ensembles help

------------------------------------------------------------------------

## 6. Gradient Boosting

-   [ ] Gradient-boosted trees
-   [ ] Learning rate
-   [ ] Tree depth
-   [ ] Number of estimators
-   [ ] Early stopping concepts
-   [ ] XGBoost / LightGBM / similar implementations

> Learn the underlying boosting concept before becoming dependent on one
> library.

------------------------------------------------------------------------

## 7. Imbalanced Data

-   [ ] Class distributions
-   [ ] Appropriate metrics
-   [ ] Class weighting
-   [ ] Threshold adjustment
-   [ ] Resampling concepts
-   [ ] Precision-recall analysis
-   [ ] Risks of synthetic sampling

------------------------------------------------------------------------

## 8. Feature Selection

-   [ ] Filter methods
-   [ ] Wrapper concepts
-   [ ] Embedded methods
-   [ ] Regularization-based selection
-   [ ] Permutation importance
-   [ ] Redundant variables
-   [ ] High-dimensional data

------------------------------------------------------------------------

## 9. Model Interpretation

-   [ ] Global vs local interpretation
-   [ ] Coefficients
-   [ ] Feature importance
-   [ ] Permutation importance
-   [ ] Partial-dependence concepts
-   [ ] SHAP concepts
-   [ ] Correlation vs causation
-   [ ] Interpretation limitations

------------------------------------------------------------------------

## 10. Time Series & Forecasting

### Video

[![Time Series
Forecasting](https://img.youtube.com/vi/fxx_E0ojKrc/maxresdefault.jpg)](https://www.youtube.com/watch?v=fxx_E0ojKrc)

[Watch: Time Series Forecasting in
Python](https://www.youtube.com/watch?v=fxx_E0ojKrc)

### Learn

-   [ ] Time-indexed data
-   [ ] Trend
-   [ ] Seasonality
-   [ ] Lag features
-   [ ] Rolling statistics
-   [ ] Forecast horizon
-   [ ] Naive baselines
-   [ ] Temporal splits
-   [ ] MAE
-   [ ] RMSE
-   [ ] MAPE limitations
-   [ ] Time-series cross-validation concepts

### BIH Lab

Forecast monthly BIH activity:

1.  Plot the series.
2.  Identify trend and seasonality.
3.  Establish a naive baseline.
4.  Create appropriate lag features.
5.  Use a temporal split.
6.  Compare a model with the baseline.
7.  Explain uncertainty and limitations.

------------------------------------------------------------------------

## BIH Advanced Modelling Lab

Build one end-to-end pipeline for a BIH project-risk problem.

Requirements:

-   [ ] `ColumnTransformer`
-   [ ] Leakage-safe preprocessing
-   [ ] At least two candidate models
-   [ ] Consistent cross-validation
-   [ ] Hyperparameter search
-   [ ] Appropriate metric
-   [ ] Error analysis
-   [ ] Model interpretation
-   [ ] Final untouched test evaluation
-   [ ] Written limitations

------------------------------------------------------------------------

## Level 4 Completion Standard

-   [ ] Build reproducible scikit-learn pipelines.
-   [ ] Select validation strategies appropriately.
-   [ ] Tune models without contaminating test data.
-   [ ] Understand regularization and ensembles.
-   [ ] Handle imbalanced targets responsibly.
-   [ ] Interpret model behaviour carefully.
-   [ ] Build basic forecasting workflows.
-   [ ] Defend model selection with evidence.

**Next:** [Level 5 --- Deep Learning &
AI](Level%205%20-%20Deep%20Learning%20and%20AI.md)
