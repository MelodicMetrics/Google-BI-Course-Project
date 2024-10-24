# Google BI Course Project

## Overview:
This project was completed as part of the Google Business Intelligence course. The goal of this project was to analyze call trends and provide actionable insights on repeat calls and infrastructure issues across multiple markets.

## Tools Used:
- Tableau
- SQL

## Project Structure:
- `/data/datasets`: Contains the datasets used
  - `Market_1 - market_1.csv`: Dataset for Market 1 Call Data
  - `Market_2 - market_2.csv`: Dataset for Market 2 Call Data
  - `Market_3 - market_3.csv`: Dataset for Market 3 Call Data
  - `Unioned Markets Through BigQuery.csv`: Combined dataset from all markets (after union operation)
- `/scripts`: BigQuery SQL scripts used for data transformation and analysis
  - `union_datasets.sql`: SQL query used to union the datasets across Market 1, Market 2, and Market 3
- `/insights`: Executive summary and key findings
  - `Google_Fiber_Presentation_Slides.pdf`: Executive summary slide deck with key insights and recommendations from the project.
- `/docs`: Contains key project documents
  - `dashboard_details.pdf`: Breaks down details of the dashboard and its functionality
  - `strategy_document.pdf`: Outlines the basic strategy used when creating visualizations
  - `stakeholder_requirements.pdf`: Outlines the business problem to be solved along with key stakeholders and their requirements for the final dashboard
  - `project_requirements.pdf`: Outlines the purpose of the project along with criteria of success


## Dashboard Documentation
For a more detailed breakdown of the dashboard's insights, features, tabs, and drill-down functionality, refer to the following document:
- [Dashboard Details PDF](./docs/dashboard_details.pdf)

## Key Insights:
- Problem Type 5 (Internet/WiFi Issues) saw a significant 21.24% increase in first repeat calls from January to February, despite an 8.18% decrease in initial calls. This suggests ongoing infrastructure challenges leading to unresolved customer issues.
- Market 1 had the highest volume of Technician Troubleshooting (Problem Type 2) calls. However, Problem Type 5 (WiFi issues) accounted for a growing percentage of repeat calls, highlighting the need for both infrastructure improvements and enhanced technician training and processes to resolve issues on the first contact.
- Market 3 consistently had Problem Type 5 (Internet/WiFi Issues) as the dominant cause for both initial and repeat calls, further reinforcing the need for infrastructure upgrades in this market.
- Midweek Trends: Call volumes on Wednesdays and Thursdays increased over time, with Wednesday surpassing Monday as the peak call day by March. This suggests a potential need for resource reallocation during midweek to manage call volumes more effectively and prevent repeat calls due to staffing shortages.

## Link to Tableau Dashboards:
- [Tableau Public Dashboard: Google Fiber Q1 Call Trends and Analysis](https://public.tableau.com/views/CourseProjectGoogleFiberRepeatCallTrendsandInsights/Tables?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## How to Use:
To explore the data, open the datasets in the `/data/datasets` directory. You can also view the SQL script used to union the datasets together in the `/scripts` directory. The Tableau dashboards linked above provide visual analysis with drill-down functionality, allowing users to explore detailed insights by market and problem type.

## Call to Action
Feel free to explore the data and dashboard, or reach out if you have any questions or feedback on the analysis!

- You can contact me at: [Email](mailto:miles.databi@gmail.com).
- Connect with me on [LinkedIn](https://www.linkedin.com/in/miles-m-davidson)!

Thank you for taking the time to explore my project!


