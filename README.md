# UnitedHealthcare (unitedhealthcare)

UnitedHealthcare is one of the largest health insurance providers in the United States, offering employer-sponsored health benefits, individual and family plans, Medicare and Medicaid plans, and managed care services. UnitedHealthcare provides APIs for healthcare providers through the UHC API Marketplace for eligibility verification, claims management, and prior authorization, and FHIR R4-compliant Interoperability APIs for patient data access and provider directory services per CMS mandates.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Health Insurance
- Healthcare
- FHIR
- Claims
- Eligibility

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### UnitedHealthcare Provider API

The UnitedHealthcare Provider API provides real-time access to eligibility verification, claims management, prior authorization, and provider directory services through the UHC API Marketplace. Enables healthcare providers to verify member coverage, check claim status, validate claims before submission, check prior authorization requirements, and access provider demographic data.

- **Human URL:** [https://apimarketplace.uhcprovider.com/#/](https://apimarketplace.uhcprovider.com/#/)
- **Base URL:** `https://api.uhcprovider.com`

#### Tags

- Health Insurance
- Healthcare
- Eligibility
- Claims
- Prior Authorization

#### Properties

- [Documentation](https://apimarketplace.uhcprovider.com/#/)
- [OpenAPI](openapi/unitedhealthcare-provider-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unitedhealthcare-provider-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unitedhealthcare-provider-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Schema](json-schema/provider-eligibility-response-schema.json)
- [Schema](json-schema/provider-claim-inquiry-response-schema.json)
- [J S O N- L D  Context](json-ld/unitedhealthcare-provider-api-context.jsonld)
- [Example](examples/provider-eligibility-response-example.json)

### UnitedHealthcare Interoperability API

The UnitedHealthcare Interoperability APIs provide FHIR R4-compliant access to patient health data in compliance with CMS Interoperability and Patient Access final rule (CMS-9115-F). Includes Patient Access API for member claims history, coverage, and health records, Provider Directory API for network provider search, and Formulary API for drug coverage information.

- **Human URL:** [https://www.uhc.com/legal/interoperability-apis](https://www.uhc.com/legal/interoperability-apis)
- **Base URL:** `https://api.uhc.com/fhir/R4`

#### Tags

- Health Insurance
- Healthcare
- FHIR
- Patient Access
- Provider Directory
- Formulary

#### Properties

- [Documentation](https://www.uhc.com/legal/interoperability-apis)
- [OpenAPI](openapi/unitedhealthcare-interoperability-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/unitedhealthcare-interoperability-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unitedhealthcare-interoperability-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Schema](json-schema/interoperability-fhir-bundle-schema.json)
- [Schema](json-schema/interoperability-fhir-patient-schema.json)
- [J S O N- L D  Context](json-ld/unitedhealthcare-interoperability-api-context.jsonld)
- [Example](examples/interoperability-fhir-bundle-example.json)

## Common Properties

- [GitHub Organization](https://github.com/UnitedHealthCare)
- [LinkedIn](https://www.linkedin.com/company/unitedhealthcare)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
