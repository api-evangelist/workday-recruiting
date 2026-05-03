# Workday Recruiting (workday-recruiting)
APIs for Workday's cloud-based recruiting and talent acquisition solution, providing programmatic access to job requisitions, candidate management, applications, interviews, job postings, and hiring workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - HCM, Human Resources, Recruiting, SaaS, Talent Acquisition

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### Workday Recruiting REST API
RESTful API for managing recruiting operations including job requisitions, candidates, applications, and hiring processes in Workday. Supports OAuth 2.0 authentication and returns data in JSON format for integration with talent management and applicant tracking systems.

**Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)

#### Tags:

 - Applications, Candidates, Job Requisitions, Recruiting, Talent Acquisition

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml)
- [OpenAPI](openapi/workday-recruiting-rest-api-openapi.yml)
- [Authentication](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication)
- [RateLimits](https://community.workday.com/articles/16827)
- [JSON-LD](json-ld/workday-recruiting-rest-api-context.jsonld)
- [JSONSchema](json-schema/) — 28 entity schemas
- [JSONStructure](json-structure/) — 28 JSON Structure definitions
- [Examples](examples/) — 28 example payloads

### Workday Recruiting SOAP Web Services API
SOAP-based web service providing comprehensive access to Workday Recruiting business services data for integration with talent management and applicant tracking systems. Includes over 120 operations covering candidate management, job requisitions, evergreen requisitions, job postings, interviews, background checks, recruiting agencies, and self-schedule calendars.

**Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html)

