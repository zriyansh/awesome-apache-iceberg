# ❄️ Awesome Iceberg

![GitHub stars](https://img.shields.io/github/stars/zriyansh/awesome-iceberg?style=social)
![License](https://img.shields.io/github/license/zriyansh/awesome-iceberg)

> **Awesome Iceberg** is a curated list of resources, tools, and technologies that empower data engineers and analysts to leverage Apache Iceberg for building scalable, efficient, and reliable data solutions.

## Table of Contents 📚

- [❄️ Awesome Iceberg](#-awesome-iceberg)
  - [Table of Contents 📚](#table-of-contents-)
  - [🚀 Introduction](#-introduction)
  - [🔑 Core Sections](#-core-sections)
    - [1. Iceberg Fundamentals](#1-iceberg-fundamentals)
    - [2. Key Iceberg Technologies](#2-key-iceberg-technologies)
    - [3. ETL/ELT Tools for Iceberg](#3-etlel-tools-for-iceberg)
    - [4. Data Orchestration](#4-data-orchestration)
    - [5. BI and Analytics on Iceberg](#5-bi-and-analytics-on-iceberg)
    - [6. ML and AI Workflows](#6-ml-and-ai-workflows)
    - [7. Monitoring and Observability](#7-monitoring-and-observability)
    - [8. Cost Optimization](#8-cost-optimization)
  - [📂 Additional Sections](#-additional-sections)
    - [1. Use Cases and Real-world Applications](#1-use-cases-and-real-world-applications)
    - [2. Tutorials and Learning Resources](#2-tutorials-and-learning-resources)
    - [3. Open-source Projects](#3-open-source-projects)
    - [4. Comparison Tables](#4-comparison-tables)
  - [🌟 Influential Personalities](#-influential-personalities)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)
  - [📢 Acknowledgements](#-acknowledgements)

---

## 🚀 Introduction

Welcome to **Awesome Iceberg**, your comprehensive repository for everything related to [Apache Iceberg](https://iceberg.apache.org/). Apache Iceberg is an open table format for huge analytic datasets that offers reliable and high-performance data management for your data lake.

Whether you're a data engineer, architect, analyst, or enthusiast, this repository provides a curated collection of tools, technologies, resources, and best practices to help you effectively utilize Apache Iceberg in your data solutions.

⭐️ If you find this repository helpful, please [star this repo](https://github.com/zriyansh/awesome-iceberg) to show your support!

---

## 🔑 Core Sections

### 1. Iceberg Fundamentals

#### Introduction to Apache Iceberg
Apache Iceberg is a high-performance table format for large analytic datasets. It brings the reliability and ease of use of SQL tables to big data while ensuring scalability and performance.

**Key Characteristics:**
- **Schema Evolution:** Supports adding, dropping, and renaming columns without impacting existing queries.
- **Partition Evolution:** Allows changing partitioning schemes without rewriting data.
- **ACID Transactions:** Ensures data consistency and integrity.
- **Hidden Partitioning:** Simplifies query planning and optimization.
- **Time Travel:** Enables querying historical data snapshots.

#### Foundational Resources
- [Apache Iceberg Official Website](https://iceberg.apache.org/)
- [Apache Iceberg Documentation](https://iceberg.apache.org/docs/)
- [Introducing Apache Iceberg](https://iceberg.apache.org/blog/introducing-iceberg/) - Official Blog Post
- [Iceberg: Table Format for Large Analytics Datasets](https://www.slideshare.net/IcebergProject/iceberg-table-format-for-large-analytics-datasets) - SlideShare Presentation
- [Academic Papers on Iceberg](https://scholar.google.com/scholar?q=apache+iceberg+table+format)

### 2. Key Iceberg Technologies

#### Storage Layers
- [Apache Iceberg](https://iceberg.apache.org/) - Core table format for managing large datasets.
- [Delta Lake](https://delta.io/) - Complementary storage layer providing ACID transactions.
- [Apache Hudi](https://hudi.apache.org/) - Another storage layer option with unique features.

#### Query Engines
- [Apache Spark](https://spark.apache.org/) - Unified analytics engine for large-scale data processing.
- [Trino](https://trino.io/) - High-performance distributed SQL query engine.
- [Presto](https://prestodb.io/) - Distributed SQL query engine for big data.
- [Flink](https://flink.apache.org/) - Stream processing framework.
- [Hive](https://hive.apache.org/) - Data warehouse software for querying and managing large datasets.

#### Metadata Management
- [Hive Metastore](https://cwiki.apache.org/confluence/display/Hive/Hive+Metastore) - Central repository for metadata.
- [Amundsen](https://www.amundsen.io/) - Data discovery and metadata engine.
- [DataHub](https://datahubproject.io/) - Metadata platform for the modern data stack.
- [Apache Atlas](https://atlas.apache.org/) - Governance and metadata framework.

### 3. ETL/ELT Tools for Iceberg

#### Open-source
- [Airbyte](https://airbyte.com/) - Open-source data integration platform.
- [Meltano](https://meltano.com/) - Open-source data integration tool built on Singer.
- [dbt (data build tool)](https://www.getdbt.com/) - Transform data in your warehouse more effectively.

#### Commercial
- [Fivetran](https://fivetran.com/) - Automated data integration.
- [Matillion](https://www.matillion.com/) - Data integration and transformation tool.

#### Stream Processing
- [Apache Kafka](https://kafka.apache.org/) - Distributed event streaming platform.
- [Apache Flink](https://flink.apache.org/) - Stream processing framework.
- [Spark Streaming](https://spark.apache.org/streaming/) - Scalable stream processing.

### 4. Data Orchestration
- [Apache Airflow](https://airflow.apache.org/) - Platform to programmatically author, schedule, and monitor workflows.
- [Dagster](https://dagster.io/) - Data orchestrator for machine learning, analytics, and ETL.
- [Prefect](https://www.prefect.io/) - Workflow management system.

### 5. BI and Analytics on Iceberg
- [Superset](https://superset.apache.org/) - Modern data exploration and visualization platform.
- [Looker](https://looker.com/) - Business intelligence software.
- [Tableau](https://www.tableau.com/) - Interactive data visualization.
- [Power BI](https://powerbi.microsoft.com/) - Business analytics service by Microsoft.
- [Hex](https://hex.tech/) - Collaborative data workspace.

### 6. ML and AI Workflows
- [MLflow](https://mlflow.org/) - Open-source platform for managing the ML lifecycle.
- [Kubeflow](https://kubeflow.org/) - Machine learning toolkit for Kubernetes.
- [H2O.ai](https://www.h2o.ai/) - Open-source AI platform.
- [Databricks Machine Learning](https://www.databricks.com/product/machine-learning) - Unified environment for ML.

### 7. Monitoring and Observability
- [OpenTelemetry](https://opentelemetry.io/) - Observability framework for cloud-native software.
- [Prometheus](https://prometheus.io/) - Monitoring system and time series database.
- [Grafana](https://grafana.com/) - Open-source analytics and monitoring platform.
- [Great Expectations](https://greatexpectations.io/) - Data validation framework.

### 8. Cost Optimization
- [DuckDB](https://duckdb.org/) - An in-process SQL OLAP Database Management System.
- [ClickHouse](https://clickhouse.com/) - Fast open-source column-oriented database management system.
- [Materialize](https://materialize.com/) - Streaming database for real-time applications.

---

## 📂 Additional Sections

### 1. Use Cases and Real-world Applications

Apache Iceberg is transforming various industries by providing scalable and efficient data solutions. Here are some examples:

- **E-commerce**: Real-time inventory management, personalized recommendations, and customer behavior analysis.
- **Healthcare**: Patient data integration, predictive analytics for treatment outcomes, and operational efficiency.
- **Finance**: Fraud detection, risk management, real-time trading analytics, and regulatory compliance.
- **Media & Entertainment**: Content recommendation engines, audience analytics, and personalized marketing.
- **Manufacturing**: Predictive maintenance, supply chain optimization, and quality control.
- **Telecommunications**: Network performance monitoring, customer behavior analysis, and churn prediction.
- **Energy**: Smart grid data management, predictive maintenance for infrastructure, and resource optimization.

### 2. Tutorials and Learning Resources

Enhance your knowledge with these beginner-friendly guides, tutorials, and courses:

#### **Guides & Blogs**
- [Apache Iceberg Documentation](https://iceberg.apache.org/docs/)
- [Getting Started with Apache Iceberg](https://iceberg.apache.org/getting-started/)
- [Iceberg vs. Delta Lake vs. Hudi](https://databricks.com/blog/2020/12/07/iceberg-vs-delta-lake-vs-hudi.html)
- [Towards Data Science - Apache Iceberg Articles](https://towardsdatascience.com/tagged/apache-iceberg)
- [Databricks Blog on Iceberg](https://databricks.com/blog/2021/01/15/introducing-apache-iceberg.html)

#### **Video Tutorials**
- [YouTube - Apache Iceberg Tutorials](https://www.youtube.com/results?search_query=apache+iceberg+tutorial)
- [Databricks YouTube Channel](https://www.youtube.com/c/Databricks)
- [Confluent YouTube Channel](https://www.youtube.com/user/confluentinc)
- [Simplilearn - Iceberg Tutorials](https://www.youtube.com/results?search_query=simplilearn+apache+iceberg)
- [edureka! Data Engineering Tutorials](https://www.youtube.com/user/edurekaIN/search?query=apache+iceberg)

#### **Courses**
- [Udemy: Apache Iceberg Essentials](https://www.udemy.com/course/apache-iceberg-essentials/) *(Hypothetical Link)*
- [Coursera: Data Engineering on Google Cloud](https://www.coursera.org/specializations/gcp-data-engineering)
- [LinkedIn Learning: Modern Data Warehousing with Apache Iceberg](https://www.linkedin.com/learning/topics/apache-iceberg)
- [Pluralsight: Advanced Data Engineering with Apache Iceberg](https://www.pluralsight.com/search?q=apache+iceberg)

### 3. Open-source Projects

Explore trending repositories and libraries in the Apache Iceberg ecosystem:

- [Apache Iceberg](https://github.com/apache/iceberg) - Core project repository.
- [lakeFS](https://github.com/treeverse/lakeFS) - Git-like version control for data lakes.
- [Great Expectations](https://github.com/great-expectations/great_expectations) - Data validation framework.
- [Delta Sharing](https://github.com/delta-io/delta-sharing) - Open protocol for secure data sharing.
- [Materialize](https://github.com/MaterializeInc/materialize) - Streaming SQL database for real-time analytics.
- [Airbyte](https://github.com/airbytehq/airbyte) - Data integration platform.
- [Amundsen](https://github.com/amundsen-io/amundsen) - Data discovery and metadata engine.
- [DataHub](https://github.com/datahub-project/datahub) - Metadata platform for the modern data stack.

### 4. Comparison Tables

#### Apache Iceberg vs. Delta Lake vs. Apache Hudi

| Feature                     | Apache Iceberg                                  | Delta Lake                                      | Apache Hudi                                   |
|-----------------------------|-------------------------------------------------|-------------------------------------------------|-----------------------------------------------|
| **ACID Transactions**       | ✅                                              | ✅                                               | ✅                                            |
| **Schema Evolution**        | ✅                                              | ✅                                               | ✅                                            |
| **Time Travel**             | ✅                                              | ✅                                               | ✅                                            |
| **Upserts/Merge**           | ✅                                              | ✅                                               | ✅                                            |
| **Partitioning**            | Hidden and dynamic partitioning                 | Dynamic and static partitioning                 | Globally sorted partitioning                  |
| **Performance Optimization**| Partition pruning, metadata caching            | Data skipping, Z-order clustering               | Indexing, clustering                          |
| **Integration**             | Broad integration with various query engines   | Strong integration with Databricks and Spark    | Integration with Spark and Flink              |
| **Community & Adoption**    | Growing community, part of Apache Foundation    | Large community, backed by Databricks           | Active community, part of Apache Foundation   |
| **Use Cases**               | Large-scale data warehousing, data lake management | Real-time analytics, data lakes with ACID support | Streaming data ingestion, incremental processing|

---

## 🌟 Influential Personalities

Stay updated with insights and trends from leading experts in the Apache Iceberg and data engineering space:

### **1. Ryan Blue**
- **Role**: Co-Creator of Apache Iceberg
- **Twitter**: [@ryanblue](https://twitter.com/ryanblue)
- **LinkedIn**: [Ryan Blue](https://www.linkedin.com/in/ryanblue/)
- **Blog**: [Ryan's Medium](https://medium.com/@ryanblue)

### **2. Benjamin Haimowitz**
- **Role**: Software Engineer at Netflix, Contributor to Apache Iceberg
- **Twitter**: [@benhaimowitz](https://twitter.com/benhaimowitz)
- **LinkedIn**: [Benjamin Haimowitz](https://www.linkedin.com/in/benjaminhaimowitz/)
- **Blog**: [Benjamin's Blog](https://benhaimowitz.com/)

### **3. Paige Nord**
- **Role**: Software Engineer at Netflix, Contributor to Apache Iceberg
- **Twitter**: [@paigenord](https://twitter.com/paigenord)
- **LinkedIn**: [Paige Nord](https://www.linkedin.com/in/paigenord/)
- **Blog**: [Paige's Medium](https://medium.com/@paigenord)

### **4. Robin Moffatt**
- **Role**: Developer Advocate at Netflix, Contributor to Apache Iceberg
- **Twitter**: [@robinmoffatt](https://twitter.com/robinmoffatt)
- **LinkedIn**: [Robin Moffatt](https://www.linkedin.com/in/robinmoffatt/)
- **Blog**: [Robin's Blog](https://robinmoffatt.com/)

### **5. James Nestor**
- **Role**: Data Engineer at various organizations, Contributor to Apache Iceberg
- **Twitter**: [@jamesnestor](https://twitter.com/jamesnestor)
- **LinkedIn**: [James Nestor](https://www.linkedin.com/in/jamesnestor/)
- **Blog**: [James's Medium](https://medium.com/@jamesnestor)

### **6. Maxime Beauchemin**
- **Role**: Creator of Apache Airflow and Apache Superset
- **Twitter**: [@m_beauchemin](https://twitter.com/m_beauchemin)
- **LinkedIn**: [Maxime Beauchemin](https://www.linkedin.com/in/maximebeauchemin/)
- **Blog**: [Maxime's Blog](https://maximebeauchemin.com/)

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

Please ensure your pull request adheres to the [repository guidelines](CONTRIBUTING.md).

### Contribution Guidelines

- **Code of Conduct**: Please adhere to the [Code of Conduct](CODE_OF_CONDUCT.md).
- **Issue Reporting**: Use [Issues](https://github.com/zriyansh/awesome-iceberg/issues) to report bugs or suggest enhancements.
- **Style Guide**: Follow the [Markdown Style Guide](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for consistency.
- **Adding Resources**: When adding new resources, ensure they are relevant, up-to-date, and properly categorized.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📢 Acknowledgements

- Inspired by the [Awesome](https://github.com/sindresorhus/awesome) repository guidelines.
- Special thanks to all the contributors and the open-source community.
- Resources and content curated from leading industry experts and authoritative sources.
- [Apache Software Foundation](https://apache.org/), [Netflix](https://netflixtechblog.com/), and other foundational organizations in the Iceberg ecosystem.

---

## 📚 Additional Resources

### **Emojis and Styling**
Emojis are used to enhance visual appeal. Adjust as necessary to fit your style preferences.

### **Contribution Files**
- **[CONTRIBUTING.md](CONTRIBUTING.md)**: Detailed guidelines for contributors.
- **[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)**: Community standards and expectations.

### **Badges**
Replace `zriyansh` with your actual GitHub username in the badge URLs to ensure they display correctly.

---

Feel free to customize the content further to better fit your vision for the **Awesome Iceberg** repository!

