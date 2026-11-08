# 🌍 Global Companies Market Intelligence Platform

<p align="center">
  <strong>End-to-End Data Analytics, SQL Engineering & Business Intelligence Project</strong><br>
  Python · Pandas · MySQL · SQL · Tableau · Matplotlib · Seaborn · Plotly
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database_Engineering-4479A1?logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-Advanced_Analytics-CC2927?logo=microsoftsqlserver&logoColor=white">
  <img src="https://img.shields.io/badge/Tableau-Business_Intelligence-E97627?logo=tableau&logoColor=white">
  <img src="https://img.shields.io/badge/Plotly-Interactive_Visualization-3F4F75?logo=plotly&logoColor=white">
  <img src="https://img.shields.io/badge/Project-End--to--End_Analytics-success">
</p>

---

## 📌 Project Overview

The **Global Companies Market Intelligence Platform** is an end-to-end data analytics and business intelligence project designed to analyze the financial performance, market valuation, profitability, workforce, operational efficiency, and investment characteristics of companies across countries, industries, and sectors.

The project integrates multiple financial and business datasets into a consolidated company-level analytical dataset, performs data cleaning and feature engineering using Python, develops a relational database architecture in MySQL, conducts advanced SQL-based business analysis, and builds interactive analytical dashboards in Tableau.

The platform transforms raw company information into structured, analysis-ready data and business insights through a comprehensive analytical workflow.

### 🎯 Project Objectives

- Integrate multiple company datasets into a consolidated master dataset.
- Perform data cleaning, validation, transformation, and quality checks.
- Engineer financial ratios, workforce efficiency metrics, rankings, percentiles, and scoring indicators.
- Develop a structured relational database using MySQL.
- Perform advanced SQL analysis using joins, subqueries, CTEs, window functions, and views.
- Analyze company performance across countries, industries, and sectors.
- Evaluate financial performance, profitability, valuation, operational efficiency, and investment characteristics.
- Develop interactive Tableau dashboards for company, country, industry, financial, and executive analysis.
- Generate analytical visualizations and business-oriented findings.

---

## 📊 Project Highlights

| Project Metric | Value |
|---|---:|
| Integrated Source Datasets | 5 |
| Consolidated Master Dataset | 11,114 Records |
| Featured Dataset Columns | 35 |
| Python Notebooks | 7 |
| SQL Files | 15 |
| SQL Analysis Scripts | 12 |
| Tableau Worksheets | 73 |
| Tableau Dashboards / Story Views | 6 |
| Financial & Analytical Features | 25+ |

---

## 🗂️ Project Architecture

```text
Global-Companies-Market-Intelligence-Platform/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── Market_Cap.csv
│   │   ├── Revenue.csv
│   │   ├── Earnings.csv
│   │   ├── Employees.csv
│   │   └── Category.csv
│   │
│   ├── cleaned/
│   │
│   ├── processed/
│   │   ├── companies_master.csv
│   │   ├── companies_master.xlsx
│   │   ├── companies_master_featured.csv
│   │   └── companies_master_featured.xlsx
│   │
│   └── external/
│
├── notebooks/
│   ├── 01_Data_Loading.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Data_Merging.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Exploratory_Data_Analysis.ipynb
│   ├── 06_Data_Visualization.ipynb
│   └── 07_SQL_Export.ipynb
│
├── mysql/
│   │
│   ├── 01_Database_Design/
│   │   ├── 01_ER_Diagram.png
│   │   ├── 02_Relationship_Diagram.png
│   │   ├── 03_Create_Database.sql
│   │   ├── 04_Create_Tables.sql
│   │   ├── 05_Insert_Data.sql
│   │   ├── 06_Normalization_Explanation.md
│   │   ├── 07_Data_Dictionary.md
│   │   └── 08_Database_Schema.pdf
│   │
│   └── 02_SQL_Analysis/
│       ├── 01_Basic_Queries.sql
│       ├── 02_Filtering.sql
│       ├── 03_Aggregations.sql
│       ├── 04_GroupBy_Having.sql
│       ├── 05_Case_When.sql
│       ├── 06_Subqueries.sql
│       ├── 07_Joins.sql
│       ├── 08_CTEs.sql
│       ├── 09_Window_Functions.sql
│       ├── 10_Views.sql
│       ├── 11_Advanced_Business_Analytics.sql
│       └── 12_Executive_Business_Questions.sql
│
├── tableau/
│   ├── Executive_Dashboard.twbx
│   ├── Financial_Dashboard.twbx
│   ├── Country_Dashboard.twbx
│   ├── Industry_Dashboard.twbx
│   ├── KPI_Dashboard.twbx
│   └── Story.twbx
│
├── reports/
│   ├── Executive_Summary.pdf
│   ├── Business_Insights.pdf
│   ├── Recommendations.pdf
│   └── Presentation.pptx
│
├── assets/
│   ├── project_banner.png
│   ├── workflow.png
│   ├── architecture.png
│   ├── dashboard_preview.png
│   ├── er_diagram.png
│   └── relationship_diagram.png
│
└── images/
    ├── dashboard1.png
    ├── dashboard2.png
    ├── dashboard3.png
    └── dashboard4.png
```

