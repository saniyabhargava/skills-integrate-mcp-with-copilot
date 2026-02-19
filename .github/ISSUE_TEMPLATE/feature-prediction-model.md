---
name: Feature request — Prediction model
about: Add a student-grade prediction model (SGPA) and inference API
title: "Feature: Add SGPA prediction model and inference"
labels: enhancement, ml
assignees: ''
---

## Summary
Add a machine learning component that predicts student SGPA from inputs (study hours, tutoring, absences, parental support, extracurricular activities, sports).

## Goals
- Provide a reproducible training pipeline and model artifact
- Serve predictions via an API endpoint
- Include unit tests for inference and an example notebook

## Acceptance criteria
- Training pipeline in `ml/` or `notebooks/` that trains and saves a model
- `/api/predict` (or equivalent) endpoint that returns predictions for sample inputs
- README section describing training, inputs, and performance metrics
- CI step to validate inference runs (smoke test)

## Tasks
- [ ] Design input schema and feature preprocessing
- [ ] Implement training script and save model
- [ ] Implement inference API and tests
- [ ] Add example notebook and sample dataset

## Notes
Consider use of scikit-learn for baseline models and add a simple CI smoke-test to validate predictions.
