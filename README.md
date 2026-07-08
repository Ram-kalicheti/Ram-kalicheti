<!-- Ram-kalicheti/Ram-kalicheti profile README -->

<img src="assets/header.svg" width="100%" alt="Sitha Ram Reddy Kalicheti - Data Engineer" />

<p align="left">
  <a href="https://linkedin.com/in/sitharamreddykalicheti"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sitharamreddykalicheti@gmail.com"><img src="https://img.shields.io/badge/Email-24292F?style=flat&logo=gmail&logoColor=EA4335" alt="Email"/></a>
  <a href="https://github.com/Ram-kalicheti"><img src="https://img.shields.io/badge/GitHub-24292F?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Virginia,%20USA-24292F?style=flat&logo=googlemaps&logoColor=4C9AFF" alt="Location"/>
  <img src="https://img.shields.io/badge/DP--700-0A66C2?style=flat&logo=microsoft&logoColor=white" alt="DP-700"/>
  <img src="https://img.shields.io/badge/AZ--104-0A66C2?style=flat&logo=microsoftazure&logoColor=white" alt="AZ-104"/>
</p>

### About

Data engineer with 3+ years of enterprise delivery at Infosys, building cloud data integration platforms on Azure for Big 4 clients across SAP SuccessFactors, Salesforce, and Workday ecosystems. Recent work focuses on streaming and lakehouse architecture: exactly-once processing, tested transformations, and governance an auditor could sign off on. I care most about the parts people skip, replay safety, data quality gates, honest model evaluation, and documenting what broke and why.

`Open to Data Engineer and AI Data Engineer roles - Azure · Databricks · Streaming - Virginia, USA`

### Core Stack

**Platform**
&nbsp;
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Azure%20Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat&logo=databricks&logoColor=white)
![Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0A66C2?style=flat&logo=microsoft&logoColor=white)

**Pipeline**
&nbsp;
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Event Hubs](https://img.shields.io/badge/Event%20Hubs-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**ML & Serving**
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Data & Governance**
&nbsp;
![SQL](https://img.shields.io/badge/SQL-0A66C2?style=flat&logo=postgresql&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-FF3621?style=flat&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### Featured Work

**[Sentinel](https://github.com/Ram-kalicheti/sentinel)** &nbsp; Real-time financial fraud intelligence on Azure Databricks

Transactions stream through Event Hubs into a bronze-silver-gold medallion in Delta Lake with exactly-once processing and idempotent MERGE, are scored by an XGBoost model behind an MLflow promotion gate, and surface on a fraud-analyst dashboard governed by Unity Catalog. The model is gated: it ships only if it clears a cross-validated bar, and in this build it did not, so the pipeline held it back and the dashboard says so plainly. Serving runs at 17ms P99 off a Redis feature store.

`Azure Databricks` `Spark Structured Streaming` `Delta Lake` `Event Hubs` `Airflow` `dbt Core` `MLflow` `Unity Catalog` `FastAPI` `Redis`

**[Meridian](https://github.com/Ram-kalicheti/meridian)** &nbsp; Multi-tenant AI document intelligence on Microsoft Fabric

A cross-tenant medallion pipeline embeds documents into Azure AI Search for hybrid vector and BM25 retrieval, served through a token-governed API with release-gating on retrieval quality. RAGAS context precision reached 0.92 against a 0.85 gate, with per-tenant token budgets enforced at the API Management layer and Redis semantic caching.

`Microsoft Fabric` `Azure Data Factory` `Azure OpenAI` `Azure AI Search` `APIM` `FastAPI` `Terraform` `Power BI`

<sub>More: <a href="https://github.com/Ram-kalicheti/cloud-observability-agent">Multi-Cloud Observability Agent</a> · <a href="https://github.com/Ram-kalicheti/self-healing-infra">Self-Healing Infrastructure</a></sub>

### Experience

**Infosys** &nbsp; Data Engineer (Systems Engineer to Technology Analyst) &nbsp; · &nbsp; Oct 2021 - Dec 2024

Delivered cloud data integration platforms on Azure for Big 4 clients (KPMG, PwC) across SAP SuccessFactors, Salesforce, and Workday ecosystems. Consolidated legacy point-to-point integrations into unified, orchestrated pipelines, cutting client operating costs and manual handoffs. Left December 2024 to pursue an M.S. in Applied Information Technology at George Mason University.

### Certifications

![DP-700](https://img.shields.io/badge/DP--700%20Fabric%20Data%20Engineer%20Associate-0A66C2?style=for-the-badge&logo=microsoft&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104%20Azure%20Administrator%20Associate-0A66C2?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AZ-900](https://img.shields.io/badge/AZ--900%20Azure%20Fundamentals-24292F?style=for-the-badge&logo=microsoftazure&logoColor=white)

<sub><i>Invisible when it works, obvious when it breaks. I build the parts that keep working.</i></sub>
