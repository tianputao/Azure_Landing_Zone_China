# Enterprise-Scale Landing Zones ARM templates

> The content that was previously here has been archived as it is no longer relevant. Please follow the guidance in the [ALZ Wiki](https://aka.ms/alz/wiki) for the latest information on how to deploy Enterprise-Scale Landing Zones.
> To view the content that was previously here, refer to the [archive](https://github.com/Azure/Enterprise-Scale/blob/45d5c2bd8c1a9e19b1a46a3a0dabb311e5320b64/eslzArm/README.md).

This folder contains the first-party ARM templates for Enterprise-Scale which and are being used when deploying and bootstrapping in the Azure Portal.
<!-- cSpell:ignore multisubscription -->

# What is an Azure landing zone?

Azure landing zones are the output of a multisubscription Azure environment that accounts for scale, security governance, networking, and identity. Azure landing zones enable application migration, modernization and innovation at enterprise-scale in Azure. These zones consider all platform resources that are required to support the customer's application portfolio and don't differentiate between infrastructure as a service or platform as a service.

![Diagram that shows a landing zone design.](https://github.com/tianputao/Azure_Landing_Zone_China/blob/main/lz-design-Diagram.png)

A landing zone is an environment for hosting your workloads, preprovisioned through code. Watch the following video to learn more.

<!-- markdownlint-disable MD034 -->

> [!VIDEO https://www.microsoft.com/videoplayer/embed/RE4xdvm]

<!-- markdownlint-enable MD034 -->

## Scalable and modular

No single solution fits all technical environments. A few Azure landing zone implementation options can help you meet the deployment and operations needs of your growing cloud portfolio.

- **Scalable:** All Azure landing zones support cloud adoption at scale by providing repeatable environments, with consistent configuration and controls, regardless of the workloads or Azure resources deployed to each landing zone instance.
- **Modular:** All Azure landing zones provide a modular approach to building out your environment, based on a common set of design areas. Each design area can be easily extended to support the distinct needs of various technology platforms like Azure SQL Database, Azure Kubernetes Service, and Azure Virtual Desktop.

 Whether you're looking to deploy your first production application to Azure or you're operating a complex portfolio of tech platforms and workloads, the Azure landing zone implementation options can be tailored to your needs.

## Azure landing zone conceptual architecture

For the majority of organizations, the Azure landing zone conceptual architecture shown below represents the destination in their cloud adoption journey. It's a mature, scaled-out target architecture intended to help organizations operate successful cloud environments that drive their business whilst maintaining best practice security and governance.

This conceptual architecture represents scale and maturity decisions based on a wealth of lessons learned and feedback from customers who have adopted Azure as part of their digital estate.

While your specific implementation may vary, as a result of specific business decisions or existing investments in tools that need to persist in your cloud environment, this conceptual architecture will help set a direction for the overall approach your organization takes to designing and implementing a landing zone.

![Azure landing zone conceptual architecture diagram](https://github.com/tianputao/Azure_Landing_Zone_China/blob/main/ES-ALZ-Diagram.png)

## Azure landing zone accelerator

For organizations where this conceptual architecture fits with the operating model and resource structure they plan to use, there is a ready-made deployment experience available which we call the **Azure landing zone accelerator**.

The accelerator is an Azure portal-based deployment that will provide a full implementation of the conceptual architecture, along with opinionated configurations for key components such as management groups and policies.


## Deploy Azure platform landing zone
[![`DTA-Button-ALZ`](https://eslzfiles.blob.core.chinacloudapi.cn/images/azureChinaIcon.png?sanitize=true)](https://portal.azure.cn/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Feslzfiles.blob.core.chinacloudapi.cn%2Fdefault-landingzone-files%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Feslzfiles.blob.core.chinacloudapi.cn%2Fdefault-landingzone-files%2Feslz-portal.json)

## Test
[![`DTA-Button-ALZ`](https://eslzfiles.blob.core.chinacloudapi.cn/images/azureChinaIcon.png?sanitize=true)](https://portal.azure.cn/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Frefs%2Fheads%2Fmain%2FeslzArm%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Frefs%2Fheads%2Fmain%2FeslzArm%2Feslz-portal.json)

## Deploy Azure application landing zone
[![`DTA-Button-ALZ`](https://eslzfiles.blob.core.chinacloudapi.cn/images/azureChinaIcon.png?sanitize=true)](https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftianputao%2FAzure_Landing_Zone_China%2Fmain%2Fapplication_landing_zone.json)

There are other deployment options available, some that deliver the full architecture using third-party deployment technologies, and others that start from a smaller footprint. For more information, see [Implementation options](./implementation-options.md).

## Next steps

Organizations may be at different stages of their cloud journey when reviewing this guidance. As a result, the actions and recommendations required to progress toward the outcome detailed above may vary. To understand best next actions in relation to where you are in your cloud adoption, review the journey to the target architecture content.

> [!div class="nextstepaction"]
> [Journey to the target architecture](./landing-zone-journey.md)

When you're choosing the right Azure landing zone implementation option, you should understand the [Azure landing zone design areas](./design-areas.md).

> [!div class="nextstepaction"]
> [Review design areas](./design-areas.md)
