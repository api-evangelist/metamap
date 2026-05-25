# MetaMap (metamap)
MetaMap (formerly Mati) is an identity verification platform founded in 2017 in San Francisco, serving 600+ companies across 50+ countries with a focus on Latin America, Africa, and other emerging markets. The platform combines document verification, biometric liveness, facematch, watchlist screening, behavioral risk signals, and 40+ government-database "GovChecks" to power KYC, AML compliance, customer onboarding, authentication, and financial risk management workflows for banks, fintechs, lenders, telcos, and transportation providers. Developers integrate via a REST API on `api.prod.metamap.com`, configurable workflows ("metamaps"), webhooks, and native SDKs for Web, iOS, Android, Flutter, React Native, Cordova, and Capacitor. MetaMap joined Incode in 2024 to expand identity-verification coverage globally.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/metamap/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Identity Verification, KYC, AML, Anti-Money Laundering, Compliance, Biometrics, Document Verification, Facematch, Liveness, GovCheck, Watchlist, Background Check, Credit Check, Risk, Fraud Prevention, Onboarding, LatAm, Africa, Mobile SDK

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## API Surface

| Surface | Endpoints | Description |
|---|---|---|
| Authentication | 2 | OAuth 2.0 client-credentials token exchange (`POST /oauth`); 1-hour JWT bearer. |
| Verifications | 7 | Start, retrieve, update, delete a verification; send-input; skip-upload-wait; PDF download. |
| Webhooks | 1 | Retrieve resource data when a webhook fires. |
| Custom Watchlists | 1 | Upload a custom watchlist file. |
| Watchlist Checks | 1 | Comply Advantage (sanctions, PEP, adverse media). |
| Email Checks | 2 | Ownership (OTP) and behavioral risk. |
| Phone Checks | 2 | Ownership (SMS OTP) and behavioral risk. |
| GovChecks | 34 | 40+ country/dataset combinations across LatAm, Africa, and the Philippines. |
| Credit Checks | 1 | Brazil Serasa. |
| Background Checks | 2 | Court records in Mexico and Brazil. |
| **Total** | **53** | |

## APIs

### MetaMap API
The unified MetaMap REST API. Start and manage user verifications, send document photos / selfies / videos, run watchlist screening, email and phone ownership / risk checks, credit checks, court-record background checks, and 40+ government database checks across Latin America, Africa, and Asia. OAuth 2.0 client-credentials flow yields a 1-hour JWT bearer token; results are delivered via configurable webhooks.

