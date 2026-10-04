---
name: honeycomb-send-events
description: Send one or multiple events to a Honeycomb dataset.
api: openapi/honeycomb-events-api-openapi.yml
operations:
- createEvent
- createEvents
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/honeycomb-events-api-openapi.yml ; every operationId checked against the contract
---

# honeycomb-send-events

Send one or multiple events to a Honeycomb dataset.

## Steps

1. 1. Use `createEvent` with header `X-Honeycomb-Team` and the event payload fields required by the API.
2. 2. Use `createEvents` with header `X-Honeycomb-Team` and a batch payload of event objects.

## Rules

- Auth: Include the API key in the `X-Honeycomb-Team` header (ApiKeyAuth).
- Rate limiting: No explicit limit; on exhaustion the API returns no specific HTTP status.
