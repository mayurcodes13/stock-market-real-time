# Real-Time Stock Market Data Processing

## Introduction

As part of my personal exploration into data engineering and analytics, I developed a real-time data processing system to simulate and analyze stock market activities. This project showcases my ability to design and implement a scalable, fault-tolerant architecture that processes and analyzes high-velocity data streams, mimicking the dynamism of financial markets.

## Project Architecture

![image](https://github.com/mayurcodes13/stock-market-real-time/assets/146315481/a03c6ab8-9159-4fb5-b762-4af1cf9d3b84)

## Project Summary

The core objective was to create a system that can simulate stock market fluctuations using real-time data streaming and processing. Leveraging Apache Kafka on AWS EC2, I orchestrated a data pipeline that simulates, processes, streams, and analyzes stock market transactions.

## Implementation Details
### Technology Stack

* #### Apache Kafka: Used for creating robust real-time streaming pipelines.
* #### AWS EC2: Hosted the Kafka cluster, ensuring scalable and efficient data handling.
* #### AWS S3: Acted as the storage solution for the processed data streams.
* #### AWS Glue: Automated the cataloging of data schemas, facilitating organized data analysis.
* #### Amazon Athena: Enabled SQL-based analytics on the processed and cataloged data.
* #### Python: Scripted the data production and consumption logic.
* #### Jupyter Notebook: Served as the interactive environment for developing and testing the Python scripts.

### Process Flow

Data Simulation: I wrote Python scripts that generate simulated stock market data, emulating real-world trading activities.
Streaming Setup: Utilized Apache Kafka on AWS EC2 to establish a real-time data streaming environment, handling the flow between data producers and consumers.
Storage and Cataloging: Configured AWS S3 for storing the streamed data and AWS Glue to catalog the data structure, making it query-ready.
Data Analysis: Used Amazon Athena for conducting SQL-based analysis on the cataloged data, extracting valuable insights into simulated market trends.
