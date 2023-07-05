# Big Data Challenge

## Background
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Instructions
1. Import the necessary PySpark SQL functions for this assignment.
<img width="853" alt="Screenshot 2023-07-05 at 3 46 24 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/d4b1db4e-c85c-419d-9516-0d863962df7d">

2. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

3. Create a temporary table called home_sales.
<img width="853" alt="Screenshot 2023-07-05 at 3 47 23 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/39e553c8-bc87-4f4d-839e-6abab432394d">

4. Answer the following questions using SparkSQL:

    - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
<img width="992" alt="Screenshot 2023-07-05 at 3 48 05 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/b2e913d0-f8b1-4c58-aa2c-dbe0acecb463">

5. Cache your temporary table home_sales.

6. Check if your temporary table is cached.
<img width="411" alt="Screenshot 2023-07-05 at 3 48 42 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/23397788-2abd-486f-81f2-c378c6a95a22">

7. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

8. Partition by the "date_built" field on the formatted parquet home sales data.
<img width="712" alt="Screenshot 2023-07-05 at 3 49 29 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/c4e5ad90-6fd6-45a1-a897-2377dd921f40">

9. Create a temporary table for the parquet data.

10. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

11. Uncache the home_sales temporary table.

12. Verify that the home_sales temporary table is uncached using PySpark.
<img width="395" alt="Screenshot 2023-07-05 at 3 50 04 PM" src="https://github.com/margaretkhendre/Home-Sales-vs-Big-Data/assets/121995835/e15074a9-e8d5-421a-a9d1-7bf2b02ef112">