> **Note:** The structure above represents the intended repository organization. Actual filenames, folder contents, and workbook formats should match the files committed to the repository. The reviewed Tableau workbook is `Tableau_Global.twb`.

---

# 🧭 Project Workflow

```text
Raw Company Datasets
        │
        ▼
Python Data Loading
        │
        ▼
Data Cleaning & Validation
        │
        ▼
Data Merging
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Visualization
        │
        ▼
Featured Master Dataset
        │
        ├─────────────────────────┐
        ▼                         ▼
MySQL Database             Tableau Analytics
        │                         │
        ▼                         ▼
SQL Business Analysis       Interactive Dashboards
        │                         │
        └────────────┬────────────┘
                     ▼
          Business Intelligence
          & Financial Insights
```

---

# 📁 Dataset Description

## 1. Source Datasets

The project integrates five company datasets containing financial, workforce, and classification information.

| Dataset | Description | Key Information |
|---|---|---|
| Market_Cap.csv | Company market valuation | Market capitalization, stock price, country |
| Revenue.csv | Company revenue information | Revenue, stock price, country |
| Earnings.csv | Company earnings information | Earnings, stock price, country |
| Employees.csv | Company workforce information | Employee count, stock price, country |
| Category.csv | Company classification information | Category and subcategory |

### Common Identification Fields

- `S.No.`
- `Name`
- `Symbol`
- `Country`
- `Price (USD)`

The category dataset additionally contains:

- `Category`
- `Subcategory`

The financial datasets contain their respective financial measures.

---

## 2. Consolidated Master Dataset

The five datasets are cleaned, standardized, and merged using company identification fields.

### Dataset Statistics

| Metric | Value |
|---|---:|
| Records | 11,114 |
| Columns | 10 |
| Data Type | Company-level analytical dataset |
| Merge Strategy | Left joins |
| Merge Validation | One-to-one validation |
| Primary Identification | Company + Ticker |

### Master Dataset Schema

| Column | Description |
|---|---|
| Company | Company name |
| Ticker | Company stock ticker |
| Country | Country of company |
| Market_Cap | Market capitalization |
| Revenue | Revenue |
| Earnings | Earnings |
| Employees | Number of employees |
| Stock Price | Stock price |
| Industry | Industry classification |
| Sector | Sector classification |

---

## 3. Featured Dataset

The feature-engineering stage produces the final analytical dataset:

`companies_master_featured.csv`

### Featured Dataset Statistics

| Metric | Value |
|---|---:|
| Records | 11,114 |
| Columns | 35 |
| Format | CSV / Excel |
| Purpose | Advanced Analytics, SQL & Tableau |

### Featured Dataset Schema

