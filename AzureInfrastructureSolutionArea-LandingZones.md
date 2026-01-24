---
title: "Partner Crucible - Infrastructure Workloads - Landing Zones"
layout: "default"
categories: "Infrastructure"
---

# Azure Infrastructure - Landing Zones

![Azure Infrastructure](./Library/Azure-LandingZone.png)

## Purpose

A Collection of resources for Microsoft practice building in the **Azure Landing Zones**. For a view of other Workloadss, please see the [Taxonomy](./Taxonomy).

To contribute to the PartnerCrucible, see [Contributor's Guide](ContributorsGuide).


## Azure Tools and Approaches

Source | Description | Notes
:----- | :---------- | :-----
[Azure Design Review](https://github.com/Azure/review-checklists) | Checklists for LZ, AKS, AVS, Multitenancy, Security, AVS, and SAP | Github
[Tailor the Azure landing zone architecture to meet requirements](https://learn.microsoft.com/en-gb/azure/cloud-adoption-framework/ready/landing-zone/tailoring-alz) | Because not all use cases are the same, not all organizations can use an implementation approach in the exact way it was intended. You need to understand the considerations when a requirement for tailoring is identified | Microsoft Learn
[Transition an existing Azure environment to the Azure landing zone reference architecture](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/enterprise-scale/transition) | Recommendations to help your organization navigate changes based on your existing Azure environment that's transitioning into the Azure landing zone reference architecture. This article describes considerations for moving resources, subscriptions, and scenarios for alignment. | Microsoft Learn
[Testing approach for Azure landing zones](https://learn.microsoft.com/en-ca/azure/cloud-adoption-framework/ready/enterprise-scale/testing-approach) | The canary management group hierarchy can be independently used to author and test deployments before you deploy them into the production environment. | Microsoft Learn
[Cloudockit](https://www.cloudockit.com/) |Automatically Generate Architecture Diagrams and Technical Documentation of Your Cloud Environments | by Lansweeper

## Landing Zone Accelerators

Source | Description | Notes
:----- | :---------- | :-----
[AI Landing Zone - Preview](https://github.com/Azure/AI-Landing-Zones) | The AI Landing Zone provides an enterprise-scale production ready reference architecture with implementation (Portal, Bicep & Terraform) to deploy secure and resilient AI Apps & Agents solutions in Azure. | GitHub
[Azure OpenAI Landing Zone reference architecture](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-openai-landing-zone-reference-architecture/ba-p/3882102) | In this article, we delve into the synergy of Azure Landing Zones and Azure OpenAI Service, building a secure and scalable AI environment. unpacking the Azure OpenAI Landing Zone architecture, which integrates numerous Azure services for optimal AI workloads. | Tech Community
[Building and Deploying Azure AI Landing Zones with Terraform](https://techcommunity.microsoft.com/t5/azure-architecture-blog/empowering-ai-building-and-deploying-azure-ai-landing-zones-with/ba-p/3891249) | In this article, we delve into leveraging Terraform to deploy the Azure OpenAI Landing Zone architecture concentrating on the connectivity and application aspects. By integrating various Azure services and implementing features like Azure Firewall, Virtual Networks, and Private Endpoints, Private DNS Zones, organizations can create a secure and scalable AI environment.| Tech Community
[Landing zone accelerator for Azure Container Apps](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/announcing-landing-zone-accelerator-for-azure-container-apps/ba-p/3843989) | Design Area Guidance providing recommendations and considerations organized along critical design areas: Security, Networking, Identity & Access Management, and Monitoring. Reference implementation providing reference architecture and customizable scripting to provision Azure Container Apps and deploy workloads to production-grade secure infrastructure.| Tech Community
[Landing Zone Accelerator for Spring Apps](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/build-right-and-fast-landing-zone-accelerator-for-spring-apps/ba-p/3903517) | Azure Spring Apps (ASA) landing zone accelerator. You can start deploying your spring applications to Azure Spring Apps at scale using the built with industry-proven practices.|Tech Community
[Azure VMWare Solution Landing Zone Accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/azure-vmware/enterprise-scale-landing-zone) | The Azure VMware Solution accelerator provides a reference implementation for a scalable Azure VMware Solution in your landing zone. The design decisions your organization makes, based on the guidance provided by the accelerator, lay the groundwork for scalability. | Microsoft Learn
[AKS Landing Zone Accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/landing-zone-accelerator) |  The following guidance provides design considerations for implementing a scalable AKS cluster in your landing zone. | Microsoft Learn
[Azure Integration Services landing zone accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/landing-zone-accelerator) | Azure Integration Services landing zone accelerator is intended for an application team that's building and deploying an integration platform in a typical enterprise landing zone design.| Microsoft Learn
[APIM Landing Zone Accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/landing-zone-accelerator) | The Azure API Management landing zone accelerator provides an architectural approach and reference implementation to prepare landing zone subscriptions for a scalable API Management infrastructure. | Microsoft Learn
[Azure App Service landing zone accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/app-services/landing-zone-accelerator) | The Azure App Service landing zone accelerator is an open-source collection of architectural guidance and reference implementation to accelerate deployment of Azure App Service at scale | Microsoft Learn
[Azure Red Hat OpenShift landing zone accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/azure-red-hat-openshift/landing-zone-accelerator) | The Azure Red Hat OpenShift landing zone accelerator is a collection of design guidance and implementation references to accelerate deployment of Azure Red Hat OpenShift clusters in your landing zone. | Microsoft Learn
[Cloud-scale analytics data management landing zone overview](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/architectures/data-management-landing-zone) | The data management landing zone is a management function and is central to cloud-scale analytics. It's responsible for the governance of your analytics platform. | Microsoft Learn
[Independent software vendor (ISV) considerations for Azure landing zones](https://learn.microsoft.com/en-ca/azure/cloud-adoption-framework/ready/landing-zone/isv-landing-zone?tabs=mg-env-no%2Cminimal) |The landing zones describe how to build an Azure environment with multiple subscriptions. Each landing zone accounts for scale, security, governance, networking, and identity, and is based on feedback and lessons learned from many customers. | Microsoft Learn
[Azure Landing Zones for Canadian Public Sector](https://github.com/Azure/CanadaPubSecALZ/blob/main/docs/architecture.md)| The purpose of the reference implementation is to guide Canadian Public Sector customers on building Landing Zones in their Azure environment.| Github
[Healthcare landing zone guidance](https://github.com/Azure/CanadaPubSecALZ/blob/main/docs/archetypes/healthcare.md)| Landing zone for healthcare data platform| Github
[Cloud-scale analytics data management landing zone](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/architectures/data-management-landing-zone) | The data management landing zone is a management function and is central to cloud-scale analytics. It's responsible for the governance of your analytics platform.| Microsoft Learn
[Azure Landing Zone Accelerator for Modernized Mainframe and Midrange workloads](https://github.com/lapate/azure-mainframe-landing-zone-public) | This provides a prescriptive solution platform design coupled with Azure best practices and design principles. These principles serve as a compass for subsequent design decisions across critical technical domains | GitHub
[Data landing zones](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/architectures/data-landing-zone) | Data landing zones are connected to your data management landing zone by virtual network (VNet) peering. Each data landing zone is considered a landing zone related to Azure landing zone architecture. | Microsoft Learn
[SAP on Azure landing zone accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/sap/enterprise-scale-landing-zone)| AP on Azure landing zone accelerator to set up and operate workload landing zones inside your Cloud Adoption Framework enterprise-scale landing zone. The landing zone accelerator provides a specific architectural approach and reference implementation for your SAP systems on Azure.| Microsoft Learn
[Azure AIML Landing Zone (TerraForm)](https://github.com/Azure/terraform-azurerm-avm-ptn-aiml-landing-zone) | This pattern module creates the full AI/ML landing zone which supports multiple ai project scenarios.| GitHub


