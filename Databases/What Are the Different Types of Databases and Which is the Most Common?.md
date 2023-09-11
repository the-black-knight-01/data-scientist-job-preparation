# What Are the Different Types of Databases and Which is the Most Common?
  
1) Relational Databases (SQL):
- Use when your data is structured and consistent.
- Supports ACID transactions and complex queries.
- Examples: **MySQL**([1](https://www.youtube.com/watch?v=hlGoQC332VM&pp=ygUObXlzcWwgdHV0b3JpYWw%3D), [2](https://www.youtube.com/watch?v=7S_tz1z_5bA&t=4796s&pp=ygUObXlzcWwgdHV0b3JpYWw%3D)), PostgreSQL, Oracle. **SQL Server** ([1](https://www.youtube.com/watch?v=ljsfENuIJuY&ab_channel=Intellipaat),  [2](https://www.sqlservertutorial.net/))

2) Key-Value Store:
- Use when data model is based on key-value pairs and requires high scalability and availability.
- Provides lightning-fast data retrieval and high throughput.
- Examples: Aerospike, **DynamoDB** [1](https://www.youtube.com/watch?v=OfZgHXsYqNE&ab_channel=EnlearAcademy)

3) Document Databases:
- Handles semi-structured data with varying fields.
- Provides schema flexibility and horizontal scaling.
- Examples: MongoDB, Couchbase

4) Graph Databases:
- Perfect for data with complex relationships.
- Used in applications like social networks and recommendation engines.
- Examples: Neo4j, Amazon Neptune.

5) Columnar Databases:
- Data is stored by columns instead of rows to optimize reading from a column.
- Great for applications that involve storing massive data sets and running analytical queries.
- Examples: HBase, Redshift.

6) Time-Series Databases:
- Opt for this when dealing with time-series data like IoT sensor readings or server logs.
- Great for efficient storage and retrieval of time-stamped data.
- Examples: InfluxDB, Prometheus.

7) In-Memory Databases:
- When speed is of the essence, and you can afford to sacrifice persistence.
- Ideal for caching, real-time analytics, and high-frequency trading.
- Redis and Memcached are popular choices.

8) Wide-Column Stores:
- Use in applications with large volumes of data and high write throughput.
- Best suited for analytical workloads and applications that require high availability.
- Apache Cassandra is a prominent example.

9) Search Engines:
- When your primary use case revolves around full-text search.
- Essential for applications that require searching of data content.
- Elasticsearch and Solr are popular choices.

10) Spatial Databases:
- Used to store geographical and location-based data.
- Choose for applications that require Spatial indexing, geospatial analytics.
- Examples include PostGIS, CartoDB

11) Blob Datastore:
- Use in applications that requires storing large documents, images, audio and video files.
- Provides high availability, durability and cost effective storage.
- Examples include HDFS, Amazon S3

12) Ledger Databases:
- Used for maintaining a transparent, immutable, and cryptographically verifiable transaction log.
- Useful for applications dealing with financial transactions and supply chain systems
- Examples: Amazon QLDB, Azure SQL Ledger

Tech world offers a rich ecosystem of databases and there's no one-size-fits-all solution.
The choice of a database depends on your specific use case, data model, scalability needs, and budget.


([1](),[2]())
