---
name: honeycomb-create-and-retrieve-dataset
description: Create a new dataset and then retrieve its details.
api: openapi/honeycomb-datasets-api-openapi.yml
operations:
- createDataset
- getDataset
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/honeycomb-datasets-api-openapi.yml ; every operationId checked against the contract
---

# honeycomb-create-and-retrieve-dataset

Create a new dataset and then retrieve its details.

## Steps

1. 1. Use `createDataset` with the request body fields required for dataset creation.
2. 2. Use `getDataset` with the path parameter `datasetSlug` returned from the creation step.

## Rules

- Auth: Include the API key in header `X-Honeycomb-Team` (ApiKeyAuth).
- Pagination (for list operations): query parameters `page[size]` and `page[after]`.
