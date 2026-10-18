# Sokoni Retail Sales Analysis 2024

This repository contains a retail sales analysis project for Sokoni, based on a 2024 sales dataset collected across multiple branches and product categories.

## Project overview

The analysis is implemented in `capstone_project.ipynb` and focuses on understanding sales performance across the business by examining:

- transaction records
- product categories and names
- branch performance
- monthly sales trends
- payment methods
- customer satisfaction
- returns and profitability

The notebook loads a sales dataset, inspects the data, and prepares it for exploratory analysis and business reporting.

## Files in this repository

- `capstone_project.ipynb` — Jupyter notebook with data loading, inspection, and analysis steps
- `sokoni_retail_data.csv` — retail sales dataset used by the notebook (expected in the same folder)

## Dataset description

The sales dataset includes transaction-level information such as:

- `transaction_id`
- `date`
- `branch`
- `branch_manager`
- `product_category`
- `product_name`
- `quantity`
- `unit_price`
- `total_sales`
- `cost_price`
- `profit`
- `payment_method`
- `customer_satisfaction`
- `returned`
- `staff_count`
- `month`
- `month_num`

This makes it suitable for analyzing revenue, costs, return rates, branch comparisons, and customer behavior.

## How to run the notebook

1. Open the repository in Jupyter Notebook or JupyterLab.
2. Ensure that `sokoni_retail_data.csv` is present in the same directory as the notebook.
3. Launch `capstone_project.ipynb`.
4. Run the cells in order.

## Required libraries

The notebook uses common Python data analysis libraries, including:

- pandas
- numpy
- matplotlib
- pathlib

You can install them with:

```bash
pip install pandas numpy matplotlib
```

## Typical analysis questions

This project can help answer questions such as:

- Which branch generated the highest sales?
- Which product category performs best?
- What is the monthly sales trend across the year?
- Which payment method is most common?
- Are there any customer satisfaction or return patterns worth investigating?
- Which products contribute most to profit?

## Notes

This project is intended as a data analysis and business intelligence exercise for understanding retail performance and supporting decision-making based on transactional data.

## License

This project does not include a specified license. If you plan to share or publish the repository publicly, consider adding a license file appropriate for your use case.
