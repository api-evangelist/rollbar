# Rollbar

Rollbar is a real-time error tracking and monitoring platform for software teams. It automatically captures exceptions and errors from web, mobile, and server-side applications, groups them by root cause, and provides actionable alerts to speed up debugging. Rollbar provides SDKs for over a dozen platforms including JavaScript, Python, PHP, Ruby, Go, Swift, .NET, and Java.

**Website:** [https://rollbar.com/](https://rollbar.com/)

**Documentation:** [https://docs.rollbar.com/](https://docs.rollbar.com/)

**API Reference:** [https://explorer.docs.rollbar.com/](https://explorer.docs.rollbar.com/)

**GitHub:** [https://github.com/rollbar](https://github.com/rollbar)

## APIs

### Rollbar REST API
Programmatic management of projects, items, occurrences, teams, users, invites, notifications, and source maps via RESTful JSON interface.

- **Documentation:** [https://docs.rollbar.com/reference/getting-started-1](https://docs.rollbar.com/reference/getting-started-1)
- **OpenAPI:** [openapi/rollbar-rest-api-openapi.yml](openapi/rollbar-rest-api-openapi.yml)

### Rollbar Deployment API
Notify Rollbar of application deployments to correlate error spikes with specific releases.

- **Documentation:** [https://docs.rollbar.com/reference/post_deploy](https://docs.rollbar.com/reference/post_deploy)
- **OpenAPI:** [openapi/rollbar-deployment-api-openapi.yml](openapi/rollbar-deployment-api-openapi.yml)

### Rollbar Metrics API
Query resolution time metrics, occurrence counts, and aggregate analytics data.

- **Documentation:** [https://docs.rollbar.com/reference/metrics](https://docs.rollbar.com/reference/metrics)
- **OpenAPI:** [openapi/rollbar-metrics-api-openapi.yml](openapi/rollbar-metrics-api-openapi.yml)

### Rollbar RQL API
SQL-like query interface for advanced error analysis over item_occurrence and deploy tables.

- **Documentation:** [https://docs.rollbar.com/reference/rql](https://docs.rollbar.com/reference/rql)
- **OpenAPI:** [openapi/rollbar-rql-api-openapi.yml](openapi/rollbar-rql-api-openapi.yml)

### Rollbar Webhooks
Real-time outbound webhook notifications for error events, deployments, and status changes.

- **Documentation:** [https://docs.rollbar.com/docs/webhooks](https://docs.rollbar.com/docs/webhooks)
- **AsyncAPI:** [asyncapi/rollbar-webhooks-asyncapi.yml](asyncapi/rollbar-webhooks-asyncapi.yml)

## Artifacts

### OpenAPI Specs
| File | Description |
|------|-------------|
| [openapi/rollbar-rest-api-openapi.yml](openapi/rollbar-rest-api-openapi.yml) | Rollbar REST API specification |
| [openapi/rollbar-deployment-api-openapi.yml](openapi/rollbar-deployment-api-openapi.yml) | Rollbar Deployment API specification |
| [openapi/rollbar-metrics-api-openapi.yml](openapi/rollbar-metrics-api-openapi.yml) | Rollbar Metrics API specification |
| [openapi/rollbar-rql-api-openapi.yml](openapi/rollbar-rql-api-openapi.yml) | Rollbar RQL API specification |

### AsyncAPI Specs
| File | Description |
|------|-------------|
| [asyncapi/rollbar-webhooks-asyncapi.yml](asyncapi/rollbar-webhooks-asyncapi.yml) | Rollbar webhook events AsyncAPI specification |

### Rules
| File | Description |
|------|-------------|
| [rules/rollbar-rules.yml](rules/rollbar-rules.yml) | Spectral ruleset enforcing Rollbar API conventions |

### Capabilities
| File | Description |
|------|-------------|
| [capabilities/error-monitoring.yaml](capabilities/error-monitoring.yaml) | Unified error monitoring workflow capability |
| [capabilities/shared/rollbar-rest-api.yaml](capabilities/shared/rollbar-rest-api.yaml) | Rollbar REST API shared capability definition |

### JSON Schema
| File | Description |
|------|-------------|
| [json-schema/rollbar-item-schema.json](json-schema/rollbar-item-schema.json) | Rollbar error item schema |
| [json-schema/rollbar-occurrence-schema.json](json-schema/rollbar-occurrence-schema.json) | Rollbar occurrence schema |
| [json-schema/rollbar-deploy-schema.json](json-schema/rollbar-deploy-schema.json) | Rollbar deployment schema |
| [json-schema/rollbar-webhook-payload-schema.json](json-schema/rollbar-webhook-payload-schema.json) | Rollbar webhook payload schema |

### JSON Structure
| File | Description |
|------|-------------|
| [json-structure/rollbar-item-structure.json](json-structure/rollbar-item-structure.json) | Rollbar data structure documentation |

### JSON-LD
| File | Description |
|------|-------------|
| [json-ld/rollbar-context.jsonld](json-ld/rollbar-context.jsonld) | JSON-LD context for Rollbar data semantics |

### Examples
| File | Description |
|------|-------------|
| [examples/rollbar-create-item-example.json](examples/rollbar-create-item-example.json) | Create an error item example |
| [examples/rollbar-list-items-example.json](examples/rollbar-list-items-example.json) | List error items example |

### Vocabulary
| File | Description |
|------|-------------|
| [vocabulary/rollbar-vocabulary.yml](vocabulary/rollbar-vocabulary.yml) | Rollbar domain vocabulary |

## Capabilities

### Error Monitoring (`capabilities/error-monitoring.yaml`)
Unified workflow for error monitoring, incident triage, and deployment correlation. Enables engineering teams and on-call engineers to:
- Investigate and triage errors by status, level, and environment
- Drill into individual occurrences with full stack traces
- Report new errors from any application
- Resolve and mute items
- Manage projects and teams
- Configure webhook notifications

**REST Port:** 8080 | **MCP Port:** 9080 | **Tools:** 9

## Integrations

Slack, PagerDuty, Jira, GitHub, Bitbucket, Heroku

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
