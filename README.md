# Lithic (lithic)

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

Lithic is a modern card-issuing and program-management platform offering REST APIs for cards, accounts, transactions, authorization control, ACH/wire payments, external bank accounts, account-holder KYC/KYB, 3-D Secure, tokenization, disputes, and webhooks. OpenAPI spec is published via Stainless and powers official SDKs in Node, Python, Go, Java, Kotlin.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lithic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lithic/refs/heads/main/apis.yml)

## Tags

- FinTech
- BaaS
- Card Issuing
- Payments
- Embedded Finance

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Lithic REST API

REST API covering cards, accounts, account holders (KYC/KYB), authorization rules and 3DS, transactions, financial accounts, external bank accounts, ACH and wire payments, book transfers, statements, payments, disputes, tokenization, and webhooks across 191 endpoints.

- **Human URL:** [https://docs.lithic.com/reference](https://docs.lithic.com/reference)
- **Base URL:** `https://api.lithic.com/v1`

#### Tags

- REST
- Card Issuing
- Payments
- ACH

#### Properties

- [Documentation](https://docs.lithic.com/reference)
- [OpenAPI](openapi/lithic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lithic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lithic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lithic Auth Stream Access (ASA)

Real-time HTTP endpoint customers expose for Lithic to call synchronously during authorization for custom approve/decline logic.

- **Human URL:** [https://docs.lithic.com/docs/auth-stream-access-asa](https://docs.lithic.com/docs/auth-stream-access-asa)
- **Base URL:** `customer-hosted`

#### Tags

- Webhooks
- RTD

#### Properties

- [Documentation](https://docs.lithic.com/docs/auth-stream-access-asa)
- [Postman Collection](collections/lithic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lithic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lithic Webhooks

Outbound HTTP webhook delivery for transaction, card, account-holder, dispute, and payment events.

- **Human URL:** [https://docs.lithic.com/docs/event-webhooks](https://docs.lithic.com/docs/event-webhooks)
- **Base URL:** `https://api.lithic.com/v1/events`

#### Tags

- Webhooks

#### Properties

- [Documentation](https://docs.lithic.com/docs/event-webhooks)
- [Postman Collection](collections/lithic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lithic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lithic-com)
- [LinkedIn](https://www.linkedin.com/company/lithic)
- [Website](https://lithic.com/)
- [Plans](plans/lithic-plans-pricing.yml)
- [Rate Limits](rate-limits/lithic-rate-limits.yml)
- [Fin Ops](finops/lithic-finops.yml)
- [L L Ms Txt](https://docs.lithic.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
