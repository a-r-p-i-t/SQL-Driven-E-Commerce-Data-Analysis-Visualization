# E-Commerce Data Analysis with SQL and Python

This project performs comprehensive data analysis on e-commerce data using SQL for querying the database and Python for data visualization. The project aims to extract meaningful business insights from the dataset, which includes orders, products, payments, and customer information.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Conclusion](#conclusion)
- [License](#license)


## Introduction

This repository contains the code and analysis for an e-commerce dataset using SQL and Python. The objective is to gain insights into sales performance, customer behavior, and product popularity to help inform business decisions.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ecommerce-data-analysis.git


2. **Install the required modules:**

    ```bash
    pip install mysql-connector-python pandas seaborn matplotlib numpy


## Data Analysis and Visualization

We use SQL for querying the database and Python (with pandas, seaborn, and matplotlib) for data visualization.<br><br>
**[csv_2_tables.py](./csv_2_tables.py)** file is implemented to convert raw data from CSV to tables and prepare the data in tabular form.<br><br>
**[SQL Driven E-Commerce Data Analysis.ipynb](./SQL_Driven_E-Commerce_Data_Analysis.ipynb)** notebook contains the implementation of Data Analysis & Visualization of the E-Commerce data.<br><br>
Below are some insights derived from the analysis of the E-Commerce data:-


1. **Moving average of order values for each customer over their order history.**

2. **Retention Rate of Customers over 6 months.**

3. **Total sales per category**
<br><br><br>


  ![Screenshot 2024-08-03 145002](https://github.com/user-attachments/assets/8f1cc587-fba7-4616-b9a0-4cc8152aca2c)
  <br><br><br>

4. **Number of customers from each state**


   ![Screenshot 2024-08-03 144910](https://github.com/user-attachments/assets/16f755f8-8e3c-43e2-bcc4-1d503cb1f001)
   <br><br><br>


6. **Top 3 customers who spent the most money in each year.**


   ![Screenshot 2024-08-03 161502](https://github.com/user-attachments/assets/c4802882-d2e0-47c1-be94-6470f5a194e9)
   <br><br><br>


8. **Percentage of total revenue contributed by each product category.**


   ![Screenshot 2024-08-03 144744](https://github.com/user-attachments/assets/c4b2f8a8-3f23-4193-b9e1-24101cecbc7d)
   <br><br><br>


9. **Number of orders per month in 2018.**


   ![Screenshot 2024-08-03 145039](https://github.com/user-attachments/assets/61ac25c2-1ddc-47e9-8454-04da8804bc1a)
   <br><br><br>



11. **Total revenue generated by each seller, ranked by revenue**


   ![Screenshot 2024-08-03 151910](https://github.com/user-attachments/assets/22301789-b98d-4568-9f88-fdf833c0987d)
   <br><br><br>



11. **Cumulative sales per month for each year.**


  ![Screenshot 2024-08-03 144634](https://github.com/user-attachments/assets/161e812a-3509-45fb-9dcb-c2e501f76169)
  <br><br><br>


## Conclusion

This project provides an in-depth analysis of an eCommerce dataset using SQL queries and visualizations. The analysis spans multiple aspects of the eCommerce operations, from customer demographics to sales performance and product trends.Below are some key insights derived from the data:

**1. Customer Distribution:** We identified unique cities where customers are located, providing insights into regional market penetration.

**2. Order Trends:** Analyzed the number of orders placed in specific years, revealing trends and seasonality in customer purchasing behavior.

**3. Sales Analysis:** Calculated total sales per product category, offering a clear view of which categories drive the most revenue.

**4. Payment Patterns:** Determined the percentage of orders paid in installments, shedding light on customer payment preferences.

**5. Customer Demographics:** Counted the number of customers from each state, highlighting key markets.

**6. Monthly Order Volume:** Measured the number of orders per month in 2018, identifying peak sales periods.

**7. Order Composition:** Found the average number of products per order, grouped by customer city, to understand buying habits.

**8. Revenue Contribution:** Calculated the percentage of total revenue contributed by each product category, emphasizing the top-performing categories.

**9. Price and Purchase Correlation:** Identified the correlation between product price and purchase frequency, providing insights into pricing strategies.

**10. Seller Performance:** Ranked sellers by revenue, highlighting top performers and potential areas for growth.

**11. Customer Order History:** Calculated the moving average of order values for each customer, helping to track spending patterns over time.

**12. Cumulative Sales:** Analyzed cumulative sales per month for each year, providing a long-term view of revenue growth.

**13. Year-Over-Year Growth:** Evaluated the year-over-year growth rate of total sales, highlighting overall business growth.

**14. Top Customers:** Identified top-spending customers each year, focusing on key contributors to revenue.

**15. Customer Retention:** Calculated the customer retention rate over six months, emphasizing customer loyalty and retention strategies.
<br><br><br>



## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

