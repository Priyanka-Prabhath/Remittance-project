# Remittance Dataset Analysis

Exploring remittance flows across company-to-country corridors. The project follows a data analysis workflow from data cleaning and preparation through exploratory and time-series analysis, with the goal of identifying patterns that may support forecasting.

## Project Goal

Analyze remittance volume and payout behavior across corridors (company → country), looking for trends, seasonality, and relationships between current and past values.

## Analysis

- **Data cleaning and preparation:** Address missing values and gaps in the daily timeline using reindexing and linear interpolation.
- **Seasonality and trends:** Use STL (Seasonal-Trend decomposition using LOESS) to examine trend and seasonal components.
- **Behavior by calendar date:** Create normalized heatmaps to compare activity across days of the week and days of the month.
- **Lag relationships:** Explore correlations between previous days’ payout amounts and future values as a search for potentially useful predictive signals.

## Project Files

| File | Description |
| --- | --- |
| `remmitance_EDA.ipynb` | Exploratory data analysis notebook with the data-cleaning and visualization workflow. |
| `feature_engineering_model_training.ipynb` | Notebook for feature engineering and preparing data for model training. |
| `remittance_sliced.csv` | Processed dataset described in the notebooks as cleaned and reindexed. |

## Technologies

- **Pandas and NumPy** — data manipulation and numerical analysis
- **Matplotlib and Seaborn** — visualizations and heatmaps
- **Statsmodels** — STL decomposition
- **Scikit-learn** — scaling and evaluation metrics

## Getting Started

Open the notebooks in Jupyter Notebook or JupyterLab to explore the analysis. Run the exploratory data analysis notebook before the feature engineering and model training notebook if the latter relies on data prepared in the former.

> Note: The notebook filenames and dataset description above follow the files and details documented in this project README.
