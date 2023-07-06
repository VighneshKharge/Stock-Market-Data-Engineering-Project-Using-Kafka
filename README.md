# Stock-Market-Data-Engineering-Project-Using-Kafka

## Description 

In this project, I have executed an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka for data injection into AWS S3, Then mapping Schema by AWS Glue Crawler, Created a table by AWS Glue, and Queried the data using AWS Athena. 

## Architecture Diagram

![Architecture Diagram](https://github.com/VighneshKharge/Stock-Market-Data-Engineering-Project-Using-Kafka/blob/main/Architecture.png)

## Technologies used along with their use case 

1. **Python Langauge**
    - To create a data stream from the dataset to fetch that data into Kafka Python is used.

2. **Apache Kafka**
   - In Kafka-producer data is extracted from the dataset using Python at 10 sec intervals and transferred to Kafka-topic. From the Kafka topic, Kafka-consumer is receiving the data. Now to transfer data from the consumer to the S3 bucket, SDK boto3 is used.

3. **S3 (Simple Storage Service)**
   - To store data received from consumers in JSON format in a bucket created.

4. **AWS Glue Crawler**
   - To determine the schema of the data in s3 to help AWS Glue Catalog to create the table.

5. **AWS Glue Crawler**
   - From the determined schema by the crawler Glue Data Catalog will create a table that we can query using AWS Athena.

6. **AWS Athena**
   - To query data from the table.


## Detailed step-by-step project exceustion 
     
   

