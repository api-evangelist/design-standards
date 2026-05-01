# Design Standards Capabilities

Capabilities a design standards program contributes to product, interface, and API delivery.

## Specification Capabilities

- API-first development anchored on OpenAPI, AsyncAPI, and JSON Schema.
- Versioned canonical documents with semantic versioning.
- Machine-readable rules expressed as Spectral rulesets, JSON Schemas, or other linters.

## Naming and Format Capabilities

- Resource and path naming conventions (plural nouns, kebab-case).
- Property casing rules (snake_case or camelCase, used consistently).
- ISO standard formats: 8601 dates, 4217 currency, 3166 country, 639-1 language.
- Numeric precision rules (int32, int64, decimal, float).

## HTTP Capabilities

- Allowed methods and idempotency expectations.
- Canonical status code usage and error envelope (RFC 7807 problem+json).
- Required and optional headers, including correlation, deprecation, and rate-limit families.
- Pagination, filtering, sorting, and embedding conventions.

## Security Capabilities

- Authentication scheme selection (OAuth 2.0, OIDC, signed JWT).
- Permission naming patterns (resource.action.scope).
- Transport security (TLS minimums, HSTS).
- Data classification and PII handling rules.

## Lifecycle Capabilities

- Versioning policy.
- Deprecation policy with sunset windows.
- Change management and RFC processes.
- Backward compatibility expectations.

## Accessibility and UX Capabilities

- WCAG 2.1 AA conformance baseline.
- Color, contrast, and typography tokens.
- Keyboard navigation and screen reader support.
- Localization and internationalization rules.

## Governance Capabilities

- Standards owning body and review cadence.
- Public RFC process for changes.
- Compliance dashboards and exception tracking.
- Onboarding curricula tied to the standards.