#### Tags:

 - Candidates, Job Requisitions, Recruiting, SOAP API, Web Services

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html)
- [APIReference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [WSDL](wsdl/workday-recruiting-soap.wsdl)
- [WSDL](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.wsdl)
- [XSD](xsd/workday-recruiting-soap.xsd)
- [XSD](https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.xsd)
- [ChangeLog](https://community.workday.com/api-versions)

## Common Properties

- [Portal](https://community.workday.com)
- [GettingStarted](https://community.workday.com/api-start)
- [Documentation](https://community.workday.com/api)
- [Authentication](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication)
- [Console](https://developer.workday.com/about)
- [Blog](https://blog.workday.com/en-us/application-development.html)
- [StatusPage](https://community.workday.com/trust/status)
- [Support](https://www.workday.com/en-us/services/support.html)
- [SignUp](https://resourcecenter.workday.com/)
- [TermsOfService](https://www.workday.com/en-us/legal.html)
- [PrivacyPolicy](https://www.workday.com/en-us/privacy.html)
- [RateLimits](https://community.workday.com/articles/16827)
- [ChangeLog](https://community.workday.com/api-versions)
- [GitHubOrganization](https://github.com/Workday)
- [Workday Everywhere SDK](https://www.npmjs.com/package/@workday/everywhere)
- [Workday Canvas Kit](https://github.com/Workday/canvas-kit)
- [Workday Extend JavaScript Example](https://github.com/Workday/extend-js-example)
- [Marketplace](https://marketplace.workday.com/en-US/home)
- [Partners](https://www.workday.com/en-us/company/partners/overview.html)
- [SpectralRules](rules/workday-recruiting-spectral-rules.yml)
- [NaftikoCapability](capabilities/requisition-management.yaml)
- [NaftikoCapability](capabilities/candidate-pipeline.yaml)
- [NaftikoCapability](capabilities/interview-and-screening.yaml)
- [NaftikoCapability](capabilities/recruiting-configuration.yaml)
- [NaftikoCapability](capabilities/shared/recruiting.yaml)
- [Vocabulary](vocabulary/workday-recruiting-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Job Requisition Management | Create, edit, close, freeze, and reopen job requisitions for open positions, with full lifecycle and approval workflow support. |
| Evergreen Requisitions | Manage ongoing requisitions used for continuous hiring needs without a specific number of openings or close date. |
| Candidate Management | Create, retrieve, and update candidate profiles including personal information, attachments, photos, and assessment data. |
| Job Application Lifecycle | Manage applications from submission through disposition, including stage movement, advancement, and offer initiation. |
| Job Posting Distribution | Post, update, and unpost jobs to internal and external career sites and manage job posting site brands and configurations. |
| Interview Scheduling | Schedule interviews, submit interview feedback, configure interview settings, and manage self-schedule calendars. |
| Background Check Integration | Submit and retrieve background check results and manage background check packages for candidate screening. |
| Recruiting Agency Workflows | Manage agency relationships, agency users, and agency candidate submissions tied to job requisitions. |
| High-Volume Applicant Import | Bulk applicant import operations to support high-volume hiring and third-party sourcing pipelines. |
| Position Management | Create and manage positions and position restrictions within the position management staffing model. |
| Recruiting Configuration | Manage recruiting configuration including questionnaires, assessment categories, veteran statuses, site brands, and regions. |
| OAuth 2.0 Authentication | Standards-based OAuth 2.0 authentication for secure programmatic access to recruiting data. |
| SOAP Web Services | Comprehensive SOAP web services with over 120 recruiting operations for deep enterprise integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Applicant Tracking System Integration | Sync requisitions, candidates, and applications between Workday and third-party ATS or CRM platforms. |
| Talent Sourcing Automation | Push candidates from sourcing tools and job boards into Workday requisition pipelines. |
| Job Board Distribution | Automatically distribute Workday job postings to external job boards and career site networks. |
| Background Screening Workflow | Trigger and ingest background check results from screening vendors tied to candidate stages. |
| Interview Coordination | Integrate with calendar and scheduling tools to coordinate interviewer availability and candidate self-scheduling. |
| Assessment and Skills Testing | Connect Workday Recruiting to assessment platforms for skills, behavioral, and technical evaluations. |
| Hiring Analytics and Reporting | Extract recruiting data for reporting in BI tools, data warehouses, and people analytics platforms. |
| Onboarding Handoff | Trigger onboarding workflows in HRIS or onboarding platforms upon requisition fill or hire stage. |
| Recruiting Agency Submissions | Enable third-party staffing agencies to submit candidates directly into Workday requisitions. |
| Compliance and EEO Reporting | Capture self-identification data and applicant flow logs to satisfy EEO, OFCCP, and regional reporting requirements. |
| Internal Mobility | Connect internal career site workflows to surface roles to existing employees. |
| High-Volume Hiring | Power retail, hospitality, and seasonal hiring with bulk applicant import and rapid-disposition workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Workday HCM | Native integration with Workday Human Capital Management for seamless transition from candidate to employee. |
| LinkedIn Talent Solutions | Connect with LinkedIn Recruiter and LinkedIn Job Postings for sourcing and posting workflows. |
| Indeed | Distribute Workday job postings to Indeed and ingest applications back into Workday. |
| HireRight | Background check integration for criminal, employment, and education verification. |
| Sterling | Background screening, drug testing, and identity verification integration. |
| HackerRank | Technical assessment integration for engineering and developer hiring pipelines. |
| Calendly | Self-schedule interview integration for candidate-driven scheduling. |
| Microsoft Outlook and Teams | Calendar and meeting integration for interview scheduling and coordination. |
| Google Workspace | Calendar and meeting integration for interview scheduling. |
| DocuSign | E-signature integration for offer letter and onboarding document workflows. |
| Workday Marketplace Partners | Pre-built integrations with talent acquisition vendors listed in the Workday Marketplace. |

## Solutions

| Name | Description |
|------|-------------|
| Workday Talent Acquisition | End-to-end recruiting solution from sourcing through hire, unifying recruiting with the broader Workday HCM platform. |
| HiredScore AI for Recruiting | AI-driven candidate matching, screening, and recruiter productivity embedded in Workday Recruiting. |
| Workday Onboarding | Native onboarding handoff that converts hires into engaged employees inside the Workday HCM system of record. |
| Workday Skills Cloud | Skills-driven hiring leveraging the Workday skills ontology across requisitions and candidate profiles. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Workday Recruiting REST API](openapi/workday-recruiting-rest-api-openapi.yml)

### WSDL

- [Workday Recruiting SOAP Web Services](wsdl/workday-recruiting-soap.wsdl)

### XSD

- [Workday Recruiting SOAP Schema](xsd/workday-recruiting-soap.xsd)

### JSON-LD

- [Workday Recruiting REST API Context](json-ld/workday-recruiting-rest-api-context.jsonld)

### JSON Schema

28 entity schemas under [json-schema/](json-schema/) covering applicants, attachments, background checks, candidates, candidate assessments, evergreen requisitions, interviews, interview feedback, job applications, job postings, job posting sites, job requisitions, offers, positions, questionnaires, recruiting agencies, references, and veteran statuses (including create variants where applicable).

### JSON Structure

28 JSON Structure definitions under [json-structure/](json-structure/) mirroring the JSON Schema set.

### Examples

28 example payloads under [examples/](examples/) for each REST entity.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Workday Recruiting REST API](capabilities/shared/recruiting.yaml) — 47 operations for the full hiring lifecycle (requisitions, candidates, applications, interviews, background checks, agencies, applicants, positions, configuration)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Requisition Management](capabilities/requisition-management.yaml) | Workday Recruiting REST API | 17 | Hiring Manager, Recruiter |
| [Candidate Pipeline](capabilities/candidate-pipeline.yaml) | Workday Recruiting REST API | 19 | Recruiter, Sourcer |
| [Interview and Screening](capabilities/interview-and-screening.yaml) | Workday Recruiting REST API | 8 | Recruiter, Hiring Manager |
| [Recruiting Configuration](capabilities/recruiting-configuration.yaml) | Workday Recruiting REST API | 3 | Recruiting Administrator |

## Vocabulary

- [Workday Recruiting Vocabulary](vocabulary/workday-recruiting-vocabulary.yaml) — Unified taxonomy mapping 17 resources, 17 actions, 4 workflows, and 7 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Workday Recruiting Spectral Rules](rules/workday-recruiting-spectral-rules.yml) — 67 rules across 14 categories enforcing Workday Recruiting API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
