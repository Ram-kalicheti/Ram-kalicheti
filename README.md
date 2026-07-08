<!-- Ram-kalicheti/Ram-kalicheti profile README -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6d28d9,100:7c3aed&height=200&section=header&text=Sitha%20Ram%20Reddy%20Kalicheti&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Engineer%20%7C%20Azure%20%C2%B7%20Databricks%20%C2%B7%20Streaming&descAlignY=55&descSize=18" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=800&color=8B5CF6&center=true&vCenter=true&width=650&lines=Building+streaming+data+platforms+on+Azure;Delta+Lake+%C2%B7+dbt+%C2%B7+Airflow+%C2%B7+MLflow;Governance+first%2C+honest+metrics+always" alt="Typing SVG" /></a>

<br/>

![Location](https://img.shields.io/badge/Virginia,%20USA-6d28d9?style=flat-square&logo=googlemaps&logoColor=white)
![Degree](https://img.shields.io/badge/M.S.%20Applied%20IT%20@%20GMU-4c1d95?style=flat-square&logo=googlescholar&logoColor=white)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sitharamreddykalicheti)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sitharamreddykalicheti@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Ram-kalicheti&style=flat-square&color=6d28d9)

</div>

---

## About

Data engineer with 3+ years of enterprise delivery at Infosys, building cloud data integration platforms on Azure for Big 4 clients across SAP SuccessFactors, Salesforce, and Workday ecosystems. I design pipelines that hold up in production: exactly-once processing, tested transformations, and governance that a real auditor could sign off on.

My recent work focuses on streaming and lakehouse architecture. I care most about the parts people skip, replay safety, data quality gates, honest model evaluation, and documenting what broke and why.

```
Open to  :  Data Engineer roles (Azure / Databricks / streaming)
Based in :  Virginia, USA
Focus    :  Lakehouse architecture, streaming pipelines, ML platform engineering
```

---

## Tech Stack

**Cloud & Platforms**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Azure%20Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Event Hubs](https://img.shields.io/badge/Event%20Hubs-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Container Apps](https://img.shields.io/badge/Container%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Data Engineering**

![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=databricks&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-FF3621?style=flat-square&logo=databricks&logoColor=white)

**ML & Serving**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=xgboost&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Languages & Tooling**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## Featured Projects

<details open>
<summary><b>Sentinel: Real-Time Financial Fraud Intelligence Platform</b></summary>

<br/>

Real-time fraud detection on Azure Databricks. Transactions stream through Event Hubs into a bronze-silver-gold medallion in Delta Lake, get scored by an XGBoost model behind an MLflow promotion gate, and surface on a fraud-analyst dashboard governed by Unity Catalog.

| | |
|---|---|
| **Stack** | Azure Databricks, Spark Structured Streaming, Delta Lake, Event Hubs, Apache Airflow, dbt Core, MLflow, XGBoost, Unity Catalog, FastAPI, Redis |
| **Engineering** | Exactly-once ingestion with idempotent Delta MERGE, dead-letter routing, SCD2 customer history via CDC-aware merge |
| **Serving** | FastAPI scorer at 17ms P99 backed by a Redis online feature store |
| **Governance** | Unity Catalog PII column tags, row-level security, documented lineage |
| **Honesty** | Model held back by a cross-validated promotion gate and reported plainly, no inflated accuracy |
| **Repo** | [github.com/Ram-kalicheti/sentinel](https://github.com/Ram-kalicheti/sentinel) |

The part I am most deliberate about is the promotion gate: a pipeline that refuses to ship a model that has not cleared its bar is worth more than one that pretends. The dashboard reports that honestly next to the serving surface.

</details>

<details>
<summary><b>Meridian: Multi-Tenant AI Document Intelligence Platform</b></summary>

<br/>

Multi-tenant document intelligence on Microsoft Fabric. A cross-tenant medallion pipeline embeds documents into Azure AI Search for hybrid retrieval, served through a token-governed API with release-gating on retrieval quality.

| | |
|---|---|
| **Stack** | Microsoft Fabric, Azure Data Factory, Azure OpenAI, Azure AI Search, FastAPI, Redis, Azure API Management, Container Apps, Terraform, Python, PySpark, Power BI |
| **Engineering** | Cross-tenant service-principal auth, 6-check data quality suite, hybrid vector and BM25 retrieval |
| **Serving** | RAG-powered FastAPI with SSE streaming, per-tenant token governance via APIM, Redis semantic caching |
| **Quality gate** | RAGAS context precision reached 0.92 against a 0.85 release gate |
| **Repo** | [github.com/Ram-kalicheti/meridian](https://github.com/Ram-kalicheti/meridian) |

</details>

<details>
<summary><b>Multi-Cloud Observability Agent</b></summary>

<br/>

An anomaly-detection agent spanning AWS and Azure, correlating metrics across clouds and surfacing incidents through a lightweight API and UI.

| | |
|---|---|
| **Stack** | Python, FastAPI, scikit-learn, OpenAI API, AWS Lambda, CloudWatch, DynamoDB, Azure Functions, Cosmos DB, React, Docker, GitHub Actions |
| **Focus** | Real multi-cloud breadth, serverless event processing, anomaly detection |
| **Repo** | [github.com/Ram-kalicheti/cloud-observability-agent](https://github.com/Ram-kalicheti/cloud-observability-agent) |

</details>

<details>
<summary><b>Self-Healing Infrastructure with Chaos Engineering</b></summary>

<br/>

Multi-cloud infrastructure that detects failures and recovers automatically, exercised with chaos experiments across AWS EKS and Azure AKS.

| | |
|---|---|
| **Stack** | Terraform, AWS EKS, Azure AKS, Kubernetes, Helm, Prometheus, Grafana, Python |
| **Focus** | Infrastructure-as-code, chaos engineering, automated recovery and observability |
| **Repo** | [github.com/Ram-kalicheti/self-healing-infra](https://github.com/Ram-kalicheti/self-healing-infra) |

</details>

---

## Experience

**Infosys** - Data Engineer (Systems Engineer to Technology Analyst) · Oct 2021 - Dec 2024

Delivered cloud data integration platforms on Azure for Big 4 clients (KPMG, PwC) across SAP SuccessFactors, Salesforce, and Workday ecosystems. Consolidated legacy point-to-point integrations into unified, orchestrated pipelines, cutting client operating costs and manual handoffs.

![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Azure%20Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic%20Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

Left December 2024 to pursue an M.S. in Applied Information Technology at George Mason University.

---

## Certifications

![DP-700](https://img.shields.io/badge/DP--700%20Fabric%20Data%20Engineer%20Associate-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![AZ-104](https://img.shields.io/badge/AZ--104%20Azure%20Administrator%20Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AZ-900](https://img.shields.io/badge/AZ--900%20Azure%20Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

---

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Ram-kalicheti&show_icons=true&hide_border=true&title_color=8B5CF6&icon_color=6d28d9&text_color=c9d1d9&bg_color=0d1117" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ram-kalicheti&layout=compact&hide_border=true&title_color=8B5CF6&text_color=c9d1d9&bg_color=0d1117" />

<br/>

<img width="60%" src="https://streak-stats.demolab.com?user=Ram-kalicheti&hide_border=true&background=0d1117&stroke=6d28d9&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" />

</div>

---

<div align="center">

<i>Invisible when it works, obvious when it breaks. I build the parts that keep working.</i>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:6d28d9,100:4c1d95&height=100&section=footer" />

</div>
