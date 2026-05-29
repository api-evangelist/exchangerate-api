# ExchangeRate-API (exchangerate-api)

ExchangeRate-API is a currency exchange rates API providing authoritative daily and intraday foreign exchange rates for 161 currencies. The v6 surface includes Latest, Pair, Enriched, Historical, Supported Codes, and Quota endpoints, plus a no-API-key Open Access endpoint at open.er-api.com that requires attribution.

**APIs.yml:** [apis.yml](apis.yml)

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/exchangerate-api/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Type

- **x-type:** company
- **x-tier:** 3 (bulk-registered from public-apis)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) -- category: Currency Exchange

## Tags

- Currency Exchange, Foreign Exchange, Financial Data, Forex, Currency Conversion, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### ExchangeRate-API Latest Rates API

Returns the latest exchange rates from a base currency to all 161 supported currencies. Update cadence varies by plan tier (daily on Free, hourly on Pro, every 5 minutes on Business / Volume).

**Human URL:** [https://www.exchangerate-api.com/docs/standard-requests](https://www.exchangerate-api.com/docs/standard-requests)

#### Tags

- Currency Exchange, Latest Rates, Foreign Exchange

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/standard-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-latest-rates-schema.json)
- [JSON Structure](json-structure/exchangerate-api-latest-rates-structure.json)
- [Example](examples/exchangerate-api-get-latest-rates-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-latest-rates.yaml)

### ExchangeRate-API Pair Conversion API

Returns the exchange rate between a base and a target currency, optionally with a converted amount.

**Human URL:** [https://www.exchangerate-api.com/docs/pair-conversion-requests](https://www.exchangerate-api.com/docs/pair-conversion-requests)

#### Tags

- Currency Exchange, Pair Conversion, Foreign Exchange

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/pair-conversion-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-pair-schema.json)
- [JSON Structure](json-structure/exchangerate-api-pair-structure.json)
- [Example](examples/exchangerate-api-get-pair-conversion-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-pair-conversion.yaml)

### ExchangeRate-API Enriched Data API

Returns the exchange rate between a base and target currency along with enriched target currency metadata (locale, two-letter country code, currency name, display symbol, flag URL). Business and Volume plans only.

**Human URL:** [https://www.exchangerate-api.com/docs/enriched-data-requests](https://www.exchangerate-api.com/docs/enriched-data-requests)

#### Tags

- Currency Exchange, Enriched Data, Locale

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/enriched-data-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-enriched-schema.json)
- [JSON Structure](json-structure/exchangerate-api-enriched-structure.json)
- [Example](examples/exchangerate-api-get-enriched-pair-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-enriched-data.yaml)

### ExchangeRate-API Historical Rates API

Returns historical exchange rates for a given base currency on a specific date. Full currency coverage from 2021-01-01 onward; 35 currencies available from 1990-01-01 to 2020-12-31. Pro, Business, and Volume plans only.

**Human URL:** [https://www.exchangerate-api.com/docs/historical-data-requests](https://www.exchangerate-api.com/docs/historical-data-requests)

#### Tags

- Currency Exchange, Historical Rates, Time Series

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/historical-data-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-historical-schema.json)
- [JSON Structure](json-structure/exchangerate-api-historical-structure.json)
- [Example](examples/exchangerate-api-get-historical-rates-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-historical-rates.yaml)

### ExchangeRate-API Supported Codes API

Returns an array of all supported ISO 4217 currency codes and their full names.

**Human URL:** [https://www.exchangerate-api.com/docs/supported-codes-endpoint](https://www.exchangerate-api.com/docs/supported-codes-endpoint)

#### Tags

- Currency Exchange, Supported Codes, ISO 4217

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/supported-codes-endpoint)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-supported-codes-schema.json)
- [Example](examples/exchangerate-api-get-supported-codes-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-supported-codes.yaml)

### ExchangeRate-API Quota API

Returns the plan quota, number of requests remaining in the current billing window, and refresh metadata for the API key.

**Human URL:** [https://www.exchangerate-api.com/docs/overview](https://www.exchangerate-api.com/docs/overview)

#### Tags

- Currency Exchange, Quota, Account

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/overview)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-quota-schema.json)
- [Example](examples/exchangerate-api-get-quota-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-quota.yaml)

### ExchangeRate-API Open Access API

No-API-key public endpoint at open.er-api.com providing latest exchange rates. Updates once daily; attribution to exchangerate-api.com required. Anti-abuse throttled.

**Human URL:** [https://www.exchangerate-api.com/docs/free](https://www.exchangerate-api.com/docs/free)

#### Tags

- Currency Exchange, Open Access, Free

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/free)
- [OpenAPI](openapi/exchangerate-api-openapi.yml)
- [JSON Schema](json-schema/exchangerate-api-open-access-schema.json)
- [Example](examples/exchangerate-api-get-open-access-latest-example.json)
- [Naftiko Capability](capabilities/exchangerate-api-open-access.yaml)

## Common Properties

