# Handson-L10-Spark-Streaming-MachineLearning-MLlib

## Overview
This is a hands-on assignment that teaches how to utilize Spark Structured Streaming and Spark MLlib to process real-time ride sharing data. The data_generator is a stream that tasks 4 and 5 read to make predictions.

## Task 4
This task trains a linear regression model using distance to predict the price of the ride.

## Task 5
This task trains a linear regression model using time-based features to predict average fare for each streaming window.

## How to Run
*In Terminal 1:*
Start the data generator:

    python data_generator.py

*In Terminal 2:*
Run Task 4:

    spark-submit task4.py

OR
Run Task 5:

    SPARK_LOCAL_IP=127.0.0.1 spark-submit --conf spark.driver.bindAddress=127.0.0.1 --conf spark.driver.host=127.0.0.1 task5.py

# Results Screenshots

<img width="1000" height="500" alt="Screenshot 2026-06-15 at 7 51 10 PM" src="https://github.com/user-attachments/assets/759d83ae-39a5-40ba-967e-a1ade158ea8d" />
<img width="1000" height="500" alt="Screenshot 2026-06-15 at 8 04 20 PM" src="https://github.com/user-attachments/assets/0ed83079-4be0-46db-a673-a45891e64d55" />
