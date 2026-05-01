# Harness Cloud Cost Management

Harness Cloud Cost Management (CCM) provides intelligent cloud cost optimization with AI-driven recommendations, customizable cost perspectives, budgets, anomaly detection, and chargeback / showback through cost categories. CCM ingests cost data from AWS, Azure, GCP, and Kubernetes clusters and exposes a REST API on the Harness platform for FinOps automation.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/harness-cloud-cost/refs/heads/main/apis.yml)

## Tags

- Anomaly Detection
- Budgets
- Cloud Cost Management
- FinOps
- Kubernetes
- Recommendations

## APIs

### Harness Cloud Cost Management API

The Harness CCM API provides programmatic access to cloud cost data, perspectives, budgets, anomaly detection, AI-driven recommendations, cost categories (chargeback / showback), and cloud connector configuration across AWS, Azure, GCP, and Kubernetes.

- **Human URL:** https://www.harness.io/products/cloud-cost
- **Base URL:** https://app.harness.io
- **Authentication:** API key via `x-api-key` header (Harness PAT or Service Account API key)
- **Account Scope:** All requests require an `accountIdentifier` query parameter

#### Key Capabilities

- **Perspectives** — Group and analyze cloud cost data across AWS, Azure, GCP, and Kubernetes through customizable views.
- **Budgets** — Define spending budgets with alert thresholds based on actual or forecasted cost.
- **Recommendations** — AI-driven recommendations covering workload right-sizing, node pool optimization, ECS service tuning, and EC2 instance recommendations.
- **Anomaly Detection** — Automatic detection of unusual cost patterns with feedback loops for accuracy.
- **Cost Categories** — Allocate cloud costs to business units for chargeback and showback reporting.
- **Connectors** — Manage cloud provider and Kubernetes connectors that ingest cost data.

#### Resources

- [Documentation](https://developer.harness.io/docs/cloud-cost-management)
- [Getting Started](https://developer.harness.io/docs/cloud-cost-management/get-started/overview)
- [API Reference](https://apidocs.harness.io/)
- [OpenAPI Spec](https://raw.githubusercontent.com/api-evangelist/harness-cloud-cost/refs/heads/main/openapi/harness-cloud-cost-openapi.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/harness-cloud-cost/refs/heads/main/rules/harness-cloud-cost-rules.yml)

## Properties

- [Website](https://www.harness.io/products/cloud-cost)
- [Documentation](https://developer.harness.io/docs/cloud-cost-management)
- [API Reference](https://apidocs.harness.io/)
- [Pricing](https://www.harness.io/pricing)
- [Status](https://status.harness.io)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
