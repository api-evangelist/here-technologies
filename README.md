# HERE Technologies (here-technologies)

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
