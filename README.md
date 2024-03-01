## Hello!
This is a list of some of my projects. Please keep checking soon as I will be adding a variety of projects. 

---

# Projects
- <a href="https://github.com/joe-bryan/cdc-kafka-spark/">DVD Streaming Rentals</a> - Resources: Python, postgres, Debezium, Kafka, Spark, Airflow, S3, Databricks, RDS, Confluent Cloud, SQL
  -  Data pipeline that captures row-level changes to the data in a Postgres database. From there, Apache Kafka receives the feed in real time. Apache Spark runs daily and batches the changes over to an S3 data lake. The goal of the pipeline is to have a secure location for data analysts and data scientists to get the data for drawing insights and running algorithms. The data consists of DVD rental transactions.

  -  The diagrams show two ways to achieve the pipeline. The Databricks version uses managed versions of Postgres, Kafka, and Spark. The Docker version uses local resources instead. With the Docker way, ensure you have more than 4GB of RAM available as the number of containers eats your computer resources.
<br>
<br><img width="700" alt="Databricks pipeline" src="https://github.com/joe-bryan/cdc-kafka-spark/assets/101160575/c4a19ef8-41f8-4de9-acb8-d44929f05e83">
<img width="700" alt="Docker pipeline" src="https://github.com/joe-bryan/cdc-kafka-spark/assets/101160575/e9c3ed1a-6e71-4c7e-8f3d-ac43e287033e">
<br>
<br>

- <a href="https://github.com/joe-bryan/dbt-business-intelligence/">Denormalized Table with dbt Data Warehouse</a> - Resources: SQL, dbt, postgres
  -  Data pipeline that transforms data in a postgres data warehouse using dbt. The goal of the pipeline is to create a denormalized table for the business intelligence team to create a dashboard to understand its customers better.
<br>
<br>
<img width="700" alt="dbt lineage" src="https://github.com/joe-bryan/dbt-business-intelligence/assets/101160575/fa8cb22c-3de4-41de-8be4-458a3ff53fd7">
<img width="700" alt="dbt docs" src="https://github.com/joe-bryan/dbt-business-intelligence/assets/101160575/221df1b4-5e44-4824-b675-97a25676a6db">
<br>
<br>

- <a href="https://github.com/joe-bryan/toyota-streaming-listings">Streaming Toyota Auto Listings</a> - Resources: Kinesis, Kinesis Firehouse, S3, Glue, Quicksight, CloudFormation
  - Constructed an event streaming pipeline with AWS resources; enabled real-time analytics with an AWS dashboard
<br>
<img width="524" alt="QuickSight Dashboard" src="https://github.com/joe-bryan/toyota-streaming-listings/assets/101160575/4eca4927-167d-43ea-962a-fcc55135b8e6">
<img width="700" alt="AWS Kinesis streaming data pipeline" src="https://github.com/joe-bryan/toyota-streaming-listings/assets/101160575/5d5abb35-d593-4314-9036-cf633836fdc5">
<br>
<br>

- <a href="https://github.com/joe-bryan/data-engineer-gtfs-bus">MBTA Delayed Subways Data Engineering</a> - Resources: Python, Terraform, Google Cloud Platform, Google Cloud Storage, BigQuery, Prefect, Streamlit
  - Built a data pipe that ingests data from the Massachusets Bay Transportation Authority (MBTA) to display which subways are delayed and by how much.
 <br>
 <img width="550" alt="Streamlit Screenshot" src="https://github.com/joe-bryan/projects/assets/101160575/e491ec2d-f3b6-43a6-b218-7a2c9f880bb9">
 <img width="550" alt="Data Pipeline Diagram" src="https://github.com/joe-bryan/projects/assets/101160575/17c510a1-4361-4802-9d5c-db584d963a83">
<br>
<br>
