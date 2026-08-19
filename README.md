# EV Market Intelligence Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-217346?logo=microsoftexcel&logoColor=white)
![Market Research](https://img.shields.io/badge/Market-Research-blue)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-purple)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-orange)
![Analytics](https://img.shields.io/badge/Analytics-Project-red)

## Overview

A data-driven market intelligence project analyzing India's Electric Vehicle (EV) ecosystem using Python, Excel, and Power BI. The project transforms raw market and policy data into actionable business insights by identifying growth trends, consumer adoption patterns, battery technology developments, and future investment opportunities.

---

## Business Problem

India's EV market is expanding rapidly, generating large volumes of industry, policy, and market data. Businesses require structured analysis to understand:

- Market growth patterns
- Consumer adoption trends
- Battery technology evolution
- Government policy impact
- Future investment opportunities

---

## Objectives

- Analyze India's EV market growth
- Study segment-wise adoption (2W, 3W, Passenger Vehicles, Commercial Vehicles)
- Evaluate government initiatives such as FAME and PLI
- Analyze battery technologies and the EV supply chain
- Identify investment opportunities and industry challenges
- Create interactive dashboards for business decision-making

---

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn) — data cleaning and exploratory analysis
- Jupyter Notebook — analysis workflow
- Microsoft Excel — data prep and supporting calculations
- Power BI — interactive dashboarding

## Data Sources

- India's EV registrations by vehicle category, 2001–2024 (monthly) — [Kaggle](https://www.kaggle.com/datasets/srinrealyf/india-ev-market-data)
- EV sales by manufacturer and category, 2015–2024 — Kaggle
- Statewise EV charging infrastructure — compiled for this project's Power BI dashboard
- Operational public charging stations by state — Kaggle

## Running the Notebooks

```bash
git clone https://github.com/tanvi01423/EV-Market-Intelligence-Analytics.git
cd EV-Market-Intelligence-Analytics
pip install -r requirements.txt
jupyter notebook notebooks/01_data_cleaning_eda.ipynb
```

---

## Workflow

```
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Visualization
      ↓
Market Segmentation
      ↓
Business Insights
      ↓
Recommendations
```

---

## Key Analysis

### Market Analysis
- EV sales trend analysis
- Market share analysis
- CAGR calculation
- Segment-wise growth

### Policy Analysis
- FAME Scheme
- PLI Scheme
- State EV Policies

### Battery Ecosystem
- Battery technologies
- Supply chain
- Recycling and second-life applications
- Circular economy

### Consumer Insights
- Charging infrastructure
- Purchase barriers
- Total Cost of Ownership

---

## Dashboard Preview

### Indian EV Market Dashboard
![Dashboard 1](https://github.com/tanvi01423/EV-Market-Intelligence-Analytics/raw/main/Screenshot%202026-01-01%20162537.png)

### Recovery Rate and Cost Savings on Minerals
![Dashboard 2](https://github.com/tanvi01423/EV-Market-Intelligence-Analytics/raw/main/Screenshot%202025-12-30%20121105.png)

### Cost Share of Various Components
![Dashboard 3](https://github.com/tanvi01423/EV-Market-Intelligence-Analytics/raw/main/Screenshot%202025-12-30%20152143.png)

### Profit Margin
![Dashboard 4](https://github.com/tanvi01423/EV-Market-Intelligence-Analytics/raw/main/Screenshot%202025-12-28%20215916.png)

The full interactive report is available in [`Indian EV Market.pbix`](./Indian%20EV%20Market.pbix) — open with Power BI Desktop.
The full written report is available in [`EV industry report.pdf`](./EV%20industry%20report.pdf).

---

## Key Insights

- India's EV market is experiencing rapid growth, led primarily by the two-wheeler and three-wheeler segments.
- Government incentives significantly influence EV adoption.
- Charging infrastructure remains one of the major adoption challenges.
- Battery recycling and second-life applications present substantial business opportunities.
- Domestic battery manufacturing is expected to reduce import dependency in the future.

---

## Repository Structure

```
EV-Market-Intelligence-Analytics/
│
├── notebooks/                          # Python analysis
│   └── 01_data_cleaning_eda.ipynb      # Data cleaning + exploratory data analysis
│
├── data/                                # Datasets used in the analysis
│   ├── statewise_ev_charging_infrastructure.csv
│   ├── ev_cat_01-24.csv                # Monthly EV registrations by category, 2001-2024
│   ├── ev_sales_by_makers_and_cat_15-24.csv
│   ├── OperationalPC.csv               # Operational public charging stations by state
│   ├── ev_maker_by_place.csv
│   └── clean_*.csv                     # Cleaned outputs from the EDA notebook
│
├── report/                   # Supporting report assets
├── images/                   # Chart/image assets used in the report
├── EV industry report.pdf    # Full written analysis
├── Indian EV Market.pbix     # Power BI dashboard file
├── requirements.txt          # Python dependencies to run the notebooks
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Intelligence
- Market Research
- Python (Pandas, NumPy)
- Power BI
- Strategic Decision Making

---

## Planned Restructuring

- [x] Rename `python code/` → `notebooks/` (no spaces in folder names)
- [x] Add a `data/` folder with the underlying dataset(s) used for analysis, for reproducibility
- [x] Add a `requirements.txt` for the Python environment
- [ ] Move all screenshots into `images/` with descriptive filenames
- [ ] Add `02_sales_forecasting_model.ipynb` (in progress)

---

## Future Improvements

- [ ] EV Sales Forecasting using Machine Learning
- [ ] Customer Sentiment Analysis
- [ ] Battery Demand Prediction
- [ ] Interactive Web Dashboard (see companion repo: [EV-Market-Dashboard-1](https://github.com/tanvi01423/EV-Market-Dashboard-1))

---

## About

A data-driven market intelligence project analyzing India's Electric Vehicle ecosystem using Python, Excel, and Power BI to uncover trends, market opportunities, and strategic insights across EV adoption, battery technologies, charging infrastructure, and government policies.


---

## About

A data-driven market intelligence project analyzing India's Electric Vehicle ecosystem using Python, Excel, and Power BI to uncover trends, market opportunities, and strategic insights across EV adoption, battery technologies, charging infrastructure, and government policies.

  
