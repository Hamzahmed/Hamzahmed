# Hamza Ahmed

**Senior Software, Data & AI Engineer**

I build production data platforms, real-time and batch pipelines, backend integrations, cloud infrastructure, and applied AI systems. Over 7+ years, I have worked across startups, consulting, and product teams—owning systems from ingestion and orchestration through modeling, APIs, deployment, observability, and the workflows people use on top of the data.

My recent work focuses on combining strong data engineering foundations with automation, LLMs, and agentic systems that solve real operational problems.

[Knownbyfew](https://knownbyfew.com) · [Martian Bee](https://martianbee.com) · [hamza@knownbyfew.com](mailto:hamza@knownbyfew.com)

## Currently building

### [Martian Bee](https://martianbee.com)

Martian Bee is a private B2B analytics platform I am building as founder and engineer. It brings together a Rust-based execution layer, Apache DataFusion and Arrow, Delta Lake, PostgreSQL, CDC ingestion, semantic metrics, and AI-assisted querying to make advanced analytics infrastructure more accessible to smaller teams.

It is also where I bring together the full range of my work: product design, data architecture, backend engineering, infrastructure, applied AI, and production-quality delivery. Martian Bee is in active development, so the core source code and deeper product architecture remain private for now.

## A few selected public engineering projects

### [MongoDB to PostgreSQL CDC with SCD2 History](https://github.com/Hamzahmed/mongodb-postgres-cdc-scd2)

A queue-first snapshot and change-data-capture service that moves MongoDB records into PostgreSQL while maintaining ordered event processing, durable resume state, complete SCD2 history, and a current-state view.

**Highlights:** MongoDB change streams, PostgreSQL landing queues, idempotent ingestion, event ordering, delete handling, Docker-based local demo, and automated tests.

### [MongoDB CDC to S3 with Recovery and Backfill](https://github.com/Hamzahmed/mongodb-s3-cdc-recovery)

A configurable ingestion platform for streaming and scheduled MongoDB data into partitioned object storage, with recovery paths designed for real operational failure modes.

**Highlights:** initial snapshots, continuous CDC, GZIP JSONL output, checksums, multipart S3 uploads, resume tokens, recovery markers, bounded backfills, targeted patch workflows, and local object-store support.

### [Databricks LLM Content Pipeline with Human Review](https://github.com/Hamzahmed/databricks-llm-content-pipeline)

A registry-driven Databricks workflow that filters source material, generates structured content with LLMs, routes valid and invalid results, and prepares outputs for human review.

**Highlights:** PySpark, Delta Lake, model-based relevance filtering, deterministic pre-screening, retries and backoff, Unity Catalog Volumes, registry state transitions, optional Slack and Google Drive delivery, and safe migration utilities.

## What I have built

- Real-time and batch data platforms processing millions of records per day across MongoDB, Kafka, Amazon S3, Databricks, Snowflake, and PostgreSQL.
- Cloud data systems across AWS, GCP, and Azure for organizations including Google, Nike, Epic Games, and Hitachi Energy.
- Streaming, CDC, orchestration, and transformation systems using Kafka, Pub/Sub, Airflow/MWAA, dbt, Spark, AWS Glue, Fivetran, and Airbyte.
- Agentic and LLM-powered workflows for research, content generation, customer support, moderation, natural-language data access, and stakeholder automation.
- Analytics and metric systems spanning Snowflake, Databricks, BigQuery, Redshift, Sigma, Tableau, and Looker Studio.
- Infrastructure and delivery workflows using Terraform, Docker, Kubernetes, GitHub Actions, CircleCI, and cloud-native compute services.

Some measurable outcomes from that work include a 96% reduction in pipeline infrastructure cost, a 30% reduction in Athena query cost with a 45% speed improvement, and substantial reductions in manual support time, fraud, and platform abuse.

## Technical focus

**Languages**  
Python, SQL, Rust, Go, TypeScript, Bash

**Data platforms and storage**  
Snowflake, Databricks, BigQuery, Redshift, PostgreSQL, MongoDB, ClickHouse, Delta Lake

**Data engineering and orchestration**  
Spark / PySpark, dbt, Airflow / MWAA, Kafka, Pub/Sub, Fivetran, Airbyte, AWS Glue, Dataflow, CDC, ETL / ELT, SCD2

**Cloud and infrastructure**  
AWS, GCP, Azure, Terraform, Docker, Kubernetes, GitHub Actions, CircleCI

**AI and agentic systems**  
OpenAI-compatible APIs, LangChain, LlamaIndex, RAG, FAISS, BERT, MCP integrations, Databricks Genie / GenieAgent, structured generation, relevance filtering, and human-review workflows

## Background

Before moving fully into software and data engineering, I studied physics and mathematics and worked in astrophysics research. That included mathematical modeling around Einstein field equations, machine-learning experiments with Keras and TensorFlow, and processing observatory data for analysis.

That background still shapes how I work: define the system clearly, test assumptions, trace evidence, and treat reliability as part of the design rather than something added at the end.

## Freelance work

Through [Knownbyfew](https://knownbyfew.com), I work with teams that need senior-level help building or improving:

- data platforms, warehouses, and lakehouse architecture;
- ETL / ELT, CDC, streaming, orchestration, and data-quality systems;
- backend integrations, APIs, and operational automation;
- Snowflake, Databricks, AWS, GCP, PostgreSQL, and MongoDB systems;
- applied AI and agentic workflows built on production data;
- engineering processes for safely using AI coding agents.

I am most useful on projects that need someone who can move between architecture, implementation, debugging, infrastructure, and delivery without treating them as separate problems.

---

The public repositories above are a **few selected, anonymized reference implementations** based on systems I designed and built. They use synthetic data and contain no client credentials, proprietary configuration, private datasets, or confidential business logic.
