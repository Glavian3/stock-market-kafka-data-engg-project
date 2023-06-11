# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
Welcome to the Stock Market Kafka Real-Time Data Engineering Project! This project focuses on executing an end-to-end data engineering solution for real-time stock market data using Kafka. By leveraging various technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL, we can build a robust data pipeline to process and analyze stock market data in real time.



## Architecture 
The project architecture is designed to facilitate the seamless flow of real-time stock market data. Here is an overview of the key components:

<img src="Architecture.jpg">

## Technology Used
Throughout this project, we utilize the following technologies:

* Programming Language - Python: Python is used for developing data processing scripts and integrating various components of the data pipeline.

* Amazon Web Services (AWS): We leverage AWS services to build a scalable and reliable data pipeline.

  * S3 (Simple Storage Service): Amazon S3 provides secure and scalable storage for storing stock market data and intermediate outputs.

  * Athena: Amazon Athena is utilized for interactive querying and analysis of the stored data in S3. It allows us to run SQL queries on the data without the need for traditional database setup or management.

  * Glue Crawler: AWS Glue Crawler automatically discovers and catalogs the schema of the stored data, making it easier to query and analyze the data using Athena.

  * Glue Catalog: The Glue Catalog serves as a central metadata repository that stores the schema information of the stock market data, enabling efficient data discovery and querying.

  * EC2: Amazon EC2 instances provide the computational power required for running data processing scripts and other components of the data pipeline.

* Apache Kafka: Apache Kafka acts as a high-throughput distributed messaging system that enables real-time streaming of stock market data. It serves as the backbone of the data pipeline, allowing seamless communication between data producers and consumers.


## Dataset Used
For this project, you can use any dataset that focuses on the stock market. The primary focus of this project is the operational aspect of data engineering and building a robust data pipeline.

Here is an example dataset used in the project: [Stock Market Dataset](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv)

Feel free to explore and select a dataset that aligns with your requirements and preferences.

I hope you find this Stock Market Kafka Real-Time Data Engineering Project insightful and exciting. By implementing this project, you will gain hands-on experience in building a scalable and efficient data pipeline for real-time stock market data analysis. Happy coding!
