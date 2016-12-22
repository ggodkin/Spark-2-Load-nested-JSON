# Spark-2-Load-nested-JSON
#### Example of loading nested JSON into Spark 2 dataframe
#####val df = spark.read.json("peopleNestedTbls.json")
#####df.printSchema
#####df.createOrReplaceTempView("testV")
#####spark.sql("select * from testV").take(1)
