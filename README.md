# CNH (cnh)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CNH Industrial is a global leader in the manufacturing and distribution of agricultural and construction equipment, with brands including Case IH, New Holland, STEYR, Case CE, and New Holland Construction. Through develop.cnh.com CNH operates a developer portal that exposes the FieldOps API - a unified, ISO 15143-3 compliant REST API for vehicle telemetry, equipment management, farm/grower hierarchy, operations, prescription Rx delivery, and webhook subscriptions across both agronomic machinery and construction equipment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Agriculture
- Construction
- Telematics
- Equipment
- FieldOps

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### CNH FieldOps API

The CNH FieldOps API replaces the previously available CNH Ag Data and CONNECT Machine Data APIs and provides a unified, OAuth 2.0 secured REST API for both agronomic machinery and construction equipment connected to a FieldOps account. Vehicle telemetry follows the ISO 15143-3 specification with two profiles - CP (CAN Parameter, default) and MH (Machine Health) - and supports time-series data such as locations, operating hours, idle hours, fuel and DEF remaining, peak speed, distance, fault codes, and engine condition. Additional endpoint groups cover Equipment, Operations By Vehicle, Prescriptions (send Rx files), Farm Setup (Grower / Farm / Field / Boundary), Files, and Webhooks.

- **Human URL:** [https://develop.cnh.com/api-guides/fieldops-api](https://develop.cnh.com/api-guides/fieldops-api)
- **Base URL:** `https://api.fieldops.cnh.com`

#### Tags

- Agriculture
- Construction
- ISO 15143-3
- OAuth2
- Telemetry
- Vehicles

#### Properties

- [Getting Started](https://develop.cnh.com/get-started)
- [Documentation](https://develop.cnh.com/api-guides)
- [Reference](https://develop.cnh.com/api-guides/fieldops-api)
- [Reference](https://develop.cnh.com/api-guides/fieldops-api/vehicle-telemetry)
- [OpenAPI](openapi/cnh-fieldops-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cnh-fieldops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cnh-fieldops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cnh-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cnh-telemetry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/cnh-context.jsonld)
- [Spectral Ruleset](rules/cnh-rules.yml)

### CNH Developer Portal

The CNH Developer Portal at develop.cnh.com hosts onboarding, authentication guidance, API guides, Postman collections, and curated SwaggerHub documentation for FieldOps and related CNH APIs. Developers register for credentials, obtain refresh tokens, and progress from sandbox to live data through the portal.

- **Human URL:** [https://develop.cnh.com/](https://develop.cnh.com/)

#### Tags

- Developer Portal
- Documentation
- OAuth2

#### Properties

- [Portal](https://develop.cnh.com/)
- [Getting Started](https://develop.cnh.com/get-started)
- [Postman Collection](collections/cnh-fieldops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cnh-fieldops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cnh)
- [Website](https://www.cnhindustrial.com/)
- [Portal](https://develop.cnh.com/)
- [Getting Started](https://develop.cnh.com/get-started)
- [Documentation](https://develop.cnh.com/api-guides)
- [OpenAPI](openapi/cnh-fieldops-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cnh-equipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cnh-telemetry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/cnh-context.jsonld)
- [Spectral Ruleset](rules/cnh-rules.yml)
- [Privacy Policy](https://www.cnhindustrial.com/en-us/privacy/pages/default.aspx)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
