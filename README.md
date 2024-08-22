
# [Interactive Sales Dashboard](https://1drv.ms/x/s!AraNMyAmEUHuj2EfKCSuUBIYTxNA)

![image](https://github.com/user-attachments/assets/2b8e88bc-60fb-4eb0-9934-1de810efb554)


### Problem Statement

We aim to create a comprehensive sales dashboard using a provided dataset that includes order details, customer information, product categories, and sales data. The objective is to:

1. Visualize sales data by category, state, and time.
2. Identify the top-performing customers in terms of profit.
3. Analyze sales trends over months.
4. Present the number of unique customers over time.

### Data Cleaning Steps

1. **Convert Data into Table Format**:
   - Transform the dataset into a structured table format for better manipulation and analysis.

2. **Numerical Conversion**:
   - Convert `Sales`, `Profit`, and `Quantity` columns to numerical data types to facilitate calculations.

3. **Remove Decimal Points**:
   - Clean the `Quantity` column by removing any decimal points to ensure consistency in product counts.

4. **Sort Data Chronologically**:
   - Sort the `Order Date` column from oldest to newest to maintain temporal accuracy in analysis.

5. **Extract Year and Month**:
   - Add `Year` and `Month` columns by extracting the respective information from the `Order Date` column using the `=YEAR()` and `=MONTH()` functions.

6. **Check for Duplicates**:
   - Identify and remove any duplicate entries across all columns to ensure data integrity.

7. **Handle Missing Values**:
   - Check for blank spaces or missing values in the dataset and remove or impute them as necessary.

### Dashboard Insights

1. **Sales by Category**:
   - Analyze sales figures by product sub-category to identify the best and worst-performing product types. The funnel chart visualization helps in understanding the contribution of each sub-category to total sales.

2. **Profit Over Time**:
   - Visualize profit trends over time using a line chart. This analysis helps in identifying periods of high and low profitability, enabling strategic decision-making.

3. **Monthly Sales Analysis**:
   - Create a pivot table to summarize sales on a month-to-month basis. Use an area chart to illustrate sales trends, which can help in identifying seasonal patterns and planning inventory.

4. **Top 5 Profitable Customers**:
   - Identify the top 5 customers contributing the most profit. A pie chart can be used to represent the share of each top customer in total profit, providing insights into customer value.

5. **Sales by State**:
   - Summarize sales data by state and visualize it using a map chart to understand regional sales performance and identify potential markets.

6. **Customer Count Over Time**:
   - Track the number of unique customers over time using a bar chart. This helps in understanding customer growth and retention trends.

--- 

You can access the [Interactive Sales Dashboard here](https://1drv.ms/x/s!AraNMyAmEUHuj2EfKCSuUBIYTxNA) for a detailed exploration of the data.
