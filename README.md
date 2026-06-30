## Project overview

This project predicts whether a loan applicant is a good or bad credit risk,
using the German Credit dataset (UCI). It simulates a real-world credit risk
analytics workflow, from raw data to a stakeholder-ready dashboard.

## Phases

**1. Problem definition & dataset**
Defined the business question (predict loan default risk), selected the
UCI German Credit dataset, and decoded its raw categorical codes into
human-readable features.

**2. Data engineering & SQL pipeline**
Built a reproducible pipeline to clean, transform, and load the data into
a SQL database, with a documented data dictionary and schema.

**3. Exploratory data analysis & feature engineering**
Analyzed distributions, correlations, and outliers. Engineered domain-specific
features (e.g. debt-to-income ratio, credit utilization) to improve model signal.

**4. Machine learning modelling & evaluation**
Trained and compared Logistic Regression and XGBoost models. Evaluated using
ROC-AUC, Gini coefficient, and KS statistic. Used SHAP for explainability —
critical for regulatory transparency in financial services.

**5. Power BI dashboard**
Built an interactive 3-page dashboard: portfolio overview, customer
segmentation, and model insights (feature importance, risk tiers).

**6. Documentation & presentation**
Structured the repo for clarity (data, notebooks, src, dashboard, reports),
with this README in English and a short German summary (LIESMICH.md).

## Projektübersicht

Dieses Projekt sagt voraus, ob ein Kreditantragsteller ein gutes oder
schlechtes Risiko darstellt, basierend auf dem deutschen Kreditdatensatz
(UCI). Es umfasst Datenaufbereitung, explorative Analyse, maschinelles
Lernen (XGBoost mit SHAP-Erklärbarkeit) und ein interaktives Power-BI-Dashboard.
