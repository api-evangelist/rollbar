# Rollbar (rollbar)
Rollbar is a real-time error tracking and monitoring platform that helps developers detect, diagnose, and fix errors in their applications. Their developer platform offers REST, Metrics, RQL, and Deployment APIs along with webhook integrations, enabling teams to programmatically manage error data, automate workflows, and correlate deployments with application stability.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rollbar/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Error Tracking, Monitoring, Debugging, Deployments, Analytics, Webhooks

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Rollbar REST API
The Rollbar REST API provides programmatic access to the Rollbar error tracking and monitoring platform. It allows developers to manage projects, items, occurrences, deploys, teams, users, and invites through a RESTful JSON interface. Authentication is handled via access tokens passed in the X-Rollbar-Access-Token header. The API is used by Rollbar's official SDKs to report errors and exceptions, and can also be used to build custom integrations, extract data for analysis, or automate workflows around error management.

**Human URL:** [https://docs.rollbar.com/reference/getting-started-1](https://docs.rollbar.com/reference/getting-started-1)


#### Tags:

 - Error Tracking, Monitoring, Occurrences, Items, Projects, Deploys

#### Properties

- [Documentation](https://docs.rollbar.com/reference/getting-started-1)
- [OpenAPI](openapi/rollbar-rest-api-openapi.yml)

### Rollbar Metrics API
The Rollbar Metrics API is part of Rollbar Analyze and provides programmatic access to metrics data for error tracking analysis and discovery. It enables developers to query resolution time metrics, occurrence counts, and other aggregate data across projects. The API supports filtering and grouping of results, making it useful for building dashboards, generating reports, and monitoring error trends over time.

**Human URL:** [https://docs.rollbar.com/docs/metrics-api-examples](https://docs.rollbar.com/docs/metrics-api-examples)


#### Tags:

 - Metrics, Analytics, Error Tracking, Monitoring

#### Properties

- [Documentation](https://docs.rollbar.com/docs/metrics-api-examples)
- [OpenAPI](openapi/rollbar-metrics-api-openapi.yml)

### Rollbar RQL API
The Rollbar RQL (Rollbar Query Language) API provides a SQL-like interface for querying error and deployment data stored in Rollbar. It supports SELECT queries against two logical tables: item_occurrence and deploy, allowing developers to perform complex filtering, grouping, and analysis of error data. RQL jobs can be submitted and retrieved via the API endpoint at /api/1/rql/jobs/, enabling programmatic access to advanced analytics that go beyond the standard REST API capabilities.

**Human URL:** [https://docs.rollbar.com/docs/rql](https://docs.rollbar.com/docs/rql)


#### Tags:

 - Query Language, Analytics, Error Tracking, SQL

#### Properties

- [Documentation](https://docs.rollbar.com/docs/rql)
- [OpenAPI](openapi/rollbar-rql-api-openapi.yml)

### Rollbar Deployment API
The Rollbar Deployment API allows developers to notify Rollbar of application deployments and releases. By reporting deploys, teams can correlate error spikes with specific releases, track which code version introduced a bug, and automatically resolve items that were fixed in a deploy. The API accepts deployment metadata such as revision, environment, and rollbar_username, and integrates with CI/CD pipelines to provide continuous visibility into how deployments affect application stability.

**Human URL:** [https://docs.rollbar.com/docs/deployment-api](https://docs.rollbar.com/docs/deployment-api)


#### Tags:

 - Deployments, CI/CD, Release Management, Error Tracking

#### Properties

- [Documentation](https://docs.rollbar.com/docs/deployment-api)
- [OpenAPI](openapi/rollbar-deployment-api-openapi.yml)

### Rollbar Webhooks
Rollbar's webhook notification system delivers real-time event notifications to configured endpoints when errors, deployments, and other significant events occur. Webhooks support events including new items, every occurrence, exponential repeat items, high occurrence rate, item resolved, item reactivated, item reopened, and deploy events. Payloads are delivered via HTTP POST in JSON or XML format with automatic retry and exponential backoff on failure.

**Human URL:** [https://docs.rollbar.com/docs/webhooks](https://docs.rollbar.com/docs/webhooks)


#### Tags:

 - Webhooks, Events, Notifications, Error Tracking

#### Properties

- [Documentation](https://docs.rollbar.com/docs/webhooks)
- [AsyncAPI](asyncapi/rollbar-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://docs.rollbar.com/reference/getting-started-1)
- [Documentation](https://docs.rollbar.com/docs)
- [Website](https://rollbar.com)
- [PrivacyPolicy](https://rollbar.com/privacy/)
- [TermsOfService](https://rollbar.com/terms/)
- [Support](https://rollbar.com/support/)
- [Blog](https://rollbar.com/blog/)
- [Login](https://rollbar.com/login/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