| Category | Fields |
|---|---|
| Company Information | Company, Ticker, Country |
| Financial Measures | Market_Cap, Revenue, Earnings |
| Workforce | Employees |
| Stock Information | Stock Price |
| Classification | Industry, Sector |
| Efficiency Metrics | Revenue_per_Employee, Earnings_per_Employee, MarketCap_per_Employee |
| Financial Ratios | MarketCap_Revenue_Ratio, Earnings_Margin |
| Ranking Metrics | Revenue_Rank, MarketCap_Rank, Earnings_Rank, Employee_Rank |
| Percentile Metrics | Revenue_Percentile, MarketCap_Percentile |
| Company Classification | Company_Size, Revenue_Category, MarketCap_Category |
| Advanced Percentiles | Profitability_Percentile, Revenue_Efficiency_Percentile, Earnings_Efficiency_Percentile |
| Financial Health | Financial_Health_Score, Financial_Rating |
| Score Components | Profitability_Score, Efficiency_Score, Valuation_Score, Health_Score_Component |
| Investment Analysis | Investment_Score, Investment_Rating |

---

# 🐍 Phase 1 — Python Data Analytics

## 01. Data Loading

**Notebook:** `01_Data_Loading.ipynb`

### Activities

- Imported the five source datasets using Pandas.
- Inspected dataset dimensions and structure.
- Examined column names and data types.
- Checked missing values and duplicate records.
- Generated descriptive statistics.
- Identified formatting inconsistencies in source financial data.
- Investigated malformed Market Capitalization records.

### Libraries

`Pandas` · `NumPy`

---

## 02. Data Cleaning & Validation

**Notebook:** `02_Data_Cleaning.ipynb`

### Activities

- Converted financial values into numeric formats.
- Removed currency symbols and standardized numerical representations.
- Normalized column names.
- Standardized company identification fields.
- Cleaned company names and country values.
- Converted employee counts into appropriate numerical formats.
- Replaced zero employee counts with missing values.
- Identified and handled duplicate ticker records.
- Validated missing tickers and financial information.
- Checked stock prices and financial data consistency.
- Exported cleaned datasets for further processing.

### Key Data Quality Considerations

- Missing financial values are retained where source information is unavailable.
- Duplicate company names are not automatically treated as identical companies.
- Ticker-based identification is used to preserve company-level distinctions.
- Missing employee information affects employee-efficiency calculations.

---

## 03. Data Merging

**Notebook:** `03_Data_Merging.ipynb`

### Activities

- Integrated cleaned financial and category datasets.
- Merged company records using Company and Ticker.
- Applied left joins to preserve the primary company dataset.
- Used one-to-one merge validation.
- Generated a consolidated company master dataset.
- Exported CSV and Excel versions.
- Created a merge report for data quality assessment.

### Output Files

- `companies_master.csv`
- `companies_master.xlsx`
- `merge_report.csv`

### Final Master Dataset

**11,114 company records × 10 columns**

---

## 04. Feature Engineering

**Notebook:** `04_Feature_Engineering.ipynb`

This stage transforms the consolidated company dataset into an advanced analytical dataset containing financial performance, efficiency, percentile rankings, company classifications, and scoring metrics.

### A. Financial Efficiency Metrics

| Feature | Calculation |
|---|---|
| Revenue per Employee | Revenue / Employees |
| Earnings per Employee | Earnings / Employees |
| Market Cap per Employee | Market Cap / Employees |
| Market Cap Revenue Ratio | Market Cap / Revenue |
| Earnings Margin | Earnings / Revenue × 100 |

### B. Company Rankings

- Revenue Rank
- Market Cap Rank
- Earnings Rank
- Employee Rank

### C. Percentile Analysis

- Revenue Percentile
- Market Cap Percentile
- Profitability Percentile
- Revenue Efficiency Percentile
- Earnings Efficiency Percentile

### D. Company Classification

- Company Size
- Revenue Category
- Market Cap Category
- Financial Rating
- Investment Rating

### E. Financial Health Scoring

Financial Health Score combines three major components:

| Component | Weight |
|---|---:|
| Profitability | 40% |
| Revenue Efficiency | 30% |
| Earnings Efficiency | 30% |

