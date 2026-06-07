# Python Project: EDA & Customer Cohort Analysis

This project analyzes an e-commerce dataset using Python and pandas.  
The main goal is to explore customer behavior, calculate cohort retention, analyze revenue dynamics, and create a simple HTML report that can be shared as part of a data analyst portfolio.

## Business Question

How do customer retention and revenue change across monthly cohorts, and which cohorts generate the strongest customer value over time?

Additional questions:

- How many new customers joined each monthly cohort?
- How does revenue change by month?
- How does retention change across the customer lifecycle?
- Which cohorts generated the highest total and cumulative revenue?
- What can be analyzed next to better understand customer behavior?

## Tools

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Google Colab
- HTML report
- GitHub
- GitHub Pages

## Project Structure

```text
python-eda-cohort-analysis/
|
├── README.md
├── data/
│   └── client_base.xlsx
|
├── notebooks/
│   └── retention_cohort_analysis_colab.ipynb
|
├── docs/
│   └── index.html
|
└── requirements.txt
```

## Notebook

The project was originally created in Google Colab.  
The notebook contains the full analysis workflow: data loading, EDA, cohort calculation, retention analysis, revenue analysis, visualizations, and HTML report generation.

[Open in Google Colab](https://colab.research.google.com/drive/1GZEIQfdWhnp5FQNYa2ARo0VStgZB1h3D?usp=sharing)

## HTML Report

The project also includes an exported HTML report.  
This report is a static version of the analysis with charts and summary sections.

If GitHub Pages is enabled for this repository, the HTML report can be viewed here:

[Open HTML report: EDA & Customer Cohort Analysis](https://irynasenchenko.github.io/python-eda-cohort-analysis/)

## Analysis Steps

- Loaded and inspected customer and order datasets
- Checked dataset structure and missing values
- Created cohort month and cohort index columns
- Calculated cohort size by registration month
- Analyzed revenue and order count dynamics by month
- Built user retention tables
- Calculated retention rate by cohort
- Analyzed cohort revenue and cumulative revenue
- Summarized key insights and next steps

## Key Insights

Based on the current dataset:

- The largest cohort was **July 2025** with **452 new customers**.
- Monthly revenue peaked in **August 2025**.
- August 2025 also had the highest number of orders.
- Most cohorts show around **49–60% retention after the first month**, followed by a gradual decline.
- The **July 2025 cohort** generated the highest total cohort revenue.

## Recommendations / Next Steps

Potential next steps for deeper analysis:

- Analyze why the July 2025 cohort was the strongest by size and revenue.
- Compare retention by acquisition channel.
- Check whether payment method or order status affects revenue and retention.
- Add customer segmentation by age, gender, city, or acquisition channel.
- Build a Tableau or Power BI dashboard based on the cohort results.

## Data Privacy Note

The dataset used in this repository is synthetic and prepared for learning purposes.  
It does not contain real customer data.

## How to Use This Repository

1. Open the notebook in Google Colab.
2. Upload `customers.csv` and `orders.csv` or connect your Google Drive.
3. Run the notebook cells.
4. Export the result as `.ipynb` or HTML if needed.

## Portfolio Value

This project demonstrates:

- Python data analysis basics
- EDA workflow
- cohort analysis logic
- retention analysis
- revenue analysis
- data visualization
- ability to present analysis results as a portfolio project
