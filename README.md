### Hi, I'm Libor 👋

**MS SQL (T-SQL) Developer & WMS Specialist** with 13+ years of commercial experience in relational OLTP databases, query optimization, and warehouse logistics integrations. Currently transitioning into **Python Backend & Data Engineering**, building type-safe, tested, and containerized data pipelines.

---

### 🛠️ Tech Stack

* **Python & Data Engineering:** Python 3.14 (async/await, strict typing), Polars, Pydantic v2, PyArrow, Apache Iceberg, Dagster, Streamlit
* **Databases & WMS (13+ yrs commercial):** MS SQL Server, T-SQL (stored procedures, views, triggers, functions, execution plans, indexing), SSRS, WMS/ERP integrations
* **Quality, CI/CD & Infra:** pytest, mypy, Ruff, Git, GitHub Actions CI, Docker, MinIO (S3), Project Nessie, uv

---

### 🚀 Featured Project

#### [Real-Estate-Watchdog-v2](https://github.com/libor-konopka/Real-Estate-Watchdog-v2)
Asynchronous **Medallion Data Lakehouse** pipeline (Bronze / Silver / Gold) for monitoring and analyzing Czech real estate listings:
* **Ingestion & Contracts:** Async scraping (`aiohttp`, `selectolax`, GraphQL) with incremental fast-path skipping, HTTP `HEAD` tombstone reconciliation, and strict `Pydantic v2` + `PyArrow` schemas.
* **Transformations & Storage:** Vectorized deduplication (Haversine GPS + blocking keys) and lifecycle tracking in `Polars`, persisted as versioned `Apache Iceberg` tables on `MinIO` + `Project Nessie`.
* **Orchestration & Quality:** `Dagster` asset lineage, `Streamlit` analytical dashboard, `pytest` unit test suite, and automated `GitHub Actions CI` (`ruff`, `mypy`, `pytest`).

---

### 🔗 Connect

* **LinkedIn:** [linkedin.com/in/libor-konopka](https://www.linkedin.com/in/libor-konopka)
* **Email:** mail.liborkonopka@gmail.com
