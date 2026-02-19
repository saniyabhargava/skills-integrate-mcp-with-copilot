---
name: Feature request — Actionable feedback & recommendations
about: Provide tailored recommendations based on model outputs
title: "Feature: Add actionable feedback and personalized recommendations"
labels: enhancement, ux
assignees: ''
---

## Summary
When predictions indicate risk or opportunity, return actionable recommendations (study plans, tutoring suggestions, extracurricular balance tips).

## Goals
- Provide rule-based and/or learned recommendations
- Store and surface recommendations per-student
- Allow editing and improving recommendation rules

## Acceptance criteria
- Endpoint or UI for retrieving recommendations for a student
- Basic rule-set or mapping from prediction ranges to recommendations
- Tests and documentation for the recommendation logic

## Tasks
- [ ] Define recommendation templates and rule engine
- [ ] Implement storage for recommendations (simple JSON or DB)
- [ ] Wire recommendations to prediction outputs
