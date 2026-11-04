# Cohort Analysis — Pandas Exercise

## Project Objectives

- Organize user activity records into cohorts based on each user's first observed activity month.
- Calculate the number of months elapsed since cohort entry for subsequent activity records.
- Build a cohort-by-period matrix and calculate retention ratios using Pandas.
- Visualize cohort behavior with a retention heatmap and practice interpreting changes over time.

**Source:** `26.3 Когортный анализ.ipynb`

A notebook exploring cohort assignment from transaction dates and user identifiers, using Pandas and date transformations.

**Reproducibility:** The referenced `когортный анализ.xlsx` input file was not present in the supplied archives. This is an analytics exercise, not a production data pipeline.

## Synthetic demo data

`data/synthetic_cohorts.csv` contains 387 **artificial** user-activity rows with `user_id` and `date`. Run the notebook from this directory. This example demonstrates cohort calculations, not real customer retention. Requires pandas, numpy, seaborn and matplotlib.
