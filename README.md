# Snow Software (snow-software)

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

Snow Software (now Flexera Snow) is an IT asset and SaaS management platform providing visibility into software licenses, cloud spend, SaaS usage, and hardware assets across the enterprise. Snow Atlas is the cloud-native platform offering SAM (Software Asset Management), SaaS Management, Cloud License Management, and Commander for hybrid IT. The Snow Atlas REST APIs enable programmatic access to licenses, computers, SaaS applications, subscriptions, user accounts, agreements, and audit logs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud License Management
- FinOps
- IT Asset Management
- SaaS Management
- Software Asset Management

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Snow Atlas SAM Licenses API

The Snow Atlas SAM Licenses API provides programmatic access to software license data including license upgrades, application license transfers, computer license tracking, license policies, maintenance periods, purchase orders, and license metrics. Supports filtering and pagination.

- **Human URL:** [https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis)

#### Tags

- IT Asset Management
- License Management
- Software Asset Management

#### Properties

- [Documentation](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-licenses-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snow-software-computers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection](collections/snow-software-licenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-licenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snow Atlas SaaS Applications API

The Snow Atlas SaaS Applications API provides visibility into SaaS applications in use across the organization. Enables listing, updating, and managing SaaS apps, application KPIs, users, and consumption data for SaaS spend optimization.

- **Human URL:** [https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis)

#### Tags

- SaaS Management
- Software Asset Management
- Spend Optimization

#### Properties

- [Documentation](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-applications-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snow-software-computers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection](collections/snow-software-licenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-licenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snow Atlas SaaS Subscriptions API

The Snow Atlas SaaS Subscriptions API manages SaaS subscription data including subscription details, costs, renewal dates, and vendor information for enterprise SaaS portfolio management.

- **Human URL:** [https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis)

#### Tags

- Contract Management
- SaaS Management
- Subscription Management

#### Properties

- [Documentation](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-subscriptions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snow-software-computers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection](collections/snow-software-licenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-licenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snow Atlas SAM Computers API

The Snow Atlas SAM Computers API provides access to computer inventory data including hardware assets, application metering per computer, installed software, update history, custom values, and bulk status management for IT asset lifecycle management.

- **Human URL:** [https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis)

#### Tags

- Hardware Asset Management
- IT Asset Management
- Inventory

#### Properties

- [Documentation](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-computers-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snow-software-computers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman Collection](collections/snow-software-licenses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-licenses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/snow-software-saas-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snow-software-saas-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/snow-software-ab)
- [Website](https://www.snowsoftware.com)
- [Documentation](https://docs.snowsoftware.com/)
- [Developer Portal](https://docs.flexera.com/snow-atlas/snow-atlas-api/get-started-with-apis)
- [GitHub Organization](https://github.com/SnowSoftware)
- [Integrations](https://github.com/SnowSoftware/snowatlas-integrations)
- [Blog](https://www.snowsoftware.com/blog)
- [Support](https://community.snowsoftware.com)
- [Login](https://app.snowsoftware.io)
- [About](https://www.snowsoftware.com/company)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
