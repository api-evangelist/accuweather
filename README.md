# AccuWeather (accuweather)
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
