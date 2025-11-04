# Housing Pricing Analysis

This notebook performs an end-to-end exploratory data analysis (EDA) for a housing price dataset and demonstrates basic data cleaning, visualization, feature engineering, and baseline model building. Typical outputs include:
- Summary statistics and data quality checks
- Missing value analysis and treatment strategies
- Visualizations (distributions, boxplots, correlations, scatter plots)
- Feature transformations and simple feature engineering
- Baseline regression models and evaluation (e.g., RMSE)

---

## Open in Google Colab

You can open and run the notebook in Google Colab directly from this repository:

Open in Colab (manual URL):
https://colab.research.google.com/github/nebyathhailu/house-pricing-eda/blob/main/housing_pricing_analysis.ipynb

Tip: Use Colab's "Runtime → Run all" after selecting a Python runtime with a GPU/TPU if desired.

---

## Required packages

The Colab runtime already contains most scientific Python packages. The notebook use (but is not limited to) the following libraries:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Notebook structure / outline

The notebook is organized into sections similar to:

1. Introduction / objectives
2. Imports and environment setup
3. Data loading
4. Initial inspection (shape, dtypes, head)
5. Missing values analysis and handling
6. Univariate and bivariate EDA (distributions, boxplots)
7. Correlation analysis and heatmaps
8. Feature engineering / transformations
9. Baseline model(s) (train/test split, simple regressors)
10. Evaluation and conclusions

---

## How to run (quick steps)

1. Click the Colab link above to open the notebook in Google Colab.
2. Ensure your runtime is set to Python 3 (Runtime → Change runtime type).
3. Mount Google Drive.
4. Execute cells in order (Runtime → Run all).
5. Inspect outputs, figures, and model evaluation cells for results.

If you prefer to run the notebook locally:
1. Clone the repository.
2. Create and activate a Python environment (venv or conda).
3. Install dependencies: pip install -r requirements.txt (if provided) or install packages listed above.
4. Launch Jupyter Notebook / JupyterLab and open `housing_pricing_analysis.ipynb`.


For questions about this notebook, open an issue in the repository or contact me on GitHub: https://github.com/nebyathhailu
