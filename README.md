# PostgreSQL Data Analysis Project

## Project Overview
This project focuses on analyzing transactional data from a PostgreSQL database, aiming to extract meaningful insights related to customer behavior, transaction patterns, and terminal usage. The analysis includes the creation of several tables and aggregations that offer a deep dive into various aspects of transaction data, such as gender-specific transaction trends, daily transaction patterns, and terminal performance.

## Steps Involved

1. **Data Preparation**:  
   - Created a `transactions_data` table, which aggregates transaction information along with various related data points such as transaction success, category, gender, and terminal details.
   - Applied transformations like extracting the transaction hour and applying conditional logic to flag holidays.

2. **Terminal and Country Analysis**:  
   - Developed the `terminal_country` table, which identifies the country with the highest transaction volume for each terminal, based on a combination of transaction count and country-specific data.

3. **Client Information Aggregation**:  
   - The `clients_info` table consolidates client-related information, including demographic attributes such as gender and age group, providing a clearer view of customer profiles.

4. **Data Aggregation**:  
   - The `transactions_data_agg` table aggregates the data at a monthly level, offering insights into the total transaction sum and count, as well as gender-specific transaction statistics and return transaction counts.

5. **SQL Query Optimization**:  
   - Ensured efficient data extraction and transformation by leveraging advanced SQL features like `WITH` clauses, `ROW_NUMBER()`, and window functions.

6. **Data Exploration and Visualization**:  
   - The aggregated data forms the basis for further analysis and visualization, such as plotting trends across different time periods (e.g., morning vs. evening) and geographic locations.

## Conclusion
This project offers a structured approach to transforming raw transactional data into actionable insights. It highlights important trends, such as gender-specific transaction behavior and regional terminal usage, which can be used to optimize business strategies, improve user experience, and increase operational efficiency.

## Technologies Used
- Python
- PostgreSQL
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Dataset
The dataset used in this project includes transactional data, client demographic information, terminal details, and category-related metadata. The data is stored across multiple tables in a PostgreSQL database, enabling complex queries and analyses.
