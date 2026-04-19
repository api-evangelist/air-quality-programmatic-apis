# Air Quality Programmatic APIs (air-quality-programmatic-apis)

Air Quality Programmatic APIs provide real-time and forecast air quality data from 11,000+ monitoring stations in 1,000+ cities worldwide. APIs deliver Air Quality Index (AQI) measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants. Provided by AQICN (World Air Quality Index project) in partnership with the US EPA and global environmental agencies. Data is available via JSON API and map tile API for visualization.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-search/air-quality-programmatic-apis/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Air Quality, Environment, EPA, Open Data, Public Health, IoT, Government Data, Real-Time Data

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-04-19

## APIs

### AQICN Real-Time Air Quality API
Real-time and forecast air quality data from 11,000+ monitoring stations globally. Returns AQI measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants by city, station, geographic coordinates, or IP geolocation. Includes weather data and 3-8 day air quality forecasts.

**Human URL:** [https://aqicn.org/api/](https://aqicn.org/api/)

#### Tags:

 - Air Quality, AQI, PM2.5, EPA, Environment, Public Health, Real-Time, Open Data

#### Properties

- [Documentation](https://aqicn.org/api/)
- [JSON API Reference](https://aqicn.org/json-api/doc/)
- [Map Tile API](openapi/air-quality-programmatic-apis-openapi.yml)
- [API Token Request](https://aqicn.org/data-platform/token/)

### AQICN JSON Air Quality API
JSON API returning real-time AQI station data by city name, station name, geographic coordinates, or IP geolocation. Includes pollutant breakdowns (PM2.5, PM10, NO2, CO, SO2, O3), weather data, and multi-day forecasts.

**Human URL:** [https://aqicn.org/json-api/doc/](https://aqicn.org/json-api/doc/)

#### Tags:

 - Air Quality, AQI, PM2.5, JSON, Real-Time, Forecast

#### Properties

- [Documentation](https://aqicn.org/json-api/doc/)
- [APIReference](https://aqicn.org/json-api/doc/)
- [OpenAPI](openapi/aqicn-json-api-openapi.yaml)

## Common Properties

- [AQICN FAQ](https://aqicn.org/faq/)
- [AQICN API Token](https://aqicn.org/data-platform/token/)
- [AQICN Map](https://aqicn.org/map/)
- [AQICN Data Platform](https://aqicn.org/data-platform/)
- [AQICN Terms of Use](https://aqicn.org/api/tos/)
- [AQICN Spectral Rules](rules/aqicn-spectral-rules.yml)
- [Air Quality Monitoring Capability](capabilities/air-quality-monitoring.yaml)
- [AQICN Vocabulary](vocabulary/aqicn-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Real-Time AQI Data | Live air quality index readings from 11,000+ monitoring stations updated continuously. |
| Global Coverage | Data from 1,000+ cities worldwide including US EPA, China MEP, Europe EEA, and other monitoring networks. |
| Multi-Pollutant Data | Pollutant-specific AQI for PM2.5, PM10, nitrogen dioxide, carbon monoxide, sulfur dioxide, and ozone. |
| Air Quality Forecasts | 3-8 day air quality forecasts for major monitoring stations. |
| Geolocation Queries | Find nearest stations by latitude/longitude, city name, or IP-based geolocation. |
| Map Tile API | Raster map tiles for overlaying real-time AQI data on web maps (Leaflet, Google Maps, etc.). |
| Station Search | Search and discover monitoring stations by name or location within a geographic boundary. |
| Weather Data | Current weather conditions co-located with air quality measurements. |

## Use Cases

| Name | Description |
|------|-------------|
| Air Quality Mobile Apps | Build apps that show users real-time air quality for their location with health recommendations. |
| Environmental Monitoring Dashboards | Create web dashboards visualizing air quality trends across cities and regions. |
| Public Health Research | Access historical and real-time air quality data for epidemiological and public health research. |
| Smart City Integration | Integrate air quality data into smart city platforms and IoT systems for environmental management. |
| Outdoor Activity Planning | Provide air quality-based recommendations for outdoor activities in fitness and weather apps. |

## Integrations

| Name | Description |
|------|-------------|
| Leaflet Maps | Integrate AQI map tiles with Leaflet.js for interactive air quality maps. |
| Google Maps | Overlay AQI data on Google Maps using the tile API. |
| US EPA AirNow | Data aggregated from US EPA AirNow monitoring network. |
| OpenAQ | Complementary open air quality data platform with API access. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [air-quality-programmatic-apis-openapi.yml](openapi/air-quality-programmatic-apis-openapi.yml)
- [aqicn-json-api-openapi.yaml](openapi/aqicn-json-api-openapi.yaml)

### JSON Schema

- [aqicn-aqi-station-schema.json](json-schema/aqicn-aqi-station-schema.json)
- [aqicn-attribution-schema.json](json-schema/aqicn-attribution-schema.json)
- [aqicn-city-info-schema.json](json-schema/aqicn-city-info-schema.json)
- [aqicn-forecast-data-schema.json](json-schema/aqicn-forecast-data-schema.json)
- [aqicn-forecast-day-schema.json](json-schema/aqicn-forecast-day-schema.json)
- [aqicn-pollutant-data-schema.json](json-schema/aqicn-pollutant-data-schema.json)
- [aqicn-station-data-schema.json](json-schema/aqicn-station-data-schema.json)
- [aqicn-station-search-result-schema.json](json-schema/aqicn-station-search-result-schema.json)
- [aqicn-time-info-schema.json](json-schema/aqicn-time-info-schema.json)

### JSON Structure

- [aqicn-aqi-station-structure.json](json-structure/aqicn-aqi-station-structure.json)
- [aqicn-attribution-structure.json](json-structure/aqicn-attribution-structure.json)
- [aqicn-city-info-structure.json](json-structure/aqicn-city-info-structure.json)
- [aqicn-forecast-data-structure.json](json-structure/aqicn-forecast-data-structure.json)
- [aqicn-forecast-day-structure.json](json-structure/aqicn-forecast-day-structure.json)
- ... and 4 more

### JSON-LD

- [aqicn-context.jsonld](json-ld/aqicn-context.jsonld)

### Examples

- [aqicn-aqi-station-example.json](examples/aqicn-aqi-station-example.json)
- [aqicn-attribution-example.json](examples/aqicn-attribution-example.json)
- [aqicn-city-info-example.json](examples/aqicn-city-info-example.json)
- [aqicn-forecast-data-example.json](examples/aqicn-forecast-data-example.json)
- [aqicn-forecast-day-example.json](examples/aqicn-forecast-day-example.json)
- ... and 4 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [aqicn-api.yaml](capabilities/shared/aqicn-api.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [air-quality-monitoring.yaml](capabilities/air-quality-monitoring.yaml) | AQICN JSON API | 3 | Developer, Environmental Analyst |

## Vocabulary

- [AQICN Vocabulary](vocabulary/aqicn-vocabulary.yaml) — Taxonomy mapping 4 resources, 4 actions, 1 workflow, and 2 personas across air quality monitoring domains

## Rules

- [aqicn-spectral-rules.yml](rules/aqicn-spectral-rules.yml) — 10 rules enforcing AQICN API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
