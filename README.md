# Stock-Market-Data-Engineering-Project-Using-Kafka

## Description 

In this project, I have executed an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka for data injection into AWS S3, Then mapping Schema by AWS Glue Crawler, Created a table by AWS Glue, and Queried the data using AWS Athena. 

## Architecture Diagram

![Architecture Diagram](https://github.com/VighneshKharge/Stock-Market-Data-Engineering-Project-Using-Kafka/blob/main/Architecture.jpg)

## Technologies used along with their use case 

1. **Python Langauge**
   To create a data stream from the dataset to fetch that data into Kafka Python is used.

2. **Apache Kafka**
   In Kafka-producer data is extracted from the dataset using Python at 10 sec intervals and transferred to Kafka-topic.
    
   

