# Healthcare Integration Portfolio

Index of public-safe healthcare integration, interoperability, and AI backend demos by [Dawit Tegegnwork Wubale](https://github.com/dawit-Tegegnwork).

[![Portfolio site](https://img.shields.io/badge/Portfolio-live-0ea5e9?style=flat-square)](https://dawit-tegegnwork.github.io/portfolio-website/)

## Live links

| Resource | URL |
|----------|-----|
| Portfolio website | https://dawit-tegegnwork.github.io/portfolio-website/ |
| Healthcare AI (cloud deploy) | [Render deploy guide](https://github.com/dawit-Tegegnwork/healthcare-ai-workflow-assistant/blob/main/docs/RENDER_DEPLOY.md) |
| Enterprise workflow (cloud deploy) | [Render deploy guide](https://github.com/dawit-Tegegnwork/enterprise-workflow-management-system/blob/master/docs/RENDER_DEPLOY.md) |

All projects use synthetic or demo data with documented limitations. None represent official national deployments or production clinical systems.

## Integration & Interoperability

### [LIS Analyzer Integration Demo](https://github.com/dawit-Tegegnwork/lis-analyzer-integration-demo)

Python demo for laboratory analyzer integration: CSV/JSON ingestion, validation, code mapping, and LIS-ready payloads.

**Stack:** Python, synthetic lab data, CI tests

### [eCHIS → DHIS2 OpenHIM Mediator](https://github.com/dawit-Tegegnwork/echis-dhis2-mediator)

OpenHIM mediator prototype for synthetic eCHIS-style community health reports → validation → DHIS2 dataValueSets, with optional AI quality review.

**Stack:** Node.js, Express, OpenHIM, Docker Compose, DHIS2 mock/play sandbox

### [OpenELIS Global 2](https://github.com/dawit-Tegegnwork/OpenELIS-Global-2) *(fork)*

Fork of OpenELIS Global for exploring the OpenELIS/LIMS ecosystem. Not original authorship.

**Stack:** Java, OpenELIS, LIMS

## Healthcare AI Backend

### [Healthcare AI Workflow Assistant](https://github.com/dawit-Tegegnwork/healthcare-ai-workflow-assistant)

FastAPI workflow demo: synthetic notes, mock LLM structured extraction, human review, PostgreSQL audit logs, dashboard.

**Stack:** Python, FastAPI, SQLModel, PostgreSQL, Docker Compose, pytest

## Full-stack & Backend Portfolio Demos

| Project | Focus |
|---------|-------|
| [enterprise-workflow-management-system](https://github.com/dawit-Tegegnwork/enterprise-workflow-management-system) | RBAC, JWT, approvals, audit, CSV export |
| [golang-transaction-api](https://github.com/dawit-Tegegnwork/golang-transaction-api) | Idempotency, transaction-safe transfers |
| [node-firebase-mobile-backend](https://github.com/dawit-Tegegnwork/node-firebase-mobile-backend) | Firebase emulators, Cloud Functions |
| [cpims-information-management-demo](https://github.com/dawit-Tegegnwork/cpims-information-management-demo) | Synthetic case records, data quality |
| [application-support-runbook-lab](https://github.com/dawit-Tegegnwork/application-support-runbook-lab) | Incident triage, UAT, SQL checks |

## EMR / Facility Software (Work in Progress)

### [Hospital Management System](https://github.com/dawit-Tegegnwork/hospital-management-system)

Work-in-progress Ethiopian EMR scaffold with module screens for registration, pharmacy, laboratory, radiology, and billing. Authentication and several backend integrations are still incomplete.

**Stack:** TypeScript, React, Vite, tRPC, Express, MySQL, Drizzle

## Profile

- GitHub profile: [dawit-Tegegnwork](https://github.com/dawit-Tegegnwork)
- Personal portfolio site: [portfolio-website](https://github.com/dawit-Tegegnwork/portfolio-website)

## Target Roles

Backend Software Engineer · Healthcare AI Engineer · Digital Health Software Engineer · Health Interoperability Engineer · OpenMRS / OpenELIS / Bahmni / DHIS2 / FHIR / HL7 roles
