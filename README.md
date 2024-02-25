
# Real-Time-Data-Streaming-with-Kafka-and-AWS-Project


In this project, I've crafted a real-time data analysis solution for swift insights into the dynamic financial landscape. Utilizing advanced technologies like Apache Kafka, AWS Glue, and Athena, the project aims to streamline data processing and empower decision-makers with timely information for navigating the complexities of stock markets.




## Architecture Flow

![App Screenshot](https://github.com/VennapusaManoj1998/Real-Time-Data-Streaming-with-Kafka-and-AWS-Project/blob/main/Kafka_Project.png)


## Key Components


- **Python:** Used for scripting and implementing various components of the project.

- **Amazon Web Services (AWS):** Cloud platform utilized for hosting and managing the project components.

- **Apache Kafka:** Kafka is a distributed streaming platform that facilitates the real-time processing and transmission of large volumes of data across multiple applications, making it widely used for building scalable and fault-tolerant event-driven architectures..

- **Zoo Keeper:** ZooKeeper is a distributed coordination service essential for maintaining configuration information, naming, and providing synchronization within distributed systems. It plays a crucial role in managing and ensuring the consistency and reliability of distributed applications.

#### For Kafka, Zookeeper is the resource manager
**1:** Cluster management,
**2:** Failure detection and recovery and 
**3:** Stores ACL (access control list) and secrets

- **AWS crawler:** A crawler, in the context of web or data, is an automated program that systematically navigates through websites or data sources, gathering information for indexing, analysis, or other purposes. It is commonly used in search engines and data extraction processes.

- **AWS Glue:** AWS Glue is a fully managed extract, transform, and load (ETL) service that simplifies the process of preparing and loading data for analysis. It automates much of the ETL process, making it easier to discover, catalog, and transform data stored on AWS.

- **Amazon Athena (Identity and Access Management):** Athena is a serverless query service provided by AWS that enables users to analyze data stored in Amazon S3 using standard SQL queries. It allows for on-demand and ad-hoc querying, making it a powerful tool for data exploration and analysis without the need for infrastructure management.

- **SQL:** Utilized for querying and analyzing data.


## Project

- Real-time data is streamed into Kafka topics.
- Python scripts and AWS Glue are employed for data transformation and preparation.
- Transformed data is stored in Amazon S3 for scalable and cost-effective storage.
- Amazon Athena enables SQL-based querying of the stored data for analysis.
- Optional: Visualization tools can be used to create dashboards and visual representations of the analyzed stock market data.
## Key Benefits

- **Real-Time Analysis::** Enables real-time analysis of stock market data for timely decision-making.

- **Scalability:** Leveraging AWS services allows for scalable and cost-efficient data storage and processing.

- **Flexibility:** The use of SQL queries and Python scripting provides flexibility in data analysis and transformation.