### F. Investment Analysis

Additional analytical fields:

- Profitability Score
- Efficiency Score
- Valuation Score
- Health Score Component
- Investment Score
- Investment Rating

### Output

`companies_master_featured.csv`

`companies_master_featured.xlsx`

**11,114 records × 35 columns**

---

## 05. Exploratory Data Analysis (EDA)

**Notebook:** `05_Exploratory_Data_Analysis.ipynb`

The EDA notebook contains eight major analytical sections.

| Section | Analysis |
|---|---|
| A | Company Analysis |
| B | Country Analysis |
| C | Financial Analysis |
| D | Workforce Analysis |
| E | Distribution Analysis |
| F | Correlation Analysis |
| G | Outlier Analysis |
| H | Business Questions |

### Business Questions Investigated

- Which companies generate the highest revenue?
- Which companies have the highest market capitalization?
- Which companies report the highest earnings?
- Which countries contribute the most revenue?
- Which countries have the highest market valuation?
- How is workforce distributed across companies and countries?
- How does revenue relate to market capitalization?
- How does revenue relate to earnings?
- Which companies demonstrate high revenue per employee?
- Which companies exhibit strong profitability?
- How do financial health scores vary?
- How do company sizes differ?
- How do industries and sectors compare?
- Which companies rank highest across multiple financial indicators?

---

## 06. Data Visualization

**Notebook:** `06_Data_Visualization.ipynb`

The visualization notebook contains 20 major visualization sections covering financial, operational, geographic, and analytical comparisons.

### Visualization Categories

| Visualization | Analytical Purpose |
|---|---|
| Ranking Charts | Compare top-performing companies |
| Country Charts | Analyze country-level financial performance |
| Scatter Plots | Examine financial relationships |
| Bubble Charts | Compare multiple company metrics |
| Histograms | Analyze distributions |
| Box Plots | Examine variability and outliers |
| Pie Charts | Visualize category composition |
| Heatmaps | Analyze relationships and performance |
| Interactive Plotly Charts | Explore data interactively |
| Advanced Business Charts | Present business-oriented analysis |
| Line Charts | Visualize analytical trends |
| Horizontal Charts | Compare ranked categories |
| Violin Plots | Analyze distribution characteristics |
| KDE Plots | Examine distribution patterns |
| Treemaps | Visualize hierarchical financial data |
| Sunburst Charts | Explore hierarchical categories |
| Area Charts | Present cumulative patterns |
| KPI Charts | Highlight important metrics |
| Advanced Scatter Plots | Analyze multidimensional relationships |
| Interactive Dashboards | Combine visual analytical components |

### Libraries

- Matplotlib
- Seaborn
- Plotly

---

## 07. SQL Data Export

**Notebook:** `07_SQL_Export.ipynb`

### Activities

- Loaded the featured master dataset.
- Established a MySQL connection using SQLAlchemy.
- Used an environment variable for the MySQL password.
- Exported the featured dataset into a MySQL staging/master table.
- Validated imported record counts.
- Checked company identification and duplicate records.
- Performed missing-value validation.
- Generated SQL validation reports.

### Output

MySQL table:

`companies_master`

Validation report:

`sql_validation.csv`

### Import Validation

| Metric | Result |
|---|---:|
| Exported Records | 11,114 |
| Imported Records | 11,114 |
| Featured Dataset Columns | 35 |

---

# 🗄️ Phase 2 — MySQL Database Engineering

## Database Architecture

**Database:** `global_companies_db`

The database is designed to organize company information, classifications, and financial measures using relational tables and foreign-key relationships.

### Database Components

| Table | Purpose |
|---|---|
| countries | Country dimension |
| industries | Industry dimension |
| sectors | Sector dimension |
| companies | Company master information |
| financials | Financial measures and analytical features |
| companies_master | Denormalized analytical staging/master table |

### Relational Structure

```text
countries
   │
   └── companies
          │
          ├── industries
          │
          ├── sectors
          │
          └── financials
```

### Database Design Features

