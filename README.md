# Power BI Sales Dashboard - Locard Stores

## Description
This project visualizes sales trends, customer segmentation, and product performance using Power BI. It highlights actionable insights to help businesses drive growth by analyzing key metrics such as total sales, regional performance, and product category breakdowns. The dashboard is interactive, allowing users to explore the data by selecting different regions, time periods, and product categories.

## Dataset
The dataset used in this project contains 9,800 records of sales data, including columns such as:
- **Date**
- **Sales Amount**
- **Region**
- **Product Category**
- **Customer Segment**

The dataset was preprocessed using Power BI's Query Editor to clean, transform, and shape the data for analysis. This includes:
- Removing duplicate records.
- Handling missing or inconsistent data.
- Creating calculated columns and measures for advanced analysis (e.g., Year-over-Year growth, regional sales performance).

The data is simulated for the purpose of this project but closely resembles real-world sales data.

## Skills Demonstrated
This project demonstrates the following Power BI skills:
- **Data Modeling**: Creating relationships between tables, managing schema, and optimizing for performance.
- **DAX (Data Analysis Expressions)**: Writing complex DAX measures to calculate business metrics such as YoY growth and running totals.
- **Power Query**: Transforming and shaping raw data to create meaningful insights.
- **Interactive Visualizations**: Building dynamic dashboards with slicers, filters, and drill-through capabilities.
- **Visualization Design**: Using charts, tables, and custom visuals to present insights effectively.

## Instructions
To view or use this project, follow these steps:
1. **Download the `.pbix` file** from this repository.
2. **Open the file in Power BI Desktop**:
   - If you don't have Power BI Desktop, download it from [here](https://powerbi.microsoft.com/desktop/).
   - Once opened, Power BI will load the dataset and generate the visualizations.
3. **Interact with the dashboard**:
   - Use slicers to filter the data by region, product category, and time period.
   - Hover over charts and tables to view additional details and metrics.

## Results

### Sales Overview
![Sales Overview](images/sales-overview.png)  
This is the main screen of the dashboard, displaying a summary of total sales, regional performance, and a breakdown of sales by product category. The key metrics can be filtered by time (monthly, quarterly, yearly).

### Regional Sales Performance
![Regional Sales](images/regional-sales.png)  
This visual displays sales performance across different regions. Users can select specific regions to get a detailed view of performance by product category and sales volume.

### Product Category Breakdown
![Product Category Breakdown](images/product-category.png)  
This chart provides an overview of sales by product category, showing which products contribute the most to overall revenue.

### Key Metrics
![Key Metrics](images/key-metrics.png)  
This section of the dashboard highlights key performance indicators (KPIs) such as total sales, growth rates, and top-performing regions.

## Key Insights
From analyzing the dashboard, the following key insights were discovered:
1. **Regional Performance**: The North region consistently outperforms other regions in terms of total sales, with a 15% YoY growth. This suggests that marketing and sales efforts in this region may be more effective.
2. **Product Category Insights**: The "Electronics" category shows the highest sales growth, with a 20% increase compared to the previous year. This category has become a key revenue driver.
3. **Seasonal Trends**: The dashboard reveals a noticeable spike in sales during Q4 (October to December), likely due to holiday shopping. Businesses can use this information to adjust inventory and marketing strategies for the upcoming year.

## How to Contribute
Feel free to fork this repository and make improvements. If you have suggestions for new features or visualizations, create an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


