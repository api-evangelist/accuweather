# AccuWeather GraphQL

This directory contains a conceptual GraphQL schema for the AccuWeather One Platform API. AccuWeather does not currently publish an official GraphQL endpoint; this schema is a translation of the REST API surface into GraphQL types and queries, intended for use in tooling, documentation, and API design work.

## Source

- REST API documentation: https://developer.accuweather.com/apis
- Base URL: https://dataservice.accuweather.com
- Authentication: API key passed as the `apikey` query parameter

## Schema Overview

File: `accuweather-schema.graphql`

The schema covers the full breadth of AccuWeather data:

### Root Queries

| Query | Description |
|---|---|
| `locationSearch` | Text-based location search |
| `location` | Lookup by LocationKey |
| `nearbyLocations` | Geo-coordinate proximity search |
| `autoLocation` | IP-based location detection |
| `currentConditions` | Real-time observed conditions |
| `hourlyForecast` | 1–120 hour forecasts |
| `dailyForecast` | 1–15 day forecasts with headline |
| `minuteForecast` | MinuteCast 120-minute precipitation |
| `indices` | Lifestyle and weather indices |
| `sunAndMoon` | Sunrise, sunset, and moon phase |
| `alerts` | Active weather alerts |
| `airQuality` | AQI with pollutant breakdown |
| `historicalConditions` | Past 6 or 24 hours of observations |

### Type Groups

**Location**: `Location`, `LocationKey`, `Country`, `Region`, `AdministrativeArea`, `SupplementalAdminArea`, `TimeZone`, `GeoPosition`, `Elevation`, `LocationDetails`, `DataSource`

**Current Conditions**: `CurrentConditions`, `PressureTendency`, `PrecipitationSummary`, `TemperatureSummary`

**Forecasts**: `DailyForecastResponse`, `DailyForecast`, `DayNightForecast`, `HourlyForecast`, `MinuteForecastResponse`, `MinuteSummary`, `MinuteForecast`

**Indices and Astronomy**: `DailyIndex`, `SunAndMoon`, `SunriseSunset`, `MoonPhase`

**Wind**: `Wind`, `WindGust`, `WindDirection`, `WindSpeed`

**Temperature**: `TemperaturePair`, `TemperatureRange`, `RealFeel`, `RealFeelValue`, `WetBulb`

**Atmosphere**: `PressurePair`, `PressureTendency`, `RelativeHumidity`, `VisibilityPair`, `CloudCover`, `DegreeDaySummary`, `SolarIrradiance`

**Precipitation**: `PrecipPair`, `PrecipitationType`, `PrecipitationProbability`, `ThunderstormProbability`, `SnowProbability`, `IceProbability`

**Headline and Severity**: `Headline`, `SeverityLevel`, `WeatherText`, `WeatherIcon`, `PhotoURL`

**Alerts**: `Alert`, `AlertSummary`, `AlertDetails`, `AlertArea`, `AlertText`, `AlertAction`, `AlertType`

**Air Quality and Allergy**: `AirQualityIndex`, `Pollutant`, `PollutantConcentration`, `AllergyOutlook`, `AirAndPollen`

**Historical**: `HistoricalConditions`

**API Access**: `APICredential`, `APIUsage`, `PremiumFeature`

**Shared**: `UnitValue`

## Total Named Types

58 named types (excluding the root `Query` type and `schema` definition).

## Usage Notes

- All location lookups return an AccuWeather `LocationKey` (a string such as `"347625"`) that is required for condition and forecast queries.
- The `metric` boolean argument on forecast queries toggles between SI (Celsius, km/h, mm) and imperial (Fahrenheit, mph, inches) unit responses.
- The `details` boolean argument on location and condition queries expands the response with additional fields (e.g., `LocationDetails`, full precipitation summaries).
- AccuWeather enforces per-package daily call limits. The `APIUsage` type reflects those limits.
- MinuteCast (`minuteForecast`) is a premium feature available on higher-tier plans.

## Links

- Developer Portal: https://developer.accuweather.com/
- Pricing and Packages: https://developer.accuweather.com/packages
- Terms of Service: https://developer.accuweather.com/legal
- Status Page: https://status.accuweather.com/
