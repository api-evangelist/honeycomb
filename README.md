# Honeycomb (honeycomb)
Honeycomb is an observability platform designed to help engineering teams debug, understand, and optimize their production systems. Their developer platform provides a comprehensive REST API for programmatic access to event ingestion, querying, SLO management, alerting, and environment administration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/honeycomb/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Observability, Monitoring, Tracing, Debugging, Telemetry, Analytics, SLOs, Alerting

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-28

## APIs

### Honeycomb API
The Honeycomb API is a REST API that provides programmatic access to the Honeycomb observability platform. It enables developers to send events, manage datasets and columns, create and run queries, configure SLOs and burn alerts, set up triggers and recipients, manage boards and markers, and administer environments and API keys. The API covers the full range of Honeycomb platform capabilities including event ingestion, query execution, query annotations, calculated fields, marker settings, and reporting for long-term SLO performance analysis.

**Human URL:** [https://api-docs.honeycomb.io/api](https://api-docs.honeycomb.io/api)


#### Tags:

 - Observability, Monitoring, Tracing, Debugging, Telemetry

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api)

### Honeycomb Events API
The Honeycomb Events API is the lowest-level interface for sending event data to Honeycomb. It supports both single event creation and batch event submission, allowing developers to send structured telemetry data directly to Honeycomb datasets. While Honeycomb recommends using OpenTelemetry or Beeline SDKs for most instrumentation use cases, the Events API provides direct control for custom integrations and specialized data pipelines.

**Human URL:** [https://api-docs.honeycomb.io/api/events](https://api-docs.honeycomb.io/api/events)


#### Tags:

 - Observability, Events, Ingestion, Telemetry

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/events)

### Honeycomb Queries API
The Honeycomb Queries API allows developers to programmatically create and manage query specifications within Honeycomb. Queries are used to identify and reference queries across other parts of the API, including boards, triggers, and query annotations. Developers can run queries asynchronously by creating a Query Result that references a Query ID, then polling the query result endpoint until the data is ready. The Query Data API complements this by providing access to query results.

**Human URL:** [https://api-docs.honeycomb.io/api/queries](https://api-docs.honeycomb.io/api/queries)


#### Tags:

 - Observability, Queries, Analytics, Data Analysis

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/queries)

### Honeycomb SLOs API
The Honeycomb SLOs API enables developers to define and monitor Service Level Objectives programmatically. It supports creating, listing, updating, and deleting SLO objects for an organization. Combined with the Burn Alerts API for notifications and the Reporting API for historical SLO performance analysis, it provides a complete interface for managing reliability targets and tracking error budgets over time.

**Human URL:** [https://api-docs.honeycomb.io/api/slos](https://api-docs.honeycomb.io/api/slos)


#### Tags:

 - Observability, SLOs, Service Level Objectives, Reliability

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/slos)

### Honeycomb Datasets API
The Honeycomb Datasets API provides management capabilities for datasets, which represent collections of related events from the same source. It allows developers to list, create, and update datasets programmatically. The related Columns API enables management of fields within datasets, including listing, creating, updating, and deleting columns that define the structure of event data stored in Honeycomb.

**Human URL:** [https://api-docs.honeycomb.io/api/datasets](https://api-docs.honeycomb.io/api/datasets)


#### Tags:

 - Observability, Datasets, Data Management

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/datasets)

### Honeycomb Boards API
The Honeycomb Boards API allows developers to programmatically create and manage boards, which are collections of queries displayed together as a dashboard-like view. Boards provide a way to organize and share related queries for monitoring and debugging workflows. The API supports listing, creating, updating, and deleting boards, making it possible to automate the setup of observability dashboards across environments.

**Human URL:** [https://api-docs.honeycomb.io/api/boards](https://api-docs.honeycomb.io/api/boards)


#### Tags:

 - Observability, Dashboards, Visualization

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/boards)

### Honeycomb Markers API
The Honeycomb Markers API enables developers to create and manage markers that indicate points in time on graphs where notable events occurred, such as deploys, configuration changes, or outages. Marker Settings allow grouping similar markers together with consistent visual styling. The API supports listing, creating, updating, and deleting both markers and marker settings, making it straightforward to integrate deployment pipelines and incident workflows with Honeycomb visualizations.

**Human URL:** [https://api-docs.honeycomb.io/api/marker-settings](https://api-docs.honeycomb.io/api/marker-settings)


#### Tags:

 - Observability, Markers, Deployments, Annotations

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/marker-settings)

### Honeycomb Triggers API
The Honeycomb Triggers API allows developers to programmatically configure alerting rules that fire when query results meet specified conditions. Triggers work in conjunction with the Recipients API, which manages notification destinations including PagerDuty, Email, Webhook, Microsoft Teams, and Slack. The API supports listing, creating, updating, and deleting triggers, enabling automated setup of alerting workflows for production observability.

**Human URL:** [https://api-docs.honeycomb.io/api/triggers](https://api-docs.honeycomb.io/api/triggers)


#### Tags:

 - Observability, Alerts, Notifications, Monitoring

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/triggers)

### Honeycomb Environments API
The Honeycomb Environments API provides administrative capabilities for managing environments within a Honeycomb team. Environments allow organizations to separate telemetry data across different stages such as development, staging, and production. The API supports listing, creating, updating, and deleting environments, along with the Auth API for validating API keys and determining their associated team and environment permissions.

**Human URL:** [https://api-docs.honeycomb.io/api/environments](https://api-docs.honeycomb.io/api/environments)


#### Tags:

 - Observability, Environments, Administration

#### Properties

- [Documentation](https://api-docs.honeycomb.io/api/environments)

## Common Properties

- [Portal](https://api-docs.honeycomb.io/)
- [Documentation](https://docs.honeycomb.io/)
- [Website](https://www.honeycomb.io/)
- [PrivacyPolicy](https://www.honeycomb.io/privacy-policy)
- [TermsOfService](https://www.honeycomb.io/terms-of-service)
- [Support](https://support.honeycomb.io/)
- [Blog](https://www.honeycomb.io/blog)
- [Login](https://ui.honeycomb.io/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
