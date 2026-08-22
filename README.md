# SAP Concur Expense (sap-concur-expense)

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

SAP Concur Expense is a cloud-based travel and expense management solution that automates and streamlines expense reporting, approval workflows, and reimbursement processes for businesses. It integrates with corporate card programs, receipt capture, and ERP systems to provide end-to-end expense lifecycle management with audit controls and policy enforcement.

**APIs.json:** [https://developer.concur.com/](https://developer.concur.com/)

## Tags

- Expense Management
- Financial Management
- Receipts
- Reimbursement
- Reporting
- SAP
- Travel

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Expense Report v3 API

Allows developers to read and write expense report headers, manage the expense report lifecycle including submission and approval workflows, and retrieve expense report data for integration with ERP and financial systems.

- **Human URL:** [https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html](https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Approval
- Expenses
- Financial
- Reports
- Workflow

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [OpenAPI](openapi/sap-concur-expense-report-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Expense Entry v3 API

Manage individual expense entries within expense reports including itemizations, attendees, custom fields, and form field values. Supports creating, reading, updating, and deleting individual line items in expense reports.

- **Human URL:** [https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html](https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Expense Entries
- Itemization
- Line Items

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html)
- [OpenAPI](openapi/sap-concur-expense-report-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Quick Expense v3 API

Create and manage basic expenses quickly outside of a formal expense report. Quick expenses can be added to an expense report later. Useful for capturing expenses on-the-go before being ready to file a complete report.

- **Human URL:** [https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html](https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Expenses
- Mobile
- Quick Expense

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html)
- [OpenAPI](openapi/sap-concur-expense-report-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Receipt Image v3 API

Upload, retrieve, and manage receipt images associated with expense entries. Supports attaching scanned receipts, e-receipts from travel providers, and credit card transaction images to expense line items for compliance and audit.

- **Human URL:** [https://developer.concur.com/api-reference/image/v1.image.html](https://developer.concur.com/api-reference/image/v1.image.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Documents
- Images
- Receipts

#### Properties

- [Documentation](https://developer.concur.com/api-reference/image/v1.image.html)
- [OpenAPI](openapi/sap-concur-expense-report-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Digital Tax Invoice API

Retrieve digital tax invoice data associated with expense entries for compliance and auditing in jurisdictions that require electronic invoicing (e-invoicing). Provides access to CFDI (Mexico), NF-e (Brazil), and other country-specific digital tax documents.

- **Human URL:** [https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html](https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Compliance
- Invoice
- Tax

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Expense Group Configuration API

Retrieve expense group configurations including expense types, expense policies, payment types, and workflow settings. Used to dynamically configure expense capture UIs and enforce policy rules during expense report creation.

- **Human URL:** [https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html](https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Configuration
- Policies
- Settings

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Expense Allocations API

Manage allocation of expenses across multiple cost centers, projects, departments, or GL accounts. Supports percentage-based and amount-based allocation splits for corporate expense policy compliance and financial reporting.

- **Human URL:** [https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html](https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v3.0`

#### Tags

- Accounting
- Allocations
- Cost Centers

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Payment Batch v1 API

Retrieve and manage payment batches for processed expense reports ready for reimbursement. Provides visibility into batch payment status, amounts, and payee information for integration with payroll and ERP payment systems.

- **Human URL:** [https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html](https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html)
- **Base URL:** `https://us.api.concursolutions.com/api/v1.1`

#### Tags

- Batch Processing
- Payments
- Reimbursement

#### Properties

- [Documentation](https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html)
- [Postman Collection](collections/sap-concur-expense-report.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-concur-expense-report.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Developer  Portal](https://developer.concur.com/)
- [Getting Started](https://developer.concur.com/api-reference/expense/)
- [Authentication](https://developer.concur.com/api-reference/authentication/getting-started.html)
- [O Auth 2.0](https://developer.concur.com/api-reference/authentication/apidoc.html)
- [A P I  Explorer](https://developer.concur.com/api-explorer/)
- [Support](https://developer.concur.com/support)
- [Terms of Service](https://developer.concur.com/terms-of-use)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [Status Page](https://open.concur.com/)
- [Release Notes](https://developer.concur.com/tools-support/release-notes/)
- [Community](https://community.sap.com/topics/concur)
- [Blog](https://developer.concur.com/blog/)
- [GitHub Organization](https://github.com/concur)
- [Website](https://www.concur.com/)
- [Sign Up](https://www.concur.com/en-us/try-concur.html)
- [S D Ks](https://github.com/concur/concur-platform-sdk-java)
- [Postman  Collection](https://developer.concur.com/tools-support/postman.html)
- [OpenAPI](openapi/sap-concur-expense-report-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sap-concur-expense-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-concur-expense-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-concur-expense-receipt-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-concur-expense-report-structure.json)
- [JSON Structure](json-structure/sap-concur-expense-entry-structure.json)
- [JSON-LD](json-ld/sap-concur-expense-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/sap-concur-expense-rules.yml)
- [Vocabulary](vocabulary/sap-concur-expense-vocabulary.yml)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
