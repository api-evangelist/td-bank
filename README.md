# TD Bank (td-bank)

TD Bank, N.A. (America's Most Convenient Bank) is the U.S. retail and commercial subsidiary of Toronto-Dominion Bank, serving more than 10 million customers from Maine to Florida through roughly 1,100 branches. TD's Open Banking developer portal (hosted at developer.td.com / openbanking.amcb.developer.td.com) exposes an FDX-aligned API suite — Account Basic, Account Detailed, Customer, Transactions, Statements, Tax Forms, Bill Payment, Rewards — plus Consent, Token, Service Token, Apps Management, and Notifications utility APIs that are operated for vetted fintechs and data aggregators via the Akoya Data Access Network. TD also exposes TD Online Mart Recurring Payment APIs through its US/Canadian Merchant Solutions (Worldline-backed).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/td-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/td-bank/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Account Aggregation
- AML
- Akoya
- Banking
- Bank Secrecy Act
- Bill Payment
- Consent
- Consumer Banking
- FDX
- Financial Services
- Merchant Solutions
- Notifications
- Open Banking
- Payments
- Rewards
- Tax Forms
- Token Management
- Transactions

## Timestamps

- **Created:** 2025-05-03
- **Modified:** 2026-05-23

## APIs

### TD Bank Account Basic API

FDX v6.2 lightweight accounts endpoint that returns minimal descriptive information and the accountId for each of a consumer's consented TD accounts. The accountId is then used by the Account Detailed API to retrieve full structure, terms, balances, and identifiers.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Account Aggregation
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-account-basic-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-account-basic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-account-basic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Account Detailed API

FDX v6.2 OpenAPI 3.1.0 specification that returns comprehensive information for a specific account — structure, terms, current/available balances, identifiers, and account-type-specific fields (deposit, loan, investment) — for any account previously surfaced through the Account Basic API.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/account-detailed-v1-0-0-api-spec-ofs](https://docs.pat.openbanking.amcb.developer.td.com/guides/account-detailed-v1-0-0-api-spec-ofs)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Account Aggregation
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/account-detailed-v1-0-0-api-spec-ofs)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-account-detailed-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-account-detailed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-account-detailed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Customer API

FDX v6.2 Customer endpoint that returns the customer contact record (name, address, email, telephone, account holders) tied to a permissioned accountId. Used by aggregators to confirm account ownership and to power KYC / identity verification flows.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Customer
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-customer-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-customer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-customer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Transactions API

FDX v6.2 Transactions endpoint that returns posted and pending transaction data for a consented account — amounts, dates, descriptions, merchant fields, status — with support for pagination, date-range filtering, and transaction image retrieval.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Transactions
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-transactions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-transactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-transactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Statements API

FDX v6.2 Statements endpoint that lists available statement periods for a consented account and lets consumers retrieve the statement PDF. Supports the standard FDX statement metadata model.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/statements-v1-0-0-api-spec-ofs](https://docs.pat.openbanking.amcb.developer.td.com/guides/statements-v1-0-0-api-spec-ofs)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Statements
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/statements-v1-0-0-api-spec-ofs)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-statements-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-statements-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-statements-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Tax Forms API

FDX v6.2 Tax Forms endpoint that lists tax forms (e.g. 1099-INT, 1099-DIV) issued for a consented TD account in a given year and lets consumers retrieve the form PDF.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Tax Forms
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-tax-forms-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-tax-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-tax-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Bill Payment API

FDX v6.2 Bill Payment endpoint that retrieves information about a consented customer's bill payment activity and payees, enabling fintechs to review payment history, payee metadata, and recurring billing rules.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Bill Payment
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-bill-payment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-bill-payment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-bill-payment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Rewards API

TD Open Banking Rewards API v1.0.0 returns reward program and membership information for the currently authenticated user — designed to track rewards participation across travel, retail, and merchant programs tied to TD credit card and loyalty accounts.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/rewards-api-spec-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/rewards-api-spec-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`

#### Tags

- Rewards
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/rewards-api-spec-hdi)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/fdx/v6)
- [OpenAPI](openapi/td-bank-rewards-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-rewards-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-rewards-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Consent API

TD Open Banking Consent API implements the FDX consent model — fetching consent details for a consumer, revoking consents, and retrieving consent revocation records. Explicit consumer consent is the gating mechanism for every Data API call.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/consent-flow](https://docs.pat.openbanking.amcb.developer.td.com/guides/consent-flow)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/consent/v1`

#### Tags

