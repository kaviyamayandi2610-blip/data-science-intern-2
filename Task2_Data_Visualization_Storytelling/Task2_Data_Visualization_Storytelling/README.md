# Task 2 – Data Visualization and Storytelling

## Objective
Create visualizations that convey a compelling business story using sales data.

## Tools
- Power BI or Tableau
- Dataset: `dataset/Superstore_Sales.csv`

## Dashboard KPIs
- Total Sales: $154,820
- Total Profit: $23,464
- Profit Margin: 15.2%
- Total Quantity: 1,295
- Total Orders: 240

## Recommended Dashboard Visuals
1. KPI Cards – Sales, Profit, Profit Margin, Quantity, Orders
2. Line Chart – Monthly Sales Trend
3. Bar Chart – Sales by Region
4. Bar Chart – Sales by Category
5. Bar Chart – Profit by Category
6. Slicers – Date, Region, Category, Segment

## Business Story
- East is the highest-sales region.
- Technology is the highest-sales category.
- Furniture has the lowest total profit and should be reviewed.
- The monthly trend helps identify strong and weak sales periods.
- The dashboard should focus on business decisions rather than decoration.

## Power BI Steps
1. Open Power BI Desktop.
2. Select **Get Data → Text/CSV**.
3. Load `dataset/Superstore_Sales.csv`.
4. Set `Order Date` to Date type and Sales/Profit to numeric.
5. Create KPI cards for Sales, Profit, Quantity and Orders.
6. Create a line chart with Month on X-axis and Sales on Y-axis.
7. Create bar charts for Region vs Sales and Category vs Sales.
8. Create a bar chart for Category vs Profit.
9. Add slicers for Date, Region, Category and Segment.
10. Arrange the visuals into one clean dashboard page.
11. Add a text box called **Key Business Insights**.
12. Export the report page as PDF or take dashboard screenshots.
13. Put the screenshots/PDF inside the `report` or `screenshots` folder.

## GitHub Structure
```text
Task2_Data_Visualization_Storytelling/
├── dataset/
│   └── Superstore_Sales.csv
├── report/
│   └── Task2_Visual_Report.pdf
├── screenshots/
│   └── (add your Power BI dashboard screenshot here)
└── README.md
```

## Interview Questions
### 1. What is the importance of data visualization?
Data visualization converts raw data into visual patterns so users can understand trends, comparisons, outliers and business performance quickly.

### 2. When do you use a pie chart vs bar chart?
Use a pie chart for a small number of parts-of-a-whole comparisons. Use a bar chart when comparing categories, especially when there are several categories or precise comparison matters.

### 3. How do you make visualizations more engaging?
Use a clear title, meaningful labels, limited colors, useful annotations, appropriate chart types and business-focused insights.

### 4. What is data storytelling?
Data storytelling combines data, visuals and context to communicate a clear message and support a business decision.

### 5. How do you avoid misleading visualizations?
Use appropriate scales, avoid unnecessary 3D effects, label axes clearly, provide context and avoid manipulating the visual range to exaggerate differences.

### 6. What are best practices in dashboard design?
Keep the layout simple, prioritize KPIs, use consistent formatting, avoid clutter, provide filters and make the main business message easy to find.

### 7. What tools have you used for visualization?
For this task, I used Power BI for dashboard design and a sales dataset for business analysis. The provided visual report is also included as a reference.

## Submission
Create a new GitHub repository for this task and upload the dataset, report, screenshots and README. Then submit the repository link.
