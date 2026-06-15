# SAP Concur Expense (sap-concur-expense)

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
