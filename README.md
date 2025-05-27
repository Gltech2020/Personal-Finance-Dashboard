# Personal-Finance-Analysis
---
## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Insights and Recommendations](insights-and-recommendations)
- [Limitations](limitations)
- [Use Cases](use-cases)
  
## Project Overview
---
This Personal Finance Analysis Dashboard provides a visual breakdown of income and expenses over multiple years. 
Built using Microsoft Excel, it is designed to help individuals gain insights into their financial habits and identify areas for budgeting and improvement.

## Data Sources
---
Personal Finance dataset was taken from [Download Here](https://github.com/Gltech2020/Personal-Finance-Link/blob/main/Personal_Finance_Dataset.csv)

## Tools Used
---
- Microsoft Excel (for data modeling and visualization)
- Pivot Tables and Charts
- Slicers for intercative filtering

## Data Cleaning
---
- Uploading data
- Dealing with missing values
- Data formatting

## Exploratory Data Analysis
---
The EDA involved answering these questions:
1. What is the total income vs total expenses? 
2. ⁠What is the monthly net saving (income-expenses)?
3. ⁠How expenses change month to month.
4. ⁠Top 4 spending categories

## Data Analysis
---
I used Pivot Tables in Excel to analyze personal finance data from 2020–2024. 
The goal was to extract insights and build an interactive dashboard for visualizing spending habits and income trends.
1. Monthly Expense Summary
   - Used a Pivot Table to summarize total expenses per month, helping identify high-spending periods.

2. Spending by Category
   - Grouped data by the Category field (e.g., Food & Drink, Rent, Utilities) to compare how much was spent in each area.

3. Income vs Expense Trend
   - Pivoted the data by Type (Income/Expense) and by month to visualize net balance over time.

4. Top 5 Expense Categories
   - Created a Pivot Table to sort and filter highest expense categories, allowing quick focus on major cost drivers.

## Insights and Recommendations
---
1. Reduce Overspending in Key Categories
   - #### Observation:
   - Food & Drink, Rent, and Shopping made up over 60% of total expenses.
   - #### Recommendation:
   -  Set monthly spending limits on these categories and explore budgeting apps or meal planning tools.

2. Increase Investment Contributions
   - #### Observation:
   - Only 10% of monthly income was directed toward Investments.
   - #### Recommendation:
   - Increase investment contributions by automating a fixed transfer every month for long-term financial growth.

3. Identify and Eliminate Low-Value Expenses
   - #### Observation:
   - Frequent small transactions in the "Entertainment" and "Shopping" categories added up significantly.
   - #### Recommendation:
   - Review subscriptions and impulse purchases; consider implementing a 24-hour rule before non-essential buys.

4. Build a Monthly Savings Target
   - #### Observation:
   - Income often exceeded expenses, but no savings entries were consistently logged.
   - #### Recommendation:
   - Define a monthly savings goal and log it as a transaction to build habit-tracking accountability.

5. Stabilize Irregular Spending Patterns
   - #### Observation:
   - Some months showed 30–40% higher spending due to non-recurring costs (e.g., travel, health).
   - #### Recommendation:
   - Create an emergency or sinking fund to absorb these spikes and avoid disrupting monthly budgets.
     
## Limitations
---
While the project provides valuable insights using Excel and Pivot Tables, it has several limitations:

1. Static Data
 - The dataset only covers a fixed period (e.g., 2020–2024) and doesn't reflect ongoing financial behavior.
2. Synthetic / Sample Data
 - If the dataset is not real (e.g., generated or anonymized), it may not fully represent realistic spending patterns or edge cases.
3. Manual Data Entry
 - The analysis assumes consistent and accurate transaction logging. In real-life scenarios, missing or mislabeled entries could skew results.
4. No External Factors Considered
 - External influences (e.g., inflation, currency changes, job loss) are not factored into the financial trends.
5. Limited Granularity
 - Pivot Tables provide high-level summaries but lack the advanced modeling or forecasting features available in tools like Power BI or Python.
6. No Real-Time Updates
 Excel dashboards are not dynamic unless refreshed manually. Automated updates would require integration with financial APIs or Power Query.

## Use Cases
---
- Personal budgeting and expense tracking
- Financial behavior analysis
- Identifying savings opportunities
- Monthly and yearly financial reporting
