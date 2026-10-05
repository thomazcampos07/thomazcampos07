# Hi, I'm Thomaz 👋

**Senior Data Engineer · Databricks, Apache Spark, Python**

🌎 Based in Brazil (UTC-3) · 💻 Open to remote opportunities (US & global) ·
[LinkedIn](https://www.linkedin.com/in/thomaz-campos) ·
[Email](mailto:thomazcampos07@gmail.com)

I build data platforms that analytics and ML teams can trust. I have built one
from scratch at a fintech, migrated it from BigQuery and Airflow to Databricks,
and run streaming ingestion and Medallion-architecture lakehouses on AWS. I also
led a GenAI support-automation project that automated 80% of tickets and
saved about US$100K in six months.

## 🛠️ Tech stack

- **Lakehouse & processing:** Databricks (Auto Loader, Unity Catalog), Apache Spark (Structured Streaming), Delta Lake
- **Orchestration & modeling:** Apache Airflow, dbt, dimensional modeling, incremental and backfill-safe loads
- **Languages:** Python, SQL
- **Cloud:** AWS (S3, Lambda, Glue, Athena, IAM), Google Cloud (BigQuery, Vertex AI)
- **Infra & ops:** Terraform, Databricks Asset Bundles, Docker, Git, GitHub Actions, MLflow

**Certifications:** Astronomer Apache Airflow (Fundamentals, DAG Authoring) · dbt Fundamentals

**Spoken languages:** English (fluent) · Portuguese (native) · Spanish (intermediate)

## 📌 Featured projects

- **[sp-bus-eta](https://github.com/thomazcampos07/sp-bus-eta):** live bus ride times in São Paulo, end to end. An AWS Lambda collects GPS positions every minute into S3, and a daily Databricks job (Auto Loader, Medallion layers) turns them into p50/p90 ride times. Infrastructure in Terraform, pipeline as an Asset Bundle.
- **[homelab](https://github.com/thomazcampos07/homelab):** infrastructure-as-code for my home server. Pi-hole + Unbound, WireGuard, monitoring with a dead man's switch, and encrypted backups, all in Docker with pinned images and Dependabot.
- **[ficha-fit](https://github.com/thomazcampos07/ficha-fit):** Streamlit app that turns a form into a personalized workout plan with the OpenAI API.

## 🧠 What I care about

- Reliable, observable pipelines that are idempotent and safe to backfill
- Clean, testable code and data quality checks built into the pipeline
- Turning raw data into business-ready datasets that people actually use
