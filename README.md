# Customer Sales Analysis Using Python

## Project Overview
This project analyzes e-commerce transaction data to understand customer purchasing behavior, sales trends, and product performance. The goal is to derive actionable business insights using data cleaning, exploratory data analysis, and visualization techniques.


## Objectives
- Identify overall sales and revenue trends
- Analyze revenue distribution across countries
- Identify high-value customers
- Evaluate top-performing products by revenue and quantity
- Generate insights to support data-driven business decisions


## Dataset
- **Type:** E-commerce / Online Retail Transaction Data
- **Records:** ~540,000 transactions (before cleaning)
- **Features include:**
  - Invoice number and date
  - Product description
  - Quantity and unit price
  - Customer ID
  - Country

**Note:**  
The dataset is not included in this repository due to file size constraints.  
It can be obtained from the **Online Retail Dataset** (UCI / Kaggle).


## Data Cleaning & Feature Engineering
- Removed transactions with missing customer identifiers
- Excluded invalid transactions (returns and zero-price items)
- Converted invoice dates to datetime format
- Engineered new features:
  - `Revenue`
  - `Year`, `Month`, `Day`


## Exploratory Data Analysis
Key analyses performed:
- Monthly revenue trends
- Revenue contribution by country
- Customer-level revenue distribution
- Product performance by revenue and quantity sold


## Key Insights
- Revenue shows strong seasonality with peak sales in the final quarter
- The United Kingdom is the dominant revenue-generating market
- A small group of customers contributes a large share of total revenue (Pareto effect)
- Some products drive revenue through premium pricing, while others contribute via high sales volume


## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook



## Files in This Repository
- `customer_sales_analysis.ipynb` — Complete analysis and visualizations


## Conclusion
This project demonstrates practical data analytics skills including data cleaning, exploratory analysis, and business insight generation. The results highlight opportunities for targeted marketing, customer segmentation, and inventory optimization.


## Author
**Anjali Velu Ramalingam**  
Graduate Student – Data Science / Analytics
