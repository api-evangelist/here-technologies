# HERE Technologies (here-technologies)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

HERE Technologies is a location data and technology company offering a broad REST API surface for mapping, geocoding, search, routing, fleet planning, traffic, weather, transit, geofencing, tracking, and HD live mapping for automated driving, plus client SDKs (Maps API for JavaScript, native SDKs for iOS and Android, Flutter), HERE Studio and Workspace for data hosting, and HERE Platform for enterprise data ingestion and processing. Most Location Services APIs are served under the *.hereapi.com domain and authenticated by API key, OAuth token, or app id / app code.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/here-technologies/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/here-technologies/refs/heads/main/apis.yml)

## Tags

- Maps
- Geocoding
- Routing
- Location Services
- Traffic
- HD Live Map
- Automotive
- Fleet

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### HERE Geocoding and Search API

Forward and reverse geocoding, address lookup, place discovery, browse, and details. Returns rich location data including addresses, places, categories, and geometry.

- **Human URL:** [https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html](https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html)
- **Base URL:** `https://geocode.search.hereapi.com`

#### Tags

- Geocoding
- Search
- Places
- REST API

#### Properties

- [Documentation](https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Autosuggest API

Type-ahead search returning place and address suggestions for partial queries, sharing the geocoding and search dataset.

- **Human URL:** [https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html](https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html)
- **Base URL:** `https://autosuggest.search.hereapi.com`

#### Tags

- Autosuggest
- Search
- Type-ahead

#### Properties

- [Documentation](https://www.here.com/docs/bundle/geocoding-and-search-api-developer-guide/page/README.html)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Routing API v8

Calculates routes for car, truck, bicycle, pedestrian, scooter, taxi, and EV vehicles with traffic, restrictions, tolls, alternatives, and turn-by-turn instructions.

- **Human URL:** [https://www.here.com/docs/category/routing-api-v8](https://www.here.com/docs/category/routing-api-v8)
- **Base URL:** `https://router.hereapi.com`

#### Tags

- Routing
- Navigation
- REST API

#### Properties

- [Documentation](https://www.here.com/docs/category/routing-api-v8)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Matrix Routing API v8

Batch many-to-many travel time and distance matrices for fleet routing, logistics, and territory planning.

- **Human URL:** [https://www.here.com/docs/category/matrix-routing-api-v8](https://www.here.com/docs/category/matrix-routing-api-v8)
- **Base URL:** `https://matrix.router.hereapi.com`

#### Tags

- Matrix Routing
- Logistics
- Fleet

#### Properties

- [Documentation](https://www.here.com/docs/category/matrix-routing-api-v8)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Isoline Routing API v8

Computes reachable areas (isolines) by time, distance, or consumption from one or more origins for site selection and service-area analysis.

- **Human URL:** [https://www.here.com/docs/category/isoline-routing-api-v8](https://www.here.com/docs/category/isoline-routing-api-v8)
- **Base URL:** `https://isoline.router.hereapi.com`

#### Tags

- Isoline
- Routing
- Reachability

#### Properties

- [Documentation](https://www.here.com/docs/category/isoline-routing-api-v8)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Tour Planning API

Vehicle routing problem (VRP) solver for fleets, with time windows, capacities, breaks, skills, multi-trip, and pickup-and-delivery constraints.

- **Human URL:** [https://www.here.com/docs/category/tour-planning](https://www.here.com/docs/category/tour-planning)
- **Base URL:** `https://tourplanning.hereapi.com`

#### Tags

- VRP
- Fleet
- Optimization

#### Properties

- [Documentation](https://www.here.com/docs/category/tour-planning)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Waypoint Sequence API

Optimizes the order of intermediate stops for a single vehicle route to minimize travel time or distance.

- **Human URL:** [https://www.here.com/docs/category/waypoint-sequence](https://www.here.com/docs/category/waypoint-sequence)
- **Base URL:** `https://wps.hereapi.com`

#### Tags

- Waypoints
- Optimization
- Routing

#### Properties

- [Documentation](https://www.here.com/docs/category/waypoint-sequence)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Traffic API v7

Real-time traffic flow and incident data: speeds, jam factors, and incident events for monitoring, routing, and analytics.

- **Human URL:** [https://www.here.com/docs/category/traffic-api-v7](https://www.here.com/docs/category/traffic-api-v7)
- **Base URL:** `https://data.traffic.hereapi.com`

#### Tags

- Traffic
- Flow
- Incidents

#### Properties

- [Documentation](https://www.here.com/docs/category/traffic-api-v7)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Public Transit API

Multi-modal public transit routing, station and stop lookup, departure boards, and next-departure data for transit-enabled apps.

- **Human URL:** [https://www.here.com/docs/category/public-transit](https://www.here.com/docs/category/public-transit)
- **Base URL:** `https://transit.hereapi.com`

#### Tags

- Transit
- Public Transport
- Routing

#### Properties

- [Documentation](https://www.here.com/docs/category/public-transit)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Destination Weather API

Current conditions, forecasts, and severe weather alerts at a coordinate or destination, intended to enrich routing, ETAs, and travel planning.

- **Human URL:** [https://www.here.com/docs/category/destination-weather](https://www.here.com/docs/category/destination-weather)
- **Base URL:** `https://weather.hereapi.com`

#### Tags

- Weather
- Forecast
- REST API

#### Properties

- [Documentation](https://www.here.com/docs/category/destination-weather)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Map Tile API

Raster, vector, satellite, and hybrid map tiles served via tile and style endpoints, including the HERE Vector Tile API for client-side rendering.

- **Human URL:** [https://www.here.com/docs/category/map-tile-api-v3](https://www.here.com/docs/category/map-tile-api-v3)
- **Base URL:** `https://maps.hereapi.com`

#### Tags

- Tiles
- Rendering
- Maps

#### Properties

- [Documentation](https://www.here.com/docs/category/map-tile-api-v3)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Map Image API

Renders static map images for a given location, route, or geometry as PNG/JPEG, with markers and overlays.

- **Human URL:** [https://www.here.com/docs/category/map-image-api](https://www.here.com/docs/category/map-image-api)
- **Base URL:** `https://image.maps.hereapi.com`

#### Tags

- Static Map
- Image
- Rendering

#### Properties

- [Documentation](https://www.here.com/docs/category/map-image-api)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Tracking API

Asset tracking platform: ingests positions and telemetry from devices, manages devices and projects, and exposes geofencing, history, and events through REST.

- **Human URL:** [https://www.here.com/docs/category/tracking](https://www.here.com/docs/category/tracking)
- **Base URL:** `https://tracking.api.here.com`

#### Tags

- Tracking
- IoT
- Telematics

#### Properties

- [Documentation](https://www.here.com/docs/category/tracking)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Positioning API

High-precision indoor and outdoor positioning using Wi-Fi, cellular, and Bluetooth signals.

- **Human URL:** [https://www.here.com/docs/category/positioning](https://www.here.com/docs/category/positioning)
- **Base URL:** `https://positioning.hereapi.com`

#### Tags

- Positioning
- Indoor
- Wi-Fi

#### Properties

- [Documentation](https://www.here.com/docs/category/positioning)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Parking API

On-street and off-street parking availability, pricing, restrictions, and locations.

- **Human URL:** [https://www.here.com/docs/category/parking](https://www.here.com/docs/category/parking)
- **Base URL:** `https://parking.hereapi.com`

#### Tags

- Parking
- Mobility

#### Properties

- [Documentation](https://www.here.com/docs/category/parking)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Platform Data API

Catalog, layer, and partition APIs for hosting and accessing location-centric data products on the HERE Platform / Workspace.

- **Human URL:** [https://www.here.com/docs/category/data-api](https://www.here.com/docs/category/data-api)
- **Base URL:** `https://platform.here.com`

#### Tags

- Platform
- Data
- Workspace

#### Properties

- [Documentation](https://www.here.com/docs/category/data-api)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE HD Live Map

High-definition map product for automated driving with road geometry, lanes, signs, hazards, and dynamic updates, distributed via the HERE Platform.

- **Human URL:** [https://www.here.com/platform/automotive-services/hd-live-map](https://www.here.com/platform/automotive-services/hd-live-map)
- **Base URL:** `https://platform.here.com`

#### Tags

- HD Map
- Autonomous Driving
- Automotive

#### Properties

- [Documentation](https://www.here.com/platform/automotive-services/hd-live-map)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Maps API for JavaScript

Browser SDK for embedding interactive maps, routing, search, and traffic visualizations in web applications.

- **Human URL:** [https://www.here.com/docs/category/maps-api-for-javascript](https://www.here.com/docs/category/maps-api-for-javascript)
- **Base URL:** `https://js.api.here.com`

#### Tags

- JavaScript
- Web SDK
- Maps

#### Properties

- [Documentation](https://www.here.com/docs/category/maps-api-for-javascript)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE SDK for iOS

Native iOS SDK with maps, routing, search, navigation, and offline capabilities for mobile applications.

- **Human URL:** [https://www.here.com/docs/category/here-sdk-for-ios](https://www.here.com/docs/category/here-sdk-for-ios)
- **Base URL:** `https://www.here.com/docs/category/here-sdk-for-ios`

#### Tags

- iOS
- SDK
- Mobile

#### Properties

- [Documentation](https://www.here.com/docs/category/here-sdk-for-ios)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE SDK for Android

Native Android SDK with maps, routing, search, navigation, and offline capabilities for mobile applications.

- **Human URL:** [https://www.here.com/docs/category/here-sdk-for-android](https://www.here.com/docs/category/here-sdk-for-android)
- **Base URL:** `https://www.here.com/docs/category/here-sdk-for-android`

#### Tags

- Android
- SDK
- Mobile

#### Properties

- [Documentation](https://www.here.com/docs/category/here-sdk-for-android)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE SDK for Flutter

Flutter SDK wrapping HERE Mobile SDK capabilities for cross-platform mobile applications.

- **Human URL:** [https://www.here.com/docs/category/here-sdk-for-flutter](https://www.here.com/docs/category/here-sdk-for-flutter)
- **Base URL:** `https://www.here.com/docs/category/here-sdk-for-flutter`

#### Tags

- Flutter
- SDK
- Mobile

#### Properties

- [Documentation](https://www.here.com/docs/category/here-sdk-for-flutter)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HERE Studio

Web-based mapping studio for designing custom map styles, uploading and visualizing geospatial data, and publishing interactive map experiences on top of the HERE Platform.

- **Human URL:** [https://www.here.com/docs/category/studio](https://www.here.com/docs/category/studio)
- **Base URL:** `https://studio.here.com`

#### Tags

- Studio
- Cartography
- Visualization

#### Properties

- [Documentation](https://www.here.com/docs/category/studio)
- [Postman Collection](collections/here-technologies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/here-technologies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/here)
- [Website](https://www.here.com/)
- [Documentation](https://www.here.com/docs)
- [Git Hub](https://github.com/heremaps)
- [Plans](plans/here-technologies-plans-pricing.yml)
- [Rate Limits](rate-limits/here-technologies-rate-limits.yml)
- [Fin Ops](finops/here-technologies-finops.yml)
- [Integrations](https://www.here.com/platform)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
