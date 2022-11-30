# User Defined Functions

[Google Slides](https://docs.google.com/presentation/d/19omQfyf4I7Xq0DAga1nf5gPV_h7uPFCH0grUB942D6E/edit#slide=id.g127afccfc6a_0_1)

`udf_tutorial.ipynb` - Walkthrough of how to define and apply UDFs in base Python, Pandas, and PySpark.

UDF’s are used to extend the functions of the framework and re-use these functions on multiple DataFrames. For example, you wanted to convert every first letter of a word in a name string to a capital case; PySpark build-in features don’t have this function hence you can create it a UDF and reuse this as needed on many DataFrames. UDF’s are once created they can be reused on several DataFrames and SQL expressions.

## Types of UDFs
1. Spark Scala UDF
2. Pyspark UDF
3. Pyspark Pandas UDF

## Pyspark UDFs
Pyspark UDFs are customizable reusable functions. They work best on small volumes of data, making them not beneficial for our big datasets. 

If there is not a built-in SQL function that meets the specific needs of a function, then UDFs are beneficial. Otherwise, UDFs take more computational power than built-in SQL functions, making them slow and not cost-effective.

## Pandas UDFs
Pandas UDFs are also very customizable and reusable. Compared to Pyspark UDFs they are faster but are still slow compared to built-in functions and standard UDFs. Another difference between the two is their input and output. Pandas UDFs take and return vectors. This is why they are sometimes referred to as vectorized UDFs.

## Kahoot Quiz
[Kahoot Link](https://create.kahoot.it/share/pandas-and-pyspark-udf-s/8cfb984a-79f7-4d66-99ac-50871f56ba81)

## Resources
* [PySpark UDF (User Defined Function) (spark by examples article)](https://sparkbyexamples.com/pyspark/pyspark-udf-user-defined-function/)
* [pandas user-defined functions (databricks article)](https://docs.databricks.com/spark/latest/spark-sql/udf-python-pandas.html)
* [Spark UDF — Deep Insights in Performance (medium article)](https://medium.com/quantumblack/spark-udf-deep-insights-in-performance-f0a95a4d8c62)
* [Spark UDF — Deep Insights in Performance (medium article)](https://medium.com/quantumblack/spark-udf-deep-insights-in-performance-f0a95a4d8c62)