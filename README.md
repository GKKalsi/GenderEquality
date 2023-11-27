# Gender Equality Indicators
Gender equality is a fundamental human right and essential for a more peaceful, prosperous, and livable world. The primary objective of this project is to produce a report using selected gender equality indicators aimed at marking progress made in addressing gaps between males and females.
<br>

# Project Activities
- Requirements gathering and analysis from relevant stakeholders.
- Identification of data sources and evaluation of different data ingestion methods available with each.
- Creating an Extraction, Load and Transform (ETL) data pipeline.
- Visualise the data in PowerBi based on stakeholder requirements.
- Document project methodology in a report format.

# World Bank API Usage Documentation
**Key Data Source:** [The World Bank Group](https://data.worldbank.org/) <br/>
**API Documentation:** https://datahelpdesk.worldbank.org/knowledgebase/articles/898581<br/>
**Base URL:** <a href="api.worldbank.org/v2/">api.worldbank.org/v2/</a><br/><br/>

| Parameter | Description | Example |
| --- | --- | --- |
| `date` | Date or date range by year, month or quarter | `date=2000:2010` |
| `format` | Output format: xml, json, jsonP | `format=json` |
| `downloadformat` | Download format: csv, xml, excel | `downloadformat=csv` |
| `page` | Page number of the result set | `page=2` |
| `per_page` | Number of results per page (default 50) | `per_page=25` |
| `mrv` | Most recent values based on the number specified | `mrv=5` |
| `mrnev` | Most recent non-empty values based on the number specified | `mrnev=5` |
| `gapfill` | Fills values by back tracking to the next available period (works with mrv) | `gapfill=Y` |
| `frequency` | Frequency of values: Q (quarterly), M (monthly), Y (yearly) (works with mrv) | `frequency=M` |
| `footnote` | Fetches footnote detail in data calls | `footnote=y` |
| `language` | Local language translations for some countries | `language=vi` |
