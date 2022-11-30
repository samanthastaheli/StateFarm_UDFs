# User Defined Functions

[Google Slides](https://docs.google.com/presentation/d/19omQfyf4I7Xq0DAga1nf5gPV_h7uPFCH0grUB942D6E/edit#slide=id.g127afccfc6a_0_1)

`udf_tutorial.ipynb` - Walkthrough of how to define and apply UDFs in base Python, Pandas, and PySpark.

UDF’s are used to extend the functions of the framework and re-use these functions on multiple DataFrames. For example, you wanted to convert every first letter of a word in a name string to a capital case; PySpark build-in features don’t have this function hence you can create it a UDF and reuse this as needed on many DataFrames. UDF’s are once created they can be reused on several DataFrames and SQL expressions.

## Types of UDFs
1. Spark Scala UDF
2. Pyspark UDF
3. Pyspark Pandas UDF

### Differences



need...

## Pyspark UDFs
Pyspark UDFs are customizable reusable functions. They work best on small volumes of data, making them not beneficial for out big datasets. 

If there is not a built in sql function that meets specific needs of a function, then UDFs are benifical. Otherwise, UDFs take more computatiponal power than built in sql functions, making them slow and not cost effective.

## Pandas UDFs
Pandas UDFs are very customizable. Compared to Pyspark UDFs they are faster, but are still slow compared to built in funcitons. 

## Codeing Challenge 

## Kahoot Quiz
[Kahoot Link](link goes here)

## Resources
* [PySpark UDF (User Defined Function) (spark by examples artticle)](https://sparkbyexamples.com/pyspark/pyspark-udf-user-defined-function/)
* [pandas user-defined functions (databricks article)](https://docs.databricks.com/spark/latest/spark-sql/udf-python-pandas.html)
* [Spark UDF — Deep Insights in Performance (medium article)](https://medium.com/quantumblack/spark-udf-deep-insights-in-performance-f0a95a4d8c62)
