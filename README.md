# Financial Performance Analysis

## Overview
This Power BI project focuses on analyzing the financial performance of a company across various countries and products. The goal is to identify key trends, profitability, and areas for improvement to optimize business strategies.

## Tools and Technologies
- **Power BI**: For data visualization and dashboard creation.
- **Power Query**: For data cleaning and transformation. Created a date table using the advanced editor (M language) and established relationships with the original dataset.
- **DAX**: For creating calculated columns and measures, including:
  - `Total Sales`
  - `Total COGS (Cost of Goods Sold)`
  - `Total Margin`
  - `Profit %`
  - `Average Orders`

## Dataset
- **Source**: Internal company database.
- **Description**: The dataset contains financial data with columns such as `Country`, `Product`, `Segment`, `Discount Band`, `Sales`, `COGS`, `Date`, and `Profit`.

## Steps
1. **Data Cleaning**:
   - Handled missing values and removed duplicates using Power Query.
   - Created a date table using M language for time-based analysis.
2. **Data Modeling**:
   - Established relationships between the date table and the main dataset.
3. **DAX Calculations**:
   - Created measures for `Total Sales`, `Total COGS`, `Total Margin`, `Profit %`, and `Average Orders`.
4. **Visualizations**:
   - Designed interactive charts, including:
     - Column chart for sales by country.
     - Donut chart for sales by discount band.
     - Line chart for sales trends over time.
     - Area chart for sales vs. COGS by date hierarchy.
5. **Dashboard**:
   - Combined visuals into a user-friendly dashboard with slicers for `Country`, `Segment`, `Product`, `Discount Band`, and `Date`.

## Key Insights
- **Loss in Enterprise Sales**: Identified that selling products through the Enterprise segment resulted in losses.
- **High Sales Volume through Government**: Government channels contributed the highest sales volume.
- **Top-Selling Product**: "Paeso" is the highest-selling product in the company.

## Screenshots
![Dashboard Screenshot](./images/dashboard.png)

## How to Use
1. Download the `.pbix` file.
2. Open it in Power BI Desktop.
3. Explore the dashboard and interact with slicers for `Country`, `Segment`, `Product`, `Discount Band`, and `Date`.

## License
This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
