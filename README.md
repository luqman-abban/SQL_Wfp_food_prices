# SQL_Wfp_food_prices
This repository contains SQL queries and data files for analyzing food prices in Pakistan. The analysis focuses on various aspects of food pricing, including trends, price fairness, and regional differences. 

## Data Files

- `commodity.csv`: This file lists the commodities available in the dataset with their names.
- `wfp_food_prices_pakistan.csv`: Contains the actual food prices data across different markets in Pakistan, including dates, market names, commodity names, and prices.

## SQL Queries

The SQL queries included in this repository serve several analytical purposes:

1. **Price Analysis**: Identify commodities with prices less than or equal to 50 PKR in specified cities.
2. **Market Observations**: Count observations per market/city and list distinct cities.
3. **Commodity Analysis**: Show names and observations count of commodities; analyze average prices for Wheat flour - Retail by city.
4. **Price Categorization**: Categorize prices based on predefined logic (LOW, FAIR, HIGH).
5. **City and Price Fairness Analysis**: Differentiate city categories (Big, Medium-sized, Small) and assess price fairness.

## Usage

Ensure your SQL environment is set up to handle the date formats and data structures present in the CSV files. Import the data files into your database before executing the queries.

## Note

Please adjust the SQL queries according to your database's specific requirements and settings. The `set sql_safe_updates=0;` command is used to allow updates without specifying a key in the `WHERE` clause. Use it with caution.

## Contributing

Feel free to fork this repository and contribute by adding more queries or improving the existing analysis. Make sure to follow best practices for data analysis and SQL query optimization.
