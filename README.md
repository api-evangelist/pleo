# Pleo (pleo)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
