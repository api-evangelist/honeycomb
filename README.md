# honeycomb (honeycomb)

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
