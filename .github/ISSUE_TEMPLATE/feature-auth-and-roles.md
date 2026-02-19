---
name: Feature request — Authentication & roles
about: Add user authentication, roles (student/teacher/admin), and permissioning
title: "Feature: Add authentication and role-based access control"
labels: enhancement, security
assignees: ''
---

## Summary
Implement authentication and basic RBAC so students, teachers, and admins can access appropriate features (view vs. manage data).

## Goals
- Secure endpoints and UI with auth
- Role-based permissions for managing datasets and models
- Simple local dev auth (e.g., token-based or OAuth stub)

## Acceptance criteria
- Authentication middleware and sample users
- Roles: `student`, `teacher`, `admin` with clear permissions
- Documentation for adding users and roles

## Tasks
- [ ] Add auth middleware and sample config
- [ ] Protect sensitive endpoints and admin UI
- [ ] Add docs and tests for RBAC
