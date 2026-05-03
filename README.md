# Veryfi

Veryfi provides AI-powered OCR APIs for extracting structured data from financial documents including receipts, invoices, bank statements, checks, W-2s, W-8s, W-9s, business cards, contracts, and custom documents. The platform captures line items, taxes, totals, barcodes, vendor details, and more across 91 currencies and 38 languages with enterprise-grade accuracy.

**URL:** [https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-03

## APIs

### Veryfi OCR API (v8)

Base URL: `https://api.veryfi.com/api/v8`

Authentication: `CLIENT-ID` header + `AUTHORIZATION: apikey USERNAME:API_KEY` header + optional HMAC-SHA256 request signatures.

- **Documentation:** [https://docs.veryfi.com/](https://docs.veryfi.com/)
- **Interactive Console:** [https://hub.veryfi.com/](https://hub.veryfi.com/)
- **OpenAPI Spec:** [openapi/veryfi-ocr-openapi.yml](openapi/veryfi-ocr-openapi.yml)

### Supported Document Types

| API | Endpoint | Description |
|-----|----------|-------------|
| Receipts & Invoices | `/partner/documents` | Full line-item extraction from receipts/invoices |
| Bank Statements | `/partner/bank-statements` | Transaction data, balances, account info |
| Checks | `/partner/checks` | MICR data, payee, amount, date |
| W-2 Forms | `/partner/w2s` | Wages, tax withholdings, employer/employee info |
| W-9 Forms | `/partner/w9s` | TIN, entity type, taxpayer info |
| Any Documents | `/partner/any-documents` | Custom blueprint extraction for any doc type |
| Classification | `/partner/classify` | Determine document type before processing |

## SDKs

Veryfi provides official SDKs for 12+ languages via the [veryfi GitHub org](https://github.com/veryfi):
Python, Node.js, Go, Java, Swift, C#, Ruby, PHP, Rust, Kotlin, Dart

Mobile SDKs (Veryfi Lens): iOS, Android, React Native, Ionic Capacitor, Xamarin, Cordova

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/veryfi-ocr-openapi.yml](openapi/veryfi-ocr-openapi.yml) | Full Veryfi OCR API v8 — documents, bank statements, checks, W-2s, W-9s, classification |

### Capabilities (Naftiko)

| File | Description |
|------|-------------|
| [capabilities/financial-document-processing.yaml](capabilities/financial-document-processing.yaml) | Unified financial document processing workflow — 12 tools for all document types |
| [capabilities/shared/veryfi-ocr.yaml](capabilities/shared/veryfi-ocr.yaml) | Shared Veryfi OCR API consumed definition |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/veryfi-ocr-rules.yml](rules/veryfi-ocr-rules.yml) | Spectral ruleset enforcing Veryfi OCR API conventions |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [json-schema/veryfi-document-schema.json](json-schema/veryfi-document-schema.json) | Receipt/invoice document schema |
| [json-schema/veryfi-bank-statement-schema.json](json-schema/veryfi-bank-statement-schema.json) | Bank statement schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [json-structure/veryfi-document-structure.json](json-structure/veryfi-document-structure.json) | Document field structure documentation |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/veryfi-context.jsonld](json-ld/veryfi-context.jsonld) | JSON-LD context mapping Veryfi vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [examples/veryfi-process-document-example.json](examples/veryfi-process-document-example.json) | Process a receipt/invoice |
| [examples/veryfi-process-bank-statement-example.json](examples/veryfi-process-bank-statement-example.json) | Process a bank statement |
| [examples/veryfi-process-w2-example.json](examples/veryfi-process-w2-example.json) | Process a W-2 tax form |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/veryfi-vocabulary.yml](vocabulary/veryfi-vocabulary.yml) | OCR and financial document domain vocabulary |

## Common Properties

- [Website](https://www.veryfi.com/)
- [API Documentation](https://docs.veryfi.com/)
- [Interactive Console](https://hub.veryfi.com/)
- [Sign Up](https://app.veryfi.com/signup/api/)
- [Help Center](https://faq.veryfi.com/)
- [GitHub Organization](https://github.com/veryfi)
- [Privacy Policy](https://www.veryfi.com/privacy-policy/)
- [Terms of Service](https://www.veryfi.com/terms-of-service/)

## Maintainers

**Kin Lane** — kin@apievangelist.com
