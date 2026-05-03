# Togai

Togai is a metering and billing platform for software and SaaS products, purpose-built for consumption-based and usage-based pricing models. The Togai API provides programmatic access to customers, accounts, event ingestion, usage meters, price plans, invoices, credits, entitlements, and financial reporting.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/togai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Billing, Metering, Usage-Based Pricing, Revenue Management, SaaS, Fintech

## Timestamps

- **Created:** 2025-02-10
- **Modified:** 2026-05-03

## APIs

### Togai API

Full usage-based billing and metering platform. Resources include customers, accounts, event schemas, usage meters, price plans, pricing rules, invoices, credits, entitlements, wallet, licenses, and reports.

**Human URL:** [https://docs.togai.com/api-reference/getting-started](https://docs.togai.com/api-reference/getting-started)

**Base URL:** https://api.togai.com

#### Tags

 - Billing, Metering, Usage-Based Pricing, Revenue Management, Customers, Invoices

#### Properties

- [Documentation](https://docs.togai.com/api-reference/getting-started)
- [OpenAPI](openapi/togai-openapi.yml)
- [JSON Schema](json-schema/togai-customer-schema.json)
- [Naftiko Capabilities](capabilities/usage-based-billing.yaml)
- [Spectral Rules](rules/togai-rules.yml)
- [Vocabulary](vocabulary/togai-vocabulary.yml)

## Artifacts

### OpenAPI Specifications

- [openapi/togai-openapi.yml](openapi/togai-openapi.yml) — Full Togai platform API (customers, accounts, events, price plans, invoices, credits, entitlements, wallet)

### Spectral Rules

- [rules/togai-rules.yml](rules/togai-rules.yml) — Governance ruleset for Togai API conventions

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [usage-based-billing.yaml](capabilities/usage-based-billing.yaml) | Full billing lifecycle: customers, accounts, events, pricing, invoices, credits (10 MCP tools) |

**Shared:** [capabilities/shared/togai-api.yaml](capabilities/shared/togai-api.yaml)

### JSON Schema

- [json-schema/togai-customer-schema.json](json-schema/togai-customer-schema.json) — Customer entity
- [json-schema/togai-event-schema.json](json-schema/togai-event-schema.json) — Usage event entity

### JSON Structure

- [json-structure/togai-customer-structure.json](json-structure/togai-customer-structure.json)

### JSON-LD

- [json-ld/togai-context.jsonld](json-ld/togai-context.jsonld)

### Examples

- [examples/togai-create-customer-example.json](examples/togai-create-customer-example.json)
- [examples/togai-ingest-events-example.json](examples/togai-ingest-events-example.json)

### Vocabulary

- [vocabulary/togai-vocabulary.yml](vocabulary/togai-vocabulary.yml)

## Common Properties

- [Website](https://www.togai.com/)
- [Developer Portal](https://docs.togai.com/)
- [Documentation](https://docs.togai.com/docs)
- [API Reference](https://docs.togai.com/api-reference/getting-started)
- [Sign Up](https://app.togai.com/auth/signup)
- [Pricing](https://www.togai.com/pricing/)
- [Blog](https://www.togai.com/blog/)
- [Changelog](https://docs.togai.com/changelog/change-log)
- [GitHub Organization](https://github.com/TogaiHQ)
- [Sandbox](https://sandbox-api.togai.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
