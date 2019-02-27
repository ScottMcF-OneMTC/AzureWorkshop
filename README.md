# Azure Engineering Workshop for Enterprises

This repository is an aggregation of links and content to support a multi-day Azure workshop delivered by an Azure technical expert, focused on medium to large enterprises that are adopting Azure beyond a few subscriptions. The content is based on dozens of workshops delivered on the Microsoft Redmond campus between our Core Services Engineering & Operations engineers and engineers from our large enterprise customers.

If there's something missing, please just ping me on Twitter at [@lyledodge](https://twitter.com/lyledodge), or send me an email at [lyle.dodge@microsoft.com](mailto:lyle.dodge@microsoft.com).

## Sample Multi-Day Workshop Agenda

Most of the time we take 2-3 topics from the below list per day, and have 1-2 60-90 minute breakout sessions on each.

| Content Area  | What to Expect  |
|---------|---------|
| [Digital Transformation](#digital-transformaion) | Content from CSE&O leadership on our own transformation |
| [Operations and Service Management](#operations-and-service-management) | From an infrastructure and operations point of view, how CSE&O manages our hundreds of Azure subscriptions that run our Line of Business Applications |
| [Subscriptions](#subscriptions) | Everything around subscriptions and subscription management |
| [DevOps](#devops) | Everything around our usage of Azure DevOps, from thousands of builds/releases per day to how our software engineering teams work in the same tools as the business |
| [Enterprise Telemetry](#enterprise-telemetry) | Usage of Azure telemetry and storage options for engineering and business cases |
| [Security](#security) | |
| [Networking](#networking) | |
| Culture Changes | |
| Manageability     |         |
| VM Build     |         |
| [Performance Optimization](#performance-optimization) | Various articles on optimizing the performance of your Azure footprint |
| Spend Optimization     |         |
| High Availability / Disaster Recovery     |         |
| SAP     |         |
| ARM Templates     |         |
| Monitoring     |         |
| Business Intelligence     |         |
| [In Depth LoB Application Examples](#in-depth-lob-application-examples) | A few deeper examples from our Line of Business Application teams |

## Digital Transformation

|What(link)  |Who  |Description  |
|---------|---------|---------|
| [Product Development Mindset at Microsoft's Core Services Engineering - A talk with Kurt DelBene, Chief Digital Officer  - Technology, meet Strategy: The lessons from Microsoft’s Digital Transformation with the Chief Digital Officer](https://channel9.msdn.com/Events/Build/2018/BRK2509) | Kurt DelBene, Julia White | Microsoft's Chief Digital Officer talking about our own digital transformation at //BUILD 2018 |
| [BRK2380 - Transforming IT: Key insights about Microsoft’s own digital transformation with the Chief Digital Officer](https://myignite.techcommunity.microsoft.com/sessions/66276) | Kurt DelBene, Julia White | Microsoft's Chief Digital Officer on transforming IT at Ignite 2018 |

## Operations and Service Management

|What(link)  |Who  |Description  |
|---------|---------|---------|
|[Enterprise Cloud at Microsoft - October 2018](https://www.youtube.com/watch?v=eacCccm-vg4)     | Pete Apple, Lyle Dodge        | An overview of CSE&O's Journey to Azure, from 40k+ on premise servers to today. Showing our own data and using the **Enterprise Cloud at Microsoft** deck from the Microsoft Executive Briefing Center. |

## Subscriptions

| What (link)  | Who  | Description | Format |
|---------|---------|---------|---------|
| [Azure Enterprise Scaffold](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/appendix/azure-scaffold) | - | The official Azure Enterprise Scaffold covering various Subscription models. | Docs |
| [Organizing subscriptions and resource groups within the Enterprise (Azure Blog)](https://azure.microsoft.com/en-us/blog/organizing-subscriptions-and-resource-groups-within-the-enterprise/) | Lyle Dodge | How **CSE&O** organizes our subscriptions and the access methods within the subscriptions leveraging Azure Resource Groups, RBAC and ALT accounts. | Blog Post |

## DevOps

| What (link)  | Who  | Description |
|---------|---------|---------|
| [DevOps, Agile & Azure with James Gagnon, Software Engineering Lead](https://www.youtube.com/watch?v=LhI75Uy6ANA) | James Gagnon, Cloudsimplified.io | todo |
| [CI/CD Pipelines using Azure DevOps w/Ronald Klemz in Microsoft’s Core Services Engineering org](https://www.youtube.com/watch?v=CdUQfY8OO1s) | Ronald Klemz, Lyle Dodge | todo |
| [CI/CD Pipelines Demo using Azure DevOps w/Ronald Klemz (follow up question from YouTube comment)](https://www.youtube.com/watch?v=UykEsmFfWaQ) | Ronald Klemz, Lyle Dodge | todo |
|[Branching Strategies in Azure DevOps w/Ronald Klemz in Microsoft’s Core Services Engineering org](https://www.youtube.com/watch?v=fxe7UAVWb5M)  | Ronald Klemz, Lyle Dodge | todo |
|[Moving thousands of employees and projects from TFS to Azure DevOps](https://www.youtube.com/watch?v=YXdrkNtFG0A) | Henry Dixon, Abel Wang | todo |

## Enterprise Telemetry

|What (link)  | Who  | Description |
|---------|---------|---------|
|[CSE&O's Frank Chen on the Unified Telemetry Platform](https://www.youtube.com/watch?v=m8QkFHTS43I) | Frank Chen, Lyle Dodge | An overview of how CSE&O built their unified telemetry platform to have one place for application teams, infrastructure, and business program managers point their systems to for telemetry. Allow for reporting and correlation across groups. |
|[CSE&O's Joe Pirelli on getting the right data points for your Line of Business Applications](https://www.youtube.com/watch?v=LpsZz_hslbM) | Joe Pirelli, Lyle Dodge | How one software engineering team looks at getting the right data points across both engineers and the business to maximize value to both groups. |

## Security

|What(link)  |Who  |Description  |
|---------|---------|---------|
| [Azure Secure DevOps Toolkit](https://github.com/azsk/DevOpsKit) | - | If you're doing anything in Azure, you need to deploy this today. Maintained by CSE&O on a public Github repository, comes with tools for developers via a powershell module to scan a subscription for best practices, and instructions for setting up an enterprise wide view of your risk posture. |
| [Azure Secure DevOps Toolkit on Azure Friday]() | Mark Jacobs, Scott Hanselman | A video introduction to the Secure DevOps Toolkit on the Azure Friday show. |
| [Creating and Establishing Security Parameters in the Cloud](https://www.youtube.com/watch?v=uRWJFTXW27E&t=66s) | Robert Venable, Cloudsimplified.io | Robert is a lead architect in our Finance engineering organization tasked with securely architecting our finance and big data applications. | 

## Networking

|What(link)  |Who  |Description  |
|---------|---------|---------|
| [Supporting a network in transition: How Microsoft made its move to the Cloud](https://www.youtube.com/watch?v=N9tri5u4LF0) | David Lef, Cloudsimplified.io | A conversation with one of our lead networking architects for Microsoft's corporate network design |

## Performance Optimization

|What(link)  |Who  |Description  |
|---------|---------|---------|
| [Enabling Azure SQL Database Auto-Tuning at Scale for Microsoft IT](https://channel9.msdn.com/Blogs/Azure-in-the-Enterprise/Enabling-Azure-SQL-Database-Auto-Tuning-at-Scale-for-Microsoft-IT) | Rajesh Vasireddy, Lyle Dodge | What happens when you let the underlying statistics across an entire organization's footprint of Azure SQL Databases work for you? Billions of reads per day gone and vastly improved performance. Let your DBAs work on higher value work and stop doing index tuning all together. |

## In Depth LoB Application Examples

Serverless in Supply Chain - Microsoft' Devices Supply Chain team replatform from BizTalk to Azure Cloud Native

|Title  |Who  | Description | Format |
|---------|---------|---------|---------|
| [BRK2110 - Azure Messaging and event-based architecture in the real world: Lessons learned rebuilding Microsoft’s Supply chain on Azure Serverless](https://channel9.msdn.com/Events/Build/2018/BRK2110) | Hariharan Sundaram, Lyle Dodge | //BUILD 2018 Overview Presentation | Video |
| [Serverless in Supply Chain - Leveraging Azure Event Hubs & Azure Functions to enhance application telemetry](https://www.microsoft.com/itshowcase/blog/serverless-in-supply-chain-leveraging-azure-event-hubs-azure-functions-to-enhance-application-telemetry/) | todo | todo | Blog Post / Video |
| [Serverless in Supply Chain - Introduction and architectural overview )](https://www.microsoft.com/itshowcase/blog/serverless-in-supply-chain-introduction-and-architectural-overview?wc.mc_id=itshowcase-codeapps-lydodg) | todo | todo | Blog Post / Video |
| [Serverless in Supply Chain - Leveraging API management for B2B partner integration](https://www.microsoft.com/itshowcase/blog/serverless-in-supply-chain-leveraging-api-management-for-b2b-partner-integration?wc.mc_id=itshowcase-codeapps-lydodg) | todo | todo | Blog Post / Video |
| [Serverless in Supply Chain: Leveraging Azure Active Directory for authentication and authorization](https://www.microsoft.com/itshowcase/blog/serverless-in-supply-chain-leveraging-aad-for-authentication-and-authorization?wc.mc_id=itshowcase-codeapps-lydodg) | todo | todo | Blog Post / Video |
| [Serverless in Supply Chain - B2B integration layer walkthrough](https://www.microsoft.com/itshowcase/blog/serverless-in-supply-chain-b2b-integration-layer-walkthrough?wc.mc_id=itshowcase-codeapps-lydodg) | todo | Blog Post / Video |


### Random Stuff

The table below is just a series of unsorted links that we know we need to get into this repository.

|What  |Link  |Who  |
|---------|---------|---------|
| []() |x  |x |

