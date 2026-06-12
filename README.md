# Pleo (pleo)

Pleo is a business spend management platform that issues smart company cards to employees, enabling real-time expense tracking, receipt capture, automated bookkeeping, and reimbursement workflows. The Pleo REST API allows developers to automate workflows, sync accounting data, manage users and cards, provision vendor cards, and build custom integrations against ERP and accounting systems. Authentication supports both OAuth 2.0 (with PKCE) and API keys, with a scopes-based permission model and both sandbox and production environments. API access is included on Advanced and Beyond subscription plans.

APIs.json Index: https://raw.githubusercontent.com/api-evangelist/pleo/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=pleo-api-evangelist&utm_content=repo

## Tags

- Expense Management
- Company Cards
- Spend Management
- Reimbursements
- Accounting
- FinTech
- Finance

## APIs

### Pleo Accounting API

RESTful API for exporting accounting data, managing chart of accounts, tax codes, vendors, cost centers, employees, and integrating with accounting software. Supports OpenAPI/Swagger specification and Postman collections.

- **Documentation:** https://developers.pleo.io/docs/pleo-introduction
- **Base URL:** https://external.pleo.io

### Pleo Webhooks API

Event subscription management API enabling real-time notifications via webhooks for spend events, card activity, and expense updates.

- **Documentation:** https://developers.pleo.io/docs/webhooks

## Plans, Rate Limits & FinOps

| Resource | File |
|---|---|
| Plans & Pricing | [plans/pleo-plans-pricing.yml](plans/pleo-plans-pricing.yml) |
| Rate Limits | [rate-limits/pleo-rate-limits.yml](rate-limits/pleo-rate-limits.yml) |
| FinOps | [finops/pleo-finops.yml](finops/pleo-finops.yml) |

**Pricing summary:** Four tiers — Starter (£9.50/mo, yearly only, 3 users), Essential (£45/mo, +£11/user), Advanced (£109/mo, +£15/user, includes API access + 0.5% cashback), Beyond (£219/mo, +£18/user, full API + 0.75% cashback). Annual billing saves ~10%.

**Rate limits:** No publicly documented numeric request-per-minute limits. HTTP 429 with Retry-After header is used when throttled. Batch export job items capped at 100 per request.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|---|---|
| Website | https://www.pleo.io |
| Documentation | https://developers.pleo.io |
| GitHub Organization | https://github.com/pleo-io |
| LinkedIn | https://www.linkedin.com/company/pleo-company |
| X / Twitter | https://x.com/pleo |
| Blog | https://blog.pleo.io/en |
| Pricing | https://www.pleo.io/en/pricing |
| Status Page | https://status.pleo.io |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
