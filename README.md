# honeycomb (honeycomb)

Build integrations and automate workflows with the Honeycomb API. Programmatically manage datasets, queries, triggers, SLOs, environments, API keys, and more.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-30

## APIs

### Honeycomb API

The Honeycomb API is a REST API that provides programmatic access to the Honeycomb observability platform. It enables developers to send events, manage datasets and columns, create and run queries, configure SLOs and burn alerts, set up triggers and recipients, manage boards and markers, and administer environments and API keys.

- **Human URL:** [https://api-docs.honeycomb.io/api](https://api-docs.honeycomb.io/api)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Debugging
- Monitoring
- Observability
- Telemetry
- Tracing

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api)
- [OpenAPI](openapi/honeycomb-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb Events API

The Honeycomb Events API is the lowest-level interface for sending event data to Honeycomb. It supports both single event creation and batch event submission, allowing developers to send structured telemetry data directly to Honeycomb datasets. While Honeycomb recommends using OpenTelemetry or Beeline SDKs for most instrumentation use cases, the Events API provides direct control for custom integrations and specialized data pipelines.

- **Human URL:** [https://api-docs.honeycomb.io/api/events](https://api-docs.honeycomb.io/api/events)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Events
- Ingestion
- Observability
- Telemetry

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/events)
- [OpenAPI](openapi/honeycomb-events-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/honeycomb-streaming-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Honeycomb Queries API

The Honeycomb Queries API allows developers to programmatically create and manage query specifications within Honeycomb. Queries are used to identify and reference queries across other parts of the API, including boards, triggers, and query annotations. Developers can run queries asynchronously by creating a Query Result that references a Query ID, then polling the query result endpoint until the data is ready. The Query Data API complements this by providing access to query results.

- **Human URL:** [https://api-docs.honeycomb.io/api/queries](https://api-docs.honeycomb.io/api/queries)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Analytics
- Data Analysis
- Observability
- Queries

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/queries)
- [OpenAPI](openapi/honeycomb-queries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-queries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-queries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb SLOs API

The Honeycomb SLOs API enables developers to define and monitor Service Level Objectives programmatically. It supports creating, listing, updating, and deleting SLO objects for an organization. Combined with the Burn Alerts API for notifications and the Reporting API for historical SLO performance analysis, it provides a complete interface for managing reliability targets and tracking error budgets over time.

- **Human URL:** [https://api-docs.honeycomb.io/api/slos](https://api-docs.honeycomb.io/api/slos)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Observability
- Reliability
- Service Level Objectives
- SLOs

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/slos)
- [OpenAPI](openapi/honeycomb-slos-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-slos-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-slos-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb Datasets API

The Honeycomb Datasets API provides management capabilities for datasets, which represent collections of related events from the same source. It allows developers to list, create, and update datasets programmatically. The related Columns API enables management of fields within datasets, including listing, creating, updating, and deleting columns that define the structure of event data stored in Honeycomb.

- **Human URL:** [https://api-docs.honeycomb.io/api/datasets](https://api-docs.honeycomb.io/api/datasets)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Data Management
- Datasets
- Observability

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/datasets)
- [OpenAPI](openapi/honeycomb-datasets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-datasets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-datasets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb Boards API

The Honeycomb Boards API allows developers to programmatically create and manage boards, which are collections of queries displayed together as a dashboard-like view. Boards provide a way to organize and share related queries for monitoring and debugging workflows. The API supports listing, creating, updating, and deleting boards, making it possible to automate the setup of observability dashboards across environments.

- **Human URL:** [https://api-docs.honeycomb.io/api/boards](https://api-docs.honeycomb.io/api/boards)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Dashboards
- Observability
- Visualization

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/boards)
- [OpenAPI](openapi/honeycomb-boards-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-boards-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-boards-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb Markers API

The Honeycomb Markers API enables developers to create and manage markers that indicate points in time on graphs where notable events occurred, such as deploys, configuration changes, or outages. Marker Settings allow grouping similar markers together with consistent visual styling. The API supports listing, creating, updating, and deleting both markers and marker settings, making it straightforward to integrate deployment pipelines and incident workflows with Honeycomb visualizations.

- **Human URL:** [https://api-docs.honeycomb.io/api/marker-settings](https://api-docs.honeycomb.io/api/marker-settings)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Annotations
- Deployments
- Markers
- Observability

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/marker-settings)
- [OpenAPI](openapi/honeycomb-markers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-markers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-markers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeycomb Triggers API

The Honeycomb Triggers API allows developers to programmatically configure alerting rules that fire when query results meet specified conditions. Triggers work in conjunction with the Recipients API, which manages notification destinations including PagerDuty, Email, Webhook, Microsoft Teams, and Slack. The API supports listing, creating, updating, and deleting triggers, enabling automated setup of alerting workflows for production observability.

- **Human URL:** [https://api-docs.honeycomb.io/api/triggers](https://api-docs.honeycomb.io/api/triggers)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Alerts
- Monitoring
- Notifications
- Observability

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/triggers)
- [OpenAPI](openapi/honeycomb-triggers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/honeycomb-streaming-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Honeycomb Environments API

The Honeycomb Environments API provides administrative capabilities for managing environments within a Honeycomb team. Environments allow organizations to separate telemetry data across different stages such as development, staging, and production. The API supports listing, creating, updating, and deleting environments, along with the Auth API for validating API keys and determining their associated team and environment permissions.

- **Human URL:** [https://api-docs.honeycomb.io/api/environments](https://api-docs.honeycomb.io/api/environments)
- **Base URL:** `https://api.honeycomb.io`

#### Tags

- Administration
- Environments
- Observability

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/environments)
- [OpenAPI](openapi/honeycomb-environments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/honeycomb-environments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeycomb-environments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/honeycombio)
- [JSON-LD](json-ld/honeycomb-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/honeycomb-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/honeycomb-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/honeycomb-slo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/honeycomb-trigger-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [Integrations](https://docs.honeycomb.io/integrations)
- [L L Ms Txt](https://docs.honeycomb.io/llms.txt)
