# Microsoft Azure Functions (microsoft-azure-functions)

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

Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services. The Azure Functions management API provides programmatic access to function app lifecycle management, deployment, configuration, scaling, and monitoring through Azure Resource Manager.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Azure
- Cloud
- Compute
- Event-Driven
- Microsoft
- Serverless

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Azure Functions Management API

The Azure App Service / Web Apps REST API provides management operations for Azure Functions apps including creating and configuring function apps, managing deployment slots, application settings, host keys, function keys, scaling configuration, and monitoring. Part of the Azure Resource Manager API surface.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/appservice/web-apps](https://learn.microsoft.com/en-us/rest/api/appservice/web-apps)
- **Base URL:** `https://management.azure.com`

#### Tags

- App Service
- Deployment
- Functions
- Management
- Resource Manager
- Serverless

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/appservice/web-apps)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/appservice/web-apps/get)
- [Authentication](https://learn.microsoft.com/en-us/rest/api/azure/#register-your-client-application-with-azure-ad)
- [OpenAPI](openapi/azure-functions-management-api.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-functions-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-functions-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Functions Runtime API

The Azure Functions host runtime provides HTTP endpoints for function invocation, admin operations, host status, function management, and key management. Includes endpoints for listing functions, getting function status, managing host and function keys, and triggering function execution.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference)
- **Base URL:** `https://{functionapp}.azurewebsites.net`

#### Tags

- Event-Driven
- Functions
- HTTP Trigger
- Runtime
- Serverless

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-cli-csharp)
- [Authentication](https://learn.microsoft.com/en-us/azure/azure-functions/security-concepts)
- [Postman Collection](collections/azure-functions-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-functions-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://portal.azure.com/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/azure-functions/functions-get-started)
- [Documentation](https://learn.microsoft.com/en-us/azure/azure-functions/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/functions/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Status Page](https://status.azure.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/)
- [Changelog](https://learn.microsoft.com/en-us/azure/azure-functions/functions-versions)
- [GitHub Organization](https://github.com/Azure)
- [GitHub Repository](https://github.com/Azure/azure-functions-host)
- [GitHub Repository](https://github.com/Azure/azure-functions-core-tools)
- [SDK](https://www.nuget.org/packages/Microsoft.Azure.Functions.Worker)
- [SDK](https://pypi.org/project/azure-functions/)
- [SDK](https://www.npmjs.com/package/@azure/functions)
- [SDK](https://central.sonatype.com/artifact/com.microsoft.azure.functions/azure-functions-java-library)
- [C L I](https://github.com/Azure/azure-functions-core-tools)
- [C L I](https://learn.microsoft.com/en-us/cli/azure/functionapp)
- [Training](https://learn.microsoft.com/en-us/training/paths/create-serverless-applications/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-functions)
- [X (Twitter)](https://x.com/AzureFunctions)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [M C P Server](https://github.com/Azure/azure-functions-mcp-extension)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
