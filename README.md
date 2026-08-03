# Air Quality Programmatic APIs (air-quality-programmatic-apis)

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

Air Quality Programmatic APIs provide real-time and forecast air quality data from 11,000+ monitoring stations in 1,000+ cities worldwide. APIs deliver Air Quality Index (AQI) measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants. Provided by AQICN (World Air Quality Index project) in partnership with the US EPA and global environmental agencies. Data is available via JSON API and map tile API for visualization.

**APIs.json:** [https://raw.githubusercontent.com/api-search/air-quality-programmatic-apis/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-search/air-quality-programmatic-apis/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Air Quality
- Environment
- EPA
- Open Data
- Public Health
- IoT
- Government Data
- Real-Time Data

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-19

## APIs

### AQICN Real-Time Air Quality API

Real-time and forecast air quality data from 11,000+ monitoring stations globally. Returns AQI measurements for PM2.5, PM10, NO2, CO, SO2, and ozone pollutants by city, station, geographic coordinates, or IP geolocation. Includes weather data and 3-8 day air quality forecasts.

- **Human URL:** [https://aqicn.org/api/](https://aqicn.org/api/)

#### Tags

- Air Quality
- AQI
- PM2.5
- EPA
- Environment
- Public Health
- Real-Time
- Open Data

#### Properties

- [Documentation](https://aqicn.org/api/)
- [API Reference](https://aqicn.org/json-api/doc/)
- [OpenAPI](openapi/air-quality-programmatic-apis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/air-quality-programmatic-apis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/air-quality-programmatic-apis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://aqicn.org/data-platform/token/)

### AQICN JSON Air Quality API

JSON API returning real-time AQI station data by city name, station name, geographic coordinates, or IP geolocation. Includes pollutant breakdowns (PM2.5, PM10, NO2, CO, SO2, O3), weather data, and multi-day forecasts.

- **Human URL:** [https://aqicn.org/json-api/doc/](https://aqicn.org/json-api/doc/)

#### Tags

- Air Quality
- AQI
- PM2.5
- JSON
- Real-Time
- Forecast

#### Properties

- [Documentation](https://aqicn.org/json-api/doc/)
- [API Reference](https://aqicn.org/json-api/doc/)
- [OpenAPI](openapi/aqicn-json-api-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/USEPA)
- [F A Q](https://aqicn.org/faq/)
- [Authentication](https://aqicn.org/data-platform/token/)
- [Portal](https://aqicn.org/map/)
- [Portal](https://aqicn.org/data-platform/)
- [Terms of Service](https://aqicn.org/api/tos/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/aqicn-spectral-rules.yml)
- [Vocabulary](vocabulary/aqicn-vocabulary.yaml)
- [Integrations](https://aqicn.org/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
