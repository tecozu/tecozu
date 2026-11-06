<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Renato Araújo, Data Engineer: financial rules turned into tested, observable data pipelines" src="assets/banner-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/araujo-o-renato/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-araujo--o--renato-0A66C2?style=flat-square"></a>
  <a href="mailto:araujorenato.o@outlook.com"><img alt="Email" src="https://img.shields.io/badge/Email-araujorenato.o%40outlook.com-555555?style=flat-square"></a>
  <img alt="Rio de Janeiro, UTC-3" src="https://img.shields.io/badge/Rio_de_Janeiro-UTC--3,_overlaps_US_hours-555555?style=flat-square">
  <img alt="Open to remote roles" src="https://img.shields.io/badge/open_to-remote_roles-2ea44f?style=flat-square">
</p>

I build data platforms for **structured credit**. Over 5+ years at a Brazilian securitization
firm that manages receivables investment funds (FIDCs), I moved from analyst to data engineer,
turning complex financial rules (present value, credit provisioning, reconciliation) into
modular, tested and observable pipelines on GCP.

### Recent impact (production)

| **6–8 h → ~30 s** | **10 days → 1 day** | **6 funds** |
|:---:|:---:|:---:|
| fund-portfolio generation, rebuilt on BigQuery/Dataform, Cloud Run and Cloud Workflows | to onboard a new fund, thanks to a configuration-driven design | in production on one codebase, with data-quality assertions and step-level tracking |

### Featured projects

| Project | What it shows |
|---|---|
| [**fidc-receivables-lakehouse**](https://github.com/tecozu/fidc-receivables-lakehouse) | Daily valuation of a receivables fund: idempotent file ingestion with a SHA-256 ledger, an event ledger, 252-business-day pricing, loss provisioning, incremental snapshots and a ledger-reconciliation test that caught a real bug. DuckDB + dbt + CI. |
| [**reconciliation-toolkit**](https://github.com/tecozu/reconciliation-toolkit) | Cash application (payments ↔ receivables), OFX/CSV bank statements with dedup and balance continuity, dataset comparison and file-health checks. |
| [**ecommerce-price-tracker**](https://github.com/tecozu/ecommerce-price-tracker) | Price history from Mercado Livre and the Shopee API. Separates real deals from fake discounts using trailing baselines and SCD2, and tests the classifier against ground truth. |
| [**weather-data-pipeline**](https://github.com/tecozu/weather-data-pipeline) | Airflow + dbt + Postgres + Superset in Docker. Hourly idempotent ingestion with a replayable JSONB payload; CI runs the real pipeline. |
| [**dropkit**](https://github.com/tecozu/dropkit) | Monitoring for the files partners send you: delivery SLAs on the B3 business-day calendar, SQL job alerts that fire once, Teams/Slack notifications, plus transfer, search, unzip and consolidation over local, S3 and SFTP. |
| [**csv-layout-validator**](https://github.com/tecozu/csv-layout-validator) | YAML data contracts for partner files: typed rules, CPF/CNPJ, cross-column checks, CI-friendly reports. |
| [**cnab-toolkit**](https://github.com/tecozu/cnab-toolkit) | Spec-driven generator, parser and validator for Brazilian fixed-width banking files, with layout linting and property-based tests. |

### Toolbox

**Cloud & warehouse**
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Dataform](https://img.shields.io/badge/Dataform-1A73E8?style=flat-square)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square)

**Transformation**
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Storage**
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square)

**Orchestration & infra**
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Quality & BI**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Data contracts](https://img.shields.io/badge/data_contracts-6E7781?style=flat-square)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square)
![Superset](https://img.shields.io/badge/Superset-20A6C9?style=flat-square)

### Background

Certifications: Google *Build a Data Warehouse with BigQuery* · dbt Fundamentals · Databricks Fundamentals.
MBA in Business Management at FGV (in progress).
Languages: Portuguese (native), English (fluent), Spanish (intermediate).
