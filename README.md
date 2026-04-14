### Author: Dario Margeli
## Multi-Page Business Intelligence Report
### Sales & Customer Insights Dashboard using Microsoft Power BI
## Objective
This project analyzes sales and customer data to provide actionable insights for different business roles, including executives, managers, analysts, and sales teams. I turned raw data into useful insights for decision-making.

For someone at the analyst level, it offers granular-level details. They want to see tables or combo charts, a bit more complex, maybe a little bit more data heavy.

For the manager-level audience, the report offers more summarized data with a focus on clear and actionable insights to help them operate the business. For them, more common or basic charts and graphs are offered with some detail, but really only when they support a specific insight or recommendation.

The executive audience wants high-level, crystal clear KPIs that they can use to track business health and top-line performance at a glance. For this purpose, the report offers visuals like KPI cards and simple charts.

Role: transform raw data into reports and dashboards to help the management team track KPIs and find trends, identify high-value customers.

Project. You have been hired as a Business Intelligence Analyst. Your role: track KPIs - sales, revenue, profit, returns - analyze product trends.
## Dashboard Overview
The multi-page dashboard is structured into four dynamic interactive report pages, each designed for a specific purpose and audience, providing data visualization.

The dashboard allows end users and managers to explore and understand the data on their own. To help with exploration, for interesting patterns or trends, I’ve used a bookmark to draw attention to them and drive users to a pre-filtered view to help tell that story.

Here are the report pages in the dashboard:
### 1. Executive Dashboard
- High-level KPIs (Revenue, Profit, Growth)
- Trend analysis over time
- Key business insights for decision-making

Focus: quick, strategic overview for leadership with the goal to track KPIs.

The dashboard includes top-line KPI cards for the executives. In the left middle, there is a line chart showing revenue for managers. At the bottom, there is a table with the top ten revenue-driving products. There is a revenue trending line chart that shows data over time. There is a column chart visual comparing categories. It allows us to segment the data by category in the report.

Navigation buttons & bookmarks are provided to allow users to go to additional pages.
### 2. Geographic Analysis (Maps)
- Sales distribution by region
- Regional performance comparison
- Identification of high/low performing areas

Focus: location-based insights

This page of the report accommodates geospatial fields. Its goal is to compare regional performance.
### 3. Product Performance
- Sales and profit by product/category
- Top and bottom performing products
- Detailed breakdown for managers

Focus: Operational decision-making

Product details page: allows focusing on individual products. With DAX, we built: revenue targets, order targets, and profit targets. So we can use gauge charts to show product performance against those targets. It has trending views for revenue, profit, and return rates. The idea is to show product-specific details.

The ability to drill up & down has been included in this page, allowing users to drill up and down to see daily, weekly, and monthly data.

![Executive Dashboard](images/drill2026-04-13155432.jpg)

The goal of this page of the report is to analyze product-level trends.
### 4. Customer Insights
- Customer segmentation
- Purchase behavior analysis
- Key metrics related to customer activity

Focus: Understanding customer trends and behavior

In the customer’s page of the report, I show high-level metrics, such as total customers. I show orders and revenues per customer. In this page of the report, it is possible to do composition analysis because it has categorical fields with customer demographics, like income level, gender, age, and education level. A donut chart has been used to visualize that. A trending view of total customers is present. To identify individual high-value customers, there is a table/matrix with the top-end customers.

Composition: used to break down the parts of a whole. Common visual: pie chart

This page of the report’s goal includes identifying high-value customers.
## Skills & Tools Used
With Data Analytics, Data Science & Business Intelligence skills, I used Power BI desktop to perform the entire business intelligence workflow listed in these steps:

- Understood business requirements. I learned to use Power BI to solve real business problems.

- In this phase of the business intelligence workflow, I connect to the source files, shape, and transform the raw data using Power Query. Performed ETL to extract, transform, clean, and load that data to prepare it for analysis. In some cases, data had to be merged and appended to prepare it for analysis. Tables are transformed.

- Data Modeling (relationships, schema design). In this phase, I took the data source and built a relational data model inside of Power BI's model view in the front end of Power BI by creating table relationships between primary and foreign keys. I implemented cardinality and normalization. This relational data model blends data from multiple sources. I have been able to create table relationships that allow for analyzing performance. One popular model schema is the star schema. It has a single fact table, also called a data table. All other tables are lookup tables, also called dimension tables. Each of the lookup tables connects directly to the single data table.

- DAX (calculated measures, KPIs): Created calculated columns and measures using DAX - Data Analysis Expressions in the Data view/Table view of the interface of the front end of Power BI. Data view is part of the front end of Power BI. Added new formula-based columns to tables. Measures are DAX formulas used to generate new calculated values. Measures aren't visible within a table. They can only be seen within a visual, such as a chart or matrix. I used measures to create numerical, calculated values that can be analyzed in the values field of a report visual. In Power BI, measures are used to calculate sums, averages, minimums, maximums, and counts. In summary, when creating an aggregate value. Explicit measures are created when you write a DAX formula. Explicit measures can be used anywhere in the report. They can be used in other measures.
  
- Data Visualization & Dashboard Design: created Business Intelligence dynamic dashboards and reports that include charts and visuals. They are interactive and allow visualizing the data. This is done in the report view of Power BI. I constructed visuals that show how a product performed against its targets.
## Dashboard Preview

- Screenshots of the dashboard and report pages.

![Executive Dashboard](images/screenshot%202026-04-14131322.jpg)

![Executive Dashboard](images/screenshot%202026-04-14131420.jpg)

![Executive Dashboard](images/screenshot%202026-04-14131525.jpg)

![Executive Dashboard](images/screenshot%202026-04-14131627.jpg)

![Executive Dashboard](images/screenshot%202026-04-14131628.jpg)

![Executive Dashboard](images/screenshot%202026-04-14143852.jpg)

![Executive Dashboard](images/screenshot%202026-04-14144412.jpg)

![Executive Dashboard](images/Screenshot%202026-04-14144622.jpg)

![Executive Dashboard](images/screenshot%202026-04-14144623.jpg)

![Executive Dashboard](images/screenshot%202026-04-14145135.jpg)

## Overview
This is my portfolio project. I created it while studying the course:

Microsoft Power BI Desktop for Business Intelligence

This is a project-based course that simulates real-world scenarios. It is designed by Maven Analytics mavenanalytics.io. They help professionals build practical data skills in analytics, business intelligence, and data science.

Course URL with the list of chapters:

https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/

My earned certificate URL

https://www.udemy.com/certificate/UC-e81b076a-b41d-4e0f-93f8-63747e8dd4b1/

During the course, in the role of Business Intelligence Analyst, I built professional-quality business intelligence reports from the ground up. I learned to blend and transform raw data into beautiful interactive visuals & dashboards. I have learned the tools used by professional data analysts and data scientists. I used advanced data analysis & visualization techniques.

Power BI is the number one business intelligence platform for data professionals. It includes applications for connecting, modeling, and visualizing data.

## License

This project is shared for portfolio and demonstration purposes only.

© 2026 Dario Margeli. All rights reserved.

No part of this project may be copied, modified, or redistributed without permission.
