---
name: Feature request — Data ingestion & dataset management
about: Add tools and pipelines to ingest, validate and manage datasets
title: "Feature: Add data ingestion and dataset management"
labels: enhancement, data
assignees: ''
---

## Summary
Create automated ingestion and validation for datasets (CSV/JSON) and a simple UI or CLI to manage sample datasets.

## Goals
- Reliable data ingestion pipelines with validation
- Sample dataset storage and versioning guidance
- Data schema and missing-value handling

## Acceptance criteria
- Ingestion scripts under `data/` or `scripts/` with validation checks
- Schema file (JSON Schema or similar) and example datasets
- Documentation showing how to add new datasets

## Tasks
- [ ] Define canonical dataset schema
- [ ] Implement ingestion + validation scripts
- [ ] Add example datasets and documentation
- [ ] Add tests for data validation
