
# 📊 E-Commerce Sales Analysis Dashboard

## 📌 Project Overview

The **E-Commerce Sales Analysis Dashboard** is an intermediate-level data analytics project built using Python.
It focuses on transforming raw sales data into meaningful business insights through data cleaning, exploratory data analysis, visualization, and machine learning-based sales forecasting.

An interactive **Streamlit dashboard** is included for real-time data exploration and KPI tracking.

---

## 📂 Dataset

The project uses the **Superstore Sales Dataset** located at:

```
data/raw/superstore.csv
```

If the dataset is missing or invalid, the pipeline automatically generates a synthetic dataset to ensure the project remains fully runnable.

---

## ✨ Key Features

* Data cleaning and preprocessing pipeline
* Exploratory Data Analysis (EDA)
* Missing value and correlation analysis
* Product, region, and category performance analysis
* Sales forecasting using Linear Regression
* Model evaluation and performance metrics
* Interactive Streamlit dashboard with filters and KPIs

---

## 🛠️ Technologies Used

* Python 3.11+
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* Streamlit

---

## 📁 Project Structure

```
Ecommerce_Sales_Analysis/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── processed/           # Cleaned & processed data
│
├── notebooks/               # Jupyter notebooks (EDA & analysis)
├── src/                     # Source code (data processing & ML)
├── dashboard/               # Streamlit dashboard
├── reports/
│   └── figures/             # Generated visualizations
├── requirements.txt
├── main.py
└── README.md
```

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### 1. Data Cleaning

```bash
python main.py clean
```

### 2. Run Full Analysis & Forecasting

```bash
python main.py all
```

### 3. Launch Dashboard

```bash
streamlit run dashboard/app.py
```



## 📊 Outputs Generated

* Cleaned dataset → `data/processed/cleaned_sales.csv`
* Forecast results → `data/processed/sales_forecast.csv`
* Visualization reports → `reports/figures/`



## 🎯 Project Highlights

* End-to-end data science pipeline
* Business-oriented insights
* Machine learning forecasting model
* Interactive dashboard for decision making



## 👨‍💻 Author

**Ansar Ullah**
Data Science & Machine Learning Enthusiast
