
E-Commerce Sales Analysis | Power BI

An interactive Power BI project for exploring e-commerce sales, profit, customer orders, regional performance, product categories, and shipping costs. The included PDF provides a visual reference for the report pages.

Repository contents: The supplied pbi.zip contains the source CSV datasets. It does not contain a Power BI .pbix file. Add the .pbix report to this repository if you want visitors to open and interact with the dashboard in Power BI Desktop.

Report pages

The report reference covers these views:

- Home: KPI cards and sales and profit by product category.
- Regional Analysis: sales, profit, and order comparisons by region and state.
- Shipping Cost Analysis: shipping cost measures and category comparisons, including profit after shipping.
- Insights: a summary of overall, regional, and shipping performance.
- Profit Driver Analysis: a detailed breakdown by region, state, category, and product description.

The report includes region and category slicers, as shown in the PDF. The insights page calls out the concentration of sales and profit in a small number of categories, regional differences, and shipping efficiency as areas to review.

Dataset

Extract the CSV files from pbi.zip into a Datasets/ folder. The archive currently contains:

File
Description
Rows

fact_sales.csv
Transaction-level sales data, including date, customer, product, invoice, quantity, sales, and unit price
25,065
dim_products.csv
Product lookup with weight, landed cost, shipping cost per 1,000 miles, description, and category
20
dim_customers.csv
Customer location lookup with city, postal code, state, latitude, and longitude
4,372
state_region_mapping.csv
State and abbreviation mapping to reporting regions
192

Product categories in the supplied lookup include Food, Disposables, Electronics, Grooming, Pet Food, Supplements, and Cleanig Supplies (spelling as present in the source data).

Open the report

1. Install Power BI Desktop.
2. Download or clone this repository and extract pbi.zip into Datasets/.
