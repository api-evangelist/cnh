# CNH (cnh)

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
