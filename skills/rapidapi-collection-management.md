---
name: rapidapi-collection-management
description: Create, view, update, list APIs in, and delete a curated collection.
api: openapi/rapidapi-collections-api-openapi.yml
operations:
- createCollection
- getCollection
- updateCollection
- listApisInCollection
- deleteCollection
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/rapidapi-collections-api-openapi.yml ; every operationId checked against the contract
---

# rapidapi-collection-management

Create, view, update, list APIs in, and delete a curated collection.

## Steps

1. 1. `createCollection` – include required body fields for the new collection and send the `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`) header.
2. 2. `getCollection` – provide the `collectionId` path parameter and include the `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`) header.
3. 3. `updateCollection` – supply the `collectionId` path parameter, the update payload in the request body, and the `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`) header.
4. 4. `listApisInCollection` – specify the `collectionId` path parameter and send the `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`) header.
5. 5. `deleteCollection` – provide the `collectionId` path parameter and include the `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`) header.

## Rules

- Authentication: All requests must include either the `X-RapidAPI-Key` or `X-RapidAPI-Identity-Key` header as defined by the rapidApiKey or rapidApiIdentityKey schemes.
- Idempotency: DELETE `/collections/{collectionId}` is idempotent; repeated calls with the same `collectionId` will return the same result.
- Rate limiting: No rate limit is defined; on exhaustion the API returns no specific HTTP status.
