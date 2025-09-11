# Superstore_Exploratory_Data_Analysis

A beginner-friendly exploratory data analysis project exploring a sample superstore sales dataset.

## Project Overview

This project is about exploring superstore sales data to uncover patterns in sales, profit, geographical performance, product categories, customer segments, etc. It helps build intuition about what factors impact profitability and what opportunities may exist for improving performance.

## Repository Contents

- `Superstore_Exploratory_Data_Analysis.ipynb` — Jupyter Notebook walking through the full exploratory data analysis.  
- `Sample - Superstore.csv` — The sample dataset used for analysis.  
- `ml_stats.py` — A custom utility (library) for calculating metrics / statistical summaries.  

## Dataset

The dataset includes transaction-level or aggregated superstore data, with features such as:

- Order ID, Customer ID, Region / State / City  
- Product Category / Sub-Category  
- Sales, Quantity, Discount, Profit  
- Date of Order / Ship Date  
- Product Costs and other financial metrics  

## Analysis Workflow

Here’s how the exploration is carried out:

1. **Data Loading & Inspection**  
   - Load data and view its structure: number of rows/columns, data types.  
   - Summary statistics for numerical and categorical features.  

2. **Data Cleaning**  
   - Handle missing values, if any (drop, impute).  
   - Fix data type issues (e.g. dates).  
   - Remove or cap outliers if they distort the analysis.  

3. **Exploratory Data Visualization**  
   - Visualize distribution of sales, profit, discounts.  
   - Heatmaps, bar charts, line plots by Region / Category / Date.  
   - Time-series trends (monthly/quarterly) in sales and profit.  
   - Comparative analysis: which product sub-categories are most profitable.

4. **Key Insights**  
   - Identify strong performing / underperforming segments.  
   - Effects of discount on profit.  
   - Seasonal or geographic trends.  

## Results & Insights
Here are some example findings
- Just because people are purchasing expensive product doesn't mean superstore is earning more profit.
- Just because people are purchasing MORE product doesn't mean superstore is earning more profit.
- Superstore earns more profit if clever discounts are given.
- Negative correlation of Profit vs Discount (-0.22) is the biggest concern of sales management.
- Expected Sales vs Profit correlation was high instead it is weak positive (0.48).

## Conclusion & Next Steps
The exploratory analysis reveals both strengths and areas for improvement in product mix, discounting strategy, and regional performance.

### Possible next steps:
- Build predictive models (e.g. sales forecasting, churn prediction) using cleaned data.
- Develop dashboards / interactive visualizations for business stakeholders.
- Deep dive into margins: cost, pricing, and discount trade-offs.
- Segment customers and analyze retention or repeat business trends.

## Technologies Used
- Python (Pandas, NumPy)
- Visualization: Matplotlib / Seaborn
- Jupyter Notebook
