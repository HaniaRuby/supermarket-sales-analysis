# Supermarket Sales Analysis Project

This project provides a complete analysis pipeline for supermarket sales data, including thorough data wrangling, cleaning, and visualization. It encompasses steps from data preparation to insightful visualizations and a detailed business report, making it a comprehensive guide for anyone interested in data analysis.

The [dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data) contains historical record of sales data in 3 different supermarkets. 

### Columns:
Invoice ID: A unique identifier for each transaction or sale.
Branch: The branch where the transaction took place
Yangon, Naypyitaw, Mandalay: Indicators or flags for which city the sale occurred in.
Customer Type: Indicates whether the customer is a "Normal" customer or a "Member."
Gender: The gender of the customer ("Male" or "Female").
Product Line: The category of products purchased (e.g., Health and Beauty, Food and Beverages).
Unit Price: The price per unit of the product sold.
Quantity: The number of units purchased in the transaction.
Tax 5%: The tax applied to the sale, calculated at a rate of 5%.
Total: The total amount for the transaction, including tax.
Date: The date when the transaction occurred.
Time: The time of day when the transaction took place.
Payment: The method used for payment (e.g., E-wallet, Cash, Credit Card).
Rating: Customer's rating of their experience, likely on a numerical scale.


### Key Components
1. **Data Wrangling Notebook**: A Python Notebook detailing the data cleaning process, covering everything from initial exploration to handling missing values, detecting and addressing outliers, and feature engineering.
2. **Wrangling Report**: A document that outlines the steps taken during the data wrangling process, providing transparency and justification for each cleaning decision.
3. **Power BI Dashboard**: An interactive visualization tool that presents key insights from the cleaned dataset, such as sales trends, customer demographics, and product line performance.
4. **Business Report**: A summarized document that combines findings from the data analysis and Power BI visualizations, providing actionable insights for decision-makers.


### Data Analysis Pipeline
#### 1. Data Wrangling
- **Initial Exploration**: Understanding the dataset's structure and identifying inconsistencies.
- **Data Cleaning**:
  - Removing currency symbols from numerical fields.
  - Standardizing entries in categorical columns.
  - Handling missing values and ensuring data type consistency.
- **Outlier Detection and Handling**:
  - Using the Interquartile Range (IQR) method to identify outliers.
  - Addressing or retaining outliers based on their impact on the analysis.
- **Feature Engineering**:
  - Creating new columns, such as `branch_city`, and extracting date components for deeper analysis.

### 2. Data Visualization
- **Power BI Dashboard**: 
  - Offers interactive visualizations showcasing key metrics such as sales by branch, product line performance, customer demographics, and payment method preferences.
  - Provides a clear picture of the supermarket's operational performance.

### 3. Reporting
- **Wrangling Report**: 
  - Details the data cleaning process, highlighting the issues addressed, such as missing values, data type corrections, and outlier handling.
- **Business Report**:
  - [View here](https://www.canva.com/design/DAGQppoxCak/PUg8JQ4wos9weK9OO2BupQ/view?utm_content=DAGQppoxCak&utm_campaign=designshare&utm_medium=link&utm_source=editor)
  - Summarizes the key findings from the analysis, including sales trends, customer behavior insights, and product line performance.
  - Provides actionable insights for strategic decision-making.

## Tools and Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **Seaborn and Matplotlib**: For data visualization within the notebook.
- **Regular Expressions (re)**: For text processing and data standardization.
- **Power BI**: For creating interactive and insightful dashboards.

## Conclusion
This project serves as a comprehensive case study in data wrangling and visualization. By providing a full cycle from raw data to business insights, it demonstrates the importance of clean data and effective visualization tools in deriving meaningful conclusions and supporting strategic decisions.

