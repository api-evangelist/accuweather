# AccuWeather (accuweather)

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

AccuWeather provides the world's most sophisticated weather intelligence to make lives simpler, safer, and better. Their mission is to save lives and protect property through accurate weather forecasting and data. The AccuWeather One Platform API delivers current conditions, forecasts (hourly, daily, minutecast), air quality, storm tracking, lifestyle indices, and imagery to tens of billions of API calls daily.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/accuweather/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Weather, Forecasts, Meteorology, Location Services, Air Quality, Storms

## Timestamps

- **Created:** 2023-11-22
- **Modified:** 2026-04-19

## APIs

### AccuWeather API
The AccuWeather One Platform API provides comprehensive weather data including current conditions, hourly and daily forecasts, MinuteCast minute-by-minute precipitation, air quality indices, tropical storm tracking, weather alarms, lifestyle indices, and radar/satellite imagery. Covers 3.5 million+ locations globally with 250+ weather data parameters.

**Human URL:** [https://developer.accuweather.com/](https://developer.accuweather.com/)

#### Tags:

 - Weather, Forecasts, Air Quality, Storms, MinuteCast, Location

#### Properties

- [Documentation](https://developer.accuweather.com/apis)
- [OpenAPI](openapi/accuweather-openapi-original.yml)
- [Authentication](https://developer.accuweather.com/)
- [14-Day Free Trial](https://developer.accuweather.com/)

## Common Properties

- [Portal](https://developer.accuweather.com/)
- [Getting Started](https://developer.accuweather.com/)
- [Best Practices](https://developer.accuweather.com/best-practices)
- [Status Page](https://status.accuweather.com/)
- [Terms of Service](https://developer.accuweather.com/legal)
- [FAQ](https://developer.accuweather.com/faq-page)
- [Pricing](https://developer.accuweather.com/packages)
- [Privacy Policy](https://www.accuweather.com/en/privacy)
- [AccuWeather Spectral Rules](rules/accuweather-spectral-rules.yml)
- [AccuWeather JSON-LD Context](json-ld/accuweather-context.jsonld)
- [AccuWeather Vocabulary](vocabulary/accuweather-vocabulary.yaml)
- [Weather Intelligence Capability](capabilities/weather-intelligence.yaml)

## Features

| Name | Description |
|------|-------------|
| Global Weather Coverage | Access weather data for 3.5 million+ locations worldwide with hyper-local precision pinpointed to exact latitude and longitude. |
| MinuteCast Precipitation Forecasts | Proprietary minute-by-minute precipitation forecasts with start/stop timing for rain, snow, and ice at any location. |
| 250+ Weather Data Parameters | Comprehensive data including RealFeel temperature, AccuLumen Brightness Index, 50+ lifestyle indices, and detailed atmospheric data. |
| Air Quality Monitoring | Real-time and forecast air quality index (AQI) with pollutant breakdowns including PM2.5, PM10, ozone, NO2, SO2, and CO. |
| Tropical Storm Tracking | Active storm tracking with positions, forecast tracks, and historical data for tropical cyclones in all global ocean basins. |
| Weather Imagery | Radar and satellite imagery maps in multiple resolutions (480x480, 640x480, 1024x1024) for integration into applications. |

## Use Cases

| Name | Description |
|------|-------------|
| Consumer Weather Applications | Power mobile and web weather apps with accurate current conditions, forecasts, and location-aware weather data. |
| IoT and Smart Home Automation | Trigger IoT device actions based on real-time weather conditions, forecasts, and precipitation alerts. |
| Travel and Outdoor Planning | Integrate weather data into travel booking, outdoor activity planning, and event management platforms. |
| Emergency Management | Use storm tracking, severe weather alerts, and precipitation forecasts for emergency response and public safety. |
| Agriculture and Environmental Monitoring | Access hyper-local weather data and forecasts for precision agriculture, crop management, and environmental monitoring. |

## Integrations

| Name | Description |
|------|-------------|
| Apple WeatherKit | AccuWeather data powers weather experiences on Apple platforms alongside native WeatherKit data. |
| Samsung SmartThings | Weather-based automation triggers in the Samsung SmartThings IoT ecosystem. |
| Salesforce | Weather data integration with Salesforce CRM for weather-aware sales and service workflows. |
| Microsoft Azure | Azure Maps integration providing AccuWeather data within the Microsoft cloud ecosystem. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AccuWeather One Platform API](openapi/accuweather-openapi-original.yml)

### JSON Schema

57 schema files covering all AccuWeather API data models including:
- [Air Quality Schema](json-schema/accuweather-air-quality-schema.json)
- [Autocomplete Location Schema](json-schema/accuweather-autocomplete-location-schema.json)
- [Current Conditions Schema](json-schema/accuweather-current-data-schema.json)
- [Hourly Forecast Schema](json-schema/accuweather-hourly-forecast-schema.json)
- [Daily Forecast Schema](json-schema/accuweather-daily-forecast-schema.json)

### JSON Structure

57 JSON Structure files corresponding to all JSON Schema definitions.

### JSON-LD

- [AccuWeather Context](json-ld/accuweather-context.jsonld)

### Examples

57 example JSON files for all AccuWeather API data models.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AccuWeather API](capabilities/shared/accuweather-api.yaml) — 10 operations for weather data, location search, forecasts, air quality, and storm tracking

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Weather Intelligence](capabilities/weather-intelligence.yaml) | AccuWeather One Platform API | 9 | Developer, Mobile App, IoT Platform, Emergency Management |

## Vocabulary

- [AccuWeather Vocabulary](vocabulary/accuweather-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 5 actions, 1 workflow, and 4 personas across AccuWeather's weather data platform

## Rules

- [AccuWeather Spectral Rules](rules/accuweather-spectral-rules.yml) — 21 rules across 8 categories enforcing AccuWeather API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
