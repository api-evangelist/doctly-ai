# Doctly (doctly-ai)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
