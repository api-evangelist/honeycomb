---
name: honeycomb-create-and-retrieve-query
description: Create a new query in a dataset and then retrieve it by its ID.
api: openapi/honeycomb-queries-api-openapi.yml
operations:
- createQuery
- getQuery
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/honeycomb-queries-api-openapi.yml ; every operationId checked against the contract
---

# honeycomb-create-and-retrieve-query

Create a new query in a dataset and then retrieve it by its ID.

## Steps

1. 1. Call `createQuery` with the required header `X-Honeycomb-Team` (ApiKeyAuth) and provide the dataset slug in the path `{datasetSlug}` and the query definition in the request body.
2. 2. Call `getQuery` with the required header `X-Honeycomb-Team` (ApiKeyAuth) and provide the dataset slug `{datasetSlug}` and the returned `queryId` from step 1 in the path.

## Rules

- Auth: Include the API key in the `X-Honeycomb-Team` header for both calls.
- Path parameters: `datasetSlug` is required for both operations; `queryId` is required for `getQuery`.
- No pagination is needed for these operations.
- Rate limiting: No explicit limit; on exhaustion the API returns no specific HTTP status.
