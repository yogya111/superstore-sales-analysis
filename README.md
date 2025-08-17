**Superstore Sales Analysis**


**Project Overview**

This project performs a detailed analysis of the Superstore dataset, covering 9,994 transactions from 2014–2017. The analysis explores sales patterns, profitability, discounts, and customer behavior to uncover actionable insights for business decision-making.

The notebook covers:

- Data loading and cleaning

-Exploratory data analysis (EDA)

-Outlier detection

-Sales trend analysis

-Visualization of key metrics

**Dataset**

**File: Sample - Superstore.xls**

Contains 21 columns, including:

Order Date, Customer Name, Region, Category, Sub-Category

Sales, Profit, Discount, Quantity, Postal Code, Row ID

**Objectives**

-Explore dataset structure, check for missing values, and detect outliers.

-Analyze sales trends by Region, Category, and Sub-Category.

-Examine monthly sales patterns and seasonal variations.

-Understand the relationship between Discount and Profit.

-Identify top-performing customers.

-Visualize correlations among numerical variables.

**Tools & Libraries**

-Python 3

-Pandas & NumPy – data manipulation

-Matplotlib & Seaborn – visualizations

-Squarify – treemap visualization

-SciPy & Statsmodels – statistical analysis

**Key Visualizations**

- Pie Chart: Regional sales distribution

- Line Plot: Monthly sales trend

- Bar Charts: Sales & Profit by Sub-Category, Top 10 Customers by Sales

- Scatter Plot: Discount vs Profit by Category

- Box Plot: Sales distribution across Categories

- Treemap: Sales distribution across Category/Sub-Category

- Heatmap: Correlation matrix of numeric variables

**Insights**

- The West region contributes the highest sales.

- Discounts above 30% often lead to reduced profit.

- Furniture, Office Supplies, and Technology categories dominate total revenue.

- Monthly sales show seasonal patterns with peaks during certain months.

- Top customers account for a significant portion of total sales, highlighting the importance of key accounts.

- Outlier detection (z-score > 3) identified 127 extreme sales values, indicating occasional high-value transactions.

How to Run

Clone this repository.

Place Sample - Superstore.xls in the project folder.

Open and run the Jupyter Notebook:

# Clone the repository
git clone <repository-url>

# Open notebook
jupyter notebook Superstore_Sales_Analysis.ipynb

License

This project is for educational purposes.
