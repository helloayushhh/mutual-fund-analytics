# Mutual Fund Analytics Platform

> End-to-end mutual fund analytics project using Python, SQL and Power
> BI.

------------------------------------------------------------------------

## Project Goal

Build a data analytics platform that processes mutual fund data and
turns it into insights across:

-   NAV and fund performance
-   AUM and SIP trends
-   Investor behaviour
-   Portfolio and sector allocation
-   Benchmark comparison
-   Risk and performance metrics

------------------------------------------------------------------------

## Phase 1: Project Setup & Data Ingestion

**Status:** Completed

### Activities

-   Set up the project structure for data, notebooks, scripts, SQL,
    dashboard and reports.
-   Loaded the 10 provided mutual fund datasets.
-   Fetched NAV data from `mfapi.in` for selected schemes.
-   Explored the fund master dataset.
-   Validated AMFI scheme codes against NAV data.

### Output

Raw datasets and initial data ingestion scripts.

------------------------------------------------------------------------

## Phase 2: Data Cleaning & SQL Database

**Status:** Completed

### Activities

-   Cleaned and validated the core datasets.
-   Converted date and numeric fields to appropriate types.
-   Removed duplicate records.
-   Standardised transaction data.
-   Created the SQLite database schema.
-   Loaded cleaned datasets into SQLite.
-   Created and tested analytical SQL queries.
-   Documented the dataset structure in a data dictionary.

### Output

``` text
data/processed/
db/
sql/schema.sql
sql/queries.sql
docs/data_dictionary.md
```

------------------------------------------------------------------------

## Phase 3: Exploratory Data Analysis

**Status:** In Progress

### Analysis

-   NAV trends across mutual fund schemes.
-   AUM growth across fund houses.
-   Monthly SIP inflow trends.
-   Category-wise fund inflows.
-   Investor age and gender distribution.
-   Investor transaction amount by state.
-   T30 vs B30 investor distribution.
-   Mutual fund folio growth.
-   NAV return correlation across selected funds.
-   Aggregate sector allocation across equity funds.

### Output

``` text
notebooks/03_eda_analysis.ipynb
```

The notebook also contains quantified EDA findings derived from the
analysed datasets.

------------------------------------------------------------------------

## Phase 4: Fund Performance Analytics

**Status:** Pending

### Planned Analysis

-   Daily returns
-   1-year, 3-year and 5-year CAGR
-   Sharpe Ratio
-   Sortino Ratio
-   Alpha and Beta
-   Standard deviation
-   Maximum drawdown
-   Fund scorecard
-   Benchmark comparison
-   Tracking error

### Planned Output

``` text
notebooks/04_performance_analytics.ipynb
```

------------------------------------------------------------------------

## Phase 5: Interactive Dashboard

**Status:** Pending

### Planned Dashboard

Four analytical views:

-   Industry Overview
-   Fund Performance
-   Investor Analytics
-   SIP & Market Trends

### Planned Features

-   KPI cards
-   Interactive slicers
-   Fund-level filtering
-   Benchmark comparison
-   Investor and geographic analysis

### Planned Output

``` text
dashboard/
```

------------------------------------------------------------------------

## Phase 6: Advanced Analytics

**Status:** Pending

### Planned Analysis

-   Historical VaR and CVaR
-   Rolling 90-day Sharpe Ratio
-   Investor cohort analysis
-   SIP continuity analysis
-   Simple risk-based fund recommendation logic
-   Sector concentration using HHI

### Planned Output

``` text
notebooks/05_advanced_analytics.ipynb
```

------------------------------------------------------------------------

## Phase 7: Final Documentation & Delivery

**Status:** Pending

### Planned Activities

-   Final project report
-   Presentation
-   README and code cleanup
-   Documentation updates
-   Final GitHub repository
-   Dashboard export / deployment if completed

------------------------------------------------------------------------

## Development Progress

``` text
Phase 1   Project Setup & Data Ingestion       ✓
Phase 2   Data Cleaning & SQL Database         ✓
Phase 3   Exploratory Data Analysis            → current
Phase 4   Fund Performance Analytics           ○
Phase 5   Interactive Dashboard                ○
Phase 6   Advanced Analytics                   ○
Phase 7   Final Documentation & Delivery       ○
```

------------------------------------------------------------------------

## Final Deliverable

Mutual Fund Analytics Platform

Capabilities:

-   Mutual Fund Data Processing
-   ETL & Data Cleaning
-   SQL Analytics
-   Exploratory Data Analysis
-   Fund Performance Analysis
-   Investor Behaviour Analysis
-   Risk & Benchmark Analytics
-   Interactive BI Dashboard
