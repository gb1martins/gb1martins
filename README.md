<!-- ========================= -->
<!--           BANNER          -->
<!-- ========================= -->

<p align="center">
  <img src="Capa_Git.png" width="100%">
</p>

<br>

<!-- ========================= -->
<!--         SOBRE MIM        -->
<!-- ========================= -->

<h2>👋 Olá, eu sou Gabriel!</h2>

<p>
  Sou profissional com experiência em dados, automação e desenvolvimento de
  soluções para análise e engenharia de dados.
</p>

<p>
  Tenho experiência na construção de soluções de dados, automações,
  processos ETL e desenvolvimento de pipelines, buscando transformar
  dados em informações confiáveis para apoiar decisões de negócio.
</p>

---

<!-- ========================= -->
<!--        TECNOLOGIAS        -->
<!-- ========================= -->

<h2>🛠️ Tecnologias</h2>

<h3>💻 Linguagens & Dados</h3>

<p>
  <img src="https://skillicons.dev/icons?i=python" height="45" title="Python">
  <img src="https://skillicons.dev/icons?i=postgresql" height="45" title="PostgreSQL">
  <img src="https://skillicons.dev/icons?i=mysql" height="45" title="MySQL">
</p>

<h3>☁️ Cloud & Data Engineering</h3>

<p>
  <img src="https://skillicons.dev/icons?i=aws" height="45" title="AWS">
  <img src="https://skillicons.dev/icons?i=airflow" height="45" title="Airflow">
  <img src="https://skillicons.dev/icons?i=docker" height="45" title="Docker">
  <img src="https://skillicons.dev/icons?i=dbt" height="45" title="dbt">
</p>

<p>
  <strong>AWS:</strong> S3 • Glue • Athena
</p>

<p>
  <strong>Data Engineering:</strong> ETL • Data Lake • Data Warehouse •
  Medallion Architecture • Data Pipelines
</p>

---

<!-- ========================= -->
<!--    PROJETOS EM DESTAQUE   -->
<!-- ========================= -->

<h2>🚀 Projetos em destaque</h2>

<table>
  <tr>
    <td width="50%">

### 🌦️ Airflow Weather Data Pipeline

Pipeline de dados end-to-end utilizando Python, Airflow, Docker e PostgreSQL para ingestão e processamento de dados climáticos provenientes da API OpenWeather.

**Arquitetura:**

`API → Bronze → Silver → Gold`

**Tecnologias:**

Python • Airflow • Docker • PostgreSQL • ETL

[🔗 Ver projeto](https://github.com/gb1martins/airflow-weather-data-pipeline)

    </td>

    <td width="50%">

### 🏎️ Formula 1 Data Pipeline

Pipeline de dados desenvolvido para ingestão e processamento de dados da Fórmula 1, utilizando API, Data Lake e arquitetura em camadas.

**Arquitetura:**

`API → S3 → Bronze → Silver → Gold`

**Tecnologias:**

Python • AWS S3 • AWS Glue • Athena • Data Lake

[🔗 Ver projeto](https://github.com/gb1martins/formula_1_pipeline_de_dados)

    </td>
  </tr>

  <tr>
    <td width="50%">

### ✈️ Airline Data Warehouse

Projeto de Data Warehouse utilizando modelagem dimensional para organização dos dados e realização de análises de negócio.

**Conceitos:**

Data Warehouse • Modelagem Dimensional • SQL

**Tecnologias:**

SQL • Python • PostgreSQL

[🔗 Ver projeto](https://github.com/gb1martins/airline-datawarehouse)

    </td>

    <td width="50%">

### 🔄 Data Preparation & Transformation

Projeto voltado para preparação, transformação e organização de dados utilizando Python e práticas de qualidade de dados.

**Processos:**

Limpeza • Transformação • Validação • Preparação

**Tecnologias:**

Python • Pandas

[🔗 Ver projeto](https://github.com/gb1martins/data_prep_transformation)

    </td>
  </tr>
</table>

---

<!-- ========================= -->
<!--       ARQUITETURA         -->
<!-- ========================= -->

<h2>🏗️ Interesse em Arquitetura de Dados</h2>

<p>
  Interesse em desenvolver arquiteturas de dados modernas, escaláveis e
  confiáveis, trabalhando com diferentes etapas do ciclo de vida dos dados:
</p>

<p align="center">

```text
          ┌──────────────┐
          │   Ingestão   │
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │    Bronze    │
          │    Raw Data  │
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │    Silver    │
          │ Transformation│
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │     Gold     │
          │   Analytics  │
          └──────┬───────┘
                 │
                 ▼
          ┌──────────────┐
          │   Analytics  │
          │   & BI       │
          └──────────────┘
