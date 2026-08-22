# Veryfi (veryfi)

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

Veryfi provides AI-powered OCR APIs for extracting structured data from financial documents including receipts, invoices, bank statements, checks, W-2s, W-8s, W-9s, business cards, contracts, and custom documents. The platform captures line items, taxes, totals, barcodes, vendor details, and more across 91 currencies and 38 languages with enterprise-grade accuracy. Veryfi offers SDKs in Python, Node.js, Go, Java, Swift, C#, Ruby, PHP, Rust, Kotlin, and Dart, plus mobile SDKs (Veryfi Lens) for iOS, Android, React Native, Ionic, Xamarin, and Cordova.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Document Processing
- Finance
- Invoices
- OCR
- Receipts
- Tax Forms

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Veryfi OCR API

The Veryfi OCR API (v8) provides AI-powered document data extraction across multiple document types. The base URL is https://api.veryfi.com/api/v8. Authentication uses CLIENT-ID header and AUTHORIZATION header with apikey USERNAME:API_KEY format, plus optional HMAC-SHA256 request signatures (X-Veryfi-Request-Signature and X-Veryfi-Request-Timestamp).

- **Human URL:** [https://docs.veryfi.com/](https://docs.veryfi.com/)

#### Tags

- AI
- Document Processing
- OCR

#### Properties

- [Documentation](https://docs.veryfi.com/)
- [Reference](https://docs.veryfi.com/api/)
- [Authentication](https://docs.veryfi.com/api/getting-started/authentication/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/openapi/veryfi-ocr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://hub.veryfi.com/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi Receipts & Invoices API

The Veryfi Receipts & Invoices API uses AI-powered OCR to extract structured JSON data from receipts, invoices, bills, and other financial documents. It supports documents in PDF and image formats and returns line-item level data including taxes, totals, vendor details, and barcodes.

- **Human URL:** [https://docs.veryfi.com/](https://docs.veryfi.com/)

#### Tags

- Document Processing
- Invoices
- OCR
- Receipts

#### Properties

- [Documentation](https://docs.veryfi.com/)
- [Reference](https://docs.veryfi.com/api/receipts-invoices/process-a-document/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi Bank Statements API

The Veryfi Bank Statements API extracts structured data from bank statements using AI-powered OCR, enabling automated reconciliation, fraud detection, and financial data capture workflows.

- **Human URL:** [https://docs.veryfi.com/api/bank-statements/](https://docs.veryfi.com/api/bank-statements/)

#### Tags

- Bank Statements
- Finance
- OCR

#### Properties

- [Documentation](https://docs.veryfi.com/api/bank-statements/)
- [Reference](https://docs.veryfi.com/api/bank-statements/get-a-bank-statement/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi W-2 API

The Veryfi W-2 API extracts structured data from W-2 wage and tax statements using AI-powered OCR, enabling automated processing of employee wage and tax documents for tax preparation and loan approvals.

- **Human URL:** [https://docs.veryfi.com/api/w2s/](https://docs.veryfi.com/api/w2s/)

#### Tags

- OCR
- Tax Forms
- W-2

#### Properties

- [Documentation](https://docs.veryfi.com/api/w2s/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi W-9 API

The Veryfi W-9 API extracts structured data from W-9 Request for Taxpayer Identification forms including TIN, entity type, and address information for HR and vendor management workflows.

- **Human URL:** [https://docs.veryfi.com/api/w9s/](https://docs.veryfi.com/api/w9s/)

#### Tags

- HR
- OCR
- Tax Forms
- W-9

#### Properties

- [Documentation](https://docs.veryfi.com/api/w9s/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi Checks API

The Veryfi Checks API extracts bank routing numbers, account numbers, check numbers, payee names, amounts, and dates from check images using AI-powered OCR.

- **Human URL:** [https://docs.veryfi.com/api/checks/](https://docs.veryfi.com/api/checks/)

#### Tags

- Banking
- Checks
- OCR

#### Properties

- [Documentation](https://docs.veryfi.com/api/checks/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi Any Documents API

The Veryfi ∀Docs (Any Documents) API extracts data from any custom document type using named blueprints. Supports contracts, custom forms, and any unstructured document where standard OCR APIs don't apply.

- **Human URL:** [https://docs.veryfi.com/](https://docs.veryfi.com/)

#### Tags

- Contracts
- Custom Documents
- Document Processing
- OCR

#### Properties

- [Documentation](https://docs.veryfi.com/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Veryfi Classification API

The Veryfi Classification API determines the document type before processing, enabling intelligent routing to the appropriate extraction endpoint.

- **Human URL:** [https://docs.veryfi.com/](https://docs.veryfi.com/)

#### Tags

- Classification
- Document Processing
- OCR

#### Properties

- [Documentation](https://docs.veryfi.com/)
- [Postman Collection](collections/veryfi-ocr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veryfi-ocr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/veryfi-inc)
- [Website](https://www.veryfi.com/)
- [Documentation](https://docs.veryfi.com/)
- [Console](https://hub.veryfi.com/)
- [Sign Up](https://app.veryfi.com/signup/api/)
- [Support](https://faq.veryfi.com/)
- [GitHub Organization](https://github.com/veryfi)
- [Privacy Policy](https://www.veryfi.com/privacy-policy/)
- [Terms of Service](https://www.veryfi.com/terms-of-service/)
- [SDK](https://pypi.org/project/veryfi/)
- [SDK](https://www.npmjs.com/package/veryfi)
- [Integrations](https://www.veryfi.com/integrations/)
- [M C P Server](https://github.com/veryfi/mcp-server)
- [Agent Skill](https://github.com/veryfi/veryfi-openclaw-skill)
- [L L Ms Txt](https://docs.veryfi.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
