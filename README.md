# Doctly (doctly-ai)

Doctly is an AI document-to-Markdown and structured-data extraction API. It converts PDFs, DOCX, and image files into clean Markdown or JSON via an asynchronous submit-then-poll REST API, with LITE and ULTRA accuracy levels, optional custom extractors for structured extraction, and webhook callbacks on completion.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/doctly-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/doctly-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Document Parsing
- PDF
- Markdown
- Data Extraction
- OCR

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Doctly Documents Parse API

Upload a PDF, DOCX, or image file (or remote URL) for asynchronous AI conversion to Markdown. Supports LITE and ULTRA accuracy levels, page separators, image skipping, and webhook callbacks; output is retrieved via a signed output_file_url once processing completes.

- **Human URL:** [https://docs.doctly.ai/api-reference/documents/process](https://docs.doctly.ai/api-reference/documents/process)
- **Base URL:** `https://api.doctly.ai/api/v1`

#### Tags

- Documents
- Parse
- Markdown
- PDF

#### Properties

- [Documentation](https://docs.doctly.ai/api-reference/documents/process)
- [API Reference](https://docs.doctly.ai/api-reference/introduction)
- [OpenAPI](openapi/doctly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/doctly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/doctly-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Doctly Extract API

Run a named extractor against a document to produce structured JSON output. List, retrieve, update, and delete extractors, each carrying a cost_type (PER_PAGE or PER_DOCUMENT) and cost_credits.

- **Human URL:** [https://docs.doctly.ai/api-reference/extractors/run](https://docs.doctly.ai/api-reference/extractors/run)
- **Base URL:** `https://api.doctly.ai/api/v1`

#### Tags

- Extract
- Structured Data
- JSON
- Extractors

#### Properties

- [Documentation](https://docs.doctly.ai/api-reference/extractors/run)
- [API Reference](https://docs.doctly.ai/api-reference/introduction)
- [OpenAPI](openapi/doctly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/doctly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/doctly-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Doctly Status and Results API

Poll document status and retrieve results. List documents with filtering, fetch a single document with signed output_file_url and file_url links, and delete documents. Status moves through PENDING, PROCESSING, COMPLETED, FAILED, EXPIRED.

- **Human URL:** [https://docs.doctly.ai/api-reference/documents/get](https://docs.doctly.ai/api-reference/documents/get)
- **Base URL:** `https://api.doctly.ai/api/v1`

#### Tags

- Status
- Polling
- Results
- Webhooks

#### Properties

- [Documentation](https://docs.doctly.ai/api-reference/documents/get)
- [API Reference](https://docs.doctly.ai/api-reference/introduction)
- [OpenAPI](openapi/doctly-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/doctly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/doctly-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/doctly-ai)
- [Website](https://doctly.ai)
- [Documentation](https://docs.doctly.ai)
- [GitHub Organization](https://github.com/doctly)
- [Plans](plans/doctly-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/doctly-ai-rate-limits.yml)
- [Fin Ops](finops/doctly-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