- Primary keys using auto-increment identifiers.
- Foreign-key relationships.
- Unique country, industry, and sector values.
- Unique source-row identification.
- Indexed company identification fields.
- Company names are not required to be unique.
- Financial records are linked to companies through Company_ID.
- Source_Row_ID maintains a relationship with the original dataset row.

### Database Design Files

- `03_Create_Database.sql`
- `04_Create_Tables.sql`
- `05_Insert_Data.sql`

### Database Documentation

- ER Diagram
- Relationship Diagram
- Database Schema
- Normalization Explanation
- Data Dictionary

---

# 🧠 Phase 3 — Professional SQL Analysis

The SQL analysis layer contains **12 SQL scripts**, progressing from foundational SQL operations to advanced analytical queries and executive business questions.

## SQL Analysis Modules

| No. | SQL Module | Major Concepts |
|---:|---|---|
| 01 | Basic Queries | SELECT, DISTINCT, LIMIT, ranking |
| 02 | Filtering | WHERE, IN, BETWEEN, LIKE |
| 03 | Aggregations | SUM, AVG, MIN, MAX, COUNT |
| 04 | GROUP BY & HAVING | Grouped financial and country analysis |
| 05 | CASE WHEN | Classification and conditional analysis |
| 06 | Subqueries | Nested queries and comparative analysis |
| 07 | Joins | Relational data integration |
| 08 | CTEs | Common Table Expressions |
| 09 | Window Functions | Analytical ranking and calculations |
| 10 | Views | Reusable reporting queries |
| 11 | Advanced Business Analytics | Advanced financial and market analysis |
| 12 | Executive Business Questions | Executive-level business intelligence |

## Advanced SQL Techniques

### Subqueries

- Nested financial comparisons
- Company-level benchmarking
- Country-level averages
- Industry-level comparisons

### JOINs

- Company and financial relationships
- Country-based analysis
- Industry and sector analysis
- Relational reporting

### Common Table Expressions

- Revenue rankings
- Country summaries
- Workforce rankings
- KPI calculations

### Window Functions

- RANK
- DENSE_RANK
- ROW_NUMBER
- NTILE
- LAG
- LEAD
- Running totals
- Moving averages

### SQL Views

Reusable reporting views for company and financial analysis.

### Business Analytics

- Company financial rankings
- Country performance comparisons
- Industry and sector analysis
- Financial health evaluation
- Investment-related analysis
- Executive business questions

### SQL File Structure

```text
mysql/
│
├── 01_Database_Design/
│   ├── 03_Create_Database.sql
│   ├── 04_Create_Tables.sql
│   └── 05_Insert_Data.sql
│
└── 02_SQL_Analysis/
    ├── 01_Basic_Queries.sql
    ├── 02_Filtering.sql
    ├── 03_Aggregations.sql
    ├── 04_GroupBy_Having.sql
    ├── 05_Case_When.sql
    ├── 06_Subqueries.sql
    ├── 07_Joins.sql
    ├── 08_CTEs.sql
    ├── 09_Window_Functions.sql
    ├── 10_Views.sql
    ├── 11_Advanced_Business_Analytics.sql
    └── 12_Executive_Business_Questions.sql
```

---

# 📊 Phase 4 — Tableau Business Intelligence

## Tableau Workbook

**Workbook:** `Tableau_Global.twb`

The Tableau workbook contains **73 worksheets and 6 dashboard/story views** covering company rankings, country intelligence, industry performance, financial analysis, investment characteristics, and executive KPIs.

## Dashboard 1 — KPI Dashboard

### Objective

Provide a consolidated view of important financial and business metrics.

### KPI Worksheets

- KPI - Total Companies
- KPI - Total Countries
- KPI - Total Revenue
- KPI - Total Market Cap
- KPI - Total Earnings
- KPI - Total Employees
- KPI - Highest Revenue
- KPI - Highest Market Cap
- KPI - Highest Earnings
- KPI - Highest Revenue per Employee
- KPI 1 – Total Industries
- KPI 2 – Total Sectors
- KPI 3 – Largest Industry Revenue
- KPI 4 – Largest Industry Market Cap
- KPI 5 – Average Profit Margin
- KPI – Largest Company

