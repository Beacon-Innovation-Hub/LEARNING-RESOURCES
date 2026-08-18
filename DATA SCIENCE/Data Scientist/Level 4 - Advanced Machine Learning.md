# Level 4 — Advanced Machine Learning

> Move from running models to building reliable, reproducible and carefully validated modelling systems.

[← Back to Data Scientist Roadmap](README.md)

---

# 1. Reproducible Pipelines

> Pipelines help keep preprocessing and modelling steps together, reducing leakage and making experiments easier to reproduce.

## Video Resource

### Building a Machine Learning Pipeline with Scikit-Learn

[![Scikit-learn Pipeline](https://i.ytimg.com/vi/T9ETsSD1I0w/hqdefault.jpg)](https://www.youtube.com/watch?v=T9ETsSD1I0w)

**[Watch: Building a Machine Learning Pipeline with Scikit-Learn](https://www.youtube.com/watch?v=T9ETsSD1I0w)**

## Documentation

- [scikit-learn — Pipelines and Composite Estimators](https://scikit-learn.org/stable/modules/compose.html)
- [scikit-learn — Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)
- [scikit-learn — ColumnTransformer](https://scikit-learn.org/stable/modules/generated/sklearn.compose.ColumnTransformer.html)

## Learn

- [ ] `Pipeline`
- [ ] `ColumnTransformer`
- [ ] Numerical preprocessing
- [ ] Categorical preprocessing
- [ ] Leakage-safe transformations
- [ ] Reproducibility
- [ ] Random seeds

## Practice

Rebuild one Level 3 e-commerce model using a complete scikit-learn pipeline.

---

# 2. Advanced Cross-Validation

> Cross-validation should match the structure of the data and prediction problem. Random K-Fold is not always appropriate.

## Video Resource

### Cross-Validation — StatQuest

[![Cross Validation](https://i.ytimg.com/vi/fSytzGwwBVw/hqdefault.jpg)](https://www.youtube.com/watch?v=fSytzGwwBVw)

**[Watch: Cross Validation — StatQuest](https://www.youtube.com/watch?v=fSytzGwwBVw)**

## Official Documentation

- [scikit-learn — Cross-Validation](https://scikit-learn.org/stable/modules/cross_validation.html)
- [scikit-learn — KFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html)
- [scikit-learn — GroupKFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GroupKFold.html)
- [scikit-learn — TimeSeriesSplit](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html)

## Learn

- [ ] K-Fold Cross-Validation
- [ ] Stratified K-Fold
- [ ] Repeated K-Fold
- [ ] Repeated Stratified K-Fold
- [ ] Grouped Cross-Validation
- [ ] Time-aware validation
- [ ] Choosing the number of folds
- [ ] Reproducible splitting
- [ ] Multiple evaluation metrics
- [ ] Nested Cross-Validation concepts

## Important Question

Before selecting a validation method, ask:

> Are observations actually independent?

For example, if an e-commerce dataset contains multiple purchases from the same customer, randomly placing records from the same customer into both training and validation folds may produce misleading results.

## Practice

Compare K-Fold, Stratified K-Fold and Repeated Stratified K-Fold on the Level 3 e-commerce classification problem.

Explain why their results differ.

---

# 3. Hyperparameter Optimization

> Hyperparameters control how a model learns. They must be selected using validation data rather than the final test set.

## Video Resource

### Hyperparameter Tuning

[![Hyperparameter Tuning](https://i.ytimg.com/vi/HdlDYng8g9s/hqdefault.jpg)](https://www.youtube.com/watch?v=HdlDYng8g9s)

**[Watch: Hyperparameter Tuning](https://www.youtube.com/watch?v=HdlDYng8g9s)**

## Official Documentation

- [scikit-learn — Tuning Hyperparameters](https://scikit-learn.org/stable/modules/grid_search.html)
- [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- [RandomizedSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html)

## Learn

- [ ] Parameters vs hyperparameters
- [ ] Search spaces
- [ ] Grid Search
- [ ] Randomized Search
- [ ] Cross-validated tuning
- [ ] Scoring functions
- [ ] Computational cost
- [ ] Overfitting during model selection
- [ ] Keeping the test set untouched

## Workflow

```text
Training Data
      ↓
Cross-Validation
      ↓
Hyperparameter Search
      ↓
Best Configuration
      ↓
Final Model
      ↓
Untouched Test Set
```

## Practice

Take one model from the Level 3 e-commerce challenge.

Compare:

1. Default model
2. GridSearchCV
3. RandomizedSearchCV

Report the best parameters, cross-validation score, search time and final performance.

Explain whether the additional tuning was worth the computational cost.

---

# 4. Regularization

> Regularization reduces model complexity by penalizing large coefficients and can help control overfitting.

## Video Resources

### Ridge Regression — StatQuest

[![Ridge Regression](https://i.ytimg.com/vi/Q81RR3yKn30/hqdefault.jpg)](https://www.youtube.com/watch?v=Q81RR3yKn30)

**[Watch: Ridge Regression — StatQuest](https://www.youtube.com/watch?v=Q81RR3yKn30)**

### Lasso Regression — StatQuest

[![Lasso Regression](https://i.ytimg.com/vi/NGf0voTMlcs/hqdefault.jpg)](https://www.youtube.com/watch?v=NGf0voTMlcs)

**[Watch: Lasso Regression — StatQuest](https://www.youtube.com/watch?v=NGf0voTMlcs)**

## Documentation

- [scikit-learn — Linear Models](https://scikit-learn.org/stable/modules/linear_model.html)

## Learn

- [ ] Model complexity
- [ ] Overfitting
- [ ] L1 regularization
- [ ] L2 regularization
- [ ] Ridge Regression
- [ ] Lasso Regression
- [ ] Regularization strength
- [ ] Coefficient shrinkage
- [ ] Feature selection with Lasso
- [ ] Bias-variance trade-off

## Practice

Using the e-commerce regression problem, train:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression

Compare MAE, RMSE, R² and coefficient sizes.

Explain how increasing regularization changes the model.

---

# 5. Ensemble Learning

> Ensemble methods combine multiple models to produce a stronger predictive system.

## Video Resource

### Random Forests — StatQuest

[![Random Forests](https://i.ytimg.com/vi/J4Wdy0Wc_xQ/hqdefault.jpg)](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)

**[Watch: Random Forests — StatQuest](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)**

## Documentation

- [scikit-learn — Ensemble Methods](https://scikit-learn.org/stable/modules/ensemble.html)

## Learn

- [ ] Ensemble learning
- [ ] Bagging
- [ ] Bootstrap sampling
- [ ] Random Forests
- [ ] Voting
- [ ] Boosting
- [ ] Stacking concepts
- [ ] Diversity between models
- [ ] Ensemble advantages
- [ ] Computational costs

## Practice

For the e-commerce classification problem compare:

```text
Decision Tree
      ↓
Random Forest
```

Investigate whether combining many trees improves generalization.

Explain why a Random Forest can perform better than a single Decision Tree.

---

# 6. Gradient Boosting

> Boosting builds models sequentially, with later learners attempting to correct errors made by earlier learners.

## Video Resource

### Gradient Boost — StatQuest

[![Gradient Boost](https://i.ytimg.com/vi/3CC4N4z3GJc/hqdefault.jpg)](https://www.youtube.com/watch?v=3CC4N4z3GJc)

**[Watch: Gradient Boost — StatQuest](https://www.youtube.com/watch?v=3CC4N4z3GJc)**

## Documentation

- [scikit-learn — Gradient Boosting](https://scikit-learn.org/stable/modules/ensemble.html#gradient-boosting)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)

## Learn

- [ ] Boosting
- [ ] Weak learners
- [ ] Sequential learning
- [ ] Residual/error correction
- [ ] Gradient Boosting
- [ ] Learning rate
- [ ] Number of estimators
- [ ] Tree depth
- [ ] Early stopping
- [ ] XGBoost concepts

## Practice

Compare:

```text
Decision Tree
Random Forest
Gradient Boosting
```

using the same cross-validation strategy.

Do not simply report which model wins. Explain the performance/complexity trade-off.

---

# 7. Imbalanced Data

> High accuracy can be misleading when one class occurs much more frequently than another.

This is particularly important for problems such as:

- Fraud detection
- Rare purchase events
- Customer churn
- Failed transactions
- High-risk orders

## Video Resource

### Precision and Recall — StatQuest

[![Precision and Recall](https://i.ytimg.com/vi/4jRBRDbJemM/hqdefault.jpg)](https://www.youtube.com/watch?v=4jRBRDbJemM)

**[Watch: Precision and Recall — StatQuest](https://www.youtube.com/watch?v=4jRBRDbJemM)**

## Documentation

- [scikit-learn — Classification Metrics](https://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics)
- [imbalanced-learn Documentation](https://imbalanced-learn.org/stable/)

## Learn

- [ ] Class imbalance
- [ ] Majority/minority classes
- [ ] Accuracy limitations
- [ ] Precision
- [ ] Recall
- [ ] F1
- [ ] Precision-Recall curves
- [ ] Class weighting
- [ ] Threshold adjustment
- [ ] Under-sampling concepts
- [ ] Over-sampling concepts
- [ ] SMOTE concepts
- [ ] Risks of synthetic sampling

## Practice

Create or identify an imbalanced e-commerce outcome.

Compare:

```text
Accuracy
Precision
Recall
F1
```

Then answer:

> Why could a model with 95% accuracy still be useless?

---

# 8. Feature Selection

> More features do not automatically produce a better model.

## Video Resource

### Feature Selection Techniques

[![Feature Selection](https://i.ytimg.com/vi/YaKMeAlHgqQ/hqdefault.jpg)](https://www.youtube.com/watch?v=YaKMeAlHgqQ)

**[Watch: Feature Selection Techniques](https://www.youtube.com/watch?v=YaKMeAlHgqQ)**

## Official Documentation

- [scikit-learn — Feature Selection](https://scikit-learn.org/stable/modules/feature_selection.html)
- [scikit-learn — Permutation Feature Importance](https://scikit-learn.org/stable/modules/permutation_importance.html)

## Learn

- [ ] Relevant features
- [ ] Redundant features
- [ ] Irrelevant features
- [ ] Filter methods
- [ ] Wrapper methods
- [ ] Embedded methods
- [ ] Univariate feature selection
- [ ] Recursive Feature Elimination
- [ ] L1-based selection
- [ ] Tree-based selection
- [ ] Permutation importance
- [ ] High-dimensional data

## Practice

Take your e-commerce model and compare:

```text
All Features
     vs
Selected Features
```

Compare predictive performance, training time, model complexity and interpretability.

Determine whether removing features improved the system.

---

# 9. Model Interpretation

> A good Data Scientist should understand not only what a model predicts, but also how the model is using available information.

## Video Resource

### SHAP Values Explained

[![SHAP](https://i.ytimg.com/vi/JLw2kPKoX7I/hqdefault.jpg)](https://www.youtube.com/watch?v=JLw2kPKoX7I)

**[Watch: SHAP Values Explained](https://www.youtube.com/watch?v=JLw2kPKoX7I)**

## Documentation

- [scikit-learn — Model Inspection](https://scikit-learn.org/stable/inspection.html)
- [scikit-learn — Permutation Feature Importance](https://scikit-learn.org/stable/modules/permutation_importance.html)
- [SHAP Documentation](https://shap.readthedocs.io/)

## Learn

### Global Interpretation

- [ ] Model coefficients
- [ ] Tree feature importance
- [ ] Permutation importance
- [ ] Partial dependence
- [ ] Feature relationships

### Local Interpretation

- [ ] Individual predictions
- [ ] SHAP concepts
- [ ] Local explanations
- [ ] Prediction confidence

### Critical Interpretation

- [ ] Correlated features
- [ ] Unstable importance
- [ ] Association vs causation
- [ ] Model explanation vs real-world explanation
- [ ] Interpretation limitations

## BIH E-Commerce Exercise

Select five predictions from your e-commerce model:

```text
Correct Positive
Correct Negative
False Positive
False Negative
Uncertain / Borderline Prediction
```

Investigate why the model produced each prediction.

Then answer:

> If Mr P.G. Marapira and Mr A.N.N. Sibisi asked why the system classified a particular shopping session as likely to purchase, what evidence could you provide?

Do not claim:

> "Feature X causes customers to purchase."

unless causal evidence exists.

---

# 10. Time Series & Forecasting

> Time-series modelling requires special treatment because observations are ordered through time.

## Video Resource

### Time Series Forecasting in Python

[![Time Series Forecasting](https://i.ytimg.com/vi/fxx_E0ojKrc/hqdefault.jpg)](https://www.youtube.com/watch?v=fxx_E0ojKrc)

**[Watch: Time Series Forecasting in Python](https://www.youtube.com/watch?v=fxx_E0ojKrc)**

## Documentation

- [scikit-learn — Time-related Feature Engineering](https://scikit-learn.org/stable/auto_examples/applications/plot_cyclical_feature_engineering.html)
- [scikit-learn — TimeSeriesSplit](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html)

## Learn

- [ ] Time-indexed data
- [ ] Trend
- [ ] Seasonality
- [ ] Lag features
- [ ] Rolling statistics
- [ ] Forecast horizon
- [ ] Naive baselines
- [ ] Temporal splits
- [ ] MAE
- [ ] RMSE
- [ ] MAPE limitations
- [ ] Time-series cross-validation concepts

## BIH E-Commerce Practice

Forecast a suitable e-commerce quantity such as weekly orders or sales activity.

1. Plot the time series.
2. Identify trend and seasonality.
3. Establish a naive baseline.
4. Create suitable time-based and lag features.
5. Use a temporal split.
6. Compare the model against the baseline.
7. Explain uncertainty and limitations.

---

# Level 4 Integrated Challenge

Return to the e-commerce Machine Learning system developed during Level 3.

Your task is to improve the system without contaminating the evaluation process.

The final workflow should demonstrate:

```text
Level 3 Model
      ↓
Reproducible Pipeline
      ↓
Advanced Cross-Validation
      ↓
Hyperparameter Optimization
      ↓
Regularization / Ensembles
      ↓
Feature Selection
      ↓
Model Interpretation
      ↓
Final Evaluation
```

## Required Evidence

- [ ] Complete preprocessing pipeline
- [ ] Appropriate validation strategy
- [ ] Hyperparameter search
- [ ] Baseline comparison
- [ ] At least one ensemble model
- [ ] Feature-selection investigation
- [ ] Error analysis
- [ ] Model interpretation
- [ ] Untouched final test evaluation
- [ ] Written limitations
- [ ] Recommendation to the system designers

---

# Level 4 Completion Standard

Before advancing, the learner should be able to:

- [ ] Build reproducible ML pipelines.
- [ ] Select cross-validation strategies appropriately.
- [ ] Tune models without contaminating test data.
- [ ] Explain regularization.
- [ ] Use ensemble and boosting methods appropriately.
- [ ] Handle imbalanced targets responsibly.
- [ ] Investigate feature selection.
- [ ] Interpret model behaviour carefully.
- [ ] Build basic forecasting workflows.
- [ ] Defend model selection with evidence.

---

To accomplish all of that, attempt [CHALLENGE 4](Challenges/CHALLENGE4.md), upon completion of this challenge you will then qualify to move to level 5.

# Ready to Advance?

Successful completion demonstrates readiness for:

## Level 5 — Deep Learning & AI

The learner should now understand that improving a Machine Learning model is not simply about selecting a more complicated algorithm.

The workflow should be:

```text
Reliable Data
      ↓
Leakage-Safe Pipeline
      ↓
Correct Validation
      ↓
Model Comparison
      ↓
Optimization
      ↓
Interpretation
      ↓
Evidence
      ↓
Decision
```
