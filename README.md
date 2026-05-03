# SAP Concur Expense

SAP Concur Expense is a cloud-based travel and expense management solution that automates and streamlines expense reporting, approval workflows, and reimbursement processes for businesses. It integrates with corporate card programs, receipt capture, and ERP systems to provide end-to-end expense lifecycle management with audit controls and policy enforcement.

**URL:** https://developer.concur.com/

## Tags

Expense Management, Financial Management, Receipts, Reimbursement, Reporting, SAP, Travel

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Expense Report v3 API

Allows developers to read and write expense report headers, manage the expense report lifecycle including submission and approval workflows, and retrieve expense report data for integration with ERP and financial systems.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/expense-report/v3.reports.html
- **OpenAPI:** [openapi/sap-concur-expense-report-openapi.yml](openapi/sap-concur-expense-report-openapi.yml)

**Properties:** Documentation, Authentication

### Expense Entry v3 API

Manage individual expense entries within expense reports including itemizations, attendees, custom fields, and form field values.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/expense-report/expense-entry.html

### Quick Expense v3 API

Create and manage basic expenses quickly outside of a formal expense report. Quick expenses can be added to an expense report later.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/quick-expense/v3.quick-expense.html

### Receipt Image v3 API

Upload, retrieve, and manage receipt images associated with expense entries. Supports PNG, JPG, PDF, and TIFF formats.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/image/v1.image.html

### Digital Tax Invoice API

Retrieve digital tax invoice data (CFDI, NF-e) associated with expense entries for compliance and auditing.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/digital-tax-invoices/digital-tax-invoice.html

### Expense Group Configuration API

Retrieve expense group configurations including expense types, policies, and workflow settings.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/expense-report/expense-group-configurations.html

### Expense Allocations API

Manage allocation of expenses across multiple cost centers, projects, or departments.

- **Base URL:** https://us.api.concursolutions.com/api/v3.0
- **Version:** 3.0
- **Human URL:** https://developer.concur.com/api-reference/expense/expense-report/expense-allocations.html

### Payment Batch v1 API

Retrieve payment batches for processed expense reports ready for reimbursement.

- **Base URL:** https://us.api.concursolutions.com/api/v1.1
- **Version:** 1.1
- **Human URL:** https://developer.concur.com/api-reference/expense/payment-batch/v1.payment-batches.html

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| SAP Concur Expense API (Reports, Entries, Quick Expenses, Receipts, Allocations, Payment Batches) | [openapi/sap-concur-expense-report-openapi.yml](openapi/sap-concur-expense-report-openapi.yml) |

### Capabilities

Workflow-oriented Naftiko capability compositions:

| Workflow | Description |
|----------|-------------|
| [Expense Reporting and Approval](capabilities/expense-reporting-and-approval.yaml) | Full expense report lifecycle from creation through approval and reimbursement payment batch tracking |
| [Expense Capture and Receipts](capabilities/expense-capture-and-receipts.yaml) | On-the-go quick expense capture and receipt image management for mobile users |

**Shared per-API definitions (`capabilities/shared/`):**

- [expense-report.yaml](capabilities/shared/expense-report.yaml) — Expense Report, Expense Entry, Payment Batch, and Group Configuration APIs
- [receipt-capture.yaml](capabilities/shared/receipt-capture.yaml) — Quick Expense and Receipt Image APIs

### Rules

- [rules/sap-concur-expense-rules.yml](rules/sap-concur-expense-rules.yml) — Spectral ruleset enforcing SAP Concur Expense API conventions

### JSON Schema

- [json-schema/sap-concur-expense-report-schema.json](json-schema/sap-concur-expense-report-schema.json) — SAP Concur Expense Report
- [json-schema/sap-concur-expense-entry-schema.json](json-schema/sap-concur-expense-entry-schema.json) — SAP Concur Expense Entry
- [json-schema/sap-concur-expense-receipt-schema.json](json-schema/sap-concur-expense-receipt-schema.json) — SAP Concur Receipt Image

### JSON Structure

- [json-structure/sap-concur-expense-report-structure.json](json-structure/sap-concur-expense-report-structure.json)
- [json-structure/sap-concur-expense-entry-structure.json](json-structure/sap-concur-expense-entry-structure.json)

### JSON-LD

- [json-ld/sap-concur-expense-context.jsonld](json-ld/sap-concur-expense-context.jsonld)

### Examples

- [examples/sap-concur-expense-list-reports-example.json](examples/sap-concur-expense-list-reports-example.json)
- [examples/sap-concur-expense-create-entry-example.json](examples/sap-concur-expense-create-entry-example.json)
- [examples/sap-concur-expense-list-payment-batches-example.json](examples/sap-concur-expense-list-payment-batches-example.json)

### Vocabulary

- [vocabulary/sap-concur-expense-vocabulary.yml](vocabulary/sap-concur-expense-vocabulary.yml)

## Common Resources

- **Developer Portal:** https://developer.concur.com/
- **Getting Started:** https://developer.concur.com/api-reference/expense/
- **Authentication:** https://developer.concur.com/api-reference/authentication/getting-started.html
- **OAuth 2.0:** https://developer.concur.com/api-reference/authentication/apidoc.html
- **API Explorer:** https://developer.concur.com/api-explorer/
- **Support:** https://developer.concur.com/support
- **Terms of Service:** https://developer.concur.com/terms-of-use
- **Privacy Policy:** https://www.sap.com/about/legal/privacy.html
- **Status Page:** https://open.concur.com/
- **Release Notes:** https://developer.concur.com/tools-support/release-notes/
- **Community:** https://community.sap.com/topics/concur
- **GitHub Organization:** https://github.com/concur
- **Website:** https://www.concur.com/

## Maintainers

- **Kin Lane** — kin@apievangelist.com
