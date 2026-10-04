---
name: cognition-labs-manage-playbooks
description: Create a new playbook, retrieve it, and optionally list all playbooks.
api: openapi/cognition-labs-playbooks-api-openapi.yml
operations:
- createPlaybook
- getPlaybook
- listPlaybooks
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/cognition-labs-playbooks-api-openapi.yml ; every operationId checked against the contract
---

# cognition-labs-manage-playbooks

Create a new playbook, retrieve it, and optionally list all playbooks.

## Steps

1. 1. Use `createPlaybook` with the request body fields required to define the playbook.
2. 2. Use `getPlaybook` with the `playbook_id` returned from the create step.
3. 3. (Optional) Use `listPlaybooks` to view all team playbooks.

## Rules

- Include an `Authorization: Bearer <token>` header (bearerAuth).
- All write operations (`createPlaybook`, `updatePlaybook`, `deletePlaybook`) are idempotent when the same payload and `playbook_id` are used.
