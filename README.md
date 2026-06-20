# Flightcontrol (flightcontrol)

Flightcontrol deploys applications to your own AWS account with a Heroku-like developer experience. It provisions and manages AWS infrastructure from a flightcontrol.json config-as-code file and exposes an HTTP management API for triggering deployments, managing environments, services, environment variables, scaling, jobs, domains, and CloudFront cache invalidation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flightcontrol/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flightcontrol/refs/heads/main/apis.yml)

## Tags

- Deployment
- AWS
- PaaS
- Infrastructure
- DevOps

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Flightcontrol Management API

Bearer-authenticated HTTP API to integrate Flightcontrol with CI/CD and automation - read deployment status, create and edit environments, list services, set environment variables, update service scaling, and run scheduler jobs.

- **Human URL:** [https://www.flightcontrol.dev/docs/reference/http-api](https://www.flightcontrol.dev/docs/reference/http-api)
- **Base URL:** `https://api.flightcontrol.dev/v1`

#### Tags

- Deployments
- Environments
- Services

#### Properties

- [Documentation](https://www.flightcontrol.dev/docs/reference/http-api)
- [API Reference](https://www.flightcontrol.dev/docs/reference/http-api)
- [OpenAPI](openapi/flightcontrol-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flightcontrol.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flightcontrol.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flightcontrol Deploy Hooks API

Secret-in-URL GET deploy hooks to trigger a deployment for a normal or preview environment from any build or CI system; returns the new deploymentId.

- **Human URL:** [https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks](https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks)
- **Base URL:** `https://app.flightcontrol.dev/api`

#### Tags

- Deploy Hooks
- Webhooks
- CI/CD

#### Properties

- [Documentation](https://www.flightcontrol.dev/docs/reference/http-api/deployments/deploy-hooks)
- [OpenAPI](openapi/flightcontrol-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flightcontrol.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flightcontrol.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flightcontrol CloudFront Invalidation API

Create a CloudFront cache invalidation for a service's distribution and check the status of a prior invalidation request.

- **Human URL:** [https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api](https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api)
- **Base URL:** `https://api.flightcontrol.dev/v1`

#### Tags

- CloudFront
- Cache
- CDN

#### Properties

- [Documentation](https://www.flightcontrol.dev/docs/reference/http-api/cloudfront/cache-invalidation-api)
- [OpenAPI](openapi/flightcontrol-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flightcontrol.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flightcontrol.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flightcontrol Config-as-Code

Version-controlled flightcontrol.json (or flightcontrol.cue) declaring environments, services, regions, sources, and environment variables that drive AWS provisioning; a published JSON Schema enables editor autocompletion.

- **Human URL:** [https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code](https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code)
- **Base URL:** `https://app.flightcontrol.dev`

#### Tags

- Config as Code
- Infrastructure as Code
- flightcontrol.json

#### Properties

- [Documentation](https://www.flightcontrol.dev/docs/guides/flightcontrol/using-code)
- [JSON Schema](https://app.flightcontrol.dev/schema.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/flightcontrol)
- [Website](https://www.flightcontrol.dev)
- [Documentation](https://www.flightcontrol.dev/docs)
- [Plans](plans/flightcontrol-plans-pricing.yml)
- [Rate Limits](rate-limits/flightcontrol-rate-limits.yml)
- [Fin Ops](finops/flightcontrol-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
