# Stock-Market-Data-Pipeline-Using-Apache-Kafka
This Project contains a complete data engineering pipeline that ingests and processes stock market data using Apache Kafka and Python. The project simulates streaming-style data flow, where stock data is published to Kafka topics and consumed for further processing, analysis, or storage.



## **Technology Used**

Programming Language-Python

Amazon Web Services (AWS)

1. Apache Kafka

2. S3 (Simple Storage Service)

3. Athena

4. Glue Crawler

5. Glue Catalog

6. EC2

## **Project Overview**

This project demonstrates how to:

  1. Publish stock market records to a Kafka topic using a Python producer.
  2. Consume messages from Kafka using a Python consumer.
  3. Implement safe deserialization to handle mixed or incorrect payloads.
  4. Build a foundational Kafka-based ingestion pipeline for analytics or ML workflows.
  5. Optionally integrate AWS EC2, Glue, Athena, and S3 for extended ETL and reporting.


## **Architecture**

  The project follows a classic producer → Kafka broker → consumer structure:

  CSV Stock Data → Python Producer → Apache Kafka → Python Consumer -> S3 ->Athena

  Extensions can include storing consumer output in S3 and querying with Athena.

## **Key Features**

  1. Clean ingestion pipeline using Kafka
  2. Resilient consumer with safe deserialization
  3. Easy setup on AWS EC2 or local Kafka
  4. Beginner-friendly code structure
  5. Ready for extension into full ETL or analytics workflows
