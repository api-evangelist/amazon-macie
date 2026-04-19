# Amazon Macie (amazon-macie)
Amazon Macie is a data security service that discovers sensitive data by using machine learning and pattern matching, provides visibility into data security risks, and enables automated protection against those risks. Macie automates the discovery of sensitive data, such as personally identifiable information (PII) and financial data, to provide you with a better understanding of the data that your organization stores in Amazon S3.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-macie/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Data Security, Sensitive Data, Privacy, Compliance, Machine Learning, S3

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Macie API
The Amazon Macie API provides programmatic access to create and manage the resources, data, and activities for discovering, classifying, and protecting sensitive data stored in Amazon S3 buckets. Covers 54 paths and 79 operations for findings management, classification jobs, bucket security, custom identifiers, multi-account administration, and allow lists.

**Human URL:** [https://aws.amazon.com/macie/](https://aws.amazon.com/macie/)

#### Tags:

 - Data Security, Sensitive Data, Privacy, Compliance, S3

#### Properties

- [Documentation](https://docs.aws.amazon.com/macie/latest/userguide/what-is-macie.html)
- [OpenAPI](openapi/amazon-macie-openapi-original.yaml)
- [GettingStarted](https://aws.amazon.com/macie/getting-started/)
- [Pricing](https://aws.amazon.com/macie/pricing/)
- [FAQ](https://aws.amazon.com/macie/faq/)

## Common Properties

- [Portal](https://aws.amazon.com/macie/)
- [Documentation](https://docs.aws.amazon.com/macie/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/macie/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-macie-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-macie-vocabulary.yaml)
- [NaftikoCapability](capabilities/data-security-operations.yaml)

## Features

| Name | Description |
|------|-------------|
| Automated Sensitive Data Discovery | Automatically discovers and classifies sensitive data in S3 using ML and pattern matching. |
| PII and Financial Data Detection | Detects personally identifiable information (PII), financial data, and credentials in S3 objects. |
| Custom Data Identifiers | Create custom regex patterns to detect organization-specific sensitive data types. |
| Data Security Findings | Generates detailed findings with severity ratings for all detected sensitive data exposures. |
| S3 Bucket Security Posture | Provides visibility into bucket configurations, encryption status, and public access settings. |
| Multi-Account Support | Manage Macie across multiple AWS accounts from a central administrator account. |
| Allow Lists | Define allow lists to suppress false positives for known acceptable sensitive data patterns. |

## Use Cases

| Name | Description |
|------|-------------|
| GDPR and Privacy Compliance | Discover and inventory personal data across S3 to support GDPR data mapping and compliance reporting. |
| PCI-DSS Compliance | Detect credit card numbers and financial data stored in S3 to maintain PCI-DSS compliance. |
| Data Loss Prevention | Identify sensitive data stored in public or insufficiently protected S3 buckets. |
| Security Incident Response | Quickly determine if sensitive data was exposed in an S3 bucket involved in a security incident. |
| Data Governance | Build a data inventory and understand where sensitive data lives across the organization. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Scans S3 buckets to discover and classify sensitive data objects. |
| AWS Security Hub | Sends findings to Security Hub for centralized security posture management. |
| Amazon EventBridge | Publishes findings events to EventBridge for automated remediation workflows. |
| AWS Organizations | Integrates with Organizations for multi-account sensitive data discovery. |
| Amazon CloudWatch | Publishes metrics and logs to CloudWatch for monitoring and alerting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Macie OpenAPI](openapi/amazon-macie-openapi-original.yaml)

### JSON Schema

422 schema files available in the [json-schema/](json-schema/) directory.

### JSON Structure

422 structure files available in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Amazon Macie Context](json-ld/amazon-macie-context.jsonld)

### Examples

422 example files available in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Macie](capabilities/shared/macie.yaml) — 7 operations for findings, discovery jobs, and bucket security

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Security Operations](capabilities/data-security-operations.yaml) | Amazon Macie | 7 | Security Engineer, Compliance Officer |

## Vocabulary

- [Amazon Macie Vocabulary](vocabulary/amazon-macie-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 9 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Macie Spectral Rules](rules/amazon-macie-spectral-rules.yml) — 18 rules across 7 categories enforcing Amazon Macie API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
