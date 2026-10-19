# Customer Churn Dashboard

**Status:** 🚧 In progress

## Business question
Why do customers leave, and which ones are most at risk?

## Data
- **Source:** [e.g. Telco Customer Churn on Kaggle]
- **Size:** [rows x columns]
- **Cleaning notes:** [e.g. fixed `TotalCharges` type, handled missing values]

## Tools
Python · pandas · scikit-learn · Plotly · Streamlit

## Approach
1. Cleaned data and engineered features (`notebooks/01_cleaning.ipynb`)
2. Exploratory analysis of churn by contract, tenure, and charges (`notebooks/02_eda.ipynb`)
3. Trained a baseline model, [logistic regression], and evaluated it with [precision/recall/AUC] (`notebooks/03_model.ipynb`)
4. Built an interactive Streamlit dashboard (`dashboard/app.py`)

## Key insights
- [e.g. "Month-to-month customers churn at 3x the rate of annual contracts"]
- [Insight 2]
- [Insight 3]

## Recommendation
[e.g. "Offer annual-contract discounts to month-to-month customers in their first 6 months."]

## Links
- 🚀 Live app: [Streamlit Community Cloud link]
- 📓 Notebooks: [`/notebooks`](./notebooks)

## Run it locally
```bash
git clone https://github.com/username/python-churn-dashboard.git
cd python-churn-dashboard
pip install -r requirements.txt
streamlit run dashboard/app.py
```

## Repo structure
```
data/        dataset or download link
notebooks/   cleaning, EDA, modeling
dashboard/   Streamlit app
requirements.txt
```
