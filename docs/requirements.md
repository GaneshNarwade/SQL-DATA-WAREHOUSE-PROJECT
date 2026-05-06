# Project Requirements

## Data Warehouse and Analytics Project

This repository contains a portfolio-ready data warehouse and analytics solution built with SQL Server.
It demonstrates a complete Medallion Architecture implementation using Bronze, Silver, and Gold layers.

### Project Focus
- Build a modern data warehouse from ERP and CRM CSV sources.
- Implement ETL/ELT pipelines for data ingestion, cleansing, and transformation.
- Model business-ready fact and dimension tables for analytics.
- Create SQL-based reporting queries that support customer, product, and sales insights.

### Architecture Layers
- **Bronze:** Raw source data loaded as-is into SQL Server.
- **Silver:** Cleansed and standardized data prepared for analysis.
- **Gold:** Star-schema business tables for reporting and analytics.

### Tools & Resources
- SQL Server Express
- SQL Server Management Studio (SSMS)
- CSV datasets for ERP and CRM
- Draw.io for architecture and flow diagrams
- GitHub repository for version control

### Repository Structure
- `datasets/` — raw source data files
- `docs/` — architecture notes, documentation, and requirements
- `scripts/` — ETL and transformation SQL scripts
- `tests/` — quality checks and validation scripts

For more detailed architecture and design notes, see `docs/Project_Notes_Sketches.md`.
