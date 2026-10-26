# MetaMap (metamap)

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

MetaMap (formerly Mati) is an identity verification platform founded in 2017 in San Francisco and headquartered there, serving 600+ companies across 50+ countries with a focus on Latin America, Africa, and other emerging markets. The platform combines document verification, biometric liveness, facematch, watchlist screening, behavioral risk signals, and 40+ government-database "GovChecks" to power KYC, AML compliance, customer onboarding, authentication, and financial risk management workflows for banks, fintechs, lenders, telcos, and transportation providers. Developers integrate via a REST API on api.prod.metamap.com, configurable workflows ("metamaps"), webhooks, and native SDKs for Web, iOS, Android, Flutter, React Native, Cordova, and Capacitor. MetaMap joined Incode in 2024 to expand identity-verification coverage globally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/metamap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/metamap/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Identity Verification
- KYC
- AML
- Anti-Money Laundering
- Compliance
- Biometrics
- Document Verification
- Facematch
- Liveness
- GovCheck
- Watchlist
- Background Check
- Credit Check
- Risk
- Fraud Prevention
- Onboarding
- LatAm
- Africa
- Mobile SDK

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### MetaMap API

MetaMap's identity verification REST API. Start and manage user verifications, send document photos/selfies/videos, run watchlist screening (Comply Advantage and custom watchlists), email and phone ownership/risk checks, credit checks, court-record background checks, and 40+ government database checks across Latin America (Brazil, Mexico, Colombia, Chile, Costa Rica, Dominican Republic, Panama, Paraguay, Peru, Uruguay), Africa (Ghana, Kenya, Nigeria), and Asia (Philippines). OAuth 2.0 client-credentials flow yields a 1-hour JWT bearer token; results are delivered via configurable webhooks.

