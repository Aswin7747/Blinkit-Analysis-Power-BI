
# Blinkit Analysis

## Problem Statement

Blinkit seeks to optimize its grocery business operations and enhance customer satisfaction by leveraging data insights. The project aims to analyze key performance indicators, including total sales, average sales, average product ratings, and item distribution, while providing detailed visualizations of sales trends segmented by factors such as fat content, item type, outlet establishment year, outlet size, and location. The goal is to uncover patterns and inefficiencies, enabling informed decision-making to boost sales, improve inventory management, and refine outlet performance across different types and sizes.


### Steps followed 

Data Collection and Preparation:

1. Imported Blinkit grocery dataset into Power BI.
Cleaned and transformed the data by removing duplicates, handling missing values, and formatting columns for consistency.
Created calculated columns and measures for metrics such as total sales, average sales, number of items sold, and average rating.

2. Defining Business Requirements:Mapped key business requirements to specific metrics and visualizations.
Designed the project to address total sales, average sales, number of items, average rating, and other KPIs based on outlet type, location, and establishment details.
Data Modeling:

3. Established relationships between tables to create a unified data model.
Used DAX formulas to calculate measures such as:
Total Sales = SUM(Sales)
Average Sales = AVERAGE(Sales)
Total Items = COUNT(Items)
Average Rating = AVERAGE(Rating)
Visualizations and Dashboards:

4. Created charts and graphs to visualize business insights:
Total Sales by Fat Content: Used bar or column charts to show sales distribution across fat content categories.
Total Sales by Item Type: Created a category-wise breakdown of sales using a stacked bar chart or pie chart.
Fat Content by Outlet for Total Sales: Visualized using a clustered bar chart or a matrix table.
Total Sales by Outlet Establishment: Used a line chart or bar chart to analyze performance across outlet establishments.
Sales by Outlet Size: Represented using treemaps or bar charts.
Sales by Outlet Location: Illustrated through geographic maps or clustered column charts.
All Metrics by Outlet Type: Created a dashboard with KPIs and aggregated metrics, combining slicers for interactive filtering.
Interactive Features:

5. Added slicers for filtering by fat content, item type, outlet location, and establishment type.
Enabled drill-through and drill-down options to explore detailed insights from summary views.
Testing and Validation:

6. Cross-verified the calculated metrics against the source data to ensure accuracy.
Tested all visualizations for responsiveness and correctness of filters.
Dashboard Finalization:

7. Organized all visualizations into a cohesive and user-friendly dashboard.
Used consistent color schemes and labeled charts clearly for better readability.


 
 # Report Snapshot (Blinkit Analysis)

 
![Dashboard_upload]![Screenshot 2024-12-13 203807](https://github.com/user-attachments/assets/897d131a-eb38-4fa0-8905-591f70562e24)

# Insights


### [1]  Total Sales & Average Sales
Insight: Outlets with larger establishment sizes consistently show higher total sales, indicating a correlation between outlet size and revenue potential.

Actionable Point: Consider expanding high-performing outlets to maximize revenue potential.
           
### [2]  Sales by Fat Content & Item Type
Insight: Low-fat items have higher total sales compared to regular-fat items, especially in health-conscious regions or urban areas.

Actionable Point: Promote low-fat and health-focused products through targeted marketing campaigns.

Insight: Beverage and packaged food items are the highest-selling categories across all outlet types.

Actionable Point: Focus inventory and promotions on these top-performing item types.

  ### [3]  Average Ratings
Insight: Outlets with higher average ratings often align with high sales volumes, suggesting that customer satisfaction is a strong driver of repeat business.

Actionable Point: Invest in improving customer service and product quality in underperforming outlets.

 ### [4]  Fat Content by Outlet for Total Sales
Insight: Outlets in urban locations show a balanced demand for both low-fat and regular-fat products, while rural outlets have a preference for regular-fat items.

Actionable Point: Tailor inventory based on location-specific preferences to optimize sales.
 
  ### [5] Total Sales by Outlet Establishment
Insight: Older outlets with more established customer bases tend to outperform newer ones in sales, suggesting the value of brand loyalty over time.

Actionable Point: Implement strong launch strategies for new outlets to build awareness quickly

 ### [6] Sales by Outlet Size & Location
Insight: Medium-sized outlets strike a balance between operational cost and revenue generation, often outperforming both small and very large outlets in cost-efficiency.

Actionable Point: Replicate the medium-sized outlet model in areas with similar demographics.

Insight: Sales are highest in metropolitan areas due to higher population density and purchasing power.

Actionable Point: Expand operations into other high-density urban locations to capture untapped demand.


 ### [7]Metrics by Outlet Type
Insight: Supermarket-type outlets consistently lead in all metrics, including sales, average ratings, and number of items sold, compared to convenience stores.

Actionable Point: Focus on opening more supermarket-style outlets in prime locations

 
