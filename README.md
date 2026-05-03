# UnitedHealthcare (unitedhealthcare)

UnitedHealthcare is one of the largest health insurance providers in the United States, serving more than 50 million people through employer-sponsored plans, individual and family coverage, Medicare Advantage, and Medicaid managed care. UnitedHealthcare provides APIs for healthcare providers through the UHC API Marketplace covering eligibility verification, claims management, and prior authorization, and FHIR R4-compliant Interoperability APIs for patient data access, provider directory, and drug formulary per CMS interoperability mandates (CMS-9115-F).

**URL:** [Visit UnitedHealthcare API Marketplace](https://apimarketplace.uhcprovider.com/#/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Health Insurance, Healthcare, FHIR, Claims, Eligibility

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### UnitedHealthcare Provider API

The UnitedHealthcare Provider API provides real-time access to eligibility verification, claims management, prior authorization, and provider directory services through the UHC API Marketplace. Enables healthcare providers to verify member coverage, check claim status, validate claims before submission, check prior authorization requirements, and access provider demographic data.

**Human URL:** [https://apimarketplace.uhcprovider.com/#/](https://apimarketplace.uhcprovider.com/#/)

#### Tags:

 - Health Insurance, Healthcare, Eligibility, Claims, Prior Authorization

#### Properties

- [Documentation](https://apimarketplace.uhcprovider.com/#/)
- [OpenAPI](openapi/unitedhealthcare-provider-api-openapi.yml)
- [Eligibility Response Schema](json-schema/provider-eligibility-response-schema.json)
- [Claim Inquiry Response Schema](json-schema/provider-claim-inquiry-response-schema.json)
- [JSON-LD Context](json-ld/unitedhealthcare-provider-api-context.jsonld)
- [Eligibility Response Example](examples/provider-eligibility-response-example.json)

### UnitedHealthcare Interoperability API

The UnitedHealthcare Interoperability APIs provide FHIR R4-compliant access to patient health data in compliance with CMS Interoperability and Patient Access final rule (CMS-9115-F). Includes Patient Access API for member claims history and coverage, Provider Directory API for network provider search implementing Da Vinci PDex Plan Net IG, and Formulary API for drug coverage information.

**Human URL:** [https://www.uhc.com/legal/interoperability-apis](https://www.uhc.com/legal/interoperability-apis)

#### Tags:

 - Health Insurance, Healthcare, FHIR, Patient Access, Provider Directory, Formulary

#### Properties

- [Documentation](https://www.uhc.com/legal/interoperability-apis)
- [OpenAPI](openapi/unitedhealthcare-interoperability-api-openapi.yml)
- [FHIR Bundle Schema](json-schema/interoperability-fhir-bundle-schema.json)
- [FHIR Patient Schema](json-schema/interoperability-fhir-patient-schema.json)
- [JSON-LD Context](json-ld/unitedhealthcare-interoperability-api-context.jsonld)
- [FHIR Bundle Example](examples/interoperability-fhir-bundle-example.json)

## Common Properties

- [UnitedHealthcare API Marketplace](https://apimarketplace.uhcprovider.com/#/)
- [UHC Interoperability APIs](https://www.uhc.com/legal/interoperability-apis)
- [UnitedHealthcare for Providers](https://www.uhcprovider.com)

## Features

| Name | Description |
|------|-------------|
| Real-Time Eligibility Verification | Verify UnitedHealthcare member eligibility and benefits in real time at the point of care, reducing claim denials and improving patient financial transparency. |
| Claim Pre-Check | Validate claims before submission to identify errors, missing authorizations, and billing issues that would cause denials, accelerating payment cycles. |
| Prior Authorization Check | Determine prior authorization requirements for procedures and check existing authorization status to streamline clinical workflows. |
| FHIR R4 Patient Access | CMS-mandated FHIR R4 APIs enabling patients and authorized applications to access claims history, coverage data, and clinical information. |
| Provider Directory | FHIR R4 Provider Directory implementing Da Vinci PDex Plan Net IG for searching UnitedHealthcare network providers, organizations, and locations. |
| Drug Formulary | FHIR-based formulary API providing drug coverage tier information, prior authorization requirements, and quantity limits for prescription medications. |
| Claims Inquiry | Real-time claim status inquiry returning payment details, denial reasons, adjustment codes, and explanation of benefits data. |

## Use Cases

| Name | Description |
|------|-------------|
| Point-of-Care Eligibility | Verify patient UnitedHealthcare coverage and benefits at check-in using the real-time eligibility API to collect accurate copays and reduce billing errors. |
| Revenue Cycle Management | Integrate claim pre-check and claim inquiry APIs into practice management systems to automate claim validation and track payment status. |
| Prior Authorization Workflows | Embed prior authorization checking in clinical workflows to immediately determine if approval is needed before scheduling procedures or prescribing medications. |
| Patient Portal Integration | Enable patient portals to display claims history, coverage details, and EOBs using the FHIR Patient Access API for transparent member engagement. |
| Provider Search Applications | Build provider search tools and care coordination apps using the FHIR Provider Directory API to find in-network physicians, specialists, and facilities. |
| Formulary Management | Integrate the Formulary API into EHR and e-prescribing workflows to check drug coverage tiers and authorization requirements at point of prescribing. |

## Integrations

| Name | Description |
|------|-------------|
| Epic Systems | UnitedHealthcare APIs integrate with Epic EHR for real-time eligibility verification, prior authorization, and FHIR-based data exchange. |
| Cerner/Oracle Health | FHIR R4 Interoperability APIs integrate with Cerner for patient data access and provider directory services. |
| Change Healthcare | Provider APIs complement Change Healthcare clearinghouse services for comprehensive claims management and eligibility verification. |
| Availity | UnitedHealthcare participates in Availity's real-time eligibility and claims network providing additional access pathways for providers. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [UnitedHealthcare Provider API](openapi/unitedhealthcare-provider-api-openapi.yml)
- [UnitedHealthcare Interoperability API](openapi/unitedhealthcare-interoperability-api-openapi.yml)

### JSON Schema

- [provider-eligibility-request-schema.json](json-schema/provider-eligibility-request-schema.json)
- [provider-eligibility-response-schema.json](json-schema/provider-eligibility-response-schema.json)
- [provider-benefit-check-request-schema.json](json-schema/provider-benefit-check-request-schema.json)
- [provider-benefit-check-response-schema.json](json-schema/provider-benefit-check-response-schema.json)
- [provider-claim-pre-check-request-schema.json](json-schema/provider-claim-pre-check-request-schema.json)
- [provider-claim-pre-check-response-schema.json](json-schema/provider-claim-pre-check-response-schema.json)
- [provider-claim-inquiry-request-schema.json](json-schema/provider-claim-inquiry-request-schema.json)
- [provider-claim-inquiry-response-schema.json](json-schema/provider-claim-inquiry-response-schema.json)
- [provider-prior-auth-check-request-schema.json](json-schema/provider-prior-auth-check-request-schema.json)
- [provider-prior-auth-check-response-schema.json](json-schema/provider-prior-auth-check-response-schema.json)
- [provider-provider-demographics-schema.json](json-schema/provider-provider-demographics-schema.json)
- [interoperability-fhir-bundle-schema.json](json-schema/interoperability-fhir-bundle-schema.json)
- [interoperability-fhir-patient-schema.json](json-schema/interoperability-fhir-patient-schema.json)

### JSON Structure

- [provider-eligibility-request-structure.json](json-structure/provider-eligibility-request-structure.json)
- [provider-eligibility-response-structure.json](json-structure/provider-eligibility-response-structure.json)
- [provider-benefit-check-request-structure.json](json-structure/provider-benefit-check-request-structure.json)
- [provider-benefit-check-response-structure.json](json-structure/provider-benefit-check-response-structure.json)
- [provider-claim-pre-check-request-structure.json](json-structure/provider-claim-pre-check-request-structure.json)
- [provider-claim-pre-check-response-structure.json](json-structure/provider-claim-pre-check-response-structure.json)
- [provider-claim-inquiry-request-structure.json](json-structure/provider-claim-inquiry-request-structure.json)
- [provider-claim-inquiry-response-structure.json](json-structure/provider-claim-inquiry-response-structure.json)
- [provider-prior-auth-check-request-structure.json](json-structure/provider-prior-auth-check-request-structure.json)
- [provider-prior-auth-check-response-structure.json](json-structure/provider-prior-auth-check-response-structure.json)
- [provider-provider-demographics-structure.json](json-structure/provider-provider-demographics-structure.json)
- [interoperability-fhir-bundle-structure.json](json-structure/interoperability-fhir-bundle-structure.json)
- [interoperability-fhir-patient-structure.json](json-structure/interoperability-fhir-patient-structure.json)

### JSON-LD

- [UnitedHealthcare Provider API Context](json-ld/unitedhealthcare-provider-api-context.jsonld)
- [UnitedHealthcare Interoperability API Context](json-ld/unitedhealthcare-interoperability-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [UnitedHealthcare Provider API](capabilities/shared/provider-api.yaml) — 5 operations for eligibility, claims, prior auth, and providers
- [UnitedHealthcare Interoperability API](capabilities/shared/interoperability-api.yaml) — 4 operations for patient, EOB, coverage, and practitioners

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Provider Operations](capabilities/provider-operations.yaml) | Provider API | 5 | Healthcare Provider, Billing Specialist, Prior Auth Coordinator |
| [Patient Data Access](capabilities/patient-data-access.yaml) | Interoperability API | 4 | Patient, Care Coordinator, Health App Developer |

## Vocabulary

- [UnitedHealthcare Vocabulary](vocabulary/unitedhealthcare-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 2 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [UnitedHealthcare Spectral Rules](rules/unitedhealthcare-spectral-rules.yml) — 26 rules across 10 categories enforcing UnitedHealthcare API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