**Base URL:** `https://api.prod.metamap.com`
**Human URL:** [https://docs.metamap.com](https://docs.metamap.com)

- [Documentation — API Guide](https://docs.metamap.com/docs/api-guide)
- [Documentation — Authentication](https://docs.metamap.com/reference/authentication)
- [Documentation — Webhooks](https://docs.metamap.com/docs/webhook-specifications)
- [Documentation — Errors](https://docs.metamap.com/docs/errors)
- [Documentation — `llms.txt`](https://docs.metamap.com/llms.txt)
- [OpenAPI 3.1](openapi/metamap-openapi.yml)
- [JSON Schema — Verification](json-schema/metamap-verification-schema.json)
- [JSON Schema — GovCheck](json-schema/metamap-govcheck-schema.json)
- [JSON Schema — Webhook Event](json-schema/metamap-webhook-schema.json)
- [JSON Structure — Verification](json-structure/metamap-verification-structure.json)
- [JSON-LD Context](json-ld/metamap-context.jsonld)
- [Spectral Rules](rules/metamap-rules.yml)
- [Vocabulary](vocabulary/metamap-vocabulary.yml)
- [Naftiko Capability — Verifications](capabilities/verifications.yaml)
- [Naftiko Capability — GovChecks](capabilities/govchecks.yaml)
- [Naftiko Capability — Standalone Checks](capabilities/standalone-checks.yaml)
- [Example — Authentication](examples/metamap-authentication-example.json)
- [Example — Start Verification](examples/metamap-start-verification-example.json)
- [Example — GovCheck Mexico CURP](examples/metamap-govcheck-mexico-curp-example.json)
- [Example — Comply Advantage](examples/metamap-comply-advantage-example.json)

## Common Properties

- [Portal — metamap.com](https://metamap.com)
- [About — About MetaMap](https://metamap.com/about-metamap)
- [About — Why MetaMap](https://metamap.com/why-metamap)
- [Documentation — Developer Hub](https://docs.metamap.com/)
- [GettingStarted](https://docs.metamap.com/docs/getting-started)
- [Documentation — Dashboard](https://docs.metamap.com/docs/dashboard)
- [Documentation — SSO](https://docs.metamap.com/docs/single-sign-on)
- [Documentation — Workflows (metamaps)](https://docs.metamap.com/docs/metamaps)
- [Documentation — Tools (merits)](https://docs.metamap.com/docs/merits)
- [Documentation — Verification Tools Library](https://metamap.com/verification-tools-library)
- [Documentation — All Industries](https://metamap.com/all-industries)
- [Documentation — KYC & AML Compliance](https://metamap.com/kyc-solutions-aml-compliance/)
- [Documentation — Document Verification](https://docs.metamap.com/docs/document-verification)
- [Documentation — Biometric Verification](https://docs.metamap.com/docs/biometrics)
- [Documentation — Facematch](https://docs.metamap.com/docs/facematch)
- [Documentation — Government Check](https://docs.metamap.com/docs/govcheck)
- [Documentation — GovChecks by Country](https://docs.metamap.com/docs/list-of-government-checks-by-country)
- [Documentation — Location Intelligence](https://docs.metamap.com/docs/location-intelligence)
- [Documentation — Customer Access Management](https://docs.metamap.com/docs/uam)
- [Documentation — Email Check](https://docs.metamap.com/docs/email-check)
- [Documentation — Phone Check](https://docs.metamap.com/docs/phone-check)
- [Documentation — Watchlist Check](https://docs.metamap.com/docs/anti-money-laundering)
- [Documentation — Custom Watchlists](https://docs.metamap.com/docs/custom-watchlists)
- [Documentation — E-Signature](https://docs.metamap.com/docs/e-signature)
- [Documentation — Credit Check](https://docs.metamap.com/docs/credit-check)
- [Documentation — Tax Check](https://docs.metamap.com/docs/tax-data)
- [Documentation — Court Records](https://docs.metamap.com/docs/background-check)
- [Documentation — Video Agreement](https://docs.metamap.com/docs/video-agreement-1)
- [Documentation — On-Demand Configuration](https://docs.metamap.com/docs/on-demand-configuration-odc)
- [Webhooks — Overview](https://docs.metamap.com/docs/webhooks)
- [Webhooks — Specifications](https://docs.metamap.com/docs/webhook-specifications)
- [Errors — Webhook & Step](https://docs.metamap.com/docs/errors)
- [GitHubOrganization — GetMetaMap](https://github.com/GetMetaMap)
- [SDK — Android](https://github.com/GetMetaMap/metamap-android-sdk)
- [SDK — iOS](https://github.com/GetMetaMap/metamap-ios-sdk)
- [SDK — Flutter Plugin](https://github.com/GetMetaMap/metamap-flutter-plugin)
- [SDK — React Native Plugin](https://github.com/GetMetaMap/metamap-reactnative-plugin)
- [SDK — Cordova / Ionic Plugin](https://github.com/GetMetaMap/metamap-cordova-plugin)
- [SDK — Capacitor Plugin](https://github.com/GetMetaMap/metamap-capacitor-plugin)
- [SDK — Mati Python (legacy)](https://github.com/GetMetaMap/mati-python)
- [SDK — Mati Ruby (legacy)](https://github.com/GetMetaMap/mati_ruby)
- [SDK — Mati Node (archived)](https://github.com/GetMetaMap/mati-node)
- [CodeExamples — Mobile Examples](https://github.com/GetMetaMap/metamap-mobile-examples)
- [CodeExamples — Android Kotlin Demo](https://github.com/GetMetaMap/metamap-android-demo-kotlin)
- [CodeExamples — Web Apps Demo](https://github.com/GetMetaMap/metamap-demo-web-apps)
- [CodeExamples — iOS App with Web SDK](https://github.com/GetMetaMap/iOS_app_with_web_sdk_integration)
- [CodeExamples — Android App with Web SDK](https://github.com/GetMetaMap/android_app_with_web_sdk_integration)
- [ChangeLog — Android SDK](https://docs.metamap.com/docs/android-changelog)
- [ChangeLog — iOS SDK](https://docs.metamap.com/docs/ios-changelog)
- [SignUp — MetaMap Dashboard](https://dashboard.getmati.com/)
- [Sandbox — Dashboard](https://dashboard.getmati.com/)
- [StatusPage — status.metamap.com](https://status.metamap.com)
- [TrustCenter — Vanta](https://app.vanta.com/metamap/trust/home)
- [PrivacyPolicy](https://metamap.com/privacy-policy)
- [Contact](https://metamap.com/contact-metamap)
- [Press](https://metamap.com/press-and-media/)
- [Careers](https://metamap.com/careers)
- [Resources](https://metamap.com/resources-home)
- [Pricing — Contact Sales](https://metamap.com/contact-metamap)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [MetaMap API](openapi/metamap-openapi.yml)

### JSON Schema

- [Verification](json-schema/metamap-verification-schema.json)
- [GovCheck](json-schema/metamap-govcheck-schema.json)
- [Webhook Event](json-schema/metamap-webhook-schema.json)

### JSON Structure

- [Verification](json-structure/metamap-verification-structure.json)

### JSON-LD

- [MetaMap Context](json-ld/metamap-context.jsonld)

### Spectral Rules

- [MetaMap Rules](rules/metamap-rules.yml)

### Vocabulary

- [MetaMap Vocabulary](vocabulary/metamap-vocabulary.yml)

### Capabilities (Naftiko)

- [Verifications](capabilities/verifications.yaml)
- [GovChecks](capabilities/govchecks.yaml)
- [Standalone Checks](capabilities/standalone-checks.yaml)

### Examples

- [Authentication](examples/metamap-authentication-example.json)
- [Start Verification](examples/metamap-start-verification-example.json)
- [GovCheck — Mexico CURP](examples/metamap-govcheck-mexico-curp-example.json)
- [Watchlist — Comply Advantage](examples/metamap-comply-advantage-example.json)

### Plans, Rate Limits, FinOps

- [Plans & Pricing](plans/metamap-plans-pricing.yml) — sales-led, contact for quote
- [Rate Limits](rate-limits/metamap-rate-limits.yml) — token-bucket model not publicly documented; merchant-tier gated
- [FinOps](finops/metamap-finops.yml) — FOCUS-aligned cost-attribution model

## Maintainers

- Kin Lane — [@apievangelist](https://twitter.com/apievangelist) — info@apievangelist.com — [apievangelist.com](https://apievangelist.com)

---

*This page is part of the [API Evangelist](https://apievangelist.com) catalog. The MetaMap (formerly Mati) profile was generated from the public developer hub at [docs.metamap.com](https://docs.metamap.com), the corporate site at [metamap.com](https://metamap.com), and the [GetMetaMap](https://github.com/GetMetaMap) GitHub organization.*