---

## Dashboard 2 — Country Dashboard

### Objective

Analyze global financial performance, workforce distribution, and operational efficiency across countries.

### Worksheets

- Country Comparison Table
- Country Efficiency Ranking
- Country Efficiency Bar Chart
- Country Efficiency Heatmap
- Country Efficiency Map
- Interactive World Map
- Revenue by Country
- Employees by Country
- Top Countries by Revenue
- Top Countries by Market Cap
- Top Countries by Earnings
- Country A - Revenue
- Country A - Market Cap
- Country A - Earnings
- Country A - Employees
- Country A - Companies
- Country A - Average Revenue
- Country B - Revenue
- Country B - Market Cap
- Country B - Earnings
- Country B - Employees
- Country B - Companies
- Country B - Average Revenue

### Analytical Features

- Country A vs Country B comparison
- Revenue comparison
- Market capitalization comparison
- Earnings comparison
- Employee comparison
- Company count comparison
- Average revenue comparison
- Country efficiency ranking
- Geographic financial analysis

---

## Dashboard 3 — Industry Dashboard

### Objective

Compare financial performance, profitability, workforce, and efficiency across industries.

### Worksheets

- Revenue by Industry
- Market Cap by Industry
- Earnings by Industry
- Employees by Industry
- Industry Bubble Chart
- Industry Heatmap
- Industry Performance Radar Chart
- Industry Profitability Ranking
- Industry Treemap
- Pareto Analysis
- Waterfall Chart
- Radar Score Validation

### Analytical Features

- Industry revenue analysis
- Industry market capitalization analysis
- Industry earnings analysis
- Industry workforce analysis
- Industry profitability comparison
- Industry efficiency comparison
- Industry contribution analysis
- Pareto revenue analysis
- Multidimensional industry comparison

---

## Dashboard 4 — Financial Dashboard

### Objective

Evaluate company financial performance, profitability, valuation, and investment characteristics.

### Worksheets

- Financial Benchmarking
- Financial Ratio Table
- Investment Opportunity Matrix
- Top Investment Companies
- Top Companies - Efficiency
- Revenue vs Earnings Scatter Plot
- Revenue vs Market Cap
- Revenue Distribution
- Average Revenue per Company
- Average Revenue per Employee
- Revenue per Employee
- Revenue per Employee by Industry
- Top 10 Market Cap
- Top 20 Market Cap
- Top 20 Revenue
- Top 20 Earnings

### Analytical Features

- Financial benchmarking
- Financial ratio analysis
- Profitability analysis
- Revenue efficiency analysis
- Company investment scoring
- Investment opportunity comparison
- Company financial rankings

---

## Dashboard 5 — Executive Dashboard

### Objective

Provide an executive-level overview of company financial performance, business distribution, and major analytical findings.

### Analytical Components

- Financial KPIs
- Company rankings
- Country performance
- Industry performance
- Financial health indicators
- Investment-related analysis
- Executive business insights

---

## Dashboard 6 — Tableau Story

### Objective

Present selected analytical views in a structured business intelligence storytelling format.

**Story:** `Story 1`

The story view is included in the Tableau workbook.

---

# 📈 Phase 5 — Business Intelligence & Analytical Insights

The platform supports multiple levels of business analysis.

## Company-Level Analysis

- Revenue ranking
- Market capitalization ranking
- Earnings ranking
- Workforce ranking
- Revenue per employee
- Earnings per employee
- Financial health evaluation
- Investment score comparison
- Company financial profile

## Country-Level Analysis

- Total revenue by country
- Total market capitalization by country
- Total earnings by country
- Employee distribution by country
- Company count by country
- Average revenue comparisons
- Country efficiency rankings
- Country A vs Country B benchmarking

## Industry-Level Analysis

- Revenue contribution
- Market capitalization contribution
- Earnings contribution
- Workforce distribution
- Profitability ranking
- Efficiency benchmarking
- Pareto analysis
- Industry comparison

