# Apache Flink Streaming Pipeline

This project demonstrates a sample Apache Flink streaming pipeline that ingests, transforms, and writes real-time data from a Kafka source to a PostgreSQL sink. It serves as a foundational architecture for building scalable and fault-tolerant data processing systems for event-driven applications.


## Technologies Used

- **Apache Flink**: Stream processing engine for stateful computations over unbounded data.
- **Kafka**: Distributed event streaming platform used as a data source.
- **PostgreSQL**: Relational database used as the sink for processed records.
- **Docker**: Containerization of Flink, Kafka, Zookeeper, and PostgreSQL for local orchestration.


The pipeline follows this flow:

1. **Ingestion**: Consumes JSON messages from a Kafka topic.
2. **Transformation**: Parses incoming data, performs field extraction and schema mapping.
4. **Output**: Writes the processed records into a PostgreSQL table.



Resources:
- [DataTalksClub - Data Engineering Zoomcamp (GitHub)](https://github.com/DataTalksClub/data-engineering-zoomcamp)  
- [Flink Streaming Video - YouTube (from DataTalksClub)](https://www.youtube.com/watch?v=P2loELMUUeI&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb&index=52)
