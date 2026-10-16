<div align="center">

<img src="assets/hero.svg" alt="Dharmesh Kashyap, Data Engineer. Raw data in. Decision-ready assets out." width="100%" />

[![Portfolio](https://img.shields.io/badge/portfolio-dharmeshkashyap.work-131417?style=for-the-badge&logo=vercel&logoColor=38BDF8)](https://dharmeshkashyap.work)
[![LinkedIn](https://img.shields.io/badge/linkedin-dharmesh--kashyap-131417?style=for-the-badge&logo=linkedin&logoColor=38BDF8)](https://linkedin.com/in/dharmesh-kashyap)
[![Resume](https://img.shields.io/badge/resume-download_pdf-131417?style=for-the-badge&logo=adobeacrobatreader&logoColor=38BDF8)](https://www.dharmeshkashyap.work/assets/Dharmesh_Kashyap_Resume.pdf)
[![Mail](https://img.shields.io/badge/mail-dharmeshkashyap46@gmail.com-131417?style=for-the-badge&logo=gmail&logoColor=38BDF8)](mailto:dharmeshkashyap46@gmail.com)

</div>

**Data Engineer at Seamless Digital Automations, Mumbai (since Feb 2025).** I build pipelines, warehouses and validation systems that make difficult data dependable: government surveys, scheme PDFs, boundary files and Excel uploads. The inputs are never clean, so the work is in making the output trustworthy.

<img src="assets/achievements.svg" alt="Achievements unlocked: 670K+ village boundaries, 5.2M+ warehouse records, 2,500+ scheme PDFs, 298 harmonised variables, 5 surveys across 3 rounds, 60+ mutual fund instruments" width="100%" />

<br/>

<img src="assets/levels.svg" alt="Level select: Extract, Transform, Load, Serve" width="100%" />

| Level | What happens | Tools |
|:---|:---|:---|
| **1 · Extract** | Boundary files for 670K+ villages, 2,500+ scheme PDFs, 60+ mutual fund instruments. Validation checks surface problems at the door. | Python, GeoJSON, validation |
| **2 · Transform** | HCES, ASUSE, AIDIS, SAS and Agriculture Census across 3 NSO/MoSPI rounds into one long-format schema. A 298-variable DDI dictionary keeps definitions steady. | PySpark, Hadoop, Polars, DuckDB, Parquet |
| **3 · Load** | PostgreSQL warehouse over 5.2M+ records. Staging tables promoted into dimension and fact tables through a multi-step pipeline. | PostgreSQL, Flask, SQL |
| **4 · Serve** | KPI dashboards with drill-downs. AIV Hub on AWS-hosted servers, with written network and firewall requirements after a cross-subnet routing failure. | Tableau, AIV Hub, AWS |

<br/>

<img src="assets/wide-to-long.svg" alt="Survey data unpivoted from wide format to a consistent long format. Illustrative values." width="100%" />

---

## Quests

<details>
<summary><b>Survey ETL · NABARD</b></summary>

<br/>

- Distributed PySpark/Hadoop pipelines for 5 All-India NSO/MoSPI surveys (HCES, ASUSE, AIDIS, SAS, Agriculture Census) across 3 rounds. Polars and DuckDB handle downstream transformation and validation.
- One standardised long-format schema that BI tools consume directly. Parquet recommended over CSV for delivery.
- HCES pipeline packaged as a modular Python ETL package with a full test suite.
- DDI enrichment dictionary of 298 harmonised variables across 3 HCES rounds.

`PySpark` `Hadoop` `Polars` `DuckDB` `Parquet`

</details>

<details>
<summary><b>Data Processor · ICICI Prudential · 2025 to 2026</b></summary>

<br/>

- Finance teams were uploading Excel files by hand. This Flask + PostgreSQL app takes Admin Dump and Location Vacation files into staging tables, validates them, and promotes them into a dimension/fact warehouse through a multi-step pipeline.
- Added scheduler visibility, refresh progress, conflict reporting and a notification tray.
- Audited the pipeline and fixed duplicate-promotion and staging-filter bugs.

`Flask` `PostgreSQL` `SQL` `Python`

</details>

<details>
<summary><b>News Intelligence Platform · NABARD · 2026</b></summary>

<br/>

- Multi-source scraper that extracts, cleans and structures articles into a database feeding a live dashboard.
- AI enrichment for classification, summarisation and search, plus an interactive commodities ticker.

`Python` `PostgreSQL` `LLM APIs`

</details>

<details>
<summary><b>Earlier quests</b></summary>

<br/>

- [Lead Generation Automation](https://github.com/dharmesh-kashyap/lead-generation-automation): scraping and enrichment pipeline
- [COVID-19 Mortality Analysis](https://public.tableau.com/app/profile/dharmesh.kashyap/viz/CoronaVirusdeathreport/Dashboard1): Tableau dashboard
- [Airbnb Pricing Intelligence](https://public.tableau.com/app/profile/dharmesh.kashyap/viz/AirBNBPriceVariation_/Dashboard1): Tableau dashboard

</details>

---

## Inventory

![Python](https://img.shields.io/badge/Python-131417?style=flat-square&logo=python&logoColor=38BDF8)
![SQL](https://img.shields.io/badge/SQL-131417?style=flat-square&logo=databricks&logoColor=38BDF8)
![PySpark](https://img.shields.io/badge/PySpark-131417?style=flat-square&logo=apachespark&logoColor=38BDF8)
![Hadoop](https://img.shields.io/badge/Hadoop-131417?style=flat-square&logo=apachehadoop&logoColor=38BDF8)
![Polars](https://img.shields.io/badge/Polars-131417?style=flat-square&logo=polars&logoColor=38BDF8)
![DuckDB](https://img.shields.io/badge/DuckDB-131417?style=flat-square&logo=duckdb&logoColor=38BDF8)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-131417?style=flat-square&logo=postgresql&logoColor=38BDF8)
![MySQL](https://img.shields.io/badge/MySQL-131417?style=flat-square&logo=mysql&logoColor=38BDF8)
![Flask](https://img.shields.io/badge/Flask-131417?style=flat-square&logo=flask&logoColor=38BDF8)
![AWS](https://img.shields.io/badge/AWS-131417?style=flat-square&logo=amazonaws&logoColor=38BDF8)
![Tableau](https://img.shields.io/badge/Tableau-131417?style=flat-square&logo=tableau&logoColor=38BDF8)

Dimensional modelling (staging, dimension/fact) · data validation · SQL query optimisation · KPI dashboards

---

## Save point

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake-dark.svg" />
</picture>

<img src="https://github-readme-stats.vercel.app/api?username=dharmesh-kashyap&show_icons=true&theme=github_dark&hide_border=true&bg_color=131417&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dharmesh-kashyap&layout=compact&theme=github_dark&hide_border=true&bg_color=131417&title_color=38bdf8&text_color=94a3b8&langs_count=6&hide=jupyter%20notebook" height="165" alt="Top languages" />

</div>

---

<div align="center">

<img src="assets/continue_2.svg" alt="Messy data? Let's talk." width="100%" />

<sub>MCA, Manipal Institute of Technology, MAHE (2023 to 2025) · B.Sc. IT, R. J. College, University of Mumbai (2019 to 2022) · Modern Application Development with Python on AWS · Applied Data Science with Python</sub>

</div>
