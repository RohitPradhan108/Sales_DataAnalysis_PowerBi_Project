
# Sales Data Analysis Power BI Project

This project involves analyzing sales data for a fictional chocolate company, Awesome Chocolates, using Power BI. The dataset, organized in a star schema, was sourced from Chandoo.org and includes detailed information on shipments, products, locations, sales_person, and calendar. The analysis focuses on key business metrics like sales, profit, costs, and performance across various dimensions.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Dashboard Analysis](#dashboard-analysis)
- [Key Insights](#key-insights)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The **Sales Data Analysis Power BI Project** aims to provide actionable insights into the performance of Awesome Chocolates by analyzing sales data. The project includes data cleaning and the creation of an interactive Power BI dashboard to visualize key metrics such as total sales, profit, shipments, costs, and performance by salespersons, products, and regions.

## Dataset

The dataset, `chocolate_sales_data.xlsx`, is structured as a star schema and includes the following tables:

1. **Shipments:**
   - **Columns:** Sales Person, Geography, Product, Date, Sales, Boxes
2. **Products:**
   - **Columns:** Product, Category, Cost per box
3. **Locations:**
   - **Columns:** Geo, Region
4. **People:**
   - **Columns:** Sales person, Team, Picture
5. **Calendar:**
   - **Columns:** Date

## Data Cleaning

Data cleaning was performed to ensure accuracy and consistency across the dataset. Key steps included:

- Handling missing values
- Standardizing data formats (e.g., dates, currency)
- Ensuring data integrity across relationships in the star schema

## Dashboard Analysis

The cleaned dataset was used to create a comprehensive Power BI dashboard, which includes:

- **Total Sales:** Aggregated sales figures across different dimensions.
- **Total Profit:** Calculated as the difference between total sales and total costs.
- **Total Shipments:** Number of boxes shipped.
- **Total Costs:** Aggregated costs associated with sales.
- **Salesperson Performance:** Analysis of target achievements and profit percentage for each salesperson.
- **Month-on-Month Change:** Analysis of sales, profit, and shipment trends over time.
- **Geography Analysis:** Insights into sales and profit performance by region and country.
- **Product Category Analysis:** Insights into sales and profit performance by chocolate category.

## Key Insights

The Power BI dashboard provides several key insights, including:

- Top-performing regions and countries based on sales and profit.
- Best-selling chocolate categories.
- Salesperson performance, highlighting those who consistently meet or exceed targets.
- Trends in sales, profit, and shipments over time, with month-on-month comparisons.

## Getting Started

### Prerequisites

To run this project, you will need:

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- A spreadsheet application (e.g., MS Excel) for data review

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RohitPradhan108/Sales_DataAnalysis_PowerBi_Project.git
   ```

2. **Open the Power BI file:**

   Open the `.pbix` file in Power BI Desktop to explore the dashboard.

3. **Review the data:**

   Review the `chocolate_sales_data.xlsx` file to understand the structure and relationships within the dataset.

### Usage

- Use the Power BI dashboard to explore the data and gain insights into the performance of Awesome Chocolates.
- Modify the dashboard or dataset to conduct additional analyses or tailor it to different business scenarios.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [Chandoo.org](https://chandoo.org/wp/) for providing the dataset and making this project possible.
