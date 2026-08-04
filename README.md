# LinearB (linearb)

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
