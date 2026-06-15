# Microsoft Azure Functions (microsoft-azure-functions)

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
