# Workday Recruiting (workday-recruiting)

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

APIs for Workday's cloud-based recruiting and talent acquisition solution, providing programmatic access to job requisitions, candidate management, applications, interviews, job postings, and hiring workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml)

## Tags

- HCM
- Human Resources
- Recruiting
- SaaS
- Talent Acquisition

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Workday Recruiting REST API

RESTful API for managing recruiting operations including job requisitions, candidates, applications, and hiring processes in Workday. Supports OAuth 2.0 authentication and returns data in JSON format for integration with talent management and applicant tracking systems.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/recruiting/`

#### Tags

- Applications
- Candidates
- Job Requisitions
- Recruiting
- Talent Acquisition

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/workday-recruiting-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-recruiting-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-recruiting-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication)
- [Rate Limits](https://community.workday.com/articles/16827)
- [JSON-LD](json-ld/workday-recruiting-rest-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/recruiting-rest-api-applicant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-applicant-import-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-attachment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-background-check-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-background-check-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-background-check-package-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-candidate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-candidate-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-candidate-assessment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-evergreen-requisition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-evergreen-requisition-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-interview-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-interview-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-interview-feedback-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-interview-feedback-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-job-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-job-posting-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-job-posting-site-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-job-requisition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-job-requisition-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-offer-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-position-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-position-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-questionnaire-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-recruiting-agency-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-reference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recruiting-rest-api-veteran-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/recruiting-rest-api-applicant-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-applicant-import-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-attachment-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-background-check-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-background-check-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-background-check-package-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-candidate-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-candidate-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-candidate-assessment-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-evergreen-requisition-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-evergreen-requisition-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-interview-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-interview-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-interview-feedback-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-interview-feedback-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-job-application-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-job-posting-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-job-posting-site-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-job-requisition-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-job-requisition-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-offer-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-offer-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-position-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-position-create-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-questionnaire-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-recruiting-agency-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-reference-structure.json)
- [JSON Structure](json-structure/recruiting-rest-api-veteran-status-structure.json)
- [Example](examples/recruiting-rest-api-applicant-example.json)
- [Example](examples/recruiting-rest-api-applicant-import-example.json)
- [Example](examples/recruiting-rest-api-attachment-example.json)
- [Example](examples/recruiting-rest-api-background-check-example.json)
- [Example](examples/recruiting-rest-api-background-check-create-example.json)
- [Example](examples/recruiting-rest-api-background-check-package-example.json)
- [Example](examples/recruiting-rest-api-candidate-example.json)
- [Example](examples/recruiting-rest-api-candidate-create-example.json)
- [Example](examples/recruiting-rest-api-candidate-assessment-example.json)
- [Example](examples/recruiting-rest-api-evergreen-requisition-example.json)
- [Example](examples/recruiting-rest-api-evergreen-requisition-create-example.json)
- [Example](examples/recruiting-rest-api-interview-example.json)
- [Example](examples/recruiting-rest-api-interview-create-example.json)
- [Example](examples/recruiting-rest-api-interview-feedback-example.json)
- [Example](examples/recruiting-rest-api-interview-feedback-create-example.json)
- [Example](examples/recruiting-rest-api-job-application-example.json)
- [Example](examples/recruiting-rest-api-job-posting-example.json)
- [Example](examples/recruiting-rest-api-job-posting-site-example.json)
- [Example](examples/recruiting-rest-api-job-requisition-example.json)
- [Example](examples/recruiting-rest-api-job-requisition-create-example.json)
- [Example](examples/recruiting-rest-api-offer-example.json)
- [Example](examples/recruiting-rest-api-offer-create-example.json)
- [Example](examples/recruiting-rest-api-position-example.json)
- [Example](examples/recruiting-rest-api-position-create-example.json)
- [Example](examples/recruiting-rest-api-questionnaire-example.json)
- [Example](examples/recruiting-rest-api-recruiting-agency-example.json)
- [Example](examples/recruiting-rest-api-reference-example.json)
- [Example](examples/recruiting-rest-api-veteran-status-example.json)

### Workday Recruiting SOAP Web Services API

SOAP-based web service providing comprehensive access to Workday Recruiting business services data for integration with talent management and applicant tracking systems. Includes over 120 operations covering candidate management, job requisitions, evergreen requisitions, job postings, interviews, background checks, recruiting agencies, and self-schedule calendars.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Candidates
- Job Requisitions
- Recruiting
- SOAP API
- Web Services

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html)
- [API Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [W S D L](wsdl/workday-recruiting-soap.wsdl)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.wsdl)
- [X S D](xsd/workday-recruiting-soap.xsd)
- [X S D](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.xsd)
- [Changelog](https://community.workday.com/api-versions)
- [Postman Collection](collections/workday-recruiting-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-recruiting-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://community.workday.com)
- [Getting Started](https://community.workday.com/api-start)
- [Documentation](https://community.workday.com/api)
- [Authentication](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication)
- [Console](https://developer.workday.com/about)
- [Blog](https://blog.workday.com/en-us/application-development.html)
- [Status Page](https://community.workday.com/trust/status)
- [Support](https://www.workday.com/en-us/services/support.html)
- [Sign Up](https://resourcecenter.workday.com/)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Rate Limits](https://community.workday.com/articles/16827)
- [Changelog](https://community.workday.com/api-versions)
- [GitHub Organization](https://github.com/Workday)
- [Tools](https://www.npmjs.com/package/@workday/everywhere)
- [Tools](https://github.com/Workday/canvas-kit)
- [Code Examples](https://github.com/Workday/extend-js-example)
- [Marketplace](https://marketplace.workday.com/en-US/home)
- [Partners](https://www.workday.com/en-us/company/partners/overview.html)
- [Spectral Rules](rules/workday-recruiting-spectral-rules.yml)
- [Vocabulary](vocabulary/workday-recruiting-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
