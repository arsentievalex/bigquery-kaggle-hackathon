# Automating Construction Field Reports with BigQuery AI (BigQuery Kaggle Hackathon)

> **Note:** I recommend viewing this in a [Google Colab notebook](https://colab.research.google.com/drive/1-uFeaq8J4y9fLhOkwYR6-unBVkhLPeJ0?usp=sharing), which supports rendering audio files.

## Project Overview

Construction site inspections are essential for tracking progress, safety, and regulatory compliance. Inspectors typically capture observations through photos and voice recordings, as site conditions and limited time make detailed form-filling impractical. These photos and recordings are traditionally analyzed manually to compile field reports—a slow and labor-intensive process.

This project demonstrates how **BigQuery’s native AI capabilities** can automate this workflow, extracting structured insights directly from unstructured data and generating standardized inspection reports.

## Key Features

- **AI-Driven Extraction:** Use `AI.GENERATE_TABLE` and `OBJECT_TABLES` to extract structured information from unstructured photos and voice recordings.
- **Support for Multiple Project Types:** Handles renovation, safety inspection, and construction projects, each with its own relevant data points.
- **Automated Field Report Generation:** Populates a field report template with extracted data to fully automate report creation.
- **Aggregate Analysis:** Identifies common safety issues across cities and recurring risks in renovation projects, providing actionable insights for stakeholders.

## Benefits

- Reduces manual effort and administrative workload for inspectors.
- Accelerates reporting workflows and enables faster, data-driven decision-making.
- Improves safety compliance and project monitoring efficiency.
- Delivers measurable efficiency and cost savings to construction operations.

## Data Overview

- **Structured Data:** Includes fields such as `project_id`, `project_type`, `city`, and `customer_id`.
- **Unstructured Data:** Includes project photos and voice recordings from on-site inspections.
