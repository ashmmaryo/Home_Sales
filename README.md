# Home_Sales

This challenge entails utilizing SparkSQL to analyze home sales data and derive key metrics. Tasks include creating temporary views, partitioning data, caching and uncaching temporary tables, and verifying the uncaching process.

In this task, home sales data is analyzed using PySpark SQL within a Jupyter Notebook named "Home_Sales.ipynb". After importing necessary PySpark SQL functions, the dataset is read into a Spark DataFrame from a CSV file. 
A temporary table named "home_sales" is created for easy data manipulation via SparkSQL queries.

Questions summary:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
2019:300263.7, 2020:298353.78, 2021:301819.44, 2022:296363.88

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
2010:292859.62
2011:291117.47
2012:293683.19
2013:295962.27
2014:290852.27
2015:288770.3
2016:290555.07
2017:292676.79

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
2010:285010.22
2011:276553.81
2012:307539.97
2013:303676.79
2014:298264.72
2015:297609.97
2016:293965.1
2017:280317.58

Using SparkSQL, various questions regarding the home sales data are addressed, including average prices based on different criteria. 
The temporary table is cached to boost query performance, and its caching status is verified. Data organization is optimized through partitioning based on the "date_built" field, improving data management. 
After completion, the temporary table is uncached, freeing up system resources. 
