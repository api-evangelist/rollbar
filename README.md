# Rollbar

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

Rollbar is a real-time error tracking and monitoring platform for software teams. It automatically captures exceptions and errors from web, mobile, and server-side applications, groups them by root cause, and provides actionable alerts to speed up debugging. Rollbar provides SDKs for over a dozen platforms including JavaScript, Python, PHP, Ruby, Go, Swift, .NET, and Java. The REST API enables programmatic management of projects, items, occurrences, deployments, teams, notifications, and source maps. The RQL (Rollbar Query Language) provides SQL-like queries for error analysis.

**Areas:** Error Tracking · Monitoring · Debugging · DevOps · Application Performance · Developer Tools

## Rollbar on APIs.io

Everything profiled for Rollbar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rollbar/](https://apis.io/providers/rollbar/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Rollbar Webhooks](https://apis.io/apis/rollbar/rollbar-webhooks/) — Rollbar supports outbound webhook notifications for real-time event-driven integrations. Webhooks deliver payload data when errors occur, items are…
- [Rollbar Access Tokens API](https://apis.io/apis/rollbar/rollbar-access-tokens-api/) — Manage project access tokens used for authentication and authorization when interacting with the API.
- [Rollbar Deploys API](https://apis.io/apis/rollbar/rollbar-deploys-api/) — Manage deployment records in Rollbar. Report new deploys, update their status, and retrieve deployment history for a project.
- [Rollbar Invites API](https://apis.io/apis/rollbar/rollbar-invites-api/) — Manage invitations to join teams within a Rollbar account.
- [Rollbar Items API](https://apis.io/apis/rollbar/rollbar-items-api/) — Manage error and message items tracked by Rollbar. Items represent unique errors or messages grouped by fingerprint.
- [Rollbar Items Metrics API](https://apis.io/apis/rollbar/rollbar-items-metrics-api/) — Query metrics for specific items including occurrence counts and aggregate statistics.
- [Rollbar Notifications API](https://apis.io/apis/rollbar/rollbar-notifications-api/) — Manage webhook notification rules and configuration for a project.
- [Rollbar Occurrences API](https://apis.io/apis/rollbar/rollbar-occurrences-api/) — Retrieve individual occurrences of errors and messages. Each occurrence represents a single instance of an item happening.
- [Rollbar Occurrences Metrics API](https://apis.io/apis/rollbar/rollbar-occurrences-metrics-api/) — Query occurrence count metrics over time with filtering, grouping, and aggregation capabilities.
- [Rollbar Projects API](https://apis.io/apis/rollbar/rollbar-projects-api/) — Manage projects within a Rollbar account. Projects are the top-level organizational unit for error tracking.
- [Rollbar Resolution Time Metrics API](https://apis.io/apis/rollbar/rollbar-resolution-time-metrics-api/) — Query time-to-resolution metrics for projects, filterable by environment, level, and framework.
- [Rollbar RQL Jobs API](https://apis.io/apis/rollbar/rollbar-rql-jobs-api/) — Submit, list, and retrieve results for RQL (Rollbar Query Language) jobs. RQL provides a SQL-like interface for querying error and deployment data.
- [Rollbar Source Maps API](https://apis.io/apis/rollbar/rollbar-source-maps-api/) — Upload JavaScript source maps to enable readable stack traces for minified code.
- [Rollbar Teams API](https://apis.io/apis/rollbar/rollbar-teams-api/) — Manage teams and team membership within a Rollbar account. Teams control access to projects.
- [Rollbar Users API](https://apis.io/apis/rollbar/rollbar-users-api/) — Retrieve user information within a Rollbar account.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Rollbar Webhook Events](https://apis.io/asyncapis/rollbar/rollbar-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/rollbar/webhook/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/rollbar/mcp-server/)
- [Moved to /providers/rollbar/](https://apis.io/servers/rollbar/rollbar/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Rollbar Agentic Access](https://apis.io/agentic-access/rollbar/rollbar-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Rollbar Deploy](https://apis.io/schemas/rollbar/rollbar-deploy/)
- [Rollbar Item](https://apis.io/schemas/rollbar/rollbar-item/)
- [Rollbar Occurrence](https://apis.io/schemas/rollbar/rollbar-occurrence/)
- [Rollbar Webhook Payload](https://apis.io/schemas/rollbar/rollbar-webhook-payload/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Rollbar Item Structure](https://apis.io/json-structure/rollbar/rollbar-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Rollbar Context](https://apis.io/jsonld/rollbar/rollbar-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Rollbar Vocabulary](https://apis.io/vocabularies/rollbar/rollbar-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Rollbar Create Item Example](https://apis.io/examples/rollbar/rollbar-create-item-example/)
- [Rollbar List Items Example](https://apis.io/examples/rollbar/rollbar-list-items-example/)

#### Collections (32)

Postman and Open Collection request collections.

- [Rollbar Deployment Access Tokens API](https://apis.io/collections/rollbar/open-rollbar-access-tokens-api/)
- [Rollbar Deployment API](https://apis.io/collections/rollbar/open-rollbar-deployment-api/)
- [Rollbar Deployment Access Tokens Deploys API](https://apis.io/collections/rollbar/open-rollbar-deploys-api/)
- [Rollbar Deployment Access Tokens Invites API](https://apis.io/collections/rollbar/open-rollbar-invites-api/)
- [Rollbar Deployment Access Tokens Items API](https://apis.io/collections/rollbar/open-rollbar-items-api/)
- [Rollbar Deployment Access Tokens Items Metrics API](https://apis.io/collections/rollbar/open-rollbar-items-metrics-api/)
- [Rollbar Metrics API](https://apis.io/collections/rollbar/open-rollbar-metrics-api/)
- [Rollbar Deployment Access Tokens Notifications API](https://apis.io/collections/rollbar/open-rollbar-notifications-api/)
- [Rollbar Deployment Access Tokens Occurrences API](https://apis.io/collections/rollbar/open-rollbar-occurrences-api/)
- [Rollbar Deployment Access Tokens Occurrences Metrics API](https://apis.io/collections/rollbar/open-rollbar-occurrences-metrics-api/)
- [Rollbar Deployment Access Tokens Projects API](https://apis.io/collections/rollbar/open-rollbar-projects-api/)
- [Rollbar Deployment Access Tokens Resolution Time Metrics API](https://apis.io/collections/rollbar/open-rollbar-resolution-time-metrics-api/)
- [Rollbar REST API](https://apis.io/collections/rollbar/open-rollbar-rest-api/)
- [Rollbar RQL API](https://apis.io/collections/rollbar/open-rollbar-rql-api/)
- [Rollbar Deployment Access Tokens RQL Jobs API](https://apis.io/collections/rollbar/open-rollbar-rql-jobs-api/)
- [Rollbar Deployment Access Tokens Source Maps API](https://apis.io/collections/rollbar/open-rollbar-source-maps-api/)
- [Rollbar Deployment Access Tokens Teams API](https://apis.io/collections/rollbar/open-rollbar-teams-api/)
- [Rollbar Deployment Access Tokens Users API](https://apis.io/collections/rollbar/open-rollbar-users-api/)
- [Rollbar Deployment Access Tokens API](https://apis.io/collections/rollbar/postman-rollbar-access-tokens-api/)
- [Rollbar Deployment Access Tokens Deploys API](https://apis.io/collections/rollbar/postman-rollbar-deploys-api/)
- [Rollbar Deployment Access Tokens Invites API](https://apis.io/collections/rollbar/postman-rollbar-invites-api/)
- [Rollbar Deployment Access Tokens Items API](https://apis.io/collections/rollbar/postman-rollbar-items-api/)
- [Rollbar Deployment Access Tokens Items Metrics API](https://apis.io/collections/rollbar/postman-rollbar-items-metrics-api/)
- [Rollbar Deployment Access Tokens Notifications API](https://apis.io/collections/rollbar/postman-rollbar-notifications-api/)
- [Rollbar Deployment Access Tokens Occurrences API](https://apis.io/collections/rollbar/postman-rollbar-occurrences-api/)
- …and 7 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Rollbar — asyncapi rules](https://apis.io/rules/rollbar/rollbar-asyncapi-spectral-rules/)
- [Rollbar — jsonschema rules](https://apis.io/rules/rollbar/rollbar-jsonschema-spectral-rules/)
- [Rollbar API Rules](https://apis.io/rules/rollbar/rollbar-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Rollbar Authentication](https://apis.io/security/rollbar/rollbar-authentication/)
- [Rollbar Domain Security](https://apis.io/security/rollbar/rollbar-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Rollbar Plans Pricing](https://apis.io/plans/rollbar/rollbar-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Rollbar Rate Limits](https://apis.io/rate-limits/rollbar/rollbar-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Rollbar Finops](https://apis.io/finops/rollbar/rollbar-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://rollbar.com/)
- [Documentation](https://docs.rollbar.com/)
- [Pricing](https://rollbar.com/pricing/)
- [Support](https://rollbar.com/support/)
- [Blog](https://rollbar.com/blog/feed/)
- [Terms of service](https://rollbar.com/terms/)
- [Privacy policy](https://rollbar.com/privacy/)
- [GitHub](https://github.com/rollbar)

## API Evangelist rating

**Kin Score 42.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 61.0 |
| Contract governance | 13.6 |
| Operational transparency | 13.2 |
| Developer ergonomics | 34.5 |
| Access clarity | 39.5 |

**Agent readiness 30.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rollbar/](https://apis.io/providers/rollbar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rollbar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rollbar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
