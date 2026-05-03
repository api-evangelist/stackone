# StackOne

StackOne is an AI-powered embedded integration platform as a service (iPaaS) that provides Unified APIs for SaaS products and AI Agent Actions. It enables teams to ship hundreds of integrations in days by normalizing data models across 200+ enterprise SaaS providers including Workday, BambooHR, Salesforce, Greenhouse, and more. StackOne covers HRIS, ATS, CRM, LMS, IAM, Marketing, Ticketing, Messaging, Documents, and Screening categories.

**Website:** [https://www.stackone.com/](https://www.stackone.com/)
**Documentation:** [https://docs.stackone.com/](https://docs.stackone.com/)
**GitHub:** [https://github.com/StackOneHQ](https://github.com/StackOneHQ)

## Tags

- Integrations, iPaaS, Unified API, Human Resources, Recruitment, CRM, Marketing

## APIs

### StackOne Unified API
Covers platform account management, HRIS, ATS, CRM, and Marketing unified endpoints.

- **Base URL:** `https://api.stackone.com`
- **Authentication:** Basic auth with API key as username

## OpenAPI Specifications

| Spec | Path |
|---|---|
| StackOne Unified API | [openapi/stackone-openapi.yml](openapi/stackone-openapi.yml) |

## Spectral Rules

| Ruleset | Path |
|---|---|
| StackOne API Rules | [rules/stackone-rules.yml](rules/stackone-rules.yml) |

## Naftiko Capabilities

### Shared Definitions

| API | Path |
|---|---|
| StackOne API | [capabilities/shared/stackone-api.yaml](capabilities/shared/stackone-api.yaml) |

### Workflow Capabilities

| Workflow | Description | Path |
|---|---|---|
| People Operations | HRIS + ATS unified — employees, time-off, candidates, jobs, applications | [capabilities/people-operations.yaml](capabilities/people-operations.yaml) |
| Customer Engagement | CRM + Marketing unified — contacts, campaigns, templates | [capabilities/customer-engagement.yaml](capabilities/customer-engagement.yaml) |

## JSON Schema

| Schema | Path |
|---|---|
| Employee | [json-schema/stackone-employee-schema.json](json-schema/stackone-employee-schema.json) |
| Candidate | [json-schema/stackone-candidate-schema.json](json-schema/stackone-candidate-schema.json) |

## JSON Structure

| Structure | Path |
|---|---|
| Employee | [json-structure/stackone-employee-structure.json](json-structure/stackone-employee-structure.json) |

## JSON-LD

| Context | Path |
|---|---|
| StackOne Context | [json-ld/stackone-context.jsonld](json-ld/stackone-context.jsonld) |

## Examples

| Example | Path |
|---|---|
| List Employees | [examples/stackone-list-employees-example.json](examples/stackone-list-employees-example.json) |

## Vocabulary

| Vocabulary | Path |
|---|---|
| StackOne Vocabulary | [vocabulary/stackone-vocabulary.yml](vocabulary/stackone-vocabulary.yml) |

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-02
