# Adobe Analytics (adobe-analytics)

Adobe Analytics provides real-time analytics and detailed segmentation capabilities across all marketing channels, enabling organizations to discover high-value audiences and power customer intelligence.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/apis.yml)

## Tags

- Adobe
- Analytics
- Business Intelligence
- Customer Intelligence
- Digital Marketing
- Marketing
- Web Analytics

## Timestamps

- **Created:** Sun Dec 31 2023 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** 2026-05-19

## APIs

### Adobe Analytics API

The Adobe Analytics 2.0 APIs provide programmatic access to data, reports, and administration features within Adobe Analytics. They allow you to perform almost any action available in the Analytics user interface, including reporting, segment management, calculated metrics, and component administration.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/](https://developer.adobe.com/analytics-apis/docs/2.0/)

#### Tags

- Analytics
- Data
- Marketing
- Metrics
- Reporting

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/)
- [API Reference](https://developer.adobe.com/analytics-apis/docs/2.0/apis/)
- [OpenAPI](https://raw.githubusercontent.com/AdobeDocs/analytics-2.0-apis/main/docs/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/adobe-analytics-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/)
- [Getting Started](https://developer.adobe.com/analytics-apis/docs/2.0/guides/)
- [Rate Limits](https://developer.adobe.com/analytics-apis/docs/2.0/guides/rate-limits/)
- [Getting Started](https://developer.adobe.com/analytics-apis/docs/2.0/guides/migration/)
- [GitHub Repository](https://github.com/AdobeDocs/analytics-2.0-apis)

### Adobe Analytics Bulk Data Insertion API

The Bulk Data Insertion API (BDIA) lets you upload server-side call data in batches of compressed CSV files instead of using client-side libraries such as AppMeasurement. It is the recommended successor to the single-event Data Insertion API for high-volume server-side data collection.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/bulk-data-insertion/](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/bulk-data-insertion/)

#### Tags

- Analytics
- Batch Processing
- Data Collection
- Server-Side

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/bulk-data-insertion/)
- [API Reference](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/bulk-data-insertion/endpoints/)
- [OpenAPI](openapi/adobe-analytics-bulk-data-insertion-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-analytics-bulk-data-insertion-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-bulk-data-insertion-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/)

### Adobe Analytics Livestream API

The Livestream API is a reporting feature in Adobe Analytics that allows clients to receive traffic data processed by Adobe Analytics in real time. Hits are streamed to the client on a hit-by-hit basis in the same order and rate that they are processed by Adobe servers.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/livestream/](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/livestream/)

#### Tags

- Analytics
- Data
- Real-Time
- Streaming

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/livestream/)
- [API Reference](https://developer.adobe.com/analytics-apis/docs/2.0/apis/livestream/)
- [AsyncAPI](asyncapi/adobe-analytics-livestream-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Authentication](https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/)
- [Changelog](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/livestream/release-notes/)
- [Postman Collection](collections/adobe-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-bulk-data-insertion-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-bulk-data-insertion-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-data-repair-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-data-repair-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Analytics Data Repair API

The Data Repair API allows you to permanently delete or transform data that has already been ingested in Adobe Analytics. It provides endpoints for estimating repair scope, creating repair jobs, and monitoring job status. This is a paid feature and Adobe recommends a careful, staged approach when using it.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/data-repair/](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/data-repair/)

#### Tags

- Analytics
- Compliance
- Data Management
- Privacy

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/guides/endpoints/data-repair/)
- [API Reference](https://developer.adobe.com/analytics-apis/docs/2.0/apis/data-repair/)
- [OpenAPI](openapi/adobe-analytics-data-repair-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-analytics-data-repair-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-data-repair-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/)

### Adobe Analytics Data Insertion API

The Data Insertion API allows server-side data submission to Adobe Analytics one event at a time using HTTP GET or POST requests. Unlike the Bulk Data Insertion API which processes compressed CSV files in batches, this API handles individual hit submissions in real time and is explicitly excluded from the Analytics 1.4 API end-of-life scheduled for August 12, 2026.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/1.4/guides/data-insertion/](https://developer.adobe.com/analytics-apis/docs/1.4/guides/data-insertion/)

#### Tags

- Analytics
- Data Collection
- Real-Time
- Server-Side

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/1.4/guides/data-insertion/)
- [API Reference](https://experienceleague.adobe.com/en/docs/analytics/import/c-data-insertion-api)
- [Postman Collection](collections/adobe-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-bulk-data-insertion-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-bulk-data-insertion-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-data-repair-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-data-repair-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Analytics 1.4 API

The Adobe Analytics 1.4 APIs provide programmatic access to reporting, classifications, data sources, and report suite configuration. This version is deprecated and scheduled for end-of-life on August 12, 2026, after which all endpoints will cease to function. The Data Insertion API is excluded from this end-of-life.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/1.4/](https://developer.adobe.com/analytics-apis/docs/1.4/)

#### Tags

- Analytics
- Deprecated
- Legacy
- Reporting

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/1.4/)
- [Release Notes](https://developer.adobe.com/analytics-apis/docs/1.4/guides/eol/)
- [Getting Started](https://developer.adobe.com/analytics-apis/docs/2.0/guides/migration/)
- [GitHub Repository](https://github.com/AdobeDocs/analytics-1.4-apis)
- [Postman Collection](collections/adobe-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-bulk-data-insertion-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-bulk-data-insertion-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-analytics-data-repair-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-analytics-data-repair-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.adobe.com/analytics-apis/docs/2.0/)
- [Documentation](https://experienceleague.adobe.com/docs/analytics.html)
- [Getting Started](https://developer.adobe.com/analytics-apis/docs/2.0/guides/)
- [Console](https://developer.adobe.com/console/)
- [Authentication](https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/)
- [Support](https://developer.adobe.com/analytics-apis/docs/2.0/support/)
- [Support](https://experienceleaguecommunities.adobe.com/t5/adobe-analytics/ct-p/adobe-analytics-community)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/adobe-analytics)
- [GitHub Organization](https://github.com/AdobeDocs)
- [Changelog](https://experienceleague.adobe.com/en/docs/analytics/release-notes/latest)
- [Terms of Service](https://www.adobe.com/legal/terms.html)
- [Privacy Policy](https://www.adobe.com/privacy/policy.html)
- [Status Page](https://status.adobe.com/)
- [Blog](https://blog.adobe.com/en/topics/analytics)
- [GitHub Repository](https://github.com/AdobeDocs/analytics-2.0-apis)
- [JSON Schema](json-schema/adobe-analytics-report-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/adobe-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [GitHub Repository](https://github.com/AdobeDocs/analytics-mcp)
- [GitHub Repository](https://github.com/AdobeDocs/analytics-1.4-apis)
- [Training](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/overview.html)
- [JSON-LD](json-ld/adobe-analytics-bulk-data-insertion-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/adobe-analytics-data-repair-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/adobe-analytics-spectral-rules.yml)
- [Vocabulary](vocabulary/adobe-analytics-vocabulary.yaml)

## Maintainers

**Email:** kin@apievangelist.com
