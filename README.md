# Parch and Posey Exploratory Data Analysis

This repository contains the exploratory analysis of the Posey database tables for CoreDataEngineers. The analysis aims to provide insights into the data to help our organization understand our competitor's market better. The insights were derived from multiple data tables, including sales, web events, accounts, and orders. This project is part of the group assignment for our data engineering bootcamp.

## Group Name: **[group2gitlinuxAssignment]**

### Group Members:
- **Lawal Kaosarah** - [GitHub Username](https://github.com/Kaosarah)
- **Eboaju Chioma** - [GitHub Username](https://github.com/chioma-eboaju-nebor)
- **Olugbenga Ajewole** - [GitHub Username](https://github.com/ajewoleOlugbenga)

## Project Overview
The objective of this project was to analyze the Posey database tables to extract meaningful insights that can assist our company in understanding the market landscape. We performed exploratory data analysis (EDA) on various tables and presented our findings through visualizations and a detailed PowerPoint presentation.

### Key Tasks:
1. **Data Analysis** - Explore the Posey database tables and extract insights.
2. **Visualization** - Create visual representations of the data findings using dashboards and graphs.
3. **Presentation** - Design a PowerPoint presentation to summarize the key insights.

## Data Sources
The data for this analysis was derived from the following CSV files:
- **region.csv** - Contains information about different regions and their associated sales representatives.
- **sales_reps.csv** - Provides data on sales representatives, including their regions and assigned accounts.
- **web_events.csv** - Details web events related to customer interactions.
- **accounts.csv** - Contains information about customer accounts, including account names and associated sales reps.
- **orders.csv** - Lists customer orders with details such as order quantities and product types.

## Exploratory Data Analysis (EDA)

### 1. Overview of Data Tables
- **Region Table**: Includes regions and the respective sales reps associated with each region.
- **Sales Reps Table**: Contains details about sales reps, including their accounts and the regions they operate in.
- **Web Events Table**: Records web interactions such as visits, sign-ups, and purchases.
- **Accounts Table**: Provides insights into customer accounts and their interactions with sales reps.
- **Orders Table**: Contains data on customer orders, including quantities ordered for different products.

### 2. Key Findings
- **Sales Performance by Region**: Identified the regions with the highest and lowest sales performances based on account activities.
- **Sales Rep Insights**: Analyzed the performance of sales reps to determine which reps were excelling and which were underperforming.
- **Web Event Analysis**: Investigated the impact of web events on sales and identified trends in customer interactions.
- **Account Analysis**: Explored account-level data to identify high-value customers and understand their buying patterns.
- **Order Analysis**: Examined order data to find trends in product demand and identify significant orders with high quantities.

### 3. Visualizations
- **Regional Sales**: Graphs showing sales distribution across different regions.
- **Sales Rep Performance**: Charts illustrating the performance metrics of sales reps across accounts.
- **Customer Interactions**: Visualizations of web event data, highlighting the correlation between online interactions and sales.
- **Order Volume**: Bar charts and line graphs depicting order quantities and trends over time.
- **High-Value Accounts**: Scatter plots identifying accounts with high order volumes and significant sales contributions.

### 4. SQL Analysis Questions
- **Order IDs with High Quantities**: A query to identify order IDs where `gloss_qty` or `poster_qty` exceeds 4000.
- **Orders with Zero Standard Quantity**: Find orders with `standard_qty` equal to zero but with high quantities in other categories.
- **Company Names Matching Specific Criteria**: Search for companies whose names start with 'C' or 'W' and whose primary contact contains 'ana' but not 'eana'.
- **Regional Sales Rep and Account Association**: A detailed table showing sales reps, their regions, and their associated accounts, sorted alphabetically.

## Contributions
Each group member made specific contributions to the project:

- **Lawal Kaosarah**:
  - Conducted data cleaning and preprocessing.
  - Performed EDA on the `web_events.csv` and `orders.csv` files.
  - Contributed to the visualization of customer interaction and order data.

- **Eboaju Chioma**:
  - Analyzed the `sales_reps.csv` and `accounts.csv` files.
  - Designed and created visualizations for sales rep performance and account insights.
  - Helped compile the insights into the PowerPoint presentation.

- **Olugbenga Ajewole**:
  - Worked on the `region.csv` file analysis and helped refine the order analysis.
  - Contributed to the overall documentation and README file.
  - Coordinated the group's activities and managed GitHub pull requests.

## Repository Structure
|-- Scripts | |-- Bash_Scripts | | |-- (Bash scripts for individual assignments) | |-- SQL_Scripts | |-- (SQL scripts to answer the posed questions) |-- PowerPoint | |-- (PowerPoint presentation files) |-- README.md

bash
Copy code

## How to Run the Analysis
1. Clone the repository using:
   ```bash
   git clone https://github.com/chioma-eboaju-nebor/group2gitlinuxAssignment
Navigate to the Scripts directory to find the Bash and SQL scripts used in this analysis.
Use the PowerPoint folder to view the presentation summarizing our findings.
Conclusion
The insights derived from the Posey database provide valuable information that can guide CoreDataEngineers in making strategic decisions in their market. The EDA revealed critical areas where improvements can be made, and our visualizations provide a clear and concise summary of the findings.

