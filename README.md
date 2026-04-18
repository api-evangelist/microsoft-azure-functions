# Microsoft Azure Functions (microsoft-azure-functions)
Azure Functions is a serverless compute platform from Microsoft Azure enabling event-driven code execution triggered by HTTP requests, timers, queues, blobs, and other Azure services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-functions/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Cloud, Compute, Event-Driven, Microsoft, Serverless

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-17

## APIs

### Azure Functions Management API
The Azure App Service / Web Apps REST API provides management operations for Azure Functions apps including creating and configuring function apps, managing deployment slots, application settings, host keys, function keys, scaling configuration, and monitoring.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/appservice/web-apps](https://learn.microsoft.com/en-us/rest/api/appservice/web-apps)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/appservice/web-apps)
- [OpenAPI](openapi/azure-functions-management-api.json) — 518 endpoints, 695 schemas (v2025-05-01)

### Azure Functions Runtime API
The Azure Functions host runtime provides HTTP endpoints for function invocation, admin operations, host status, function management, and key management.

**Human URL:** [https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Documentation](https://learn.microsoft.com/en-us/azure/azure-functions/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/functions/)
- [Status Page](https://status.azure.com/)
- [.NET SDK](https://www.nuget.org/packages/Microsoft.Azure.Functions.Worker)
- [Python SDK](https://pypi.org/project/azure-functions/)
- [Node.js SDK](https://www.npmjs.com/package/@azure/functions)
- [Java SDK](https://central.sonatype.com/artifact/com.microsoft.azure.functions/azure-functions-java-library)
- [Azure Functions Core Tools CLI](https://github.com/Azure/azure-functions-core-tools)
- [Training](https://learn.microsoft.com/en-us/training/paths/create-serverless-applications/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-functions)

## Features

| Name | Description |
|------|-------------|
| HTTP Triggers | Execute functions via HTTP requests with RESTful endpoint support and built-in authentication. |
| Timer Triggers | Schedule function execution using CRON expressions for recurring tasks. |
| Queue Triggers | Process messages from Azure Storage Queues and Service Bus for async workloads. |
| Blob Triggers | React to blob storage changes for file processing and data pipeline automation. |
| Event Grid Triggers | Handle events from Azure Event Grid for event-driven architectures. |
| Cosmos DB Triggers | Process database changes in Azure Cosmos DB using the change feed. |
| Durable Functions | Orchestrate complex stateful workflows with function chaining, fan-out/fan-in, and human interaction patterns. |
| Deployment Slots | Manage staging and production slots for zero-downtime deployments and traffic splitting. |
| Custom Handlers | Run functions in any language by implementing a lightweight HTTP server. |
| Managed Identity | Authenticate to Azure services without managing credentials using system or user-assigned identities. |
| Scaling | Automatic scaling from zero to thousands of instances based on event load. |
| Premium Plan | Pre-warmed instances, VNET integration, and unlimited execution duration for enterprise workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| API Backend | Build serverless REST APIs with HTTP-triggered functions and Azure API Management integration. |
| Event Processing | Process events from queues, topics, Event Grid, and IoT Hub for real-time data pipelines. |
| Scheduled Tasks | Run scheduled jobs for data cleanup, report generation, and system maintenance. |
| File Processing | Transform, validate, and process files uploaded to blob storage. |
| Webhook Handling | Receive and process webhooks from third-party services and SaaS platforms. |
| Microservices | Build lightweight microservices with independent scaling and deployment. |
| Data Transformation | ETL workloads for transforming and loading data between Azure services. |
| IoT Backend | Process IoT device telemetry and events with Event Hub and IoT Hub triggers. |

## Integrations

| Name | Description |
|------|-------------|
| Azure API Management | Front Azure Functions with API Management for rate limiting, authentication, and developer portal. |
| Azure DevOps | CI/CD pipeline integration for automated function deployment and testing. |
| GitHub Actions | Deploy Azure Functions directly from GitHub repositories with Actions workflows. |
| Visual Studio Code | Full development experience with the Azure Functions VS Code extension. |
| Azure Monitor | Application Insights integration for function monitoring, logging, and diagnostics. |
| Azure Key Vault | Secure secrets management with Key Vault references in application settings. |
| Terraform | Infrastructure-as-code management of function apps with the AzureRM Terraform provider. |

## Solutions

| Name | Description |
|------|-------------|
| Consumption Plan | Pay-per-execution pricing with automatic scaling and 5-minute execution timeout. |
| Premium Plan | Pre-warmed instances, VNET integration, unlimited duration, and larger instance sizes. |
| Dedicated Plan | Run functions on dedicated App Service plans for predictable pricing and always-on execution. |
| Container Apps | Run containerized functions on Azure Container Apps for Kubernetes-based hosting. |

## Artifacts

### OpenAPI

- [Azure Functions Management API](openapi/azure-functions-management-api.json) — 518 endpoints, 695 schemas (v2025-05-01, from Azure REST API specs)

### JSON Schema

29 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

29 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Azure Functions Context](json-ld/azure-functions-context.jsonld) — 29 types, 158 properties

### Examples

29 example JSON files in [examples/](examples/).

## Vocabulary

- [Azure Functions Vocabulary](vocabulary/azure-functions-vocabulary.yaml) — 8 resources, 2 APIs, 4 domains, 4 personas

## Rules

- [Azure Functions Spectral Rules](rules/azure-functions-spectral-rules.yml) — 19 rules enforcing Azure API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
