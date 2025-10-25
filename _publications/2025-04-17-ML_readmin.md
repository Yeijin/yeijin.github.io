---
title: "Machine Learning-Based Prediction of Unplanned Readmission Due to Major Adverse Cardiac Events Among Hospitalized Patients with Blood Cancers"
collection: publications
category: manuscripts
permalink: /publication/2025-04-17-ML_readmin
excerpt: 'This study aimed to develop an ML algorithm for predicting the 90-day unplanned readmission due to MACE among hospitalized patients with blood cancers.'
date: 2025-04-17
venue: 'Cancer Control'
paperurl: 'https://journals.sagepub.com/doi/full/10.1177/10732748251332803'
citation: 'Le N, Han S, Kenawy AS, <b>Kim Y,<b> Park C. Machine Learning-Based Prediction of Unplanned Readmission Due to Major Adverse Cardiac Events Among Hospitalized Patients with Blood Cancers. <i>Cancer Control.<i> 2025;32. doi:10.1177/10732748251332803'
---
## Abstract
### Background
Hospitalized patients with blood cancer face an elevated risk for cardiovascular diseases caused by cardiotoxic cancer therapies, which can lead to cardiovascular-related unplanned readmissions.
### Objective
We aimed to develop a machine learning (ML) model to predict 90-day unplanned readmissions for major adverse cardiovascular events (MACE) in hospitalized patients with blood cancers.
### Design
A retrospective population-based cohort study.
### Methods
We analyzed patients aged ≥18 with blood cancers (leukemia, lymphoma, myeloma) using the Nationwide Readmissions Database. MACE included acute myocardial infarction, ischemic heart disease, stroke, heart failure, revascularization, malignant arrhythmias, and cardiovascular-related death. Six ML algorithms (L2-Logistic regression, Support Vector Machine, Complement Naïve Bayes, Random Forest, XGBoost, and CatBoost) were trained on 2017-2018 data and tested on 2019 data. The SuperLearner algorithm was used for stacking models. Cost-sensitive learning addressed data imbalance, and hyperparameters were tuned using 5-fold cross-validation with Optuna framework. Performance metrics included the Area Under the Receiver Operating Characteristics Curve (ROCAUC), Precision-Recall AUC (PRAUC), balanced Brier score, and F2 score. SHapley Additive exPlanations (SHAP) values assessed feature importance, and clustering analysis identified high-risk subpopulations.
### Results
Among 76 957 patients, 1031 (1.34%) experienced unplanned 90-day MACE-related readmissions. CatBoost achieved the highest ROCAUC (0.737, 95% CI: 0.712-0.763) and PRAUC (0.040, 95% CI: 0.033-0.050). The SuperLearner algorithm achieved slight improvements in most performance metrics. Four leading predictive features were consistently identified across algorithms, including older age, heart failure, coronary atherosclerosis, and cardiac dysrhythmias. Twenty-three clusters were determined with the highest-risk cluster (mean log odds of 1.41) identified by nonrheumatic/unspecified valve disorders, coronary atherosclerosis, and heart failure.
### Discussion
Our ML model effectively predicts MACE-related readmissions in hospitalized patients with blood cancers, highlighting key predictors. Targeted discharge strategies may help reduce readmissions and alleviate the associated healthcare burden.
