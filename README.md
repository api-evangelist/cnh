# CNH (cnh)

CNH Industrial is a global leader in the manufacturing and distribution of agricultural and construction equipment, with brands including Case IH, New Holland, STEYR, Case CE, and New Holland Construction. Through develop.cnh.com CNH operates a developer portal that exposes the FieldOps API — a unified, ISO 15143-3 compliant REST API for vehicle telemetry, equipment management, farm/grower hierarchy, operations, prescription Rx delivery, and webhook subscriptions across both agronomic machinery and construction equipment.

**URL:** [https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cnh/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Access:** 3rd-Party

## Tags

- Agriculture
- Construction
- Equipment
- FieldOps
- Telematics

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-23

## APIs

### CNH FieldOps API

The CNH FieldOps API replaces the legacy CNH Ag Data and CONNECT Machine Data APIs and provides a unified, OAuth 2.0 secured REST API for both agronomic machinery and construction equipment connected to a FieldOps account. Telemetry follows ISO 15143-3 with two profiles — CP (CAN Parameter, default) and MH (Machine Health). Endpoint groups include Equipment, Vehicle Telemetry, Operations By Vehicle, Prescriptions, Farm Setup (Grower / Farm / Field / Boundary), Files, and Webhooks.

**Human URL:** [https://develop.cnh.com/api-guides/fieldops-api](https://develop.cnh.com/api-guides/fieldops-api)

**Base URL:** https://api.fieldops.cnh.com

#### Tags

- Agriculture, Construction, ISO 15143-3, OAuth2, Telemetry, Vehicles

#### Properties

- [Getting Started](https://develop.cnh.com/get-started)
- [Documentation](https://develop.cnh.com/api-guides)
- [FieldOps API Reference](https://develop.cnh.com/api-guides/fieldops-api)
- [Vehicle Telemetry Reference](https://develop.cnh.com/api-guides/fieldops-api/vehicle-telemetry)
- [OpenAPI](openapi/cnh-fieldops-openapi.yml)
- [Equipment JSON Schema](json-schema/cnh-equipment-schema.json)
- [Telemetry JSON Schema](json-schema/cnh-telemetry-schema.json)
- [JSON-LD Context](json-ld/cnh-context.jsonld)
- [Spectral Ruleset](rules/cnh-rules.yml)
- [Naftiko Capabilities](capabilities/cnh-fieldops-capabilities.yml)

#### Features

- **ISO 15143-3 Telemetry:** Standards-based vehicle telemetry across CNH brands and equipment classes.
- **CP and MH Profiles:** CAN Parameter (default) and Machine Health telemetry profiles.
- **Fault Codes:** Fault, caution, and engine-condition codes per vehicle.
- **Aggregated Metrics:** Daily metrics including operating hours, idle hours, fuel ratio, distance, and peak speed.
- **Prescription Rx Delivery:** Push prescription files directly to a vehicle or FieldOps field.
- **Farm Hierarchy:** Grower / Farm / Field / Boundary management.
- **Operations by Vehicle:** Recorded field operations per vehicle.
- **Webhooks:** Subscribe to FieldOps event notifications.
- **OAuth 2.0:** Refresh and access token authentication via develop.cnh.com.

#### Use Cases

- **Fleet Telematics:** Power third-party fleet-management systems with CNH equipment telemetry.
- **Predictive Maintenance:** Use Machine Health telemetry and fault codes to anticipate maintenance.
- **Precision Agriculture:** Push prescription Rx files into the workflow for variable-rate application.
- **Farm Management Systems:** Hydrate FMS dashboards with grower / farm / field hierarchies and operations.
- **Construction Equipment Tracking:** Track Case CE and New Holland Construction equipment via standardized ISO telematics.

### CNH Developer Portal

The CNH Developer Portal at develop.cnh.com hosts onboarding, authentication guidance, API guides, Postman collections, and curated SwaggerHub documentation.

**Human URL:** [https://develop.cnh.com/](https://develop.cnh.com/)

## Common Properties

- [Website](https://www.cnhindustrial.com/)
- [Portal](https://develop.cnh.com/)
- [Getting Started](https://develop.cnh.com/get-started)
- [Documentation](https://develop.cnh.com/api-guides)
- [OpenAPI](openapi/cnh-fieldops-openapi.yml)
- [JSON Schemas](json-schema/cnh-equipment-schema.json)
- [JSON-LD Context](json-ld/cnh-context.jsonld)
- [Spectral Ruleset](rules/cnh-rules.yml)
- [Naftiko Capabilities](capabilities/cnh-fieldops-capabilities.yml)
- [Privacy Policy](https://www.cnhindustrial.com/en-us/privacy/pages/default.aspx)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
