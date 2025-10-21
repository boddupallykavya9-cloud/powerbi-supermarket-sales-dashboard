# Supermarket Sales Dashboard – Data Visualization and Storytelling (Power BI)

## Project Overview

**Objective:** Create an informative Power BI dashboard that visualizes sales performance, product line contributions, and customer behavior to tell a clear business story.

**Dataset:** Supermarket Sales (downloaded from Kaggle). Includes fields like Branch, City, Product Line, Product, Quantity, Total, Date, Payment Method, Rating, etc.

**Deliverables:** Power BI file (.pbix), exported PDF or dashboard screenshots, dataset CSV, and README with methodology and insights.

## Dataset Description

**Source:** Kaggle – Supermarket Sales

**Key fields :**

*   Date, Month/Day
*   Branch, City
*   Product Line, Product
*   Quantity, Unit Price, Tax, Total
*   Payment Method, Customer Type, Gender
*   Rating

**Data assumptions:** Ensure date parsing is correct; handle missing values if any; verify data types (numeric vs categorical).

## Methodology

1.  **Data Loading and Cleaning:**
    *   Import the `supermarket_sales.csv` dataset into Power BI.
    *   Validate data types and address any inconsistencies.
    *   Handle missing values (if any) by dropping rows or imputing as appropriate.
    *   Ensure date parsing is correct for time-based analysis.
    *   Clean column names for consistency and ease of use.

2.  **Data Modeling :**
    *   Establish relationships between tables if using multiple data sources (not applicable in this case with a single CSV).

3.  **Data Analysis:**
    *   Calculate key metrics such as Total Sales, Average Rating, and Total Quantity.
    *   Analyze sales performance by Branch and City.
    *   Identify the contribution of different Product Lines to overall sales.
    *   Analyze sales trends over time using the Date field.
    *   Explore relationships between Rating and Total Sales.
    *   Analyze customer behavior based on Customer Type and Gender.

4.  **Data Visualization:**
    *   Create the planned visuals in Power BI:
        *   Bar chart: Total Sales by Branch
        *   Bar/Column chart: Total Sales by City
        *   Donut/Pie chart: Sales share by Product Line (or Payment Method)
        *   Line chart: Sales trend over Date
        *   Column chart: Quantity sold by Product Line
        *   Scatter plot: Rating vs Total Sales
        *   Card visuals for key metrics (Total Sales, Average Rating, Total Quantity)
    *   Ensure clear and concise titles, data labels, and legends for each visual.
    *   Utilize tooltips to provide additional context on hover.

5.  **Storytelling and Insights:**
    *   Add text boxes to provide a narrative or key takeaway near each visual.
    *   Include a prominent summary box with high-level findings and implications from the analysis.
    *   Structure the dashboard to tell a clear business story about the supermarket's sales performance, product contributions, and customer insights.

## Key Insights 

*   Cairo branch leads in overall sales
*   Home and Electronics product lines drive the majority of revenue
*   Positive correlation between higher ratings and sales in key categories
*   Time trends show seasonal patterns with notable spikes on peak days
*   Suggested actions: target top-performing branches, focus promotions on strongest product lines, consider customer feedback linked to ratings

## How to Use

1.  Ensure you have Power BI Desktop installed.
2.  Download the `supermarket_sales.csv` dataset.
3.  Open the `.pbix` file in Power BI Desktop.
4.  Refresh the data source if prompted (ensure the CSV file path is correct).
5.  Explore the different visuals and text boxes to understand the sales performance and insights.

## File Structure

*   `project/`: Project root directory
    *   `data/`: Contains raw dataset
        *   `supermarket_sales.csv`: The dataset used for the report.
    *   `reports/`: Contains Power BI file and exported report
        *   `supermarket_sales.pbix`: The Power BI report file.
        *   `supermarket_sales_report.pdf`: Exported visual representation of the dashboard.
    *   `screenshots/`: Contains dashboard captures
    *   `README.md`: This file, providing an overview of the project.
    *   `insights.txt`: (Optional) Succinct findings

## How to Reproduce

**Step-by-step:**

1.  Load dataset into Power BI
2.  Create visuals as listed above
3.  Add titles, labels, tooltips, and narrative text
4.  Build a summary text box with key insights
5.  Export to PDF (Report > Export > PDF)
6.  Prepare GitHub repo with pbix, CSV, PDF, and README

## Validation and Quality Checks

*   Ensure all visuals convey a single clear message
*   Check for clutter; remove unused fields
*   Confirm drill-down and filters work as intended (Branch, City, Product Line, Date)
*   Verify that the summary reflects what’s shown in the visuals