- **Human URL:** [https://docs.metamap.com/reference/authentication](https://docs.metamap.com/reference/authentication)
- **Base URL:** `https://api.prod.metamap.com`

#### Tags

- Identity Verification
- KYC
- AML
- Compliance
- Authentication
- Verifications

#### Properties

- [Documentation](https://docs.metamap.com/docs/api-guide)
- [Documentation](https://docs.metamap.com/reference/authentication)
- [OpenAPI](openapi/metamap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/metamap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/metamap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.metamap.com/llms.txt)
- [Webhooks](https://docs.metamap.com/docs/webhook-specifications)
- [Webhooks](https://docs.metamap.com/docs/configure-your-webhook-url)
- [Errors](https://docs.metamap.com/docs/errors)

## Common Properties

- [Portal](https://metamap.com)
- [About Us](https://metamap.com/about-metamap)
- [Documentation](https://metamap.com/why-metamap)
- [Documentation](https://metamap.com/verification-tools-library)
- [Documentation](https://metamap.com/all-industries)
- [Documentation](https://metamap.com/kyc-solutions-aml-compliance/)
- [Documentation](https://metamap.com/banking-industry-kyc-solutions/)
- [Documentation](https://metamap.com/fintech-kyc-solutions/)
- [Documentation](https://metamap.com/lending-payments-kyc-solutions/)
- [Documentation](https://metamap.com/telecommunication-kyc-solutions/)
- [Documentation](https://metamap.com/transportation-kyc-solutions/)
- [Contact](https://metamap.com/contact-metamap)
- [Documentation](https://metamap.com/careers)
- [Press](https://metamap.com/press-and-media/)
- [Documentation](https://metamap.com/resources-home)
- [Privacy Policy](https://metamap.com/privacy-policy)
- [Status Page](https://status.metamap.com)
- [Sign Up](https://dashboard.getmati.com/)
- [Documentation](https://dashboard.getmati.com/dev)
- [Documentation](https://docs.metamap.com/)
- [Getting Started](https://docs.metamap.com/docs/getting-started)
- [Documentation](https://docs.metamap.com/docs/dashboard)
- [Documentation](https://docs.metamap.com/docs/single-sign-on)
- [Documentation](https://docs.metamap.com/docs/metamaps)
- [Documentation](https://docs.metamap.com/docs/merits)
- [Documentation](https://docs.metamap.com/docs/metamap-button)
- [Documentation](https://docs.metamap.com/docs/verification-results)
- [Documentation](https://docs.metamap.com/docs/custom-encryption)
- [Documentation](https://docs.metamap.com/docs/sdk-customization)
- [Documentation](https://docs.metamap.com/docs/document-verification)
- [Documentation](https://docs.metamap.com/docs/biometrics)
- [Documentation](https://docs.metamap.com/docs/govcheck)
- [Documentation](https://docs.metamap.com/docs/list-of-government-checks-by-country)
- [Documentation](https://docs.metamap.com/docs/location-intelligence)
- [Documentation](https://docs.metamap.com/docs/uam)
- [Documentation](https://docs.metamap.com/docs/facematch)
- [Documentation](https://docs.metamap.com/docs/email-check)
- [Documentation](https://docs.metamap.com/docs/phone-check)
- [Documentation](https://docs.metamap.com/docs/anti-money-laundering)
- [Documentation](https://docs.metamap.com/docs/custom-watchlists)
- [Documentation](https://docs.metamap.com/docs/e-signature)
- [Documentation](https://docs.metamap.com/docs/credit-check)
- [Documentation](https://docs.metamap.com/docs/tax-data)
- [Documentation](https://docs.metamap.com/docs/background-check)
- [Documentation](https://docs.metamap.com/docs/video-agreement-1)
- [Documentation](https://docs.metamap.com/docs/on-demand-configuration-odc)
- [Webhooks](https://docs.metamap.com/docs/webhooks)
- [Webhooks](https://docs.metamap.com/docs/webhook-specifications)
- [F A Q](https://docs.metamap.com/docs/webhook-faq)
- [Errors](https://docs.metamap.com/docs/errors)
- [SDK](https://docs.metamap.com/docs/sdk)
- [Getting Started](https://docs.metamap.com/docs/quick-start-6)
- [SDK](https://docs.metamap.com/docs/android)
- [SDK](https://docs.metamap.com/docs/ios)
- [SDK](https://docs.metamap.com/docs/quick-start-1)
- [SDK](https://docs.metamap.com/docs/quick-start-3)
- [Changelog](https://docs.metamap.com/docs/android-changelog)
- [Changelog](https://docs.metamap.com/docs/ios-changelog)
- [GitHub Organization](https://github.com/GetMetaMap)
- [SDK](https://github.com/GetMetaMap/metamap-android-sdk)
- [SDK](https://github.com/GetMetaMap/metamap-ios-sdk)
- [SDK](https://github.com/GetMetaMap/metamap-flutter-plugin)
- [SDK](https://github.com/GetMetaMap/metamap-reactnative-plugin)
- [SDK](https://github.com/GetMetaMap/metamap-cordova-plugin)
- [SDK](https://github.com/GetMetaMap/metamap-capacitor-plugin)
- [Code Examples](https://github.com/GetMetaMap/metamap-mobile-examples)
- [Code Examples](https://github.com/GetMetaMap/metamap-android-demo-kotlin)
- [Code Examples](https://github.com/GetMetaMap/metamap-demo-web-apps)
- [Code Examples](https://github.com/GetMetaMap/iOS_app_with_web_sdk_integration)
- [Code Examples](https://github.com/GetMetaMap/android_app_with_web_sdk_integration)
- [SDK](https://github.com/GetMetaMap/mati-python)
- [SDK](https://github.com/GetMetaMap/mati_ruby)
- [SDK](https://github.com/GetMetaMap/mati-node)
- [Features](undefined)
- [Pricing](https://metamap.com/contact-metamap)
- [Sign Up](https://dashboard.getmati.com/)
- [Sandbox](https://dashboard.getmati.com/)
- [Forum](https://docs.metamap.com/discuss)
- [Plans](plans/metamap-plans-pricing.yml)
- [Rate Limits](rate-limits/metamap-rate-limits.yml)
- [Fin Ops](finops/metamap-finops.yml)
- [Trust Center](https://app.vanta.com/metamap/trust/home)
- [Webhooks](https://docs.metamap.com/docs/biometric-verification-webhooks)
- [Webhooks](https://docs.metamap.com/docs/document-verification-webhooks)
- [Webhooks](https://docs.metamap.com/docs/location-intelligence-webhooks)
- [Webhooks](https://docs.metamap.com/docs/customer-access-management-webhooks)
- [Webhooks](https://docs.metamap.com/docs/custom-watchlist-webhooks)
- [Webhooks](https://docs.metamap.com/docs/email-check-webhooks)
- [Webhooks](https://docs.metamap.com/docs/phone-check-webhooks)
- [Webhooks](https://docs.metamap.com/docs/video-agreement-webhooks)
- [Webhooks](https://docs.metamap.com/docs/webhook-messages)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
