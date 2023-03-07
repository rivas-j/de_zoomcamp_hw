## Week 5 Homework

In this homework we'll put what we learned about Spark
in practice.

We'll use high volume for-hire vehicles (HVFHV) dataset for that.

## Question 1. Install Spark and PySpark

* Install Spark
* Run PySpark
* Create a local spark session 
* Execute `spark.version`

What's the output?

- 3.3.2


## Question 2. HVFHW February 2021

Download the HVFHV data for february 2021:

```bash
wget https://nyc-tlc.s3.amazonaws.com/trip+data/fhvhv_tripdata_2021-02.csv
```

Read it with Spark using the same schema as we did 
in the lessons. We will use this dataset for all
the remaining questions.

Repartition it to 12 partitions and save it to
parquet.

What's the size of the folder with results (in MB)?

- 24 MB


## Question 3. Count records 

How many taxi trips were there on February 15?

- 452,470


## Question 4. What is the Longest trip for each day

Now calculate the duration for each trip.

- 66.87 hours


## Question 5. What port does Spark's User Interface Dashboard run on by default?

- 4040 


## Question 6. What is the name of the most frequent pickup location zone?

- Crown Heights North


