# Cortex (cortex)

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

Cortex is an Engineering Operations (EngOps) platform and internal developer portal that helps engineering teams catalog services, enforce production readiness with scorecards, automate self-service workflows, and surface engineering intelligence across their organization. Cortex centralizes data from observability, CI/CD, source control, on-call, and SaaS tooling and exposes it through a REST API used to integrate the catalog with platform engineering and SRE workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cortex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cortex/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Catalog
- Custom Data
- Dependencies
- Deploys
- Developer Experience
- EngOps
- Engineering Intelligence
- Initiatives
- Internal Developer Portal
- On-call
- Platform Engineering
- Scorecards
- Service Catalog
- SRE
- Workflows

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Cortex REST API

The Cortex REST API exposes the service catalog, scorecards, initiatives, entity relationships and dependencies, on-call assignments, custom data, and deployments managed in a Cortex workspace. Authentication is via personal or service access tokens, and entity descriptors can be retrieved as OpenAPI documents through a per-entity endpoint.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)

#### Tags

- Catalog
- Dependencies
- Deploys
- REST
- Scorecards

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Getting Started](https://docs.cortex.io/docs/getting-started)
- [API Reference](https://docs.cortex.io/reference)
- [OpenAPI](openapi/cortex-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cortex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cortex MCP Server

Cortex exposes a Model Context Protocol (MCP) server that lets AI coding assistants and IDE agents query the service catalog, look up ownership, check scorecard scores, and run workflows directly from developer tools.

- **Human URL:** [https://docs.cortex.io/](https://docs.cortex.io/)

#### Tags

- AI
- IDE
- MCP

#### Properties

- [Documentation](https://docs.cortex.io/)
- [Postman Collection](collections/cortex.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cortex.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.cortex.io/)
- [Documentation](https://docs.cortex.io/)
- [Product](https://www.cortex.io/product)
- [Service Catalog](https://www.cortex.io/product/service-catalog)
- [Scorecards](https://www.cortex.io/product/scorecards)
- [Workflows](https://www.cortex.io/product/workflows)
- [Pricing](https://www.cortex.io/pricing)
- [Customers](https://www.cortex.io/customers)
- [Blog](https://www.cortex.io/blog)
- [GitHub Organization](https://github.com/cortexapps)
- [Integrations](https://docs.cortex.io/docs/integrations)
- [Changelog](https://docs.cortex.io/changelog)
- [Status Page](https://status.cortex.io/)
- [LinkedIn](https://www.linkedin.com/company/cortexapp/)
- [Twitter](https://twitter.com/cortexapp)
- [Contact](https://www.cortex.io/contact)
- [M C P Server](https://github.com/cortexapps/cortex-mcp)
- [L L Ms Txt](https://docs.cortex.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
