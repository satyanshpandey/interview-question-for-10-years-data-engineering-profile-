# 🧠 DATA ENGINEER INTERVIEW – **CRAFTED QUESTIONS**

**Experience Level: 10+ Years**

---

## 🟢 EASY LEVEL (15 – Concept Clarity)

1. **Can you explain what Data Engineering is and how it is different from Data Analytics?**
2. **How would you explain the difference between Data Lake and Data Warehouse to a non-technical stakeholder?**
3. **What role does PySpark play in large-scale data processing?**
4. **When you say Spark uses lazy evaluation, what exactly happens under the hood?**
5. **How would you describe Apache Airflow to someone who has never used it?**
6. **What is a DAG in Airflow, and why is it important for pipeline orchestration?**
7. **In which scenarios would you prefer batch processing over streaming?**
8. **What problem does AWS Glue solve in a data engineering ecosystem?**
9. **How do you typically use Amazon S3 in a data pipeline?**
10. **Why is partitioning important when dealing with large datasets?**
11. **How would you differentiate OLTP systems from OLAP systems using a real example?**
12. **What do you mean by schema-on-read, and where have you used it?**
13. **What is a fact table, and what kind of data does it usually store?**
14. **What is the responsibility of an executor in Spark?**
15. **How do you decide whether to implement ETL or ELT in a project?**

---

## 🟡 MEDIUM LEVEL (30 – Real-world + Hands-on)

16. **Can you walk me through Spark’s architecture and explain how a Spark job is executed end to end?**
17. **How do you decide whether to use RDDs or DataFrames in a production pipeline?**
18. **What exactly happens during a shuffle operation, and why is it expensive?**
19. **Can you explain narrow and wide transformations with production examples?**
20. **How does Spark achieve fault tolerance, and what happens when an executor fails?**
21. **In what situations would you use a broadcast join, and how does Spark perform it internally?**
22. **You notice severe data skew in a Spark job—how would you identify and fix it?**
23. **How do repartition and coalesce differ, and when would you use each?**
24. **When and why do you cache or persist a DataFrame in Spark?**
25. **How do window functions help in analytics queries, and can you give a real use case?**
26. **If a SQL query is running slow on a large table, how would you approach optimizing it?**
27. **How do AWS Glue Crawlers work, and when would you avoid using them?**
28. **What are Glue Job Bookmarks, and how do they help with incremental data processing?**
29. **How do you choose between AWS Glue and EMR for a given use case?**
30. **How does Airflow XCom work, and what are its limitations?**
31. **If a DAG fails in production, how do you debug and recover it?**
32. **What is backfilling in Airflow, and what precautions should be taken while doing it?**
33. **How do SLAs work in Airflow, and how do you monitor them?**
34. **Can you explain CDC and the challenges involved in implementing it?**
35. **How do SCD Type 1 and Type 2 differ, and when would you use each?**
36. **Why are columnar formats like Parquet preferred over CSV in big data systems?**
37. **How do you secure data stored in Amazon S3?**
38. **Can you explain how IAM roles are used in data pipelines?**
39. **What is the difference between at-least-once and exactly-once processing, and where does it matter most?**
40. **How does partition pruning improve query performance?**
41. **How do you design incremental data pipelines in a large system?**
42. **What role does metadata play in a data engineering platform?**
43. **How do you handle late-arriving data in batch or streaming pipelines?**
44. **How do you track data lineage in a production environment?**
45. **What strategies do you use to optimize cost for data workloads on AWS?**

---

## 🔴 HARD LEVEL (15 – Architecture + Leadership)

46. **Can you design a real-time data pipeline on AWS and explain your technology choices?**
47. **How does Spark manage memory internally, and how does it impact performance?**
48. **When dealing with very large joins, how do you tune Spark to avoid performance bottlenecks?**
49. **How would you process billions of records efficiently using AWS Glue?**
50. **What best practices do you follow while building Airflow DAGs for production systems?**
51. **A Spark job is running much slower than expected—how do you systematically debug it?**
52. **How do you design a data model optimized for analytical workloads?**
53. **How do you manage schema evolution without breaking downstream consumers?**
54. **How do you ensure idempotency in data pipelines?**
55. **How does watermarking work in streaming systems, and why is it important?**
56. **How does Spark Structured Streaming differ from Kafka Streams?**
57. **How do you implement data quality checks at scale?**
58. **How would you design a multi-region data architecture for high availability?**
59. **When would you prefer Glue over Databricks, or vice versa?**
60. **How would you approach migrating a large on-prem ETL system to AWS?**

---

## 💻 PROGRAM / QUERY BASED (10 – Practical)

61. **Given an employee table with multiple records per employee, how would you identify and keep only the latest record using SQL?**
62. **How would you write a SQL query to find the second highest salary in each department?**
63. **How do you design a SQL-based incremental load using a last-processed timestamp?**
64. **Using PySpark, how would you read a CSV file, clean invalid records, and write it as partitioned Parquet data?**
65. **How would you use PySpark DataFrame APIs to identify the top three products by total sales?**
66. **How would you optimize a join between a very large fact table and a small dimension table in Spark?**
67. **How would you implement SCD Type 2 logic using SQL?**
68. **Can you design an Airflow DAG that performs extract, transform, and load operations with retries and SLA monitoring?**
69. **How would you write an AWS Glue PySpark job to read data from S3, transform it, and write partitioned output back to S3?**
70. **How would you design a Spark Structured Streaming job to consume Kafka data and perform time-based aggregations?**



--------------------------------------------------------------------------------------------------------------------------------


