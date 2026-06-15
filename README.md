# Veryfi (veryfi)

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
