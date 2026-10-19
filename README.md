# Healthcare Data Pipeline Dashboard

An offline, interactive dashboard demonstrating how healthcare data from claims, clinical, eligibility, and reference sources can be ingested, standardized, linked, quality checked, and shaped into an analytics-ready dataset.

## Live dashboard

https://tedcui.github.io/healthcare-data-pipeline/

## What it demonstrates

- Multi-source ingestion across ICD, CPT, EHR, eligibility, and provider data
- ETL pipeline stages and record-level reconciliation
- Data quality controls, exceptions, and operational readiness
- Field-level lineage from source systems to analytical outputs
- Real-world integration challenges and their proposed handling

The operational records and metrics are illustrative demo content. They are designed to demonstrate analytical and data-development workflows, not represent production healthcare data.

## Files

- `index.html` - GitHub Pages homepage
- `healthcare_data_pipeline_dashboard.html` - standalone offline dashboard
- `build_data_pipeline_dashboard.py` - reproducible dashboard builder

## Rebuild locally

```powershell
python build_data_pipeline_dashboard.py
```

The builder writes both dashboard HTML files. No external JavaScript packages or internet connection are required to use the dashboard.
