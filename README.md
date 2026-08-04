# Rollbar (rollbar)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Rollbar is a real-time error tracking and monitoring platform for software teams. It automatically captures exceptions and errors from web, mobile, and server-side applications, groups them by root cause, and provides actionable alerts to speed up debugging. Rollbar provides SDKs for over a dozen platforms including JavaScript, Python, PHP, Ruby, Go, Swift, .NET, and Java. The REST API enables programmatic management of projects, items, occurrences, deployments, teams, notifications, and source maps. The RQL (Rollbar Query Language) provides SQL-like queries for error analysis.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Error Tracking
- Monitoring
- Debugging
- DevOps
- Application Performance

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Rollbar REST API

The Rollbar REST API provides programmatic access to the Rollbar error tracking and monitoring platform. Manage projects, items, occurrences, deploys, teams, users, invites, notifications, and source maps through a RESTful JSON interface. Authentication is via project access tokens in the X-Rollbar-Access-Token header.

- **Human URL:** [https://docs.rollbar.com/reference/getting-started-1](https://docs.rollbar.com/reference/getting-started-1)
- **Base URL:** `https://api.rollbar.com/api/1`

#### Tags

- Error Tracking
- Monitoring
- REST
- Projects
- Teams

#### Properties

- [Documentation](https://docs.rollbar.com/reference/getting-started-1)
- [OpenAPI](https://explorer.docs.rollbar.com/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/rollbar-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rollbar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rollbar Deployment API

The Rollbar Deployment API allows developers to notify Rollbar of application deployments and releases. By reporting deploys, teams can correlate error spikes with specific releases, track deployment history, and manage rollbacks with full visibility into which code version is running in production.

- **Human URL:** [https://docs.rollbar.com/reference/post_deploy](https://docs.rollbar.com/reference/post_deploy)
- **Base URL:** `https://api.rollbar.com/api/1`

#### Tags

- Deployment
- Release Management
- Error Tracking
- REST
- DevOps

#### Properties

- [Documentation](https://docs.rollbar.com/reference/post_deploy)
- [OpenAPI](openapi/rollbar-deployment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rollbar-deployment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-deployment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rollbar Metrics API

The Rollbar Metrics API is part of Rollbar Analyze and provides programmatic access to metrics data for error tracking analysis and discovery. Enables developers to query resolution time metrics, occurrence counts, and item activation metrics across projects.

- **Human URL:** [https://docs.rollbar.com/reference/metrics](https://docs.rollbar.com/reference/metrics)
- **Base URL:** `https://api.rollbar.com/api/1`

#### Tags

- Metrics
- Analytics
- Error Tracking
- REST
- Monitoring

#### Properties

- [Documentation](https://docs.rollbar.com/reference/metrics)
- [OpenAPI](openapi/rollbar-metrics-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rollbar-metrics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-metrics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rollbar RQL API

The Rollbar RQL (Rollbar Query Language) API provides a SQL-like interface for querying error and deployment data stored in Rollbar. Supports SELECT queries against item_occurrence and deploy tables for advanced error analysis, reporting, and custom integrations.

- **Human URL:** [https://docs.rollbar.com/reference/rql](https://docs.rollbar.com/reference/rql)
- **Base URL:** `https://api.rollbar.com/api/1`

#### Tags

- Query Language
- Analytics
- Error Tracking
- REST
- SQL

#### Properties

- [Documentation](https://docs.rollbar.com/reference/rql)
- [OpenAPI](openapi/rollbar-rql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rollbar-rql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-rql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rollbar Webhooks

Rollbar supports outbound webhook notifications for real-time event-driven integrations. Webhooks deliver payload data when errors occur, items are resolved, or deployment events happen, enabling integration with Slack, PagerDuty, email, and custom HTTP endpoints.

- **Human URL:** [https://docs.rollbar.com/docs/webhooks](https://docs.rollbar.com/docs/webhooks)
- **Base URL:** `https://api.rollbar.com`

#### Tags

- Webhooks
- Event-Driven
- Notifications
- AsyncAPI
- Monitoring

#### Properties

- [Documentation](https://docs.rollbar.com/docs/webhooks)
- [AsyncAPI](asyncapi/rollbar-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/rollbar-deployment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-deployment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rollbar-metrics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-metrics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rollbar-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rollbar-rql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rollbar-rql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rollbar)
- [Website](https://rollbar.com/)
- [Documentation](https://docs.rollbar.com/)
- [Documentation](https://docs.rollbar.com/reference/getting-started-1)
- [Portal](https://explorer.docs.rollbar.com/)
- [Pricing](https://rollbar.com/pricing/)
- [GitHub Organization](https://github.com/rollbar)
- [Terms of Service](https://rollbar.com/terms/)
- [Privacy Policy](https://rollbar.com/privacy/)
- [Support](https://rollbar.com/support/)
- [OpenAPI](openapi/rollbar-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/rollbar-deployment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/rollbar-metrics-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/rollbar-rql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/rollbar-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/rollbar-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rollbar-occurrence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rollbar-deploy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rollbar-webhook-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/rollbar-context.jsonld)
- [Features](undefined)
- [M C P Server](https://github.com/rollbar/rollbar-mcp-server)
- [L L Ms Txt](https://docs.rollbar.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
