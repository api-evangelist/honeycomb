---
name: honeycomb-create-and-list-boards
description: Create a new board and then retrieve the list of all boards.
api: openapi/honeycomb-boards-api-openapi.yml
operations:
- createBoard
- listBoards
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/honeycomb-boards-api-openapi.yml ; every operationId checked against the contract
---

# honeycomb-create-and-list-boards

Create a new board and then retrieve the list of all boards.

## Steps

1. 1. Call `createBoard` with the request body containing the board properties and include the header `X-Honeycomb-Team` for authentication.
2. 2. Call `listBoards` with optional query parameters `page[size]` and `page[after]` to paginate through the boards, also including the header `X-Honeycomb-Team`.

## Rules

- Auth: Include the `X-Honeycomb-Team` header with your API key (ApiKeyAuth).
- Pagination: Use `page[size]` to set page size and `page[after]` for cursor-based pagination on `listBoards`.
