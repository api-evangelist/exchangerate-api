# ExchangeRate-API (exchangerate-api)

ExchangeRate-API is a currency exchange rates API providing authoritative daily and intraday foreign exchange rates for 161 currencies. The v6 surface includes Latest, Pair, Enriched, Historical, Supported Codes, and Quota endpoints, plus a no-API-key Open Access endpoint at open.er-api.com that requires attribution.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/exchangerate-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/exchangerate-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Currency Exchange
- Foreign Exchange
- Financial Data
- Forex
- Currency Conversion
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### ExchangeRate-API Latest Rates API

Returns the latest exchange rates from a base currency to all 161 supported currencies. Update cadence varies by plan tier (daily on Free, hourly on Pro, every 5 minutes on Business / Volume).

- **Human URL:** [https://www.exchangerate-api.com/docs/standard-requests](https://www.exchangerate-api.com/docs/standard-requests)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Latest Rates
- Foreign Exchange

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/standard-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-latest-rates-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-latest-rates-structure.json)
- [Example](examples/exchangerate-api-get-latest-rates-example.json)

### ExchangeRate-API Pair Conversion API

Returns the exchange rate between a base and a target currency, optionally with a converted amount when amount is supplied in the path.

- **Human URL:** [https://www.exchangerate-api.com/docs/pair-conversion-requests](https://www.exchangerate-api.com/docs/pair-conversion-requests)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Pair Conversion
- Foreign Exchange

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/pair-conversion-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-pair-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-pair-structure.json)
- [Example](examples/exchangerate-api-get-pair-conversion-example.json)
- [Example](examples/exchangerate-api-get-pair-conversion-with-amount-example.json)

### ExchangeRate-API Enriched Data API

Returns the exchange rate between a base and target currency along with enriched target currency metadata (locale, two-letter country code, currency name, display symbol, flag URL). Business and Volume plans only.

- **Human URL:** [https://www.exchangerate-api.com/docs/enriched-data-requests](https://www.exchangerate-api.com/docs/enriched-data-requests)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Enriched Data
- Locale

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/enriched-data-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-enriched-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-enriched-structure.json)
- [Example](examples/exchangerate-api-get-enriched-pair-example.json)

### ExchangeRate-API Historical Rates API

Returns historical exchange rates for a given base currency on a specific date. Full currency coverage from 2021-01-01 onward; 35 currencies available from 1990-01-01 to 2020-12-31. Pro, Business, and Volume plans only.

- **Human URL:** [https://www.exchangerate-api.com/docs/historical-data-requests](https://www.exchangerate-api.com/docs/historical-data-requests)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Historical Rates
- Time Series

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/historical-data-requests)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-historical-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-historical-structure.json)
- [Example](examples/exchangerate-api-get-historical-rates-example.json)
- [Example](examples/exchangerate-api-get-historical-rates-with-amount-example.json)

### ExchangeRate-API Supported Codes API

Returns an array of all supported ISO 4217 currency codes and their full names.

- **Human URL:** [https://www.exchangerate-api.com/docs/supported-codes-endpoint](https://www.exchangerate-api.com/docs/supported-codes-endpoint)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Supported Codes
- ISO 4217

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/supported-codes-endpoint)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-supported-codes-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-supported-codes-structure.json)
- [Example](examples/exchangerate-api-get-supported-codes-example.json)

### ExchangeRate-API Quota API

Returns the plan quota, number of requests remaining in the current billing window, and refresh metadata for the API key.

- **Human URL:** [https://www.exchangerate-api.com/docs/overview](https://www.exchangerate-api.com/docs/overview)
- **Base URL:** `https://v6.exchangerate-api.com/v6`

#### Tags

- Currency Exchange
- Quota
- Account

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/overview)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-quota-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-quota-structure.json)
- [Example](examples/exchangerate-api-get-quota-example.json)

### ExchangeRate-API Open Access API

No-API-key public endpoint at open.er-api.com providing latest exchange rates for a base currency. Updates once daily; attribution to exchangerate-api.com required. Anti-abuse throttled.

- **Human URL:** [https://www.exchangerate-api.com/docs/free](https://www.exchangerate-api.com/docs/free)
- **Base URL:** `https://open.er-api.com/v6`

#### Tags

- Currency Exchange
- Open Access
- Free

#### Properties

- [Documentation](https://www.exchangerate-api.com/docs/free)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exchangerate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exchangerate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/exchangerate-api-open-access-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-open-access-structure.json)
- [Example](examples/exchangerate-api-get-open-access-latest-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.exchangerate-api.com)
- [Documentation](https://www.exchangerate-api.com/docs/overview)
- [API Reference](https://www.exchangerate-api.com/docs/overview)
- [OpenAPI](openapi/exchangerate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/exchangerate-api-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/exchangerate-api-error-structure.json)
- [JSON-LD](json-ld/exchangerate-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/exchangerate-api-error-example.json)
- [Vocabulary](vocabulary/exchangerate-api-vocabulary.yml)
- [Spectral Rules](rules/exchangerate-api-rules.yml)
- [Plans](plans/exchangerate-api-plans-pricing.yml)
- [Rate Limits](rate-limits/exchangerate-api-rate-limits.yml)
- [Fin Ops](finops/exchangerate-api-finops.yml)
- [Authentication](https://www.exchangerate-api.com/docs/overview)
- [Pricing](https://www.exchangerate-api.com/#pricing)
- [Sign Up](https://app.exchangerate-api.com/sign-up)
- [Login](https://app.exchangerate-api.com/sign-in)
- [Terms of Service](https://www.exchangerate-api.com/terms)
- [Privacy Policy](https://www.exchangerate-api.com/privacy-policy)
- [Support](https://www.exchangerate-api.com/contact)
- [Contact](https://www.exchangerate-api.com/contact)
- [SDK](https://www.exchangerate-api.com/docs/python-currency-api)
- [SDK](https://github.com/EloquentStudio/exchangerate-api-node)
- [M C P Server](https://lobehub.com/mcp/mazezen-mcp-exchange-rate)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
