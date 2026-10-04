---
name: cognition-labs-create-use-terminate-session
description: Create a Devin session, view it, retrieve its details, and then terminate it.
api: openapi/cognition-labs-sessions-api-openapi.yml
operations:
- createSession
- listSessions
- getSession
- terminateSession
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cognition-labs-sessions-api-openapi.yml ; every operationId checked against the contract
---

# cognition-labs-create-use-terminate-session

Create a Devin session, view it, retrieve its details, and then terminate it.

## Steps

1. 1. Call `createSession` – send a POST to /sessions with the request body containing the session parameters (as defined by the API) and include the `Authorization: Bearer <token>` header.
2. 2. Call `listSessions` – send a GET to /sessions with the `Authorization` header to view existing sessions.
3. 3. Call `getSession` – send a GET to /sessions/{session_id} with the `Authorization` header and the path parameter `session_id` obtained from the previous steps.
4. 4. Call `terminateSession` – send a DELETE to /sessions/{session_id} with the `Authorization` header and the same `session_id` to end the session.

## Rules

- All requests require the `Authorization: Bearer <token>` header (bearerAuth).
- No idempotency key is required for these operations.
- Rate limiting is not defined; the API does not specify a limit or specific HTTP status for exhaustion.
