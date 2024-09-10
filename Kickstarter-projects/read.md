
# Power BI Kickstarter data Project Documentation

## Project Overview
This project involves analyzing Kickstarter data to gain insights into crowdfunding trends and project success rates. 

[link of database](https://www.kaggle.com/datasets/kemical/kickstarter-projects/data)

The dataset includes various attributes such as project name, category, goal, pledged amount, and more.

## Steps to Complete the Project

### 1. Data Import and Preparation
1. **Import Data**: Load the Kickstarter dataset into Power BI.
   - Go to `Home` > `Get Data` > `Text/CSV` and select your dataset file.
2. **Data Cleaning**: Ensure the data is clean and ready for analysis.
   - Remove any duplicates.
   - Handle missing values appropriately.
   -concert data types as needed (e.g., dates, currency).

### 2. Data Transformation
1. **Create Calculated Columns**:
   - `usd_pledged_real`: Conversion of the pledged column into US dollars using Fixer.io API.
   - `usd_goal_real`: Conversion of the goal column into US dollars using Fixer.io API.
2. **Add New Columns**:
   - `Project Duration`: Calculate the duration of each project from the `launched` to the `deadline` date.

### 3. Data Modeling
1. **Relationships**: Define relationships between tables if you have multiple datasets.
   - Ensure that the relationships are correctly set up to enable accurate data analysis.

### 4. Data Visualization
1. **Create Dashboards**:
   - **Overview Dashboard**: Display key metrics such as total projects, total pledged amount, and success rate.
   - **Category Analysis**: Visualize the distribution of projects across different categories.
   - **Time Series Analysis**: Show trends over time, such as the number of projects launched per year.
   - **Geographical Analysis**: Use a map visualization to show project distribution by location.

### 5. Adding Interactivity
1. **Filters and Slicers**: Add filters and slicers to allow users to interact with the data.
   - Category filter.
   - Date range slicer.
2. **Drill-Through**: Enable drill-through functionality to allow detailed analysis of specific data points.

### 6. Publishing and Sharing
1. **Publish Report**: Publish the Power BI report to the Power BI service.
   - Go to `Home` > `Publish` and select your workspace.
2. **Share Report**: Share the report with stakeholders.
   - Provide access to the report through the Power BI service.
   - Embed the report in a website or SharePoint if needed.

### 7. Documentation
1. **Create README.md**: Document the project in a README.md file on GitHub.
   - Include project overview, dataset description, steps taken, and visualizations created.
2. **Screenshots**: Add screenshots of the Power BI dashboards to the README.md file for better understanding.

## Conclusion
This Power BI project provides a comprehensive analysis of Kickstarter data, offering valuable insights into crowdfunding trends. 

![tmp_8a374833-7e4a-4117-9258-89a068f41736](https://github.com/user-attachments/assets/98e7c1b7-ce68-44a6-aeed-0e083a61b338)
![tmp_120bc8c8-5d46-4f4c-b101-183286840843](https://github.com/user-attachments/assets/38646206-7f28-442a-8c1b-9cfb1da7c7b3)
