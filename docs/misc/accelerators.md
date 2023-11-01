---
# Page settings
layout: default
keywords: Azure AppSource
comments: false

title: Marketplace Technical Accelerators
hide:
  - toc
---

Marketplace technical accelerators are a set of tools and templates that help you build and deploy your Marketplace offer. The accelerators are designed to help you build your offer quickly and efficiently.

Resources on this page include both technical accelerators and example references.

<!-- no toc -->
- [SaaS Accelerator](#saas-accelerator)
- [SaaS client libraries and tools](#saas-client-libraries-and-tools)
    - [.NET client library](#net-client-library)
    - [Java client library](#java-client-library)
    - [Microsoft Commercial Marketplace SaaS API Emulator](#microsoft-commercial-marketplace-saas-api-emulator)
    - [SaaS API Postman scripts](#saas-api-postman-scripts)
- [Accelerators supporting metered billing](#accelerators-supporting-metered-billing)
    - [Custom Meters Accelerator](#custom-meters-accelerator)
    - [Metered Billing Accelerator](#metered-billing-accelerator)
- [Commercial Marketplace solutions](#commercial-marketplace-solutions)
- [ARM-TTK validation tool](#arm-ttk-validation-tool)

---

## SaaS Accelerator

The SaaS Accelerator provides a fully functional community-led SaaS reference implementation for those interested in publishing transactable SaaS offers in Microsoft's marketplace in hours instead of days. In support of the Saas Accelerator, the Mastering the Marketplace content library has a complete course on how to build a SaaS offer using the SaaS Accelerator.

- [SaaS Accelerator on GitHub](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator)
- [SaaS Accelerator on-demand course](../saas-accelerator/index.md)

## SaaS client libraries and tools

The SaaS client libraries help you build your SaaS offer. The libraries provide strongly-typed wrappers on top of the SaaS Fulfillment and Metered Billing APIs that you can use in building your own integrations to the marketplace.

### .NET client library

- [.NET client library on GitHub](https://github.com/microsoft/commercial-marketplace-client-dotnet)
- [.NET client library on NuGet](https://www.nuget.org/packages/Marketplace.SaaS.Client)

### Java client library

- [Java client library on GitHub](https://github.com/microsoft/commercial-marketplace-client-java)

### Microsoft Commercial Marketplace SaaS API Emulator

Integrating with the commercial marketplace has a few scaffolding requirements; a barrier to getting up and running quickly. The emulator breaks that dependency, allowing teams to start building for marketplace with zero friction or dependency on the production APIs. The tool is a Node.js implementation of an emulator for the Microsoft commercial marketplace SaaS Fulfillment APIs.

- <a href="https://github.com/microsoft/Commercial-Marketplace-SaaS-API-Emulator" target="blank"></a>


### SaaS API Postman scripts

The SaaS API Postman scripts provide a set of Postman scripts that you can use to test the SaaS Fulfillment and Metered Billing APIs. The scripts are available on GitHub and include a predefined Postman collection and environment.

- <a href="https://github.com/microsoft/commercial-marketplace-resources/blob/main/src/postman/README.md" target="blank">SaaS API Postman scripts on GitHub</a>

## Accelerators supporting metered billing

There are two solutions for enhancing the metered billing capabilities of your solution. Both have different approaches and value-propositions. Please evaluate each accelerator to determine which will best suit your needs.

### Custom Meters Accelerator

A production-ready opensource solution that enables partners to implement and manage advanced meter models for Managed Application offers.​ This solution enables scheduling billing events to occur in the future.

​Empowers partners to surpass the constraints of current meter features, tailoring meter approaches to fit unique business requirements.

- <a href="https://github.com/microsoft/custom-meters-accelerator" target="blank">Project on GitHub</a>

### Metered Billing Accelerator

Developers enabling their Azure Managed Application or SaaS offers in the Azure Marketplace must keep track of the metered billing usage in their code and only send usage events to Microsoft for the usage that is above the base fee. This is a requirement for all offers that leverage metered billing.

The Metered Billing Accelerator is a tool to help you build and deploy your metered billing offer with minimal impact to your core application code, enabling applications to emit metered billing events to Microsoft with minimal changes to the application code.

- [Marketplace Mini video overview](./marketplace-minis.md#an-introduction-to-the-metered-billing-accelerator)
- <a href="https://github.com/microsoft/metered-billing-accelerator" target="blank">Project on GitHub</a>

## Commercial Marketplace solutions repository

A collection of starter solutions to enable various marketplace scenarios. See this GitHub repository for details.

- <a href="https://github.com/microsoft/commercial-marketplace-solutions" target="blank">Commercial Marketplace solutions</a>

## ARM-TTK validation tool

A PowerShell tool for analyzing and testing Azure Resource Manager templates and CreateUiDefinition.json files. The tests will check a for coding best practices.

- <a href="https://github.com/Azure/arm-ttk" target="blank">ARM-TTK validation tool</a>