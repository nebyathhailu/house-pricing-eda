# Housing Pricing Analysis — Colab Notebook

This project contains a Colab-optimized Jupyter Notebook for exploratory data analysis (EDA) and a simple baseline modeling workflow for a housing prices dataset. The main implementation is provided as a single notebook, optimized for interactive use in Google Colab.

## Features

- **Comprehensive EDA:** Data summaries, missing-value diagnostics, univariate and bivariate analyses.
- **Visualizations:** Distribution plots, boxplots, correlation heatmaps, scatter plots and more.
- **Feature Engineering:** Basic transformations and derived features to prepare data for modeling.
- **Baseline Modeling:** Train/test split, baseline regressors, and model evaluation (e.g., RMSE).
- **Colab Integration:** Ready to run in Google Colab — no local environment setup required.
- **Modular Design:** Notebook sections are organized so you can adapt or extend specific parts easily.

## Getting Started

### Run in Google Colab

Open and run the notebook directly in Google Colab by clicking the badge below:

<a href="https://colab.research.google.com/github/nebyathhailu/house-pricing-eda/blob/main/housing_pricing_analysis.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Prerequisites (for Colab)

- A Google account
- The housing dataset (commonly `train.csv` and optionally `test.csv`) available in Colab or Google Drive

## Steps

1. Open the notebook in Colab using the badge above or [open directly](https://colab.research.google.com/github/nebyathhailu/house-pricing-eda/blob/main/housing_pricing_analysis.ipynb).
2. Install required libraries if prompted. Example:
   ```python
   !pip install pandas numpy matplotlib seaborn scikit-learn missingno xgboost lightgbm
   ```
3. (Optional) Mount Google Drive if your dataset is stored there:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Place your dataset (e.g., `train.csv`) in an accessible path (Colab workspace or Drive) and update file paths in the notebook cells if needed.
5. Run cells sequentially or use `Runtime → Run all` to execute the full workflow.

## Repository Structure

- `housing_pricing_analysis.ipynb`: Main Colab notebook with data loading, EDA, feature engineering, modeling, and evaluation.
- `README.md`: This file — project overview and instructions.

## What the Notebook Covers

- Loading and inspecting the dataset (shape, dtypes, head)
- Missing-value analysis and basic handling strategies
- Univariate & bivariate analyses and visual diagnostics
- Correlation analysis and feature selection guidance
- Simple feature engineering and transformations
- Baseline regression modeling and evaluation (train/test, RMSE)
- Short discussion of results and suggested next steps

## Contributing

Contributions are welcome! Please fork the repository, create a branch for your change, and submit a pull request.
