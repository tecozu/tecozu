## Hi, I'm Renato 👋

**Data Engineer** · GCP · BigQuery · Dataform · dbt · Python · SQL
Rio de Janeiro, Brazil · open to remote ·
[LinkedIn](https://www.linkedin.com/in/araujo-o-renato/) · araujorenato.o@outlook.com

I build data platforms for **structured credit**. I have spent 5+ years at a Brazilian
securitization firm that manages receivables investment funds (FIDCs), moving from
analyst to data engineer. My work turns complex financial rules (present value, credit
provisioning, reconciliation) into modular, tested and observable pipelines.

**Recent impact (production, GCP)**
- Rebuilt fund-portfolio generation on BigQuery/Dataform, Cloud Run and Cloud Workflows.
  Runtime went **from 6–8 hours to ~30 seconds**.
- Configuration-driven design: onboarding a new fund went **from 10 business days to 1**,
  with 6 funds in production on one codebase.
- Data-quality assertions and step-level execution tracking on every pipeline stage.

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

**Cloud:** GCP (BigQuery, Dataform, Cloud Run, GCS, Cloud Workflows), AWS S3 ·
**Transformation:** SQL, dbt, Dataform (SQLX/JS), Python, pandas ·
**Storage:** BigQuery, DuckDB, PostgreSQL, SQL Server ·
**Orchestration & infra:** Airflow, Docker, GitHub Actions ·
**Quality:** dbt tests, Dataform assertions, pytest, data contracts ·
**BI:** Power BI, Superset

Certifications: Google *Build a Data Warehouse with BigQuery* · dbt Fundamentals · Databricks Fundamentals.
MBA in Business Management at FGV (in progress). Portuguese (native), English (fluent), Spanish (intermediate).
