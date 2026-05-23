# TD Bank (td-bank)

TD Bank, N.A. ("America's Most Convenient Bank") is the U.S. retail and commercial subsidiary of Toronto-Dominion Bank, serving more than 10 million customers from Maine to Florida through roughly 1,100 branches. TD's Open Banking developer portal — `developer.td.com`, with API documentation at `docs.pat.openbanking.amcb.developer.td.com` — exposes an FDX v6.2-aligned API suite for vetted fintechs and data aggregators via the Akoya Data Access Network. TD also exposes a Recurring Payment API through TD Online Mart (Worldline-backed) under TD Merchant Solutions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/td-bank/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Account Aggregation, AML, Akoya, Banking, Bank Secrecy Act, Bill Payment, Consent, Consumer Banking, FDX, Financial Services, Merchant Solutions, Notifications, Open Banking, Payments, Rewards, Tax Forms, Token Management, Transactions

## Timestamps

- **Created:** 2025-05-03
- **Modified:** 2026-05-23

## APIs

### TD Bank Account Basic API
FDX v6.2 lightweight accounts endpoint — list a consumer's consented TD accounts.
- **Docs:** [About Our APIs](https://docs.pat.openbanking.amcb.developer.td.com/guides/about-our-apis-hdi)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`
- **OpenAPI:** [openapi/td-bank-account-basic-api-openapi.yml](openapi/td-bank-account-basic-api-openapi.yml)

### TD Bank Account Detailed API
FDX v6.2 comprehensive account record (structure, terms, balances, identifiers).
- **Docs:** [Account Detailed v1.0.0 Spec](https://docs.pat.openbanking.amcb.developer.td.com/guides/account-detailed-v1-0-0-api-spec-ofs)
- **Base URL:** `https://api.openbanking.amcb.developer.td.com/fdx/v6`
- **OpenAPI:** [openapi/td-bank-account-detailed-api-openapi.yml](openapi/td-bank-account-detailed-api-openapi.yml)

### TD Bank Customer API
FDX v6.2 customer contact + account-holder record tied to a permissioned accountId.
- **OpenAPI:** [openapi/td-bank-customer-api-openapi.yml](openapi/td-bank-customer-api-openapi.yml)

### TD Bank Transactions API
FDX v6.2 posted/pending transactions per account, with date filtering and image retrieval.
- **OpenAPI:** [openapi/td-bank-transactions-api-openapi.yml](openapi/td-bank-transactions-api-openapi.yml)

### TD Bank Statements API
FDX v6.2 statement-period listing + statement PDF retrieval.
- **Docs:** [Statements v1.0.0 Spec](https://docs.pat.openbanking.amcb.developer.td.com/guides/statements-v1-0-0-api-spec-ofs)
- **OpenAPI:** [openapi/td-bank-statements-api-openapi.yml](openapi/td-bank-statements-api-openapi.yml)

### TD Bank Tax Forms API
FDX v6.2 1099/tax-form listing + PDF retrieval per consented account.
- **OpenAPI:** [openapi/td-bank-tax-forms-api-openapi.yml](openapi/td-bank-tax-forms-api-openapi.yml)

### TD Bank Bill Payment API
FDX v6.2 payee directory + bill payment activity per consented account.
- **OpenAPI:** [openapi/td-bank-bill-payment-api-openapi.yml](openapi/td-bank-bill-payment-api-openapi.yml)

### TD Bank Rewards API
Reward program / membership info for the permissioned user (TD credit-card + loyalty programs).
- **Docs:** [Rewards 1.0.0 Spec](https://docs.pat.openbanking.amcb.developer.td.com/guides/rewards-api-spec-hdi)
- **OpenAPI:** [openapi/td-bank-rewards-api-openapi.yml](openapi/td-bank-rewards-api-openapi.yml)

### TD Bank Consent API
FDX consent lifecycle — get, revoke, and list consent revocations.
- **Docs:** [Consent Flow Guide](https://docs.pat.openbanking.amcb.developer.td.com/guides/consent-flow)
- **OpenAPI:** [openapi/td-bank-consent-api-openapi.yml](openapi/td-bank-consent-api-openapi.yml)

### TD Bank Token API
OAuth 2.0 with Pushed Authorization Request (PAR) — issues access tokens for the Data APIs and the Consent API.
- **Docs:** [Advanced Token Scenarios](https://docs.pat.openbanking.amcb.developer.td.com/guides/advanced-token-scenarios)
- **OpenAPI:** [openapi/td-bank-token-api-openapi.yml](openapi/td-bank-token-api-openapi.yml)

### TD Bank Service Token API
OAuth 2.0 client_credentials (Akoya v1.0.1) for utility APIs.
- **Docs:** [Service Token Akoya v1.0.1](https://docs.pat.openbanking.amcb.developer.td.com/reference/service-token-akoya-v1-0-1)
- **OpenAPI:** [openapi/td-bank-service-token-api-openapi.yml](openapi/td-bank-service-token-api-openapi.yml)

### TD Bank Apps Management API
Apps Management v2 — fintech-app CRUD, subscriptions, FDX cluster purchases, entity lookup.
- **Docs:** [Apps Management v2 Guide](https://docs.pat.openbanking.amcb.developer.td.com/reference/management-api-v20-guide)
- **OpenAPI:** [openapi/td-bank-apps-management-api-openapi.yml](openapi/td-bank-apps-management-api-openapi.yml)

### TD Bank Notifications API
Maintenance + consent events on the TD/Akoya network (pull-based, not push).
- **OpenAPI:** [openapi/td-bank-notifications-api-openapi.yml](openapi/td-bank-notifications-api-openapi.yml)

### TD Online Mart Recurring Payment API
TD Merchant Solutions recurring-payment scheduling via the Worldline-backed TD Online Mart gateway.
- **Docs:** [TD Online Mart Ecommerce](https://www.td.com/ca/en/business-banking/merchant-solutions/online-mart-ecommerce)

## Common Properties

- **Portal:** [developer.td.com](https://developer.td.com)
- **Docs:** [docs.pat.openbanking.amcb.developer.td.com](https://docs.pat.openbanking.amcb.developer.td.com/)
- **Sandbox:** `https://api.openbanking.amcb.developer.td.com/sandbox`
- **Production:** `https://api.openbanking.amcb.developer.td.com`
- **Standards:** [FDX](https://financialdataexchange.org/), OAuth 2.0 with PAR
- **Aggregator Network:** [Akoya](https://akoya.com/), [Plaid](https://plaid.com/institutions/td-bank/)
- **GitHub:** [TD-Bank](https://github.com/TD-Bank) (no public repos)
- **News:** [td.mediaroom.com](https://td.mediaroom.com/), [stories.td.com](https://stories.td.com/us/en)
- **Investor Relations:** [TD IR](https://www.td.com/ca/en/investor-relations)

## Artifacts

| Folder | Count |
|---|---|
| `openapi/` | 13 |
| `capabilities/` | 16 (14 per-API + 2 workflow compositions) |
| `json-schema/` | 4 |
| `json-structure/` | 1 |
| `json-ld/` | 1 |
| `examples/` | 6 |
| `rules/` | 1 |
| `vocabulary/` | 1 |
| `plans/` | 1 |
| `rate-limits/` | 1 |
| `finops/` | 1 |

## Notable Findings

- **Scale:** "As one of the 10 largest banks in the U.S., TD serves over 10 million retail, small business and commercial customers from Maine to Florida."
- **Open Banking:** TD is FDX v6.2-aligned, delivered through the Akoya network it joined September 2021. Plaid data-access agreement signed December 2023.
- **First Horizon failure (May 4, 2023):** TD terminated the $13B First Horizon merger after failing to secure a regulatory-approval path; paid $225M cash + $25M reimbursement.
- **AML / BSA enforcement (Oct 10, 2024):** TD Bank, N.A. became the first U.S. bank in history to plead guilty to felony conspiracy to commit money laundering. Total penalty $3B+ (DOJ $1.8B + FinCEN $1.3B), 3-year independent compliance monitor, asset-growth restriction. ~$18.3T in unmonitored transactions over six years; 92% of transaction volume unmonitored; a five-employee insider scheme issued dozens of ATM cards to launder ~$39M in drug-cartel money. Full event captured in `review.yml`.

## Notable Absences

- TD-Bank GitHub org is private — zero public repos / SDKs
- No public OpenAPI download bundle — specs in `openapi/` are reconstructed from `docs.pat.openbanking.amcb.developer.td.com`
- No public per-call API rate limits — partner-negotiated via Akoya
- No public sandbox self-signup — partner / aggregator vetting required
- No public AsyncAPI / webhook spec — event flow is Notifications-API pull, not push
