# Robocorp (robocorp)

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

Robocorp is an open source RPA and workflow automation platform for building Python-based automation bots. The platform provides the Control Room API for managing workspaces, workers, processes, work items, assets, vaults, webhooks, and task packages. Robocorp also provides the RPA Framework, an open-source collection of Python libraries for robotic process automation including browser, desktop, email, Excel, PDF, and cloud service automation. The platform has evolved toward Sema4 AI for AI-powered automation actions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- RPA
- Workflow Automation
- Python
- Open Source
- Automation

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Robocorp Control Room API

The Robocorp Control Room API provides programmatic access to the orchestration platform for RPA automations. It supports workspace management, worker lifecycle, worker group organization, process definition and execution, process run monitoring, step run outputs, work item management, asset storage, vault secrets, webhook configuration, and task package deployment. Authentication uses API keys with the RC-WSKEY prefix.

- **Human URL:** [https://robocorp.com/api](https://robocorp.com/api)
- **Base URL:** `https://cloud.robocorp.com/api/v1`

#### Tags

- RPA
- Automation
- Orchestration
- Workflow
- Workers

#### Properties

- [Documentation](https://robocorp.com/api)
- [Guide](https://robocorp.com/docs/control-room/apis-and-webhooks)
- [OpenAPI](https://robocorp.com/api/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/openapi/robocorp-control-room-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/rules/robocorp-control-room-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-schema/robocorp-process-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-schema/robocorp-work-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/robocorp-control-room.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/robocorp-control-room.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RPA Framework

The RPA Framework is an open-source collection of Python libraries for robotic process automation designed for use with Robot Framework and Python. It includes libraries for browser automation, desktop automation, Excel, email, PDF, Windows UI, cloud service integrations, and more.

- **Human URL:** [https://rpaframework.org/](https://rpaframework.org/)

#### Tags

- RPA
- Python
- Open Source
- Libraries

#### Properties

- [Documentation](https://rpaframework.org/)
- [Git Hub](https://github.com/robocorp/rpaframework)
- [Postman Collection](collections/robocorp-control-room.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/robocorp-control-room.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/robocorp)
- [Website](https://robocorp.com)
- [Documentation](https://robocorp.com/docs)
- [Git Hub](https://github.com/robocorp)
- [Py P I](https://pypi.org/project/robocorp/)
- [Blog](https://robocorp.com/blog)
- [Privacy Policy](https://robocorp.com/privacy-policy)
- [Terms of Service](https://robocorp.com/terms-of-service)
- [Status Page](https://status.robocorp.com)
- [Changelog](https://robocorp.com/docs/changelog)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/json-ld/robocorp-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/robocorp/refs/heads/main/vocabulary/robocorp-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
