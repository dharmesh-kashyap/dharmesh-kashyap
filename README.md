<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1420,60:12304a,100:38bdf8&height=190&section=header&text=Dharmesh%20Kashyap&fontSize=44&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Data%20Engineer%20%C2%B7%20Mumbai&descAlignY=60&descSize=16" width="100%" alt="Dharmesh Kashyap, Data Engineer, Mumbai" />

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=15&duration=2600&pause=1000&color=38BDF8&center=true&vCenter=true&width=760&lines=%24+whoami+%E2%86%92+data+engineer;%24+cat+problems.txt+%E2%86%92+670K+village+boundaries%2C+2%2C500%2B+scheme+PDFs%2C+5+survey+formats;%24+tail+-f+pipeline.log+%E2%86%92+PySpark+%C2%B7+Polars+%C2%B7+DuckDB+%C2%B7+PostgreSQL;%24+echo+%22the+data+was+never+clean.+the+schema+is.%22" alt="terminal typing animation" />

<br/>

[![Portfolio](https://img.shields.io/badge/portfolio-dharmeshkashyap.work-0d1420?style=for-the-badge&logo=vercel&logoColor=38BDF8)](https://dharmeshkashyap.work)
[![LinkedIn](https://img.shields.io/badge/linkedin-dharmesh--kashyap-0d1420?style=for-the-badge&logo=linkedin&logoColor=38BDF8)](https://linkedin.com/in/dharmesh-kashyap)
[![Mail](https://img.shields.io/badge/mail-dharmeshkashyap46@gmail.com-0d1420?style=for-the-badge&logo=gmail&logoColor=38BDF8)](mailto:dharmeshkashyap46@gmail.com)

</div>

---

## `extract()` · who I am

```text
dharmesh@mumbai:~$ whoami
dharmesh kashyap, data engineer at Seamless Digital Automations

dharmesh@mumbai:~$ cat about.txt
I get handed data that was never meant to be read by a machine:
national survey microdata with a different layout every round,
government PDFs, village boundaries that disagree with each other.
I turn it into schemas, pipelines and tables people can query
without cleaning anything first.

dharmesh@mumbai:~$ cat status.txt
open to Data Engineer roles
Mumbai / Navi Mumbai / Pune / Bangalore / Hyderabad / Remote (India)
```

```sql
SELECT title, employer, since, clients
FROM   dharmesh
WHERE  status = 'open_to_work';
```

| title | employer | since | clients |
|:---|:---|:---|:---|
| Software Developer (Data Engineer) | Seamless Digital Automations, Mumbai | Feb 2025 | NABARD, ICICI Prudential |

---

## `transform()` · the work

### Test report

```text
============ tests/test_dharmesh.py ============
test_5_nso_surveys_3_rounds_one_long_format_schema ... PASSED
test_298_harmonised_variables_across_hces_rounds ..... PASSED
test_staging_to_dim_fact_warehouse_5_2M_records ...... PASSED
test_670K_village_boundaries_delivered_as_geojson .... PASSED
test_2500_scheme_pdfs_extracted_with_validation ...... PASSED
test_60_mutual_fund_instruments_monthly_pipeline ..... PASSED
test_bi_server_on_aws_setup_config_monitoring ........ PASSED
test_cross_subnet_routing_failure_diagnosed .......... PASSED
================== 8 passed ====================
```

### Case files

<table>
<tr>
<td width="50%" valign="top">

**🗂 CASE 01 · Survey ETL**
`NABARD`

Five All-India NSO/MoSPI surveys (HCES, ASUSE, AIDIS, SAS, Agriculture Census), three rounds, one schema.

PySpark on Hadoop does the heavy lifting. Polars and DuckDB handle transformation and validation. Output is long-format Parquet that BI tools read directly. The HCES pipeline ships as a tested Python package, and a 298-variable DDI dictionary keeps definitions consistent from round to round.

`PySpark` `Hadoop` `Polars` `DuckDB` `Parquet`

</td>
<td width="50%" valign="top">

**🏦 CASE 02 · Finance warehouse**
`ICICI Prudential`

A PostgreSQL schema for 5.2M+ records. Staging tables promote into dimension and fact tables through a multi-step pipeline, with query optimisation for analytics.

Wrapped in a Flask app that ingests Excel uploads, validates them, reports conflicts, and shows scheduler and refresh progress. Duplicate-promotion and staging-filter bugs were found in an audit and fixed.

`PostgreSQL` `Flask` `SQL` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🗺 CASE 03 · Village boundaries**
`NABARD`

670K+ Pan-India village boundaries as structured GeoJSON for geospatial reporting, from raw spatial data that was inconsistent at the source.

`Python` `GeoJSON` `ETL`

</td>
<td width="50%" valign="top">

**📄 CASE 04 · Scheme PDFs + fund data**
`NABARD`

2,500+ government scheme PDFs extracted with validation checks. 60+ mutual fund instruments consolidated into one schema by a recurring automated pipeline.

`Python` `ETL` `Data Validation`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**📰 CASE 05 · News intelligence platform**
`NABARD`

Multi-source scraper that extracts, cleans and structures articles into a database feeding a live dashboard. AI enrichment adds classification, summarisation and search, plus an interactive commodities ticker.

`Python` `PostgreSQL` `LLM APIs`

</td>
</tr>
</table>

### Tools by layer

| Layer | What I use |
|:---|:---|
| **Process** | ![PySpark](https://img.shields.io/badge/PySpark-0d1420?style=flat-square&logo=apachespark&logoColor=38BDF8) ![Hadoop](https://img.shields.io/badge/Hadoop-0d1420?style=flat-square&logo=apachehadoop&logoColor=38BDF8) ![Polars](https://img.shields.io/badge/Polars-0d1420?style=flat-square&logo=polars&logoColor=38BDF8) ![DuckDB](https://img.shields.io/badge/DuckDB-0d1420?style=flat-square&logo=duckdb&logoColor=38BDF8) ![Python](https://img.shields.io/badge/Python-0d1420?style=flat-square&logo=python&logoColor=38BDF8) |
| **Store** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1420?style=flat-square&logo=postgresql&logoColor=38BDF8) ![MySQL](https://img.shields.io/badge/MySQL-0d1420?style=flat-square&logo=mysql&logoColor=38BDF8) ![Parquet](https://img.shields.io/badge/Parquet-0d1420?style=flat-square&logo=apache&logoColor=38BDF8) |
| **Serve** | ![Flask](https://img.shields.io/badge/Flask-0d1420?style=flat-square&logo=flask&logoColor=38BDF8) ![Tableau](https://img.shields.io/badge/Tableau-0d1420?style=flat-square&logo=tableau&logoColor=38BDF8) ![AWS](https://img.shields.io/badge/AWS-0d1420?style=flat-square&logo=amazonaws&logoColor=38BDF8) |
| **Practice** | dimensional modelling · data validation · SQL query optimisation · KPI dashboards |

---

## Contribution log

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/dharmesh-kashyap/dharmesh-kashyap/output/github-snake-dark.svg" />
</picture>

<img src="https://github-readme-stats.vercel.app/api?username=dharmesh-kashyap&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1420&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dharmesh-kashyap&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1420&title_color=38bdf8&text_color=94a3b8&langs_count=6" height="165" alt="Top languages" />

</div>

---

## `load()` · let's talk

```text
dharmesh@mumbai:~$ ./contact.sh
> roles    : Data Engineer (pipelines, warehousing, survey and geospatial data)
> where    : Mumbai / Navi Mumbai / Pune / Bangalore / Hyderabad / Remote (India)
> mail     : dharmeshkashyap46@gmail.com
> linkedin : linkedin.com/in/dharmesh-kashyap
> web      : dharmeshkashyap.work
exit 0
```

<sub>MCA, Manipal Institute of Technology, MAHE (2023 to 2025) · B.Sc. IT, R. J. College, University of Mumbai (2019 to 2022) · Modern Application Development with Python on AWS · Applied Data Science with Python</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,60:12304a,100:0d1420&height=110&section=footer" width="100%" alt="" />
