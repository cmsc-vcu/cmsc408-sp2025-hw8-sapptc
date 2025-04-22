# Homework 8 - World Bank Indicator Analysis

## Overview

This project involves analyzing World Bank Indicator data using SQL queries to extract meaningful insights. The tasks range from basic data exploration to advanced data transformations and aggregations. The goal is to develop SQL skills for data analysis and apply them to real-world datasets.

## Repository

The code and resources for this project are available on GitHub: [cmsc408-sp2025-hw8-sapptc](https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-sapptc).

## Objectives

1. Explore and analyze the `world_bank_data` database.
2. Write SQL queries to answer specific questions about the data.
3. Perform data transformations and aggregations.
4. Gain hands-on experience with advanced SQL concepts.

## Tasks

### Data Exploration
- **Task 1:** Count the number of records in the `wdi_country` table.
- **Task 2:** View the first 10 records in the `wdi_country` table to identify missing data.
- **Task 3:** Identify non-country records in the dataset.

### Data Transformation
- **Task 4:** Create a new table containing only country records.
- **Task 5:** Count the number of countries in the world as of 2020.

### Data Aggregation
- **Task 6:** List unique regions in the `wdi_country` table.
- **Task 7:** Count the number of countries in each region.
- **Task 8:** List countries in North America along with their regions.

### Advanced Queries
- **Task 9:** Identify the region containing Qatar.
- **Task 10:** Find countries where `abbr` and `wb_abbr` differ.
- **Task 11:** Count countries in each income category.
- **Task 12:** Investigate records with missing income categories and correct errors.

### Complex Analysis
- **Task 14:** Count countries by region and income group.
- **Task 15:** Create a 2D table showing income categories by region.
- **Task 16:** Identify the region with the most low-income countries.
- **Task 17:** Analyze countries with the same region and income group as the Marshall Islands.
- **Task 18:** Identify missing region-income group combinations.

### Percentage Analysis
- **Task 19:** Calculate percentages of countries by region and income group.
- **Task 20:** Create a percentage table with income groups as columns and regions as rows.
- **Task 21:** Summarize the number, totals, and percentages of countries by income category.

## Reflection

This project provided an opportunity to:
- Strengthen SQL skills, including `SELECT`, `WHERE`, `GROUP BY`, and `JOIN`.
- Tackle complex queries involving subqueries, CTEs, and aggregations.
- Understand the importance of data cleaning and transformation in analysis.

## How to Run

1. Clone the repository:  
    ```bash
    git clone https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-jleonard99.git
    ```
2. Set up the database connection using the `.env` file.
3. Install the required Python packages using `poetry install`.
4. Activate the virtual environment:  
    ```bash
    poetry shell
    ```
5. No need to run loader.qmd. It's used as a reference for loading the data into the database.
6. Run the provided Python scripts to execute SQL queries and generate results.



