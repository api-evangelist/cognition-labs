# Cognition Labs

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cognition Labs is the applied AI lab behind Devin, the autonomous AI software engineer that plans, writes, tests, and ships code inside its own shell, code editor, and browser. The Devin API lets teams create and drive Devin sessions programmatically - sending prompts and follow-up messages, attaching files, storing organizational knowledge and reusable playbooks, injecting secrets, and tracking Agent Compute Unit (ACU) consumption - across a legacy v1 surface, a v2 enterprise surface, and a current v3 organizations/enterprise surface built around service-user and personal access tokens.

**Areas:** Artificial Intelligence · AI Agents · Autonomous Coding · Software Engineering · LLM · Devin

## Cognition Labs on APIs.io

Everything profiled for Cognition Labs is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cognition-labs/](https://apis.io/providers/cognition-labs/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Cognition Labs Attachments API](https://apis.io/apis/cognition-labs/cognition-labs-attachments-api/) — Upload and download files for Devin to work with.
- [Cognition Labs Consumption API](https://apis.io/apis/cognition-labs/cognition-labs-consumption-api/) — Agent Compute Unit (ACU) usage and billing metrics.
- [Cognition Labs Enterprise (v3) API](https://apis.io/apis/cognition-labs/cognition-labs-enterprise-v3-api/) — Cross-organization administration.
- [Cognition Labs Knowledge API](https://apis.io/apis/cognition-labs/cognition-labs-knowledge-api/) — Organization knowledge entries and folders.
- [Cognition Labs Messages API](https://apis.io/apis/cognition-labs/cognition-labs-messages-api/) — Send and read messages within a running session.
- [Cognition Labs Organizations (v3) API](https://apis.io/apis/cognition-labs/cognition-labs-organizations-v3-api/) — Current org-scoped session and user management.
- [Cognition Labs Playbooks API](https://apis.io/apis/cognition-labs/cognition-labs-playbooks-api/) — Reusable team playbooks that seed new sessions.
- [Cognition Labs Secrets API](https://apis.io/apis/cognition-labs/cognition-labs-secrets-api/) — Encrypted credentials Devin can use inside sessions.
- [Cognition Labs Sessions API](https://apis.io/apis/cognition-labs/cognition-labs-sessions-api/) — Create and manage Devin sessions (v1 legacy surface).
- [Cognition Labs Enterprise API](https://apis.io/apis/cognition-labs/cognition-labs-enterprise-api/) — Operations for enterprise-specific features and reporting
- [Cognition Labs Audit Logs API](https://apis.io/apis/cognition-labs/cognition-labs-audit-logs-api/) — Operations for managing audit logs

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cognition Labs Agentic Access](https://apis.io/agentic-access/cognition-labs/cognition-labs-agentic-access/)

#### JSON Schema (11)

The data models the API reads and writes.

- [CreateSessionInput](https://apis.io/schemas/cognition-labs/cognition-labs-create-session-input/)
- [CreateSessionResponse](https://apis.io/schemas/cognition-labs/cognition-labs-create-session-response/)
- [KnowledgeEntry](https://apis.io/schemas/cognition-labs/cognition-labs-knowledge-entry/)
- [KnowledgeFolder](https://apis.io/schemas/cognition-labs/cognition-labs-knowledge-folder/)
- [KnowledgeInput](https://apis.io/schemas/cognition-labs/cognition-labs-knowledge-input/)
- [Playbook](https://apis.io/schemas/cognition-labs/cognition-labs-playbook/)
- [PlaybookInput](https://apis.io/schemas/cognition-labs/cognition-labs-playbook-input/)
- [SecretInput](https://apis.io/schemas/cognition-labs/cognition-labs-secret-input/)
- [SecretMetadata](https://apis.io/schemas/cognition-labs/cognition-labs-secret-metadata/)
- [SessionDetail](https://apis.io/schemas/cognition-labs/cognition-labs-session-detail/)
- [SessionSummary](https://apis.io/schemas/cognition-labs/cognition-labs-session-summary/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cognition Labs Context](https://apis.io/jsonld/cognition-labs/cognition-labs-context/)

#### Collections (10)

Postman and Open Collection request collections.

- [Devin API (Cognition Labs)](https://apis.io/collections/cognition-labs/open-cognition-labs/)
- [Devin API (Cognition Labs) Attachments API](https://apis.io/collections/cognition-labs/open-cognition-labs-attachments-api/)
- [Devin API (Cognition Labs) Attachments Consumption API](https://apis.io/collections/cognition-labs/open-cognition-labs-consumption-api/)
- [Devin API (Cognition Labs) Attachments Enterprise (v3) API](https://apis.io/collections/cognition-labs/open-cognition-labs-enterprise-v3-api/)
- [Devin API (Cognition Labs) Attachments Knowledge API](https://apis.io/collections/cognition-labs/open-cognition-labs-knowledge-api/)
- [Devin API (Cognition Labs) Attachments Messages API](https://apis.io/collections/cognition-labs/open-cognition-labs-messages-api/)
- [Devin API (Cognition Labs) Attachments Organizations (v3) API](https://apis.io/collections/cognition-labs/open-cognition-labs-organizations-v3-api/)
- [Devin API (Cognition Labs) Attachments Playbooks API](https://apis.io/collections/cognition-labs/open-cognition-labs-playbooks-api/)
- [Devin API (Cognition Labs) Attachments Secrets API](https://apis.io/collections/cognition-labs/open-cognition-labs-secrets-api/)
- [Devin API (Cognition Labs) Attachments Sessions API](https://apis.io/collections/cognition-labs/open-cognition-labs-sessions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cognition Labs API Rules](https://apis.io/rules/cognition-labs/cognition-labs-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Cognition Labs Authentication](https://apis.io/security/cognition-labs/cognition-labs-authentication/)
- [Cognition Labs Domain Security](https://apis.io/security/cognition-labs/cognition-labs-domain-security/)
- [Cognition Labs Trust Center](https://apis.io/security/cognition-labs/cognition-labs-trust-center/)
- [Cognition Labs Vulnerability Disclosure](https://apis.io/security/cognition-labs/cognition-labs-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cognition Labs Plans Pricing](https://apis.io/plans/cognition-labs/cognition-labs-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cognition Labs Rate Limits](https://apis.io/rate-limits/cognition-labs/cognition-labs-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cognition Labs Finops](https://apis.io/finops/cognition-labs/cognition-labs-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cognition.ai/)
- [Documentation](https://docs.devin.ai)
- [Getting started](https://docs.devin.ai/tutorial-library/repo-setup)
- [API reference](https://docs.devin.ai/llms.txt)
- [Blog](https://cognition.com/blog)
- [Security](https://cognition.com/legal/security)
- [Compliance](https://trust.cognition.ai/)
- [Privacy policy](https://cognition.com/legal/privacy-policy)
- [GitHub](https://github.com/CognitionAI)

## API Evangelist rating

**Kin Score 52.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 68.3 |
| Contract governance | 35.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 53.0 |
| Access clarity | 34.2 |

**Agent readiness 34.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 29.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cognition-labs/](https://apis.io/providers/cognition-labs/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cognition Labs: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cognition-labs/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
