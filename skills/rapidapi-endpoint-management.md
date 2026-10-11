---
name: rapidapi-endpoint-management
description: Create, view, modify, and remove endpoints for a project.
api: openapi/rapidapi-endpoints-api-openapi.yml
operations:
- createEndpoint
- listEndpoints
- updateEndpoint
- deleteEndpoint
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/rapidapi-endpoints-api-openapi.yml ; every operationId checked against the contract
---

# rapidapi-endpoint-management

Create, view, modify, and remove endpoints for a project.

## Steps

1. 1. Use `createEndpoint` with the required request body fields and the authentication header `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`).
2. 2. Use `listEndpoints` with the path parameter `projectId` and the authentication header.
3. 3. Use `updateEndpoint` with path parameters `projectId` and `endpointId`, the request body fields to modify, and the authentication header.
4. 4. Use `deleteEndpoint` with path parameters `projectId` and `endpointId` and the authentication header.

## Rules

- Authentication: include either `X-RapidAPI-Key` or `X-RapidAPI-Identity-Key` header in every request.
- Idempotency: `createEndpoint` and `updateEndpoint` are not idempotent; repeat calls may create duplicate resources.
- No pagination is defined for `listEndpoints`.
- Rate limit: none defined; no specific HTTP status for exhaustion.
