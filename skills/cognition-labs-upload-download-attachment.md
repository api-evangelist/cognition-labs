---
name: cognition-labs-upload-download-attachment
description: Upload a file to Devin and then retrieve it.
api: openapi/cognition-labs-attachments-api-openapi.yml
operations:
- uploadAttachment
- downloadAttachment
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cognition-labs-attachments-api-openapi.yml ; every operationId checked against the contract
---

# cognition-labs-upload-download-attachment

Upload a file to Devin and then retrieve it.

## Steps

1. 1. Call `uploadAttachment` with the file payload in the request body and include the `Authorization: Bearer <token>` header.
2. 2. Call `downloadAttachment` with the `attachment_id` path parameter returned from the upload step and include the `Authorization: Bearer <token>` header.

## Rules

- Include an `Authorization: Bearer <token>` header for both operations (bearerAuth).
