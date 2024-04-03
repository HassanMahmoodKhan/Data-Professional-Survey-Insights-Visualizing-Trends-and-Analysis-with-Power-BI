# Data-Professional-Survey-Insights-Visualizing-Trends-and-Analysis-with-Power-BI

## Overview

This repository contains a comprehensive data analytics project focused on the analytical examination of a survey containing candidate feedback across professional occupations. The project utilizes Extract-Load-Transform (ELT) processes. Data, stored in Excel workbooks is extracted and loaded onto Power BI for transformation and analysis, culminating in the creation of a detailed and interactive dashboard.

## Project Structure

### 1. Extract and Load

The raw data, stored in the form of a table in an excel workbook file. The folder structure and its contents is as described below: 
- Folder: `data`
  - Contains the `Data Professional Survey` table for global respondents.
 The workbook is loaded onto the Power BI Desktop application using the `import` data option.

### 2. Transform
This step involves applying transformations directly within Power BI using the `Query Editor` tool. The editor provides a robust set of data transformation capabilities to clean, reshape, and enrich your data before it is loaded into the Power BI model. The steps involved are described below:
1) **Promoted Headers**: The top row was selected to reflect the header of the table.
2) **Removed Redundant Rows**: Removed rows that did not belong to any record to clean the dataset.
3)  **Datatype Conversion**: Converted datatype based on the column type, i.e., text to whole numbers, datetime, etc.
4)  **Split Columns**: Split a column into multiple columns based on delimiters such as underscore, comma, etc., for breaking down combined information into individual components.
5)  **Deleting Redundant Columns**: Removed columns that were no longer required.
6)  **Renaming Columns**: Renamed columns to provide more meaningful and concise names.
9)  **Custom Columns**: Created new columns based on specified conditions for introducing calculated columns such as the avergae salary category to cutail yearly salary range to a single value.

### 3. Analysis and Insights

The objective of this project is to conduct a comprehensive analysis of survey data collected from over 600 individuals representing diverse geographic locations and professional occupations. Over the course of several months, respondents have provided valuable insights through the survey, offering a rich dataset for analysis. The goal is to utilize advanced modeling and visualization techniques, particularly leveraging Power BI, to uncover significant trends, patterns, and correlations within the dataset. By examining the responses from a wide range of participants, the analysis aims to provide actionable insights into the preferences, behaviors, salaries, and sentiments of data professionals worldwide. Ultimately, this analysis seeks to enhance our understanding of professional occupations on a global scale and inform strategic decision-making processes.

Here are a few key takeaways:
- A total of 630 participants (162 Female & 468 Male) with an average age of approximately 30 years.
- The highest number of respondents identify as `Data Analysts`, i.e., >60%. This is followed by others such as Data Scientists, Data Engineers, Students, Other, etc.
- These professionals belong to an array of industries, ranging from agriculture, healthcare, telecommunications, education, etc.
- The most in-demand and employed programming language is Python with more than 400 respondents choosing it as their `Favorite Programming Langauge`.
- Highest number of participants belong to `North America`, particluarly the United States i.e., 261.
- Salary statisfaction is only a meagre 4.27 out of 10, indicating unsatisfaction by and large.
- A similar statistic in noted for `work life balance`, reporting a score of 5.74.
  
### 4. Dashboard

 To access the Power BI report file that contains the data model, relationships, visualizations related to the final revenue analysis dashboard, please refer to the `reports` folder.
 
![dashboard thumbnail](https://github.com/HassanMahmoodKhan/Data-Professional-Survey-Insights-Visualizing-Trends-and-Analysis-with-Power-BI/assets/97694796/a5e2afa0-5c83-4748-920f-a70b1ae3e777)

### 5. Deployment

For deployment purposes, I have published the report using Power BI Desktop to the [Power BI App](https://app.powerbi.com/) which allows stakeholders to view and consume the report.

## Requirements

This section contains the requirements needed to run the report. Please refer to the list below:
- Microsoft Power BI Desktop
- Microsoft Power BI App Account
- Microsoft Excel

## License

This repository employs the Apache 2.0 license. For more information, please refer to the license.


