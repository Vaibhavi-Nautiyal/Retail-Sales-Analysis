Retail Sales Analysis Using Python
This project is a complete end-to-end exploratory data analysis (EDA) of a retail sales dataset. 
The goal is to extract actionable insights from sales and profit trends using Python and visualization libraries.

** Objective**
- Analyze retail data to understand performance trends
- Identify top-performing products, regions, and segments
- Calculate and analyze key metrics such as Sales, Profit, and Discounts
- Derive business insights that can help improve decision-making

**Dataset**
- Source: Kaggle (Retail Orders Dataset)

**Data Cleaning and Transformation**
- Converted `order_date` to datetime format
- Extracted `year` and `month` for time-based analysis
- Calculated:
  - `sales = sale_price * quantity * (1 - discount_percent/100)`
  - `cost = cost_price * quantity`
  - `profit = sales - cost`
- Removed irrelevant columns like `postal_code`

**Analysis Performed**
- Yearly and Monthly Sales & Profit Trends
- Segment-wise, Category-wise, and Region-wise performance
- Top 5 products by Sales and by Profit
- Discount vs Profitability relationship

**Tools and Libraries Used**
- `Python`
- `pandas`, `matplotlib`, `seaborn`
- Jupyter Notebook

**Results**
- Sales peaked in the **Western region** and **Consumer segment**
- Certain high-sales products were not high-profit items, showing discount inefficiencies
- Monthly trends helped identify low-performing periods
- Useful KPIs like average profit per order, profit margins were extracted

**Dashboard Visualisation**
- Power BI Dashboard (to be added soon)
- Advanced segmentation & customer clustering
- Predictive modeling (optional for future scope)

