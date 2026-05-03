# Snow Software

Snow Software (now part of Flexera) is an IT asset and SaaS management platform providing visibility into software licenses, cloud spend, SaaS usage, and hardware assets across the enterprise. Snow Atlas is the cloud-native platform offering SAM (Software Asset Management), SaaS Management, Cloud License Management, and Commander for hybrid IT. The Snow Atlas REST APIs enable programmatic access to licenses, computers, SaaS applications, subscriptions, user accounts, agreements, and audit logs.

## APIs

- [Snow Atlas SAM Licenses API](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis) - Programmatic access to software licenses, upgrades, policies, computer tracking, and maintenance data.
- [Snow Atlas SaaS Applications API](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis) - SaaS portfolio visibility including applications, KPIs, users, and spend analysis.
- [Snow Atlas SaaS Subscriptions API](https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis) - SaaS subscription contract management including costs, renewals, and license counts.
- [Snow Atlas SAM Computers API](https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis) - Computer inventory and installed software tracking for ITAM.

## Properties

- [Website](https://www.snowsoftware.com)
- [Documentation](https://docs.snowsoftware.com/)
- [Developer Portal](https://docs.flexera.com/snow-atlas/snow-atlas-api/get-started-with-apis)
- [GitHub Organization](https://github.com/SnowSoftware)
- [Integrations Repository](https://github.com/SnowSoftware/snowatlas-integrations)

## Artifacts

### OpenAPI
- [snow-software-licenses-openapi.yml](openapi/snow-software-licenses-openapi.yml) — SAM Licenses API (license upgrades, policies, computer tracking, maintenance periods)
- [snow-software-saas-applications-openapi.yml](openapi/snow-software-saas-applications-openapi.yml) — SaaS Applications API (apps, KPIs, users, consumption)
- [snow-software-saas-subscriptions-openapi.yml](openapi/snow-software-saas-subscriptions-openapi.yml) — SaaS Subscriptions API (subscription details, costs, renewals)
- [snow-software-computers-openapi.json](openapi/snow-software-computers-openapi.json) — SAM Computers API (inventory, application metering, custom values)

### Rules
- [snow-software-rules.yml](rules/snow-software-rules.yml) — Spectral ruleset enforcing Snow Atlas API conventions (pagination, region variables, HATEOAS)

### Capabilities
- [it-asset-management.yaml](capabilities/it-asset-management.yaml) — Unified workflow for Snow Atlas ITAM, license management, and SaaS portfolio analysis

#### Shared Definitions
- [capabilities/shared/licenses-api.yaml](capabilities/shared/licenses-api.yaml) — Snow Atlas SAM Licenses API shared capability definition
- [capabilities/shared/saas-applications-api.yaml](capabilities/shared/saas-applications-api.yaml) — Snow Atlas SaaS Applications API shared capability definition

### JSON Schema
- [snow-software-license-schema.json](json-schema/snow-software-license-schema.json) — Schema for Snow Atlas software license objects
- [snow-software-saas-application-schema.json](json-schema/snow-software-saas-application-schema.json) — Schema for Snow Atlas SaaS application and subscription objects

### JSON Structure
- [snow-software-atlas-structure.json](json-structure/snow-software-atlas-structure.json) — Hierarchical structure of Snow Atlas ITAM and SaaS management objects

### JSON-LD
- [snow-software-context.jsonld](json-ld/snow-software-context.jsonld) — JSON-LD context for Snow Software IT asset management linked data semantics

### Examples
- [snow-software-get-saas-applications-example.json](examples/snow-software-get-saas-applications-example.json) — List SaaS applications in Snow Atlas with pagination

### Vocabulary
- [snow-software-vocabulary.yml](vocabulary/snow-software-vocabulary.yml) — Domain vocabulary for Snow Software ITAM, SAM, SaaS management, and FinOps concepts
