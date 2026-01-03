# Post-COVID Analysis (Statistical Analysis + Machine Learning + Power BI)

This project is an end-to-end data science workflow focused on post-COVID outcomes. It combines statistical analysis and hypothesis testing with supervised machine learning and interpretability, and communicates findings through an interactive Power BI dashboard.

## Goals
- Explore post-COVID symptom patterns using exploratory data analysis (EDA) and visualization
- Test relationships with inferential statistics (hypothesis testing)
- Build predictive models using statistical learning / machine learning
- Explain model behavior with SHAP-based interpretability
- Deliver insights in a clear dashboard for non-technical audiences

## Workflow
1. Data ingestion and cleaning
   - data validation, type fixes, inconsistent values, duplicates
2. Preprocessing and feature engineering
   - missing-value handling (imputation strategy)
   - categorical encoding
   - scaling/normalization where needed
3. Exploratory data analysis (EDA)
   - distributions, group comparisons, correlations, trend checks
4. Statistical analysis
   - hypothesis testing (e.g., group differences via t-tests/ANOVA when applicable)
   - confidence-based reasoning and significance reporting
5. Outlier/anomaly handling
   - anomaly detection to reduce noise and improve robustness
6. Modeling (statistical learning / ML)
   - baseline models + stronger models for comparison
   - cross-validation and evaluation on held-out data
   - performance metrics (classification and/or regression, depending on the target)
7. Interpretability
   - SHAP to identify and explain important predictors
8. Reporting and visualization
   - interactive Power BI dashboard with key insights and filters

## Deliverables
- Power BI dashboard (interactive pages + filters)
- Analysis/report documenting EDA, statistical testing, modeling, and interpretation
- Cleaned/preprocessed dataset (optional export for reproducibility)

## Tech stack
- Python: pandas, NumPy, scikit-learn
- Interpretability: SHAP
- Visualization and reporting: Power BI

## Notes
- Designed as a structured, repeatable pipeline: preprocessing is consistent across analysis and modeling.
- Focus on both statistical rigor (inference/hypothesis testing) and practical predictive performance (ML evaluation).
