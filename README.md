# Cognition Labs (cognition-labs)

Cognition Labs is the applied AI lab behind Devin, the autonomous AI software engineer that plans, writes, tests, and ships code inside its own shell, code editor, and browser. The Devin API lets teams create and drive Devin sessions programmatically - sending prompts and follow-up messages, attaching files, storing organizational knowledge and reusable playbooks, injecting secrets, and tracking Agent Compute Unit (ACU) consumption - across a legacy v1 surface, a v2 enterprise surface, and a current v3 organizations/enterprise surface built around service-user and personal access tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cognition-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cognition-labs/refs/heads/main/apis.yml)

## Tags

- AI
- AI Agent
- Autonomous Coding
- Software Engineering
- LLM
- Devin

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## APIs

### Devin Sessions API

Create a Devin session with a natural-language prompt and optional playbook, snapshot, knowledge, secrets, tags, and a max ACU cap; list sessions with filters; retrieve full session status and structured output; update tags; and terminate a running session.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/sessions/create-a-new-devin-session](https://docs.devin.ai/api-reference/v1/sessions/create-a-new-devin-session)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Sessions
- Agent
- Tasks

#### Properties

- [Documentation](https://docs.devin.ai/api-reference/overview)
- [API Reference](https://docs.devin.ai/api-reference/v1/sessions/create-a-new-devin-session)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Messages API

Send follow-up messages into a running Devin session to steer, correct, or add context to its work, and list the message history of a session. The session must be in a running state to receive a message; sending a message also wakes a sleeping session.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/sessions/send-a-message-to-an-existing-devin-session](https://docs.devin.ai/api-reference/v1/sessions/send-a-message-to-an-existing-devin-session)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Messages
- Sessions
- Conversational

#### Properties

- [API Reference](https://docs.devin.ai/api-reference/v1/sessions/send-a-message-to-an-existing-devin-session)
- [API Reference](https://docs.devin.ai/api-reference/v3/sessions/post-organizations-sessions-messages)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Attachments API

Upload files (multipart/form-data) for Devin to work with, receiving back a file URL that is referenced in a session prompt as `ATTACHMENT:"{file_url}"`, and download attachment files by ID.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/attachments/upload-files-for-devin-to-work-with](https://docs.devin.ai/api-reference/v1/attachments/upload-files-for-devin-to-work-with)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Attachments
- Files
- Uploads

#### Properties

- [API Reference](https://docs.devin.ai/api-reference/v1/attachments/upload-files-for-devin-to-work-with)
- [API Reference](https://docs.devin.ai/api-reference/v1/attachments/download-attachment-files)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Knowledge API

Create, list, update, and delete organization-level knowledge entries and folders - persistent notes with a trigger description that Devin automatically pulls into relevant sessions - plus enterprise-level knowledge notes on the v3 surface.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/knowledge/list-knowledge](https://docs.devin.ai/api-reference/v1/knowledge/list-knowledge)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Knowledge
- Context
- Organization

#### Properties

- [API Reference](https://docs.devin.ai/api-reference/v1/knowledge/list-knowledge)
- [API Reference](https://docs.devin.ai/api-reference/v1/knowledge/create-knowledge)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Playbooks API

Create, retrieve, list, update, and delete team playbooks - reusable, named instruction sets that seed new Devin sessions via a `playbook_id` so recurring tasks run the same way every time.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/playbooks/list-playbooks](https://docs.devin.ai/api-reference/v1/playbooks/list-playbooks)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Playbooks
- Workflows
- Automation

#### Properties

- [API Reference](https://docs.devin.ai/api-reference/v1/playbooks/list-playbooks)
- [API Reference](https://docs.devin.ai/api-reference/v1/playbooks/create-playbook)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Secrets API

Create, list, and delete organization secrets (cookie, key-value, dictionary, or TOTP types) that Devin can use inside sessions without exposing values back over the API; list responses return metadata only. Org-level secrets are also managed on the v3 surface.

- **Human URL:** [https://docs.devin.ai/api-reference/v1/secrets/list-secrets](https://docs.devin.ai/api-reference/v1/secrets/list-secrets)
- **Base URL:** `https://api.devin.ai/v1`

#### Tags

- Secrets
- Credentials
- Security

#### Properties

- [API Reference](https://docs.devin.ai/api-reference/v1/secrets/list-secrets)
- [API Reference](https://docs.devin.ai/api-reference/v1/secrets/create-secret)
- [Documentation](https://docs.devin.ai/admin/security)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Organizations API

Current (v3) organization-scoped surface at `/v3/organizations/{org_id}` - create and manage sessions with optional user attribution, list/invite/delete organization users, and reach the same knowledge, playbooks, and secrets resources under RBAC with service-user (`cog_`) or personal access tokens.

- **Human URL:** [https://docs.devin.ai/api-reference/v3/overview](https://docs.devin.ai/api-reference/v3/overview)
- **Base URL:** `https://api.devin.ai/v3`

#### Tags

- Organizations
- Users
- RBAC

#### Properties

- [Documentation](https://docs.devin.ai/api-reference/v3/overview)
- [Documentation](https://docs.devin.ai/api-reference/getting-started/teams-quickstart)
- [API Reference](https://docs.devin.ai/api-reference/v3/users/members-users)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Enterprise API

Cross-organization administration at `/v3/enterprise` and the v2 enterprise surface - create, list, update, and delete organizations and their members, provision and revoke service API keys, list/inspect sessions and their insights across every organization, and retrieve paginated audit logs.

- **Human URL:** [https://docs.devin.ai/api-reference/getting-started/enterprise-quickstart](https://docs.devin.ai/api-reference/getting-started/enterprise-quickstart)
- **Base URL:** `https://api.devin.ai/v3`

#### Tags

- Enterprise
- Admin
- Audit Logs

#### Properties

- [Documentation](https://docs.devin.ai/api-reference/getting-started/enterprise-quickstart)
- [API Reference](https://docs.devin.ai/api-reference/v2/organizations/list-organizations)
- [API Reference](https://docs.devin.ai/api-reference/v2/api-keys/list-enterprise-api-keys)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Devin Usage & Consumption API

Read enterprise- and session-level Agent Compute Unit (ACU) consumption - daily totals across an enterprise, per-organization and per-user daily consumption, and per-session usage/insights metrics - for chargeback, budgeting, and enforcing per-organization consumption caps.

- **Human URL:** [https://docs.devin.ai/admin/billing/usage](https://docs.devin.ai/admin/billing/usage)
- **Base URL:** `https://api.devin.ai/v3`

#### Tags

- Usage
- ACU
- Billing

#### Properties

- [Documentation](https://docs.devin.ai/admin/billing/usage)
- [Documentation](https://docs.devin.ai/admin/billing/enterprise)
- [API Reference](https://docs.devin.ai/api-reference/v3/consumption/consumption-daily)
- [OpenAPI](openapi/cognition-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cognition-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cognition-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CognitionAI)
- [LinkedIn](https://www.linkedin.com/company/cognition-ai-labs)
- [Website](https://cognition.ai/)
- [Documentation](https://docs.devin.ai)
- [Plans](plans/cognition-labs-plans-pricing.yml)
- [Rate Limits](rate-limits/cognition-labs-rate-limits.yml)
- [Fin Ops](finops/cognition-labs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

## Notes

Devin's API spans three overlapping generations of surface: a legacy **v1** API (`api.devin.ai/v1`, keys prefixed `apk_user_`/`apk_`) covering sessions, messages, attachments, knowledge, playbooks, and secrets; a **v2** enterprise API layered on top for organizations, members, API keys, and consumption; and the current **v3** API (`api.devin.ai/v3`, keys prefixed `cog_`) that re-platforms the same resources under `/v3/organizations/{org_id}` and `/v3/enterprise` with RBAC and pagination. All three generations remain live and documented as of this review. Every endpoint modeled here is read directly from Cognition's public documentation at [docs.devin.ai](https://docs.devin.ai); actually calling most of them requires an active paid Devin plan or Enterprise contract to obtain a service-user or personal access token, so nothing here was live-tested against production credentials.
