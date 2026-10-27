# Retail Sales Analysis | Python & Power BI

## Overview

This project analyzes retail sales data to evaluate sales performance, profitability, product categories, customer segments, and monthly trends. Python is used for data exploration and preparation, while Power BI is used to build an interactive dashboard.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI Desktop
- DAX

## Business Questions

- How do sales and profit change over time?
- Which product categories generate the most sales?
- Which sub-categories generate the highest and lowest profit?
- How do region and customer segment affect performance?
- How are discounts associated with profitability?

## Project Workflow

1. Load and inspect the source dataset.
2. Check data types, missing values, duplicate records, and date validity.
3. Explore sales, profit, profit margin, and order trends.
4. Prepare an analysis dataset using documented date-filtering rules.
5. Create DAX measures and an interactive Power BI dashboard.
6. Summarize findings and business recommendations.

## Key Findings

- Technology generated approximately 766,427 in sales and 135,247 in profit in the provisional analysis.
- Furniture generated approximately 683,292 in sales but only 18,042 in profit.
- Tables had the largest sub-category loss, at approximately 15,822.
- The overall profit margin was approximately 12.91%.

*Note: The findings are preliminary and based on the current analysis dataset. The reporting period and future-dated records still need to be validated, and the dataset's currency has not yet been confirmed.*

## Repository Structure

- `notebooks/` — Data exploration and analysis
- `data/` — Local source and processed data, excluded from Git
- `powerbi/` — Power BI report

## Reproducing the Analysis

1. Install the packages listed in `requirements.txt`.
2. Obtain the original dataset from its authorized source.
3. Place it in `data/raw/`.
4. Run the notebook in `notebooks/` to inspect, prepare, and analyze the data.
5. Follow the notebook's documented steps to regenerate the processed dataset.
6. Open the Power BI report in Power BI Desktop and refresh it using the regenerated data, updating the source path if necessary.

## Limitations

- Date filtering requires validation against the source dataset's intended reporting period.
- The relationship between discounts and profit is observational and does not establish causation.
- Currency and source-data redistribution permissions must be confirmed.

## Author

BBA graduate building skills in data analysis, business reporting, and business analytics.

## Project Status

**Status: In Progress**

This project is currently under development. Data exploration and preparation have been completed, and an interactive Power BI dashboard has been created. Further work includes validating the dataset's reporting period, refining the dashboard, and documenting the final business insights and recommendations.