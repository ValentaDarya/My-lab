# Data & AI Lab

Hands-on portfolio of **data science, machine learning, data engineering and analytics** work.

The projects are based on original learning exercises and Jupyter notebooks. Documentation distinguishes implemented analysis from future improvements, and avoids unsupported model-performance claims.

## Project index

| Project | Focus | Notebook status |
| --- | --- | --- |
| [Email Classification](data-science/email-classification/) | Text cleaning, TF-IDF, chi-square keyword extraction, cosine similarity | Notebook available |
| [Machine Learning Models](data-science/machine-learning-models/) | Data cleaning, EDA, decision trees, random forests, neural networks and price-prediction exercises | Notebook available |
| [Cohort Analysis](data-engineering/cohort-analysis/) | Pandas-based cohort analysis | Notebook available |
| [Mathematical Concepts](data-science/mathematical-concepts/) | Function approximation | Notebook available |

## Toolkit

Python · SQL · Pandas · NumPy · scikit-learn · Jupyter · Exploratory Data Analysis · Feature Engineering · Machine Learning

## Reproducibility notes

Some original notebooks rely on external datasets or Google Colab paths that are not bundled with the source archives. These dependencies are documented rather than silently replaced. Eight curated Jupyter notebooks are available in their project directories. Notebook outputs were cleared before publication; notebooks have not been rerun.

## Repository organization

- `data-science/`: text analytics, predictive modeling and mathematical exercises
- `data-engineering/`: analytical data processing and cohort analysis

**Current status:** Eight original notebooks are published in their project folders. Reproducibility checks are still pending.

## Synthetic datasets

To make the exercises easier to explore, this repository includes explicitly labeled **synthetic demo CSVs** for email classification, vehicle analytics and cohort analysis. They are not the original datasets and should not be used to infer real-world model quality. The notebooks have been adapted to use local demo input paths, but a complete end-to-end execution check has not yet been performed.
