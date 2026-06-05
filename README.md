# E-Commerce Sales Analysis Dashboard

## Project Overview

The E-Commerce Sales Analysis Dashboard is an intermediate portfolio project built with Python.
It includes data cleaning, exploratory data analysis, sales and customer insights, visualizations, forecasting with machine learning, and an interactive Streamlit dashboard.

## Dataset

This project uses the Superstore Sales dataset loaded from `data/raw/superstore.csv`.
If the dataset is missing or empty, the pipeline generates a realistic sample dataset so the project remains runnable.

## Features

- Full data cleaning and preprocessing
- Exploratory data analysis and summary statistics
- Missing value and correlation analysis
- Product performance and regional analysis
- Linear Regression sales forecasting and model evaluation
- Interactive Streamlit dashboard with filters and KPI cards

## Technologies Used

- Python 3.11+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Streamlit
- Plotly

## Project Structure

Ecommerce_Sales_Analysis/
├── data/raw/
├── data/processed/
├── notebooks/
├── src/
├── dashboard/
├── reports/figures/
├── requirements.txt
```

## Installation

```bash
python -m pip install -r requirements.txt
```

## Usage

Clean the dataset and prepare processed data:

```bash
python main.py clean
```

Run full analysis and forecasting:

```bash
python main.py all
```

Open the Streamlit dashboard:

```bash
streamlit run dashboard/app.py
```

If you run the dashboard from VS Code, use the provided `.vscode/launch.json` configuration or ensure `PYTHONPATH` includes the project root.

## Output Files

- `data/processed/cleaned_sales.csv`
- `data/processed/sales_forecast.csv`
- `reports/figures/analysis_summary.txt`
- Interactive dashboard in `dashboard/app.py`
