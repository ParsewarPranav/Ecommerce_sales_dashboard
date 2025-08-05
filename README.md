
# E-commerce Sales Dashboard 📊
**Project Overview**
This project involves the development of an interactive E-commerce Sales Dashboard using Power BI. The dashboard aims to provide comprehensive insights into sales performance, profitability, customer behavior, and product trends from raw transactional and order data. It serves as a vital tool for data-driven decision-making, helping stakeholders understand key business metrics at a glance.

**Features**
Key Performance Indicators (KPIs): Displays total sales amount, profit, quantity, and average order value.

Customer Performance: Identifies top customers by sales amount.

Product Analysis: Visualizes profit distribution across product sub-categories and quantity distribution by main categories.

Geographical Insights: Shows sales performance across different states.

Time-Series Trends: Tracks monthly profit trends to identify seasonal patterns.

Interactive Filters: Allows dynamic filtering by Quarter and State for granular analysis.

**Data Sources**
The dashboard utilizes two primary datasets:

Details.csv: Contains transactional details including Amount, Profit, Quantity, Category, Sub-Category, and PaymentMode.

Orders.csv: Provides order-specific information such as Order Date, CustomerName, State, and City.

These datasets were merged and transformed in Power BI to create a unified data model.

**Tools Used**
Microsoft Power BI Desktop: For data modeling, visualization, and dashboard creation.

Power Query Editor: Used for data loading, cleaning, transformation, and merging.

DAX (Data Analysis Expressions): Utilized for creating calculated measures and columns to enhance the data model.

How to Use/View the Dashboard
To view and interact with this dashboard:

Download Power BI Desktop: Ensure you have Power BI Desktop installed on your system.

Clone this Repository: Get a copy of this project's files.

Open the .pbix file: Locate and open the E-commerce Sales Dashboard.pbix (or similar name) file in Power BI Desktop.

Interact: Once opened, you can use the slicers and filters on the dashboard to explore the data dynamically.

**Key Insights**
The dashboard provides several actionable insights, including:

Overall Performance: Quick overview of total sales, profit, and quantity.

Top Customers: Identification of high-value customers for targeted engagement.

Profitability Drivers: Understanding which product sub-categories contribute most to profit.

Product Mix: Clear distribution of sales quantity across major product categories (e.g., Clothing being dominant).

Regional Performance: States like Maharashtra showing leading sales figures.

Seasonal Trends: Monthly profit analysis revealing peak and lean periods, useful for strategic planning.

Setup Instructions (for Power BI Desktop)
Data Loading: The Details.csv and Orders.csv files are loaded into Power BI.

# Data Transformation (Power Query):

Merged Details and Orders tables on Order ID.

Converted Order Date column to Date data type.

(Add any other specific transformations you did, e.g., handling nulls, creating custom columns in Power Query).

Data Modeling: Established a relationship between the merged table and any other lookup tables if applicable.

DAX Measures/Calculated Columns:

(List any specific DAX measures or calculated columns you created, e.g., Total Sales = SUM('Details'[Amount]), Profit Margin = DIVIDE(SUM('Details'[Profit]), SUM('Details'[Amount])))

(Example: Quarter = FORMAT('Orders'[Order Date], "Qtr q"))

(Example: Month Name = FORMAT('Orders'[Order Date], "mmmm"))

Visualizations: Created various charts (bar charts, column charts, donut charts) and KPI cards as seen in the dashboard screenshot.

# Challenges and Learnings
Data Consistency: Ensuring consistent date formats across datasets was crucial for accurate time-series analysis. This was addressed using Power Query transformations.

Data Merging: Successfully merging two distinct datasets (Details.csv and Orders.csv) based on a common key (Order ID) was a foundational step, ensuring all relevant information was available for analysis.

**DAX Complexity**: Developing specific DAX measures for aggregated metrics required careful consideration of calculation contexts and filter propagation.

# Future Enhancements
Advanced Filtering: Implement more granular filters, such as by specific product, payment mode, or customer segments.

Predictive Analytics: Integrate sales forecasting models to predict future sales and profit trends.

What-If Analysis: Add parameters to allow users to simulate different scenarios (e.g., impact of price changes on profit).

Additional Data Sources: Incorporate marketing spend data, website traffic, or customer demographics for a more holistic view.

Contact
For any questions or feedback, please feel free to reach out.

Author: [Pranav Parsewar
        https://github.com/ParsewarPranav ]
