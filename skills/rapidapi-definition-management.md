---
name: rapidapi-definition-management
description: Manage project definitions by importing, listing, retrieving, exporting, and deleting them.
api: openapi/rapidapi-definitions-api-openapi.yml
operations:
- importDefinition
- listDefinitions
- getDefinition
- exportDefinition
- deleteDefinition
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/rapidapi-definitions-api-openapi.yml ; every operationId checked against the contract
---

# rapidapi-definition-management

Manage project definitions by importing, listing, retrieving, exporting, and deleting them.

## Steps

1. 1. Use `importDefinition` with the request body containing the definition payload and header `X-RapidAPI-Key` (or `X-RapidAPI-Identity-Key`).
2. 2. Use `listDefinitions` with path parameter `projectId` and optional query parameters for pagination if supported.
3. 3. Use `getDefinition` with path parameters `projectId` and `definitionId` to retrieve a specific definition.
4. 4. Use `exportDefinition` with path parameters `projectId` and `definitionId` to download the definition file.
5. 5. Use `deleteDefinition` with path parameters `projectId` and `definitionId` to remove the definition.

## Rules

- Include either `X-RapidAPI-Key` or `X-RapidAPI-Identity-Key` header for authentication on every request.
- All write operations (`importDefinition`, `deleteDefinition`) are idempotent when the same definition ID is used.
