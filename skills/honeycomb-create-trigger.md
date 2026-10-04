---
name: honeycomb-create-trigger
description: Create a new trigger and verify its creation.
api: openapi/honeycomb-triggers-api-openapi.yml
operations:
- createTrigger
- getTrigger
- listTriggers
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/honeycomb-triggers-api-openapi.yml ; every operationId checked against the contract
---

# honeycomb-create-trigger

Create a new trigger and verify its creation.

## Steps

1. 1. `createTrigger` – requires header `X-Honeycomb-Team` and request body with trigger details.
2. 2. `getTrigger` – requires header `X-Honeycomb-Team` and path parameters `datasetSlug`, `triggerId`.
3. 3. `listTriggers` – requires header `X-Honeycomb-Team` and query parameters `page[size]`, `page[after]`.

## Rules

- Auth: include API key in header `X-Honeycomb-Team`.
- Pagination: use `page[size]` and `page[after]` query parameters for listing triggers.