- [Website](https://www.exchangerate-api.com)
- [Documentation](https://www.exchangerate-api.com/docs/overview)
- [API Reference](https://www.exchangerate-api.com/docs/overview)
- [Authentication](https://www.exchangerate-api.com/docs/overview)
- [Pricing](https://www.exchangerate-api.com/#pricing)
- [Sign Up](https://app.exchangerate-api.com/sign-up)
- [Login](https://app.exchangerate-api.com/sign-in)
- [Terms of Service](https://www.exchangerate-api.com/terms)
- [Privacy Policy](https://www.exchangerate-api.com/privacy-policy)
- [Support](https://www.exchangerate-api.com/contact)
- [Python Documentation](https://www.exchangerate-api.com/docs/python-currency-api)
- [Node.js Community SDK](https://github.com/EloquentStudio/exchangerate-api-node)
- [Community MCP Server](https://lobehub.com/mcp/mazezen-mcp-exchange-rate)

## Features

| Name | Description |
|------|-------------|
| Latest Rates | Get latest exchange rates from a base currency to all 161 supported currencies. |
| Pair Conversion | Direct currency-to-currency rate lookup with optional amount conversion. |
| Enriched Data | Pair conversion plus target currency locale, name, symbol, and flag. |
| Historical Rates | Exchange rates for any date back to 1990 (with full coverage from 2021). |
| Supported Codes | Full ISO 4217 currency code listing with names. |
| Open Access Endpoint | No-API-key endpoint at open.er-api.com with once-daily updates and attribution. |
| 99.99% Uptime SLA | Pingdom-measured uptime exceeded 99.99% during 2024. |
| 161 Supported Currencies | Comprehensive coverage of world fiat currencies. |

## Use Cases

| Name | Description |
|------|-------------|
| E-commerce Multi-currency Display | Show product prices in the visitor's local currency on storefronts and checkout pages. |
| Cross-border Invoicing | Convert invoice totals to the customer's billing currency at the time of invoice issuance. |
| Financial Reporting | Translate revenues, costs, and balances across currencies for consolidated reporting. |
| Travel & Booking Platforms | Show flights, hotels, and packages in the user's home currency. |
| Personal Finance Apps | Convert account balances and transactions across currencies for travel and expense tracking. |
| AI / LLM Agent Currency Tools | Expose currency conversion to AI agents via MCP servers and tool-use frameworks. |
| Historical Backtesting | Use 30+ years of historical rates to backtest trading strategies and FX exposure scenarios. |

## Integrations

| Name | Description |
|------|-------------|
| Python | Use ExchangeRate-API from Python applications via the documented HTTP API. |
| Node.js | Community Node.js SDK published by EloquentStudio for first-class JavaScript integration. |
| PHP / Java / Ruby / C# / Perl / Objective-C | Documented sample code for major server-side languages on the ExchangeRate-API docs site. |
| Spreadsheets | Pull rates into Google Sheets and Excel via HTTP request functions. |
| MCP Servers | Community-built Model Context Protocol servers expose ExchangeRate-API as a tool for LLM agents such as Claude. |

## Plans

| Tier | Monthly Requests | Update Frequency | Price |
|------|------------------|------------------|-------|
| Free | 1,500 | Daily | $0 |
| Pro | 30,000 | Hourly | $10/mo or $100/yr |
| Business | 125,000 | 5 minutes | $30/mo or $300/yr |
| Volume | Custom | Fastest | ~$700/yr |
| Open Access | (anti-abuse throttled) | Daily | Free with attribution |

See [plans/exchangerate-api-plans-pricing.yml](plans/exchangerate-api-plans-pricing.yml) for the full API Commons Plans 0.1 description.

## Rate Limits

See [rate-limits/exchangerate-api-rate-limits.yml](rate-limits/exchangerate-api-rate-limits.yml).

## FinOps

See [finops/exchangerate-api-finops.yml](finops/exchangerate-api-finops.yml).

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ExchangeRate-API](openapi/exchangerate-api-openapi.yml) -- 9 operations across 7 business surfaces

### JSON Schema

- [Latest Rates](json-schema/exchangerate-api-latest-rates-schema.json)
- [Pair](json-schema/exchangerate-api-pair-schema.json)
- [Enriched](json-schema/exchangerate-api-enriched-schema.json)
- [Historical](json-schema/exchangerate-api-historical-schema.json)
- [Supported Codes](json-schema/exchangerate-api-supported-codes-schema.json)
- [Quota](json-schema/exchangerate-api-quota-schema.json)
- [Open Access](json-schema/exchangerate-api-open-access-schema.json)
- [Error](json-schema/exchangerate-api-error-schema.json)

### JSON Structure

- See [json-structure/](json-structure/) -- 8 structure files paired with the JSON Schemas

### JSON-LD

- [ExchangeRate-API Context](json-ld/exchangerate-api-context.jsonld)

### Examples

- See [examples/](examples/) -- 10 operation example payloads

### Rules

- [Spectral Rules](rules/exchangerate-api-rules.yml)

### Vocabulary

- [ExchangeRate-API Vocabulary](vocabulary/exchangerate-api-vocabulary.yml)

## Capabilities

Naftiko capabilities organized as self-contained business surfaces.

- [Latest Rates](capabilities/exchangerate-api-latest-rates.yaml) -- 1 operation
- [Pair Conversion](capabilities/exchangerate-api-pair-conversion.yaml) -- 2 operations
- [Enriched Data](capabilities/exchangerate-api-enriched-data.yaml) -- 1 operation
- [Historical Rates](capabilities/exchangerate-api-historical-rates.yaml) -- 2 operations
- [Supported Codes](capabilities/exchangerate-api-supported-codes.yaml) -- 1 operation
- [Quota](capabilities/exchangerate-api-quota.yaml) -- 1 operation
- [Open Access](capabilities/exchangerate-api-open-access.yaml) -- 1 operation

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
