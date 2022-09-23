# Serverless Spark Solution Accelerators

Apache Spark is often used for interactive queries, machine learning, and real-time workloads.<br>

Spark developers are typically spending only 40% of time writing code while spending 60% tuning infrastructure and managing clusters.  There's a better way.<br>

Google Cloud customers have used our auto-scaling, serverless Spark to boost productivity and reduce infrastructure costs.<br>

This repository contains Serverless Spark on GCP solution accelerators built around common use cases - helping data engineers and data scientists with Apache Spark experience ramp up faster on [Serverless Spark on GCP](https://cloud.google.com/dataproc-serverless/docs).<br>


# Feedback From Serverless Spark Users
- "Our use case is to optimize retail assortment from 500M+ items.  Serverless Spark enables us to only use the compute resources when we need them and all with a single click."<br>
~ Dataproc customer who set up these production pipelines in one week<br><br>

- “Job that took 90 minutes on a manually tuned cluster took 19 minutes to finish with Serverless Spark.”<br> 
~ Principal Architect at multinational retail corporation



# What's Covered?
| # | Solution Accelerators | Focus | Feature | Contributed By |
| -- | :--- | :-- | :-- | :-- |
| 1 | [Anomaly Detection](cell-tower-anomaly-detection-dbt/README.md) | Data Engineering | Rules based processing to detect defective cell towers requiring maintenance via Serverless Spark Batch + BigLake to create GCS external tables in PARQUET and CSV + dbt to implement a data pipeline + Terraform to deploy required cloud infrastructure | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) and [Anagha Khanolkar](https://github.com/anagha-google) then refactored by [Luis Velasco](https://github.com/velascoluis) to include BigLake, dbt, and Terraform |
| 2 | [Retail Store Analytics](retail_store_analytics_metastore/README.md) | Data Analysis | Analysis of retail data to identify product sales, and recommend product aisles and inventory via Serverless Spark Batch from CLI with Cloud Composer orchestration and Dataproc Metastore | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 3 | [Pandemic Economic Impact](covid-economic-impact-vertex-ai/README.md) | Data Analysis | Vertex AI notebooks with Serverless Spark session | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 4 | [Time Series Forecasting of Sales](timeseries_forecasting/README.md) | Data Analysis | Vertex AI notebooks with Serverless Spark session | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 4 | [Real-Time Streaming of Customer Invoices](serverless_spark_streaming/README.md) | Spark Streaming | Serverless Spark Dataproc Batches | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 6 | [Malware Detection](malware_detection/README.md) | Data Analysis | Serverless Spark Batch from CLI with Cloud Composer orchestration | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 7 | [Social Media Data Analytics](social_media_data_analytics/README.md) | Data Analysis | Vertex AI notebooks with Serverless Spark session | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 8 | [Anomaly Detection (with Dataproc UI Instructions)](cell-tower-anomaly-detection-dataproc-ui/README.md) | Data Engineering | Serverless Spark Batch from CLI with Cloud Composer orchestration, Dataproc UI instructions, and the Persistent History Server (for viewing completed and running Spark jobs) | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 9 | [Pandemic Economic Impact (Batches)](covid-economic-impact-batches/README.md) | Data Engineering | Serverless Spark Dataproc Batches | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 10 | [Retail Store Analytics - Spark SQL](retail_store_analytics_metastore_sparksql/README.md) | SQL Data Analysis | Spark SQL run on Serverless Spark Batch with Dataproc Metastore | [TEKsystems](https://www.teksystems.com/en/about-us/partnerships/google-cloud) |
| 11 | [Telco Customer Churn Prediction](https://github.com/anagha-google/s8s-spark-mlops) | ML Ops | Powered by Dataproc Serverless, showcasing integration with Vertex AI Workbench | [Anagha Khanolkar](https://github.com/anagha-google) |
| 12 | [Sales and Marketing Campaign and Promotion Streaming Application](https://github.com/anagha-google/spark-on-gcp-with-confluent-kafka) | Streaming Analytics | Streaming from Kafka into BigQuery, with Apache Spark Structured Streaming powered by Dataproc Serverless | [Anagha Khanolkar](https://github.com/anagha-google) |

# Contributing
See the [contributing instructions](CONTRIBUTING.md) to start contributing.

# License
All solutions within this repository are provided under the Apache 2.0 license.  Please see the [LICENSE file](LICENSE) for more detailed terms and conditions.

# Disclaimer
This repository and its contents are not an official Google Product.

# Serverless Spark Templates
Check out this [repository](https://github.com/GoogleCloudPlatform/dataproc-templates/blob/main/README.md) for Dataproc Serverless ready-to-use, config driven Spark templates for solving simple, but large, in-Cloud data tasks, including data import/export/backup/restore and bulk API operations.

# Contact
Interested in a free, guided, and hands-on Spark Workshop to run these solution accelerators in your GCP environment?  Please fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSeNB5IK6Fk0Tz1kBuLbCPIOBmG64KCxduY-JUi1-nGJAiOFbQ/viewform?resourcekey=0-7zyKJwrk3goAImmNjeV2ng).

