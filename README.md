# 📈 Stock Market Real-Time Data Analysis Using Apache Kafka

This is an **end-to-end real-time data engineering project** designed to simulate, stream, store, and analyze stock market data using Apache Kafka and AWS cloud services.

## 📌 Project Overview

The goal of this project is to simulate stock market data, stream it using **Apache Kafka**, store it in **Amazon S3**, and query it using **Amazon Athena**. This architecture mirrors real-world data streaming systems used in financial analytics, IoT, and event-driven platforms.

## 🧱 Architecture
![image](https://github.com/user-attachments/assets/639bad98-846f-4a1b-a676-7263c55dd633)

**Main Components:**

- **Python Producer:** Simulates real-time stock data from a CSV file
- **Apache Kafka (EC2):** Handles message streaming (Producer → Topic → Consumer)
- **Kafka Consumer:** Consumes the stream and uploads to Amazon S3
- **AWS S3:** Acts as a Data Lake
- **AWS Glue Crawler & Data Catalog:** Automates schema discovery
- **Amazon Athena:** Runs SQL queries directly on S3 data

---

## ⚙️ Tech Stack

| Tool/Service       | Purpose                                |
|--------------------|----------------------------------------|
| Python             | Producer & Consumer implementation     |
| Apache Kafka       | Real-time event streaming               |
| Amazon EC2         | Hosting Kafka brokers                  |
| Amazon S3          | Data Lake (raw JSON storage)           |
| AWS Glue           | Schema inference and cataloging        |
| Amazon Athena      | SQL-based analysis on S3               |
| Boto3 (Python SDK) | AWS integration                        |