## Financial Analysis

- Revenue and earnings comparison
- Market capitalization and revenue relationship
- Earnings margin
- Financial health score
- Financial rating
- Company valuation characteristics
- Investment score
- Investment rating

## Workforce Analysis

- Employee distribution
- Employees by country
- Employees by industry
- Revenue per employee
- Earnings per employee
- Market capitalization per employee

---

# 🧮 Phase 6 — Analytical Metrics & Scoring

## Financial Metrics

| Metric | Formula |
|---|---|
| Revenue per Employee | Revenue / Employees |
| Earnings per Employee | Earnings / Employees |
| Market Cap per Employee | Market Cap / Employees |
| Market Cap Revenue Ratio | Market Cap / Revenue |
| Earnings Margin | Earnings / Revenue × 100 |

## Financial Health Score

The Financial Health Score is calculated using:

- Profitability Percentile
- Revenue Efficiency Percentile
- Earnings Efficiency Percentile

Weights:

- Profitability: 40%
- Revenue Efficiency: 30%
- Earnings Efficiency: 30%

## Financial Health Classification

The dataset contains:

- Financial Health Score
- Financial Rating

## Investment Analysis

The dataset includes:

- Profitability Score
- Efficiency Score
- Valuation Score
- Health Score Component
- Investment Score
- Investment Rating

These features support comparative company analysis and financial benchmarking.

---

# 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data processing and analytical programming |
| Pandas | Data cleaning, transformation, merging, analysis |
| NumPy | Numerical operations |
| Matplotlib | Statistical and business visualization |
| Seaborn | Exploratory and statistical visualization |
| Plotly | Interactive visualization |
| MySQL | Relational database management |
| SQL | Data querying and business analysis |
| SQLAlchemy | Python–MySQL integration |
| Tableau | Business intelligence and dashboards |
| Jupyter Notebook | Analytical development environment |
| Git | Version control |
| GitHub | Project repository and documentation |

---

# 📦 Project Deliverables

## Data Deliverables

- Five source datasets
- Cleaned datasets
- Consolidated master dataset
- Featured master dataset
- CSV and Excel exports

## Python Deliverables

- Seven analytical notebooks
- Data loading and cleaning workflow
- Dataset merging workflow
- Feature engineering
- Exploratory data analysis
- Data visualization
- SQL export and validation

## MySQL Deliverables

- Database creation scripts
- Table creation scripts
- Data insertion scripts
- Relational database architecture
- SQL analysis scripts
- Advanced analytical queries
- Reporting views
- Executive business questions

## Tableau Deliverables

- Tableau workbook
- 73 worksheets
- 6 dashboard/story views
- KPI analysis
- Company financial analysis
- Country intelligence
- Industry intelligence
- Investment analysis
- Executive overview

## Documentation & Reporting

- README documentation
- Database documentation
- Data dictionary
- ER diagram
- Relationship diagram
- Database schema documentation
- Executive summary
- Business insights report
- Recommendations report
- Project presentation

---

