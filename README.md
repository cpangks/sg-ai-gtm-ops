# Singapore Enterprise AI GTM Operations Starter Kit
Singapore Enterprise AI GTM Operations Starter Kit — account database, pipeline dashboard, and market intelligence built as a Revenue S&amp;O portfolio project

> A Revenue Strategy & Operations portfolio project simulating the 
> data infrastructure an S&O analyst would build for an AI SaaS GTM team 
> entering the Singapore market.

## What's in this repo

| File/Folder | Description |
|---|---|
| `sql/queries.sql` | 10 documented SQL queries for GTM pipeline analysis |
| `notebooks/01_data_pipeline.ipynb` | Data collection, cleaning, and SQLite loading |
| `notebooks/02_market_intelligence.ipynb` | AI-augmented competitive analysis using Claude |
| `exports/` | CSVs exported from SQLite for Tableau |

## Data model
Salesforce-mirrored schema: **Accounts → Opportunities → Contacts**

## Data sources
- SGX Listed Companies (Oct 2024)
- MAS Financial Institutions Directory
- Singapore statutory boards (gov.sg)
- Crunchbase (Series B+ Singapore tech companies)

## ICP tiering logic
| Tier | Criteria |
|---|---|
| Tier 1 | 5,000+ employees, FSI or Government, AI readiness ≥ 4 |
| Tier 2 | 500–5,000 employees, Tech or Telco, AI readiness ≥ 3 |
| Tier 3 | All other addressable accounts |

## Live dashboard
[View on Tableau Public →](#) *(link added in Phase 2)*

## Tools used
Python · SQLite · SQL · Tableau · Claude API
