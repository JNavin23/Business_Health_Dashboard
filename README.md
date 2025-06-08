# Business Health Check Dashboard

## Project Overview

This Power BI dashboard provides a comprehensive "Business Health Check" by visualizing key performance indicators (KPIs) and trends across various business dimensions. It's designed to offer quick, actionable insights into sales, profit, and customer performance, empowering data-driven decision-making.

## Key Features

* **Year-to-Date (YTD) Performance Monitoring:** Track Profit Performance YTD and Sales Performance YTD against predefined goals, with clear visual indicators for over/under performance.
* **Sales & Profit Trend Analysis:** Visualize yearly trends for both total sales and total profit to understand growth trajectories and identify patterns.
* **Category-wise Performance Breakdown:** Analyze total profit and total sales by product category, allowing for identification of top-performing or underperforming segments.
* **Top Customer Identification:** Easily identify the top 10 customers by profit, providing insights for customer relationship management and targeted strategies.
* **Dynamic KPI Cards:** Features interactive cards that dynamically display the selected category name and its corresponding total sales value based on user selections.
* **Interactive Filtering:** Utilize slicers for filtering data by `Region` and `Year` to enable detailed, drill-down analysis.


## Data Source

The dashboard utilizes sample Superstore sales and performance data, including sales, profit, quantity, and customer information.
* `0.xlsx` - An Excel file related to the project data.
* `Super_Store_sale.xlsx` - The primary sales data for analysis.

## How to Use

To interact with this dashboard:

1.  **Download the `.pbix` file:**
    * Navigate to the main repository page on GitHub.
    * Click on `Superstore performance.pbix` 
    * Click the "Download" button.
2.  **Open with Power BI Desktop:** Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed on your computer. Open the downloaded `.pbix` file using Power BI Desktop.
3.  **Interact with the Dashboard:**
    * Use the **Region** and **Year** slicers on the left to filter the data.
    * Click on bars in the **"Total Profit by Category"** chart or slices in the **"Total Sales by Category"** donut chart to dynamically update the related KPI cards and other visuals.
    * Hover over visuals to see tooltips with additional details.

## Installation / Setup (for Developers)

If you wish to explore the data model or make modifications:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/JNavin23/Business_Health_Dashboard.git](https://github.com/JNavin23/Business_Health_Dashboard.git)
    ```
2.  **Open the `.pbix` file:** Navigate to the cloned directory and open `Superstore performance.pbix` in Power BI Desktop.
3.  **Data Refresh:** The dashboard uses local Excel files. Ensure the Excel files (`0.xlsx`, `Super_Store_sale.xlsx`) are in the same directory as the `.pbix` file if you move it, or update the data source settings in Power BI Desktop if their location changes.

## Contact / Connect

**Name - Navin
Mail - Naveenjoshi272@gmail.com**