# 🚀 How to Use This Project

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Global-Companies-Market-Intelligence-Platform.git
```

```bash
cd Global-Companies-Market-Intelligence-Platform
```

## 2. Set Up Python Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 3. Run Python Notebooks

Open the project in Jupyter Notebook or VS Code.

Execute notebooks in the following order:

1. `01_Data_Loading.ipynb`
2. `02_Data_Cleaning.ipynb`
3. `03_Data_Merging.ipynb`
4. `04_Feature_Engineering.ipynb`
5. `05_Exploratory_Data_Analysis.ipynb`
6. `06_Data_Visualization.ipynb`
7. `07_SQL_Export.ipynb`

## 4. Set Up MySQL

Create the database:

```sql
SOURCE mysql/01_Database_Design/03_Create_Database.sql;
```

Create the database tables:

```sql
SOURCE mysql/01_Database_Design/04_Create_Tables.sql;
```

Load data:

```sql
SOURCE mysql/01_Database_Design/05_Insert_Data.sql;
```

> Execute SQL files from MySQL Workbench or a MySQL client. Update paths and connection settings according to your local environment.

## 5. Execute SQL Analysis

Open the scripts in:

```text
mysql/02_SQL_Analysis/
```

Run the queries in sequence, beginning with basic queries and progressing to advanced analytical SQL and executive business questions.

## 6. Open Tableau Workbook

Open:

```text
Tableau_Global.twb
```

in Tableau Desktop.

The workbook contains the company, country, industry, financial, KPI, executive, and story analytical views.

---

# 🔍 Data Quality & Limitations

The dataset contains company-level financial and workforce information, but some source fields are unavailable or incomplete.

### Data Quality Considerations

- Missing revenue, earnings, market capitalization, and employee values are present.
- Missing employee values affect efficiency calculations.
- Missing tickers affect ticker-based company identification.
- Missing industry and sector classifications affect classification-based analysis.
- Company names may appear more than once.
- Financial ratios may be undefined when denominator values are zero or missing.
- Negative earnings and revenue values may occur in the dataset.
- Financial scores depend on the feature-engineering methodology.
- Company rankings depend on available financial data.

### Interpretation Considerations

- Revenue and earnings represent financial measures recorded in the dataset.
- Market capitalization is a valuation measure, not a direct profitability indicator.
- Revenue per employee is an operational efficiency indicator, not a complete measure of productivity.
- Investment scores are analytical scoring outputs, not investment recommendations.
- Financial health classifications are modelled analytical indicators and should not be interpreted as credit ratings.
- Company comparisons should consider industry differences and missing data.

---

# 🔐 Security & Configuration

The Python–MySQL integration uses environment-variable-based password configuration.

Example:

```python
import os

mysql_password = os.getenv("MYSQL_PASSWORD")
```

Set the environment variable before running the SQL export notebook.

Do not commit:

- MySQL passwords
- Database credentials
- Private configuration files
- Sensitive connection information

Use `.gitignore` to exclude environment files and unnecessary local artifacts.

---

# 📚 Skills Demonstrated

### Data Analytics

- Data loading
- Data cleaning
- Data validation
- Data merging
- Feature engineering
- Exploratory data analysis
- Statistical analysis
- Data visualization

### SQL & Database Engineering

- Relational database design
- Database normalization
- Primary and foreign keys
- Data insertion and validation
- SQL joins
- Subqueries
- CTEs
- Window functions
- Aggregations
- SQL views
- Advanced business analytics

### Business Intelligence

- KPI development
- Financial benchmarking
- Company performance analysis
- Country intelligence
- Industry analysis
- Investment-related analysis
- Executive reporting
- Tableau dashboard development

### Analytical Thinking

- Business question formulation
- Comparative analysis
- Financial performance evaluation
- Workforce efficiency analysis
- Ranking and percentile analysis
- Data-driven decision support

---

# 🎯 Future Improvements

Potential future extensions include:

- Automated data refresh pipeline
- Scheduled database updates
- Expanded company-level financial indicators
- Historical financial trend analysis
- Time-series market analysis
- More comprehensive data quality monitoring
- Additional executive KPI dashboards
- Advanced statistical modelling
- Predictive financial analytics
- Automated report generation
- Interactive web-based analytics interface
- Cloud database integration
- API-based data ingestion

---

# 👨‍💻 Author

**Raj Kuntal**

Data Analytics · SQL · Python · Business Intelligence

- GitHub: [Raj-9719](https://github.com/Raj-9719)
- LinkedIn: [Raj Kumar Kuntal](https://www.linkedin.com/in/Raj-Kumar-Kuntal/)

---

# ⭐ Acknowledgements

This project was developed as a practical data analytics and business intelligence initiative involving financial datasets, Python-based analytical workflows, MySQL database engineering, SQL business analysis, and Tableau visualization.

---

<p align="center">
  <strong>Global Companies Market Intelligence Platform</strong><br>
  Turning Global Company Data into Analytical Insights.
</p>
