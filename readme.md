# Awesome Apache Iceberg [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Apache Iceberg resources, tools, and learning materials

Apache Iceberg is an open table format for huge analytic datasets that provides ACID transactions, schema evolution, time travel, and unified batch and streaming data processing.

## Contents

- [Official Resources](#official-resources)
- [Key People](#key-people)
- [Conference Talks](#conference-talks)
- [Blog Posts & Articles](#blog-posts--articles)
- [Vendor Documentation](#vendor-documentation)
- [Open Source Tools](#open-source-tools)
- [Comparisons](#comparisons)
- [Books & Courses](#books--courses)
- [Community](#community)
- [Companies Using Iceberg](#companies-using-iceberg)
- [Podcasts](#podcasts)
- [Best Practices](#best-practices)
- [Performance Benchmarks](#performance-benchmarks)
- [Integration Guides](#integration-guides)
- [Ecosystem Tools](#ecosystem-tools)

## Official Resources

### Core Documentation
- **[Official Website](https://iceberg.apache.org)** - Main entry point with overview and features
- **[Documentation](https://iceberg.apache.org/docs/latest/)** - Comprehensive docs covering all libraries and integrations
- **[Specification](https://iceberg.apache.org/spec/)** - Official format specification (stable with new features each version)
- **[Multi-Engine Support](https://iceberg.apache.org/multi-engine-support/)** - Compatibility matrix for Spark, Flink, and Hive versions

### GitHub Repositories
- **[apache/iceberg](https://github.com/apache/iceberg)** - Core Java implementation (6.3k+ stars)
- **[apache/iceberg-python](https://github.com/apache/iceberg-python)** - PyIceberg - Python implementation (748 stars)
- **[apache/iceberg-rust](https://github.com/apache/iceberg-rust)** - Rust implementation (700+ stars)
- **[apache/iceberg-go](https://github.com/apache/iceberg-go)** - Go implementation with CLI tools (200+ stars)
- **[apache/iceberg-cpp](https://github.com/apache/iceberg-cpp)** - C++ implementation

## Key People

### Original Creators (Netflix)
- **Ryan Blue** - Co-creator, PMC Chair
  - [LinkedIn](https://www.linkedin.com/in/rdblue/) | [GitHub](https://github.com/rdblue)
- **Daniel Weeks** - Co-creator, PMC member
  - [LinkedIn](https://www.linkedin.com/in/daniel-weeks-a1946860/) | [GitHub](https://github.com/danielcweeks)
- **Jason Reid** - Co-founder Tabular
  - [LinkedIn](https://www.linkedin.com/in/jasonreid/)

### Active PMC Members & Contributors
- **Fokko Driesprong** - PMC member, very active contributor
  - [LinkedIn](https://www.linkedin.com/in/fokkodriesprong/) | [GitHub](https://github.com/fokko)
- **Total**: 21 PMC members, 32 committers as of December 2024

## Conference Talks

### Iceberg Summit
- **[Iceberg Summit 2024](https://www.youtube.com/playlist?list=PLkifVhhWtccxBSrKFPXOmjAFFEpeYii5K)** - All 32 recordings from inaugural summit (May 14-15, 2024)
  - Ryan Blue keynote: "The Quiet Revolution"
  - 2,200+ attendees, virtual and free
- **[Iceberg Summit 2025](https://www.youtube.com/playlist?list=PLkifVhhWtccxMcqWlXXFvjJybisFF7ESh)** - April 8 (in-person), April 9 (virtual)

### Major Conference Presentations
- **Flink Forward** - Regular Iceberg sessions on streaming analytics
  - "Streaming Event-Time Partitioning With Apache Flink and Apache Iceberg" - Julia Bennett (Netflix)
- **Data + AI Summit** - Annual Iceberg integration sessions
- **QCon** - Engineering practices and architectural patterns

## Blog Posts & Articles

### Introduction & Overview
- **[Apache Iceberg University](https://university.dremio.com/course/apache-iceberg)** - Your guide to learning concepts and practices
- **[Apache Iceberg: A Beginner's Complete Guide](https://www.datacamp.com/tutorial/apache-iceberg/)** - DataCamp's complete introduction

### Technical Deep Dives
- **[Iceberg at Netflix: Data Platform Architecture](https://netflixtechblog.com/)** - Netflix Engineering Team
- **[AutoOptimize: Netflix's Data Layout Optimization](https://netflixtechblog.com/optimizing-data-warehouse-storage-7b94a48fdcbe)** - Automatic file optimization at petabyte scale
- **[FastIngest: Low-latency Gobblin with Apache Iceberg](https://www.linkedin.com/blog/engineering/open-source/fastingest-low-latency-gobblin)** - LinkedIn's 45min to 5min latency reduction

### Migration Guides
- **[Your Guide to Migrating to an Apache Iceberg Lakehouse](https://www.dremio.com/blog/migration-guide-for-apache-iceberg-lakehouses/)** - Comprehensive migration strategies
- **[Migrating to Apache Iceberg: A Complete Guide](https://medium.com/@hugolu87/migrating-to-an-iceberg-lakehouse-key-architecture-considerations-08e636890ab5/)** - Medium article by Hugo Lu.

## Vendor Documentation

### Cloud Providers
- **AWS**
  - [AWS Prescriptive Guidance](https://aws.amazon.com/prescriptive-guidance/) - Best practices for Iceberg on AWS
  - [Amazon Athena](https://docs.aws.amazon.com/athena/) - Native Iceberg v1.4.2 support
  - [AWS Glue](https://docs.aws.amazon.com/glue/) - ETL jobs and Data Catalog integration
  - [Amazon EMR](https://docs.aws.amazon.com/emr/) - Support from version 6.5.0+

- **Google Cloud**
  - BigLake Iceberg Support - BigQuery integration
  - Dataproc Integration - Spark, Hive, Presto support
  - Cloud Storage - Native support as underlying storage

- **Microsoft Azure**
  - Azure Synapse Analytics - Added support in 2022
  - Azure Data Factory - Iceberg dataset support
  - Microsoft Fabric/OneLake - Iceberg shortcuts and virtual links
  - Microsoft Purview - Native Iceberg governance (public preview)

### Data Platforms
- **Databricks**
  - Managed Iceberg tables through Unity Catalog
  - REST Catalog API for external engines
  - UniForm for Delta-Iceberg interoperability

- **Snowflake**
  - Generally available Iceberg tables support
  - External volume configuration
  - Cross-cloud/cross-region support
  - Support for Iceberg v1 and v2 specifications

- **Dremio**
  - Native Iceberg support (v21.0+)
  - Built-in catalog based on Apache Polaris
  - Automated data maintenance operations

- **Tabular** (Acquired by Databricks June 2024)
  - Founded by Iceberg creators
  - No longer accepting new signups

## Open Source Tools

### Catalog Implementations
- **[Project Nessie](https://github.com/projectnessie/nessie)** - Git-like version control for data (1.2k stars)
- **[Lakekeeper](https://github.com/lakekeeper/lakekeeper)** - Secure REST catalog with fine-grained access control (350+ stars)
- **Apache Polaris** - Snowflake's open-source metadata catalog (merging with Nessie)

### Migration Tools
- **[Iceberg Catalog Migrator](https://github.com/projectnessie/iceberg-catalog-migrator)** - Bulk migration between catalogs
- **[Apache XTable](https://github.com/apache/xtable)** - Cross-table converter for Delta, Hudi, Iceberg (800+ stars)

### REST Catalog Implementations
- **[Tabular Iceberg REST](https://github.com/tabular-io/iceberg-rest-image)** - Docker image for REST API (200+ stars)
- **[Cloudcheflabs Iceberg REST Catalog](https://github.com/cloudcheflabs/iceberg-rest-catalog)** - Easy-to-deploy server

## Comparisons

### Iceberg vs Delta Lake vs Hudi
- **Engine Support**: Iceberg has broadest multi-engine support (Spark, Trino, Flink, Presto, Hive, Impala)
- **Vendor Independence**: 100% open source under Apache governance
- **Schema Evolution**: In-place evolution without table rewrites
- **Performance**: Faster updates and deletes compared to alternatives
- **Maintenance**: Simpler operating model, no compaction required

### When to Choose Iceberg
- Multi-engine environments requiring vendor neutrality
- Large-scale analytics with complex schema evolution needs
- Cloud-native architectures with multiple storage systems
- Real-time and batch processing hybrid workloads

## Books & Courses

### Books
- **[Apache Iceberg: The Definitive Guide](https://www.dremio.com/wp-content/uploads/2023/02/apache-iceberg-TDG_ER1.pdf)** - O'Reilly Media
  - Authors: Tomer Shiran, Jason Hughes, Alex Merced (Dremio)
  - Comprehensive guide covering fundamentals to production

### Online Courses
- **Dremio University**
  - "Introduction to Apache Iceberg" by Alex Merced
  - Advanced Analytics Course by Andrew Madson
- **Apache Iceberg 101 Course Series**
  - Video course with hands-on exercises
  - Topics: Data Lakehouse concepts, transactions, catalogs, time-travel

## Community

### Communication Channels
- **[Slack Workspace](https://iceberg.apache.org/community/)** - Primary community channel
  - Channels: #jobs, #python, #meetup-{city}, vendor-{company}
- **Mailing Lists**
  - dev@iceberg.apache.org - Community discussions
  - commits@iceberg.apache.org - Commit notifications
  - issues@iceberg.apache.org - Github issue tracking
  - private@iceberg.apache.org - Private discussions for PMC members

### Community Events
- **[Iceberg Community Events](https://calendar.google.com/calendar/u/0?cid=NTkzYmIwMGJmZTQ1N2QzMTkxNDEzNTBkZDI0Yzk2NGYzOWJkYmQ5ZmQyNDMyODFhODYzMmEwMDk2M2EyMWQ4NkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)** - Events such as conferences and meetups, aimed to educate and inspire Iceberg users.
- **[Iceberg Dev Events](https://calendar.google.com/calendar/u/0?cid=MzkwNWQ0OTJmMWI0NTBiYTA3MTJmMmFlNmFmYTc2ZWI3NTdmMTNkODUyMjBjYzAzYWE0NTI3ODg1YWRjNTYyOUBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)** - Events such as the triweekly Iceberg sync, aimed to discuss the project roadmap and how to implement features.
**Iceberg Summit** - Annual conference (2,200+ attendees in 2024)
- **Meetup Groups** - Active in Bay Area, NYC, Seattle, Chicago, Boston, Atlanta, Austin, Orlando
- **Community Syncs** - Regular online meetings for project updates

### Development
- **[GitHub Issues](https://github.com/apache/iceberg/issues)** - Bug reports and feature requests
- **[Contributing Guide](https://iceberg.apache.org/contribute/)** - How to contribute

## Companies Using Iceberg

### Major Production Users
- **Netflix** - Original creator, 1M+ tables, petabyte-scale daily processing
  - Query planning: 9.6min (Hive) → 42sec (Iceberg)
- **Adobe** - 13TB/day processing, 80% of cloud data lake on Iceberg
- **Airbnb** - 50% compute resource savings, 40% job time reduction
- **LinkedIn** - Kafka ingestion reduced from 45min to 5min
- **Apple** - AIML data platform with Flink streaming
- **Stripe**, **Expedia**, **Lyft**, **Alibaba**, **Salesforce**

## Podcasts

### Data Engineering Podcast
- Ryan Blue: "The Evolution and Applications of the Iceberg Table Format"
- Jason Reid: Focus on open-source modern data stack
- Kevin Liu (Stripe): Trino and Iceberg for analytical workloads
- Tulika Bhatt (Netflix): Large-scale data processing

### The Data Stack Show
- Regular discussions on Apache Iceberg developments
- Open table format standards analysis

## Best Practices

### Table Design & Schema Evolution
- AWS Prescriptive Guidance - Format recommendations, compression (ZSTD)
- Cloudera Best Practices - Production-proven from TPC-DS benchmarking

### Performance Tuning
- Partitioning strategies and hidden partitioning benefits
- Compaction techniques (binpack, sort, Z-order)
- File size optimization and clustering

### Production Deployment
- Snapshot management and expiration policies
- Orphan file cleanup procedures
- Multi-engine architecture considerations

## Performance Benchmarks

### Third-Party Studies
- **Synvert 2022** - Iceberg fastest for inserts, updates (10x faster than Delta), deletes
- **Brooklyn Data TPC-DS** - Performance variations across workload types

### Real-World Metrics
- **Netflix**: 10x performance improvement with clustered data
- **Adobe**: 15 commits/minute in production
- **AWS Financial Services**: Better metadata handling, reduced task failures

## Integration Guides

### Compute Engines
- **Apache Spark** - Native DataSource V2 API, full SQL DDL/DML support
- **Apache Flink** - Streaming writes, CDC support, exactly-once semantics
- **Trino/Presto** - Native connector with multiple catalog support

### Query Engines
- **Dremio** - Built-in Polaris catalog, time travel
- **Starburst** - Kafka to Iceberg streaming ingestion
- **Amazon Athena** - Native support with AWS Glue integration

### File Formats
- **Apache Parquet** - Default and primary format
- **Apache ORC** - Optional support via iceberg-orc module
- **Apache Avro** - Often used for streaming scenarios

## Ecosystem Tools

### CLI Tools
- **Iceberg Diagnostic Tool** (Upsolver) - Performance analysis (`brew install iceberg-diag`)
- **Iceberg Go CLI** - Command-line operations
- **Nessie CLI** - Git-like operations for Nessie catalogs

### Monitoring & Observability
- **DQOps** - Data quality monitoring with native Iceberg support
- **Rakuten SixthSense** - Purpose-built observability for Iceberg
- **AWS CloudWatch Integration** - Lambda-based metrics collection

### Development Tools
- **[Ducklake](https://github.com/ziwon/ducklake)** - Lightweight data lake with DuckDB (100+ stars)
- **Tabulario Docker Images** - Pre-configured Spark + Iceberg environments

### Governance & Security
- **AWS Lake Formation** - Fine-grained access control
- **Lakekeeper Authorization** - OpenFGA-based access control
- **Built-in Auditing** - Stage changes for validation before commits

---


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