- Consent
- FDX
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/consent-flow)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/consent/v1)
- [OpenAPI](openapi/td-bank-consent-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-consent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-consent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Token API

OAuth 2.0 Token API with Pushed Authorization Request (PAR) — issues access tokens for the FDX Data APIs and the Consent API. Flow begins with POST PAR, returns a request URI used to build the consent URL, and exchanges the resulting authorization code for an access token via POST /token.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/advanced-token-scenarios](https://docs.pat.openbanking.amcb.developer.td.com/guides/advanced-token-scenarios)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/oauth/v1`

#### Tags

- Token Management
- OAuth
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/advanced-token-scenarios)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox/oauth/v1)
- [OpenAPI](openapi/td-bank-token-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Service Token API

OAuth 2.0 Service Token API (Akoya v1.0.1) — generates client-credentials tokens for the utility APIs (Apps Management, Notifications). Separate from the user-context Token API so partner backend systems can authenticate without a user session.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/reference/service-token-akoya-v1-0-1](https://docs.pat.openbanking.amcb.developer.td.com/reference/service-token-akoya-v1-0-1)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/oauth/v1`

#### Tags

- Token Management
- OAuth
- Akoya

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/reference/service-token-akoya-v1-0-1)
- [OpenAPI](openapi/td-bank-service-token-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-service-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-service-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Apps Management API

Apps Management API v2.0 — lets data recipients create and update fintech apps on the TD/Akoya network, list purchased FDX data clusters, manage subscriptions, and look up which entities support specific FDX clusters.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/reference/management-api-v20-guide](https://docs.pat.openbanking.amcb.developer.td.com/reference/management-api-v20-guide)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/apps/v2`

#### Tags

- Apps Management
- Akoya
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/reference/management-api-v20-guide)
- [OpenAPI](openapi/td-bank-apps-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-apps-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-apps-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Bank Notifications API

Notifications API — retrieves alerts about significant changes on the TD/Akoya network, including planned/unplanned maintenance outages and consent events (revoked or modified consumer consents). Lets data recipients react to consent revocations and platform incidents in near real time.

- **Human URL:** [https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/notifications/v1`

#### Tags

- Notifications
- Akoya
- Open Banking

#### Properties

- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- [OpenAPI](openapi/td-bank-notifications-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/td-bank-notifications-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-notifications-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TD Online Mart Recurring Payment API

TD Merchant Solutions Recurring Payment API (Worldline-backed gateway) — lets merchants schedule and process recurring membership / subscription card payments. Supports API Passcode, Username/Password, and Hash Key authentication models for shopping-cart integrations.

- **Human URL:** [https://www.td.com/ca/en/business-banking/merchant-solutions/online-mart-ecommerce](https://www.td.com/ca/en/business-banking/merchant-solutions/online-mart-ecommerce)
- **Base URL:** `https://gateway.tdmerchantservices.com`

#### Tags

- Merchant Solutions
- Payments
- Recurring Payments

#### Properties

- [Documentation](https://www.td.com/ca/en/business-banking/merchant-solutions/ecommerce-platforms)
- [Postman Collection](collections/td-bank-account-basic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-account-basic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-account-detailed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-account-detailed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-apps-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-apps-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-bill-payment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-bill-payment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-consent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-consent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-customer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-customer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-notifications-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-notifications-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-rewards-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-rewards-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-service-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-service-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-statements-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-statements-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-tax-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-tax-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-token-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-token-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/td-bank-transactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/td-bank-transactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.td.com)
- [Documentation](https://docs.pat.openbanking.amcb.developer.td.com/)
- [Authentication](https://docs.pat.openbanking.amcb.developer.td.com/guides/portal-manual-authentication)
- [Consent Flow](https://docs.pat.openbanking.amcb.developer.td.com/guides/consent-flow)
- [Open A P I Specs](https://docs.pat.openbanking.amcb.developer.td.com/guides/openapi-specs)
- [Error Reference](https://docs.pat.openbanking.amcb.developer.td.com/guides/api-error-reference)
- [Sandbox U R L](https://api.openbanking.amcb.developer.td.com/sandbox)
- [Production U R L](https://api.openbanking.amcb.developer.td.com)
- [Standards](https://financialdataexchange.org/)
- [Aggregator Network](https://akoya.com/)
- [Partner Aggregator](https://plaid.com/institutions/td-bank/)
- [Company U R L](https://www.td.com/us/en/)
- [Parent Company U R L](https://www.td.com/)
- [News Room](https://td.mediaroom.com/)
- [Stories](https://stories.td.com/us/en)
- [Investor Relations](https://www.td.com/ca/en/investor-relations)
- [Git Hub](https://github.com/TD-Bank)
- [Terms of Service](https://www.td.com/us/en/personal-banking/privacy)
- [Security Policy](https://www.td.com/us/en/personal-banking/security)
- [Vocabulary](vocabulary/td-bank-vocabulary.yml)
- [JSON-LD](json-ld/td-bank-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/td-bank-plans-pricing.yml)
- [Rate Limits](rate-limits/td-bank-rate-limits.yml)
- [Fin Ops](finops/td-bank-finops.yml)
- [Spectral Ruleset](rules/td-bank-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
