---
name: cognition-labs-manage-knowledge
description: Create, view, modify, and delete knowledge entries and folders.
api: openapi/cognition-labs-knowledge-api-openapi.yml
operations:
- listKnowledge
- createKnowledge
- updateKnowledge
- deleteKnowledge
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cognition-labs-knowledge-api-openapi.yml ; every operationId checked against the contract
---

# cognition-labs-manage-knowledge

Create, view, modify, and delete knowledge entries and folders.

## Steps

1. 1. `listKnowledge` – send a GET request to `/knowledge` with the `Authorization: Bearer <token>` header.
2. 2. `createKnowledge` – send a POST request to `/knowledge` with the `Authorization: Bearer <token>` header and the required request body fields for a knowledge entry.
3. 3. `updateKnowledge` – send a PUT request to `/knowledge/{knowledge_id}` with the `Authorization: Bearer <token>` header and the fields to update in the request body.
4. 4. `deleteKnowledge` – send a DELETE request to `/knowledge/{knowledge_id}` with the `Authorization: Bearer <token>` header.

## Rules

- Include an `Authorization: Bearer <token>` header for all requests.
