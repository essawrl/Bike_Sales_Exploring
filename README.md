# Bike_Sales_Exploring

IHi! It was my unspectacular idea to create my first pet-project, when I saw this dataset about sales. I will explain you the purpose of my discovering and what conclusions we can get. Let`s have a fun!

Goals: explore data about bike sales, detect key trends, select the most profitable segments and get valuable recomendations.

Steps of the project and main tasks:
1. Data Cleaning & Preparation:
   - Data download: get bike_sales.csv file in Pandas DataFrame;
   - Clearing the columns: remove superfluous signs and symbols;
   - Data type conversion: make sure columns have the appropriate data types;
   - Convert missed values: check and process it.
2. Exploratory Data Analysis (EDA):
   - Overview Analysis: generate summary statistics for numeric columns;
   - Profitability Analysis: calculate total profit, average profit per order, visualize profit distribution;
   - Demographic Analysis: Profit by Age Group: Which age group (Age_Group) generates the most profit?
   - Geographic Analysis: top 10 Countries by Total Revenue/Profit (Country), analysis of the states/regions in the most profitable country.
3. Sales and Product Analysis:
   - Product Analysis: which product category (Product_Category) is the most popular (by Order_Quantity)? Which product category is the most profitable (by Profit)?
   - Time Series Analysis: sales Seasonality - plot a graph of total revenue/profit by month (Month) or year (Year) to identify seasonal peaks; compare sales between different years.
4. Visualization & Reporting:
   - Use libraries like Matplotlib, Seaborn, or Plotly to create visualizations that clearly answer the questions asked;
   - Format the results as a Jupyter Notebook with markdown explanations or create a mini dashboard if you use Plotly/Dash.
