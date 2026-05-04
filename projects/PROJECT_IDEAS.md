# Project Ideas

## Project 1 — CSV Data Quality Checker

Goal: Build a Python tool that checks CSV files for common data issues.

Features:
- Missing values
- Duplicate rows
- Invalid date formats
- Invalid numeric values
- Row count summary
- Data quality report

Skills:
- Python
- pandas
- Data validation
- Reporting

---

## Project 2 — SQL Incremental Load Framework

Goal: Build a reusable SQL pattern for incremental loading.

Features:
- Control table
- Watermark column
- Stage table
- MERGE into final table
- Audit logging
- Error logging

Skills:
- SQL
- Data Engineering
- Pipeline design
- Production support thinking

---

## Project 3 — Azure Data Factory Metadata-Driven Pipeline

Goal: Build an ADF design where config drives ingestion.

Features:
- Source configuration table
- Dynamic source and target paths
- Copy activity
- Error handling
- Email notification
- Audit table

Skills:
- ADF
- Azure SQL
- ADLS
- Monitoring

---

## Project 4 — Databricks Medallion Pipeline

Goal: Build Raw → Bronze → Silver → Gold tables.

Features:
- Read raw files
- Bronze ingestion
- Silver cleaning
- Gold aggregation
- Delta Lake tables
- Data quality checks

Skills:
- Databricks
- PySpark
- Delta Lake
- Medallion architecture

---

## Project 5 — ML Model from Gold Table

Goal: Train a simple ML model using clean Gold data.

Features:
- Load Gold table
- Feature engineering
- Train/test split
- Model training
- Evaluation metrics
- Save predictions

Skills:
- Python
- scikit-learn
- ML lifecycle
- MLflow optional

---

## Project 6 — RAG Document Q&A App

Goal: Ask questions over your own documents.

Features:
- Load documents
- Chunk text
- Generate embeddings
- Store vectors
- Retrieve relevant chunks
- Generate answer with citations

Skills:
- GenAI
- RAG
- Azure AI Search / vector search
- Prompting

---

## Project 7 — Data Quality Investigation Agent

Goal: Build an agent that helps investigate data issues.

Example question:
"Why did yesterday's pipeline load fewer rows?"

Agent actions:
- Read audit table
- Compare row counts
- Check failed files
- Summarize possible causes
- Suggest next steps

Skills:
- Agentic AI
- SQL tool calling
- Observability
- Data Engineering operations

---

## Best portfolio project for Microsoft-style goal

Build this as your main project:

```text
AI-Ready Data Platform with RAG Assistant
```

Architecture:

```text
Source Files / SQL
→ ADF Ingestion
→ ADLS Raw
→ Databricks Bronze/Silver/Gold
→ MLflow Model or RAG Index
→ Azure AI Search
→ GenAI Assistant
→ Monitoring/Audit Tables
```

This project shows:
- Data Engineering
- Azure
- Databricks
- ML lifecycle
- GenAI/RAG
- Production thinking
