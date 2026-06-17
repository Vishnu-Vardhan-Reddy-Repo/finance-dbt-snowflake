# Finance Risk Analytics — dbt + Snowflake

## Project Overview
End to end Finance Risk Analytics pipeline
built with dbt, Snowflake, GitHub and Azure DevOps

## Architecture
Raw (Snowflake) → Staging → Marts → Reports

## Tech Stack
- Data Warehouse : Snowflake
- Transformation : dbt Cloud
- Source Control : GitHub
- CI/CD          : Azure DevOps
- Dataset        : Kaggle Loan Default Dataset

## Environments
| Environment | Branch  | Schema |
|-------------|---------|--------|
| Development | develop | DEV    |
| Testing     | test    | TEST   |
| Production  | main    | PROD   |

## Project Structure
models/
├── staging/    ← cleaned source data
├── marts/      ← fact & dimension tables
└── reports/    ← business reporting layer
