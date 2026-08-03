# Azure DevOps (azure-dev-ops)

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

Azure DevOps provides developer services for teams to plan work, collaborate on code, and build and deploy applications through comprehensive REST APIs covering builds, releases, pipelines, and work items.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-dev-ops/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, CI/CD, DevOps, Project Management, Version Control

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Azure DevOps
Azure DevOps provides developer services for teams to plan work, collaborate on code, and build and deploy applications through comprehensive REST APIs covering builds, releases, pipelines, and work items.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)

#### Tags:

 - CI/CD, DevOps, REST

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- [OpenAPI](openapi/azure-dev-ops-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Dev Ops](openapi/azure-dev-ops-openapi.yaml)

### JSON Schema

- [Pipeline](json-schema/azure-dev-ops-pipeline-schema.json)
- [Input Value](json-schema/azure-dev-ops-input-value-schema.json)
- [Operation Display Value](json-schema/azure-dev-ops-operation-display-value-schema.json)
- [Pipeline Template](json-schema/azure-dev-ops-pipeline-template-schema.json)
- [Code Repository](json-schema/azure-dev-ops-code-repository-schema.json)
- [Pipeline List Result](json-schema/azure-dev-ops-pipeline-list-result-schema.json)
- [Pipeline Template Definition List Result](json-schema/azure-dev-ops-pipeline-template-definition-list-result-schema.json)
- [Project Reference](json-schema/azure-dev-ops-project-reference-schema.json)
- [Bootstrap Configuration](json-schema/azure-dev-ops-bootstrap-configuration-schema.json)
- [Authorization](json-schema/azure-dev-ops-authorization-schema.json)

### JSON-LD

- [Azure Dev Ops Context](json-ld/azure-dev-ops-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Dev Ops](capabilities/shared/azure-dev-ops.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Dev Ops Management](capabilities/azure-dev-ops-management.yaml) | Azure DevOps | 5 | Cloud Engineer |

## Vocabulary

- [Azure Dev Ops Vocabulary](vocabulary/azure-dev-ops-vocabulary.yaml)

## Rules

- [Azure Dev Ops Spectral Rules](rules/azure-dev-ops-spectral-rules.yml) — 15 rules enforcing Azure DevOps API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
