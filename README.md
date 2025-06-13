 Sales Dashboard Design

## Project Overview

This project was completed as part of Task 8 in the Data Analyst Internship Program. The objective was to create a simple yet effective interactive sales dashboard that visualizes key business metrics such as sales, profit, product performance, and regional performance. The dashboard was created using Power BI.

---

## Dataset Description

The dataset used for this task was custom-generated to simulate Superstore-like sales data. It contains transactional sales data across various regions, product categories, and order dates.

| Column Name | Description |
|--------------|-------------|
| Order ID | Unique order identifier |
| Order Date | Date of the order |
| Region | Sales region (North, South, East, West) |
| Category | Product category (Furniture, Technology, Office Supplies) |
| Product | Product name |
| Sales | Sales amount |
| Profit | Profit amount |

---

## Dashboard Components

The dashboard was built on a single page and includes the following visuals:

### 1. KPI Cards
- **Total Sales**: Sum of all sales transactions.
- **Total Profit**: Sum of all profit across orders.

### 2. Line Chart
- Displays sales trend over time (monthly basis).
- Axis: Order Date (formatted as Year-Month).
- Value: Total Sales.

### 3. Bar Chart
- Shows total sales segmented by Region.
- Axis: Region.
- Value: Total Sales.

### 4. Donut Chart
- Displays sales contribution by Category.
- Legend: Category.
- Value: Total Sales.

### 5. Slicers (Filters)
- Region (allows filtering dashboard by region).
- Category (allows filtering dashboard by category).

---

## Key Insights

- Sales and profits are consistently growing across months.
- Technology category contributed the highest share of sales.
- West and East regions showed stronger sales compared to others.
- Profitability varies significantly across both regions and product categories.

---

## File Deliverables

| File Name | Description |
|-----------|-------------|
| `superstore_sales_task8.csv` | Dataset used for dashboard creation |
| `task8_sales_dashboard.pbix` | Power BI dashboard file |
| `dashboard.png` or `dashboard.pdf` | Exported dashboard screenshot |
| `README.md` | This documentation file |

---

## Usage Instructions

1. Open Power BI Desktop.
2. Load `superstore_sales_task8.csv` using **Get Data → CSV** option.
3. Build visuals following the dashboard design described above.
4. Export the completed dashboard as an image (`dashboard.png`) or PDF (`dashboard.pdf`) for submission.

---

## Submission Instructions

- Upload all files to GitHub repository.
- Submit GitHub link via internship submission form.

---

## Author

Name: Adithyanandan
Email: adithya1422@gmail.com


---

## License

This project was submitted for educational and internship evaluation purposes only.
