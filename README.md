# RapidAPI (rapidapi)

RapidAPI operates the world's largest API marketplace, connecting developers to thousands of APIs through a single platform. Their developer platform provides tools for API discovery, testing, management, design, and gateway configuration, enabling both individual developers and enterprises to build, consume, and manage APIs at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Marketplace
- API Management
- API Testing
- API Gateway
- API Design
- Enterprise

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-02

## APIs

### RapidAPI REST Platform API

The RapidAPI REST Platform API allows developers and administrators to programmatically manage their API hub configurations through RESTful endpoints. It provides CRUD operations for organizations, categories, tags, collections, transactions, subscriptions, and users, enabling automation of tasks normally performed through the Enterprise Hub Admin Panel and integration of hub management into CI/CD pipelines and custom workflows.

**Human URL:** [https://docs.rapidapi.com/docs/platform-api-overview](https://docs.rapidapi.com/docs/platform-api-overview)

#### Tags

- API Management
- Platform
- Administration
- Marketplace
- Enterprise

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/platform-api-overview)
- [OpenAPI](openapi/rapidapi-rest-platform-api-openapi.yml)
- [JSONStructure](json-structure/rapidapi-subscription-structure.json)
- [Example](examples/rapidapi-list-apis-example.json)
- [Example](examples/rapidapi-list-subscriptions-example.json)
- [SpectralRules](rules/rapidapi-rules.yml)
- [NaftikoCapabilities](capabilities/hub-management.yaml)

### RapidAPI GraphQL Platform API

The RapidAPI GraphQL Platform API exposes the same queries and mutations that RapidAPI uses internally, providing enterprise users with a powerful interface for managing their API hub. It supports creating and updating APIs, managing collections, and configuring hub settings through GraphQL queries and mutations, including integration with GitHub Actions for continuous deployment of API configurations.

**Human URL:** [https://docs.rapidapi.com/docs/graphql-platform-api-overview](https://docs.rapidapi.com/docs/graphql-platform-api-overview)

#### Tags

- GraphQL
- Platform
- API Management
- Enterprise
- Administration

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/graphql-platform-api-overview)
- [OpenAPI](openapi/rapidapi-graphql-platform-api-openapi.yml)

### RapidAPI Hub API

The RapidAPI Hub is the world's largest API marketplace, enabling developers to discover, test, and connect to thousands of APIs using a single API key. The hub provides a unified interface for browsing APIs across categories such as weather, social media, e-commerce, and finance, with auto-generated code snippets in multiple programming languages and a single dashboard for managing subscriptions and usage analytics.

**Human URL:** [https://docs.rapidapi.com/docs/consumer-quick-start-guide](https://docs.rapidapi.com/docs/consumer-quick-start-guide)

#### Tags

- API Discovery
- API Marketplace
- API Testing
- Integration
- Search

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/consumer-quick-start-guide)
- [OpenAPI](openapi/rapidapi-hub-api-openapi.yml)

### RapidAPI Testing API

RapidAPI Testing provides a comprehensive API testing and monitoring solution that supports REST, SOAP, and GraphQL APIs. It offers an intuitive interface for creating and running functional tests, performance tests, and automated monitoring checks. The testing platform integrates with CI/CD pipelines, enabling teams to verify API behavior as part of their development workflow. Tests can be scheduled to run periodically across 9 AWS regions to monitor API health and detect regressions.

**Human URL:** [https://docs.rapidapi.com/docs/testing-getting-started](https://docs.rapidapi.com/docs/testing-getting-started)

#### Tags

- API Testing
- Monitoring
- Quality Assurance
- Automation
- CI/CD

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/testing-getting-started)
- [OpenAPI](openapi/rapidapi-testing-api-openapi.yml)
- [JSONSchema](json-schema/rapidapi-test-schema.json)
- [JSONStructure](json-structure/rapidapi-test-structure.json)
- [Example](examples/rapidapi-list-tests-example.json)
- [NaftikoCapabilities](capabilities/api-quality-assurance.yaml)

### RapidAPI Studio API

RapidAPI Studio is an API design and development environment that enables teams to design, build, and document APIs collaboratively. It supports importing and editing OpenAPI specifications and Postman Collections, providing a visual interface for defining endpoints, parameters, and response schemas, and integrates with the broader RapidAPI platform to publish designed APIs directly to the hub.

**Human URL:** [https://docs.rapidapi.com/docs/studio-overview](https://docs.rapidapi.com/docs/studio-overview)

#### Tags

- API Design
- API Development
- OpenAPI
- Studio

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/studio-overview)
- [OpenAPI](openapi/rapidapi-studio-api-openapi.yml)
- [JSONSchema](json-schema/rapidapi-api-listing-schema.json)
- [JSONStructure](json-structure/rapidapi-api-listing-structure.json)

### RapidAPI Gateway API

The RapidAPI Gateway provides enterprise-grade API gateway capabilities for managing API traffic, security, and routing. It enables organizations to configure custom gateways that handle authentication, rate limiting, and request routing for their APIs, providing a centralized point of control for all API traffic flowing through the RapidAPI platform.

**Human URL:** [https://docs.rapidapi.com/docs/gateway-configuration](https://docs.rapidapi.com/docs/gateway-configuration)

#### Tags

- API Gateway
- Traffic Management
- Security
- Enterprise
- Routing

#### Properties

- [Documentation](https://docs.rapidapi.com/docs/gateway-configuration)
- [OpenAPI](openapi/rapidapi-gateway-api-openapi.yml)
- [JSONSchema](json-schema/rapidapi-gateway-config-schema.json)

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/rest-platform-api.yaml](capabilities/shared/rest-platform-api.yaml) | RapidAPI REST Platform API — organizations, APIs, subscriptions, and users |
| [capabilities/shared/testing-api.yaml](capabilities/shared/testing-api.yaml) | RapidAPI Testing API — tests, executions, environments, and schedules |

### Workflow Capabilities

| Capability | Description | Operations |
|---|---|---|
| [capabilities/hub-management.yaml](capabilities/hub-management.yaml) | Enterprise Hub administrator workflow for API lifecycle management, organization control, and subscription oversight | 8 tools |
| [capabilities/api-quality-assurance.yaml](capabilities/api-quality-assurance.yaml) | Quality engineering workflow for API test management, execution monitoring, and multi-region scheduling | 5 tools |

## Common Properties

- [Portal](https://rapidapi.com/hub)
- [Documentation](https://docs.rapidapi.com/)
- [Website](https://rapidapi.com/)
- [Privacy Policy](https://rapidapi.com/privacy/)
- [Terms of Service](https://rapidapi.com/terms-of-service/)
- [Support](https://rapidapi.com/support/)
- [Blog](https://rapidapi.com/blog/)
- [Sign Up](https://rapidapi.com/auth/sign-up)
- [JSONLD](json-ld/rapidapi-context.jsonld)
- [Vocabulary](vocabulary/rapidapi-vocabulary.yml)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
