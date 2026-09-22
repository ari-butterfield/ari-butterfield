## Ari Butterfield
 
Analytics engineer with 2+ years on defense and aerospace programs. I led a backend team of five building a discrete event simulation tool in Python that forecasts maintenance and availability for military aircraft fleets, adopted across five major defense programs covering 3,000+ aircraft. Alongside it we built the Python and SQL pipelines behind the analytics: extracting and validating operational data, landing transformed results in PostgreSQL, and delivering them to stakeholders through Power BI.
 
### Projects
 
**[airbnb-database](https://github.com/ari-butterfield/airbnb-database)** — A 28-table MySQL schema for the Airbnb domain (users, hosts, listings, bookings, reviews, payments), normalized to 3NF, with stored procedures for the property and booking flows. Spins up with `docker compose up`. The procedures are supported with assertion tests.

**[sec-pit-warehouse](https://github.com/ari-butterfield/sec-pit-warehouse)** — A bi-temporal warehouse over 29 quarters of SEC XBRL filings that keeps every filed version of every fact, so a later restatement can't leak backwards into what was knowable on an earlier date. Across 24M facts from 11,115 companies, 89.7% of companies had revised at least one previously filed number. dlt → GCS Parquet → BigQuery, modeled in dbt with DuckDB for dev and CI, infrastructure in Terraform. Merge-blocking tests for lookahead bias, duplicate authoritative values, and future-dated filings.
 
**[stock-calculator](https://github.com/ari-butterfield/stock-calculator)** — Flask app that pulls live market data from Alpha Vantage API and computes valuation and risk metrics. pandas for the transforms, pytest for the calculations, self-hosted on a VPS. [Live demo](https://178-104-54-101.sslip.io/)
 
### Tools
 
SQL (CTEs, window functions, query tuning) · Python (pandas, NumPy, PySpark) · PostgreSQL · MySQL · ETL/ELT design · data quality testing · relational data modeling (ER, 3NF) · Power BI · Docker · Git · CI/CD · AWS
 
---
 
Austin, TX, open to relocation · Secret clearance, inactive and reinstatement-eligible ·
Open to analytics and data engineering roles · [LinkedIn](https://www.linkedin.com/in/ari-butterfield)
