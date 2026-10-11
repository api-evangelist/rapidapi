---
name: rapidapi-manage-routes
description: Create, view, modify, and delete routes for a specific gateway.
api: openapi/rapidapi-routes-api-openapi.yml
operations:
- createRoute
- listRoutes
- updateRoute
- deleteRoute
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/rapidapi-routes-api-openapi.yml ; every operationId checked against the contract
---

# rapidapi-manage-routes

Create, view, modify, and delete routes for a specific gateway.

## Steps

1. 1. Use `createRoute` with required fields in the request body and header `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`).
2. 2. Use `listRoutes` with path parameter `gatewayId` and optional query parameters for pagination if supported.
3. 3. Use `updateRoute` with path parameters `gatewayId` and `routeId`, providing updated fields in the request body.
4. 4. Use `deleteRoute` with path parameters `gatewayId` and `routeId`.

## Rules

- Include an authentication header: either `X-RapidAPI-Key` or `X-RapidAPI-Identity-Key` as defined by the rapidApiKey or rapidApiIdentityKey schemes.
- All write operations (`createRoute`, `updateRoute`, `deleteRoute`) are idempotent when the same request payload and identifiers are used.
