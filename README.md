# LinearB (linearb)

LinearB is a software engineering intelligence (SEI) and developer productivity platform that correlates Git, CI/CD, project management, and incident data into DORA and engineering metrics. The LinearB REST API lets teams report deployments, push incidents, export measurements, and manage teams and services programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/linearb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/linearb/refs/heads/main/apis.yml)

## Tags

- Engineering Analytics
- SEI
- Developer Productivity
- DORA Metrics
- DevOps

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### LinearB Deployments API

Report and list software deployments by Git repository and ref so LinearB can calculate deployment frequency, lead time, and other DORA metrics.

- **Human URL:** [https://docs.linearb.io/api-deployments/](https://docs.linearb.io/api-deployments/)
- **Base URL:** `https://public-api.linearb.io/api/v1`

#### Tags

- Deployments
- Releases
- DORA

#### Properties

- [Documentation](https://docs.linearb.io/api-deployments/)
- [API Reference](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LinearB Incidents API

Upload and update custom incident reports from external incident-management tools to feed change failure rate and mean-time-to-restore (MTTR) metrics.

- **Human URL:** [https://docs.linearb.io/api-incidents/](https://docs.linearb.io/api-incidents/)
- **Base URL:** `https://public-api.linearb.io/api/v1`

#### Tags

- Incidents
- MTTR
- Change Failure Rate

#### Properties

- [Documentation](https://docs.linearb.io/api-incidents/)
- [API Reference](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LinearB Measurements API

Retrieve engineering metrics on demand or export them to CSV/JSON, with grouping, roll-up, and aggregation (p50, p75, average) across configurable time ranges.

- **Human URL:** [https://docs.linearb.io/api-measurements-v2/](https://docs.linearb.io/api-measurements-v2/)
- **Base URL:** `https://public-api.linearb.io/api/v2`

#### Tags

- Measurements
- Metrics
- Export

#### Properties

- [Documentation](https://docs.linearb.io/api-measurements-v2/)
- [API Reference](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LinearB Teams API

Search, create, update, and delete teams and manage their membership via the Teams V2 API, including team hierarchy with parent teams.

- **Human URL:** [https://docs.linearb.io/api-teams-v2/](https://docs.linearb.io/api-teams-v2/)
- **Base URL:** `https://public-api.linearb.io/api/v2`

#### Tags

- Teams
- Membership
- Organization

#### Properties

- [Documentation](https://docs.linearb.io/api-teams-v2/)
- [API Reference](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LinearB Services API

Create, list, update, and delete services that map repositories and directory paths so metrics and deployments can be attributed at the service level.

- **Human URL:** [https://docs.linearb.io/api-services/](https://docs.linearb.io/api-services/)
- **Base URL:** `https://public-api.linearb.io/api/v1`

#### Tags

- Services
- Repositories
- Catalog

#### Properties

- [Documentation](https://docs.linearb.io/api-services/)
- [API Reference](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LinearB Webhooks API

Consume LinearB events to drive WorkerB automations and outbound integrations, enabling event-driven workflows around pull requests, deployments, and incidents.

- **Human URL:** [https://docs.linearb.io/api-overview/](https://docs.linearb.io/api-overview/)
- **Base URL:** `https://public-api.linearb.io/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.linearb.io/api-overview/)
- [OpenAPI](openapi/linearb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/linearb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/linearb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/linear-b)
- [LinkedIn](https://www.linkedin.com/company/linearb)
- [Website](https://linearb.io/)
- [Documentation](https://docs.linearb.io/api-overview/)
- [Plans](plans/linearb-plans-pricing.yml)
- [Rate Limits](rate-limits/linearb-rate-limits.yml)
- [Fin Ops](finops/linearb-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
