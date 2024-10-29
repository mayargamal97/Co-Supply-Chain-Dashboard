# CO Supply Chain Dashboard

This repository contains a Power BI dashboard designed to provide an in-depth overview of the CO Supply Chain, covering metrics like revenue, order quantity, profit, delivery status, and much more. The data used here is modeled and visualized to support strategic decision-making in supply chain management.

![Screenshot (133)](https://github.com/user-attachments/assets/a33e843c-2deb-4ab6-a2b4-e37255b68fed)

## Dashboard Overview

The dashboard is structured to present key metrics and detailed analyses in a user-friendly manner:

- **Total Revenue**: Displays the cumulative revenue generated, aiding in financial assessment.
- **Total Quantity**: Shows the total quantity of items ordered, helping track volume trends.
- **Total Orders**: Gives an overview of the total orders processed.
- **Total Profit**: Highlights the total profit made, providing insight into profitability.
- **Late Delivery Risk**: A KPI for late delivery percentage, assisting in monitoring delivery efficiency.

### Visual Breakdown

1. **Sales Percentage by Order Country**: Visualizes the percentage distribution of sales across different countries, giving insight into market performance by location.

2. **Total by Customer Segment and Order City**: Shows sales distribution across customer segments (e.g., Consumer, Corporate, Home Office) and major cities, highlighting segment-specific performance.

3. **Sales Percentage by Delivery Status**: A pie chart that categorizes sales by delivery status (late, on time, advance, etc.), indicating delivery reliability.

4. **Total by Month**: A line chart that displays sales over the months, enabling trend analysis across the year.

5. **Total by Department Name**: Compares sales across different departments, showing which department generates the highest revenue.

6. **Total by Category Name**: A bar chart depicting revenue across product categories, such as Fishing, Cleats, Apparel, etc., providing insight into category-level performance.

### Data Model

The data model integrates multiple tables (e.g., `order_details`, `supplychain`, `categoryinfo`, `departments`, `Calendar`) to enable efficient data analysis. 

![Screenshot (135)](https://github.com/user-attachments/assets/058a9203-e2e0-4d05-8902-db0b1f478171)

### Technical Details

This dashboard leverages the following key Power BI features:

- **Data Analysis**: Utilized various analytical techniques to extract actionable insights from raw data.
- **Data Modeling**: Built a robust data model, connecting multiple tables with relationships to support cohesive data analysis.
- **Data Integration**: Integrated data from diverse sources into a single, cohesive model.
- **Data Visualization**: Used visual elements (line charts, bar charts, pie charts) to present data intuitively.
- **DAX (Data Analysis Expressions)**: Employed DAX functions for complex calculations and measures.
- **Power Query**: Transformed and cleaned data in Power Query before loading it into the model.

This Power BI dashboard combines powerful tools and methodologies to deliver a comprehensive view of the supply chain, allowing users to monitor key performance indicators and make data-driven decisions.

---

Feel free to explore and reach out with any questions or suggestions!
