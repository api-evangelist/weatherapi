# WeatherAPI (weatherapi)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

WeatherAPI.com provides real-time, forecast, historical, marine, future, astronomy, air quality, pollen, sports, IP lookup, time zone, and geolocation data via a JSON/XML REST API. Trusted by 850,000+ developers worldwide with an average ~200ms response time.

**URL:** [https://www.weatherapi.com/](https://www.weatherapi.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Weather, Forecast, History, Marine, Astronomy, Geolocation, Sports, Alerts, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### WeatherAPI
Real-time, forecast (up to 14 days, 300-day future tier), historical (since 2010), marine, astronomy, IP lookup, time zone, sports, and weather-alerts API. Single API key auth via the `key` query parameter. JSON and XML response formats.

**Human URL:** [https://www.weatherapi.com/](https://www.weatherapi.com/)

**Base URL:** `https://api.weatherapi.com/v1`

#### Tags

Weather, Forecast, History, Marine, Astronomy, Geolocation, Sports, Alerts

#### Properties

- [Documentation](https://www.weatherapi.com/docs/)
- [APIReference](https://www.weatherapi.com/docs/)
- [OpenAPI](openapi/weatherapi-openapi-original.yml)
- [APIExplorer](https://www.weatherapi.com/api-explorer.aspx)
- [Authentication](https://www.weatherapi.com/docs/#intro-authentication)
- [SDK — Python SDK](https://github.com/weatherapicom/python)
- [SDK — JavaScript SDK](https://github.com/weatherapicom/javascript)
- [SDK — PHP SDK](https://github.com/weatherapicom/php)
- [SDK — Java SDK](https://github.com/weatherapicom/java)
- [SDK — C# SDK](https://github.com/weatherapicom/csharp)
- [SDK — Go SDK](https://github.com/weatherapicom/go)
- [SDK — Android SDK](https://github.com/weatherapicom/android)
- [SDK — .NET Standard SDK](https://github.com/weatherapicom/weatherapi-Net-Standard)
- [SDK — iOS SDK](https://github.com/weatherapicom/weatherapi-iOS)
- [CodeExamples — Multi-language Examples](https://github.com/weatherapicom/weatherapi-examples)
- [NaftikoCapability — WeatherAPI — Weather](capabilities/weatherapi-weather.yaml)
- [NaftikoCapability — WeatherAPI — History](capabilities/weatherapi-history.yaml)
- [NaftikoCapability — WeatherAPI — Future](capabilities/weatherapi-future.yaml)
- [NaftikoCapability — WeatherAPI — Marine](capabilities/weatherapi-marine.yaml)
- [NaftikoCapability — WeatherAPI — Alerts](capabilities/weatherapi-alerts.yaml)
- [NaftikoCapability — WeatherAPI — Geo](capabilities/weatherapi-geo.yaml)
- [NaftikoCapability — WeatherAPI — Sports](capabilities/weatherapi-sports.yaml)

## Common Properties

- [Website](https://www.weatherapi.com/)
- [GettingStarted](https://www.weatherapi.com/docs/)
- [Portal](https://www.weatherapi.com/my/)
- [SignUp](https://www.weatherapi.com/signup.aspx)
- [Pricing](https://www.weatherapi.com/pricing.aspx)
- [TermsOfService](https://www.weatherapi.com/terms.aspx)
- [PrivacyPolicy](https://www.weatherapi.com/privacy.aspx)
- [Support](https://www.weatherapi.com/contact.aspx)
- [Blog](https://blog.weatherapi.com/)
- [GitHubOrganization](https://github.com/weatherapicom)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Tools — MCP Server (Official)](https://github.com/weatherapicom/weatherapi-mcp)
- [Tools — weatherapi-mcp on npm](https://www.npmjs.com/package/weatherapi-mcp)
- [Plans](plans/weatherapi-plans-pricing.yml)
- [RateLimits](rate-limits/weatherapi-rate-limits.yml)
- [FinOps](finops/weatherapi-finops.yml)
- [SpectralRules](rules/weatherapi-rules.yml)
- [Vocabulary](vocabulary/weatherapi-vocabulary.yml)
- [JSON-LD](json-ld/weatherapi-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Real-time Weather | Current conditions refreshed every 10–15 minutes for any global location. |
| 14-Day Forecast | Daily and hourly forecast covering up to 14 days ahead (15-minute interval on Enterprise). |
| Historical Weather | Past weather data from January 1, 2010 onwards. |
| Future Weather | Long-range forecasts from 14 to 300 days ahead (Pro+ and above). |
| Marine Weather | Wave height, swell direction, and tide tables for coastal and ocean locations. |
| Astronomy | Sunrise, sunset, moonrise, moonset, moon phase, and illumination. |
| Air Quality and Pollen | US EPA and UK DEFRA indices plus pollen data with current and forecast endpoints. |
| Weather Alerts | Government-issued warnings worldwide (USA, UK, Europe, and global). |
| Sports Events | Upcoming football, cricket, and golf events tied to a location. |
| Geo Services | Location search/autocomplete, IP lookup, and time zone resolution. |
| Bulk Requests | POST /current.json#bulk accepts up to 50 locations per call (Pro+ and above). |
| Multilingual Conditions | Condition descriptions in 40+ languages via the `lang` parameter. |
| JSON and XML Responses | Every endpoint supports `.json` and `.xml` response variants. |
| Official MCP Server | Drop-in Model Context Protocol server for Claude Desktop, Cursor, and other agents. |

## Use Cases

| Name | Description |
|------|-------------|
| Consumer Weather Apps | Power mobile and web weather apps with global coverage and 200ms response times. |
| Travel & Trip Planning | Show forecast, alerts, marine, and astronomy data for trip destinations. |
| Logistics & Fleet Routing | Avoid weather disruptions on routes using forecast and alerts endpoints. |
| Smart Home & IoT | Drive thermostats, sprinklers, and shades from real-time and forecast data. |
| Agriculture | Use rainfall, evapotranspiration, and forecast data to plan irrigation and harvest. |
| Energy Forecasting | Solar irradiance, wind, and temperature inputs for renewable-energy generation models. |
| Insurance & Risk | Historical archives for claims investigation and parametric weather insurance. |
| Sports & Events | Schedule outdoor events around forecast windows and alerts. |
| Maritime & Shipping | Wave, swell, and tide data for coastal and ocean operations. |
| AI Agents | Give Claude and other LLM agents live weather context via the official MCP server. |

## Integrations

| Name | Description |
|------|-------------|
| Claude Desktop | Drop-in MCP server (weatherapi-mcp) registered in claude_desktop_config.json. |
| Cursor | MCP integration via .cursor/mcp.json. |
| Microcks | OpenAPI spec carries `x-microcks-operation` extensions for one-command mocking. |
| SwaggerHub | Spec is also published on SwaggerHub under WeatherAPI.com / WeatherAPI. |
| WeatherAI.io | Sibling product providing AI-summarised weather narrative. |
| Miing.com | Sibling product for air-quality analytics. |
| Azuce.com | Sibling product for solar forecasting. |

## Solutions

| Name | Description |
|------|-------------|
| Free Tier | 100K calls/month, 3-day forecast, 1-day history — for evaluation and hobby use. |
| Starter ($7/mo) | 3M calls/month, 7-day forecast and history — small production workloads. |
| Pro+ ($25/mo) | 5M calls/month, marine weather, bulk requests, 365-day rolling history. |
| Business ($65/mo) | 10M calls/month, 14-day forecast, marine with tides, IP allow/block lists, 99.9% SLA. |
| Enterprise (custom) | 15-minute intervals, full historical archives, 100% uptime SLA with contract. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [weatherapi-openapi-original.yml](openapi/weatherapi-openapi-original.yml)

### JSON Schema (26 files)

- [weatherapi-air-quality-schema.json](json-schema/weatherapi-air-quality-schema.json)
- [weatherapi-alert-schema.json](json-schema/weatherapi-alert-schema.json)
- [weatherapi-alerts-response-schema.json](json-schema/weatherapi-alerts-response-schema.json)
- [weatherapi-astro-element-schema.json](json-schema/weatherapi-astro-element-schema.json)
- [weatherapi-astronomy-response-schema.json](json-schema/weatherapi-astronomy-response-schema.json)
- [weatherapi-bulk-location-schema.json](json-schema/weatherapi-bulk-location-schema.json)
- [weatherapi-bulk-request-schema.json](json-schema/weatherapi-bulk-request-schema.json)
- [weatherapi-bulk-response-schema.json](json-schema/weatherapi-bulk-response-schema.json)
- [weatherapi-condition-schema.json](json-schema/weatherapi-condition-schema.json)
- [weatherapi-current-weather-response-schema.json](json-schema/weatherapi-current-weather-response-schema.json)
- [weatherapi-current-weather-schema.json](json-schema/weatherapi-current-weather-schema.json)
- [weatherapi-forecast-day-entry-schema.json](json-schema/weatherapi-forecast-day-entry-schema.json)
- [weatherapi-forecast-day-schema.json](json-schema/weatherapi-forecast-day-schema.json)
- [weatherapi-forecast-weather-response-schema.json](json-schema/weatherapi-forecast-weather-response-schema.json)
- [weatherapi-hour-forecast-schema.json](json-schema/weatherapi-hour-forecast-schema.json)
- [weatherapi-ip-lookup-response-schema.json](json-schema/weatherapi-ip-lookup-response-schema.json)
- [weatherapi-location-schema.json](json-schema/weatherapi-location-schema.json)
- [weatherapi-marine-forecast-day-schema.json](json-schema/weatherapi-marine-forecast-day-schema.json)
- [weatherapi-marine-hour-schema.json](json-schema/weatherapi-marine-hour-schema.json)
- [weatherapi-marine-weather-response-schema.json](json-schema/weatherapi-marine-weather-response-schema.json)
- [weatherapi-pollen-schema.json](json-schema/weatherapi-pollen-schema.json)
- [weatherapi-search-location-schema.json](json-schema/weatherapi-search-location-schema.json)
- [weatherapi-sport-event-schema.json](json-schema/weatherapi-sport-event-schema.json)
- [weatherapi-sports-response-schema.json](json-schema/weatherapi-sports-response-schema.json)
- [weatherapi-tide-schema.json](json-schema/weatherapi-tide-schema.json)
- [weatherapi-timezone-response-schema.json](json-schema/weatherapi-timezone-response-schema.json)

### JSON Structure (26 files)

- [weatherapi-air-quality-structure.json](json-structure/weatherapi-air-quality-structure.json)
- [weatherapi-alert-structure.json](json-structure/weatherapi-alert-structure.json)
- [weatherapi-alerts-response-structure.json](json-structure/weatherapi-alerts-response-structure.json)
- [weatherapi-astro-element-structure.json](json-structure/weatherapi-astro-element-structure.json)
- [weatherapi-astronomy-response-structure.json](json-structure/weatherapi-astronomy-response-structure.json)
- [weatherapi-bulk-location-structure.json](json-structure/weatherapi-bulk-location-structure.json)
- [weatherapi-bulk-request-structure.json](json-structure/weatherapi-bulk-request-structure.json)
- [weatherapi-bulk-response-structure.json](json-structure/weatherapi-bulk-response-structure.json)
- [weatherapi-condition-structure.json](json-structure/weatherapi-condition-structure.json)
- [weatherapi-current-weather-response-structure.json](json-structure/weatherapi-current-weather-response-structure.json)
- [weatherapi-current-weather-structure.json](json-structure/weatherapi-current-weather-structure.json)
- [weatherapi-forecast-day-entry-structure.json](json-structure/weatherapi-forecast-day-entry-structure.json)
- [weatherapi-forecast-day-structure.json](json-structure/weatherapi-forecast-day-structure.json)
- [weatherapi-forecast-weather-response-structure.json](json-structure/weatherapi-forecast-weather-response-structure.json)
- [weatherapi-hour-forecast-structure.json](json-structure/weatherapi-hour-forecast-structure.json)
- [weatherapi-ip-lookup-response-structure.json](json-structure/weatherapi-ip-lookup-response-structure.json)
- [weatherapi-location-structure.json](json-structure/weatherapi-location-structure.json)
- [weatherapi-marine-forecast-day-structure.json](json-structure/weatherapi-marine-forecast-day-structure.json)
- [weatherapi-marine-hour-structure.json](json-structure/weatherapi-marine-hour-structure.json)
- [weatherapi-marine-weather-response-structure.json](json-structure/weatherapi-marine-weather-response-structure.json)
- [weatherapi-pollen-structure.json](json-structure/weatherapi-pollen-structure.json)
- [weatherapi-search-location-structure.json](json-structure/weatherapi-search-location-structure.json)
- [weatherapi-sport-event-structure.json](json-structure/weatherapi-sport-event-structure.json)
- [weatherapi-sports-response-structure.json](json-structure/weatherapi-sports-response-structure.json)
- [weatherapi-tide-structure.json](json-structure/weatherapi-tide-structure.json)
- [weatherapi-timezone-response-structure.json](json-structure/weatherapi-timezone-response-structure.json)

### JSON-LD

- [weatherapi-context.jsonld](json-ld/weatherapi-context.jsonld)

### Examples (26 files)

- [weatherapi-air-quality-example.json](examples/weatherapi-air-quality-example.json)
- [weatherapi-alert-example.json](examples/weatherapi-alert-example.json)
- [weatherapi-alerts-response-example.json](examples/weatherapi-alerts-response-example.json)
- [weatherapi-astro-element-example.json](examples/weatherapi-astro-element-example.json)
- [weatherapi-astronomy-response-example.json](examples/weatherapi-astronomy-response-example.json)
- [weatherapi-bulk-location-example.json](examples/weatherapi-bulk-location-example.json)
- [weatherapi-bulk-request-example.json](examples/weatherapi-bulk-request-example.json)
- [weatherapi-bulk-response-example.json](examples/weatherapi-bulk-response-example.json)
- [weatherapi-condition-example.json](examples/weatherapi-condition-example.json)
- [weatherapi-current-weather-example.json](examples/weatherapi-current-weather-example.json)
- [weatherapi-current-weather-response-example.json](examples/weatherapi-current-weather-response-example.json)
- [weatherapi-forecast-day-entry-example.json](examples/weatherapi-forecast-day-entry-example.json)
- [weatherapi-forecast-day-example.json](examples/weatherapi-forecast-day-example.json)
- [weatherapi-forecast-weather-response-example.json](examples/weatherapi-forecast-weather-response-example.json)
- [weatherapi-hour-forecast-example.json](examples/weatherapi-hour-forecast-example.json)
- [weatherapi-ip-lookup-response-example.json](examples/weatherapi-ip-lookup-response-example.json)
- [weatherapi-location-example.json](examples/weatherapi-location-example.json)
- [weatherapi-marine-forecast-day-example.json](examples/weatherapi-marine-forecast-day-example.json)
- [weatherapi-marine-hour-example.json](examples/weatherapi-marine-hour-example.json)
- [weatherapi-marine-weather-response-example.json](examples/weatherapi-marine-weather-response-example.json)
- [weatherapi-pollen-example.json](examples/weatherapi-pollen-example.json)
- [weatherapi-search-location-example.json](examples/weatherapi-search-location-example.json)
- [weatherapi-sport-event-example.json](examples/weatherapi-sport-event-example.json)
- [weatherapi-sports-response-example.json](examples/weatherapi-sports-response-example.json)
- [weatherapi-tide-example.json](examples/weatherapi-tide-example.json)
- [weatherapi-timezone-response-example.json](examples/weatherapi-timezone-response-example.json)

## Naftiko Capabilities

Self-contained Naftiko capability files (one per OpenAPI tag), each declaring inline `consumes` + REST + MCP adapters.

### WeatherAPI

| Capability | Operations | MCP Tools | File |
|----------|-----------|-----------|------|
| WeatherAPI.com — Alerts | 1 | 1 | [weatherapi-alerts.yaml](capabilities/weatherapi-alerts.yaml) |
| WeatherAPI.com — Future | 1 | 1 | [weatherapi-future.yaml](capabilities/weatherapi-future.yaml) |
| WeatherAPI.com — Geo | 4 | 4 | [weatherapi-geo.yaml](capabilities/weatherapi-geo.yaml) |
| WeatherAPI.com — History | 1 | 1 | [weatherapi-history.yaml](capabilities/weatherapi-history.yaml) |
| WeatherAPI.com — Marine | 1 | 1 | [weatherapi-marine.yaml](capabilities/weatherapi-marine.yaml) |
| WeatherAPI.com — Sports | 1 | 1 | [weatherapi-sports.yaml](capabilities/weatherapi-sports.yaml) |
| WeatherAPI.com — Weather | 3 | 3 | [weatherapi-weather.yaml](capabilities/weatherapi-weather.yaml) |

## Vocabulary

- [WeatherAPI Vocabulary](vocabulary/weatherapi-vocabulary.yml) — Unified taxonomy mapping 12 resources, 3 actions, 7 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [WeatherAPI Spectral Rules](rules/weatherapi-rules.yml) — 37 Spectral rules enforcing WeatherAPI.com API conventions (path .json suffix, camelCase operationIds, snake_case schema properties, ApiKeyAuth via query parameter, Title Case tags, provider-prefixed summaries).

## Commercial Surface

- [Plans & Pricing](plans/weatherapi-plans-pricing.yml) — 5 tiered subscription plans (Free, Starter, Pro+, Business, Enterprise) using API Commons Plans 0.1.
- [Rate Limits](rate-limits/weatherapi-rate-limits.yml) — Monthly call quotas (100K → 10M+) and per-account scope, using API Commons Rate Limits 0.1.
- [FinOps](finops/weatherapi-finops.yml) — FOCUS-aligned FinOps mapping for tiered subscription billing.

## Maintainers

- **Kin Lane** — kin@apievangelist.com
