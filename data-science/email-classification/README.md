# Email Classification — Text Analytics & Feature Engineering

**Source:** `Email_Classification_Analysis_v2.ipynb` (original notebook reviewed).

## Workflow implemented in the notebook
- Exploratory analysis and class distribution
- Duplicate detection, including texts with conflicting labels
- Dataset cleaning and class balancing with RandomOverSampler
- Stratified 75/25 train/test split
- TF-IDF and chi-square-based keyword extraction
- Category keyword overlap and cosine similarity analysis

## Important limitation
This notebook performs exploratory analysis and feature extraction; it does **not** establish a validated production classifier. Training and cross-validation of a baseline classifier are listed as next steps in the original notebook.

The original files will be imported separately. Some notebook paths refer to Colab-specific locations.

## Synthetic demo data

`data/synthetic_emails.csv` contains 120 **artificial** email-like texts with `tagged_text` and `classification` columns. Run the notebook from this directory; generated Excel outputs are written to `outputs/`. Requires pandas, numpy, matplotlib, scikit-learn, openpyxl; imbalanced-learn is optional. The sample is illustrative and is not evidence of classification performance on real messages.
