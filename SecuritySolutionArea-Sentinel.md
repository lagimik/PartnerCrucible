---
title: "Partner Crucible - Security Workloads - Sentinel"
layout: "default"
categories: "Security"
---

# Security Workloads - Sentinel

![Sentinel](./Library/sentinel-logo.png)

# Purpose

A Collection of resources for building Sentinel and SOC demos. For a view of other Workloadss, please see the [Taxonomy](./Taxonomy).

To contribute to the PartnerCrucible, see [Contributor's Guide](ContributorsGuide).

# Industry

Source | Description | Notes
:----- | :-----  | :-----
[Microsoft named a Leader in the 2025 Gartner® Magic Quadrant™ for SIEM](https://www.microsoft.com/en-us/security/blog/2025/10/16/microsoft-named-a-leader-in-the-2025-gartner-magic-quadrant-for-siem/) |  2025 Gartner® Magic Quadrant™ for Security Information and Event Management (SIEM)| Garter
[The Total Economic Impact Of Microsoft Azure Sentinel](https://www.microsoft.com/en-us/security/blog/2024/03/19/microsoft-sentinel-delivered-234-roi-according-to-new-forrester-study/) | Microsoft commissioned Forrester Consulting to conduct a Total Economic Impact™ (TEI) study. Using the methodology of the TEI framework, Forrester consultants evaluated the cost, benefits, and flexibility of Microsoft Sentinel and developed a framework that organizations can use to evaluate the potential financial impact on their organizations. | Forrester 2024

# Practices and Tools

Source | Description | Notes
:----- | :---------- | :----
[Azure Sentinel Technical Playbook for MSSPs](http://aka.ms/azsentinelmssp)| How to deploy Azure Sentinel as a managed security services provider | March 2021
[Microsoft Sentinel for MSSPs](https://learn.microsoft.com/en-us/azure/sentinel/multiple-tenants-service-providers) | If you're a managed security service provider (MSSP) and you're using Azure Lighthouse to offer security operations center (SOC) services to your customers, you can manage your customers' Microsoft Sentinel resources directly from your own Azure tenant, without having to connect to the customer's tenant | Microsoft Learn
[Sentinel POC – Architecture and Recommendations for MSSPs ](https://myfabersecurity.com/2023/03/31/sentinel-poc-architecture-and-recommendations-for-mssps-part-1/) | This post is a part of series that covers various topics from the very basics, to ensure partners that may be familiar with other SIEMs, but that are not yet familiar with Azure can get all the information they need to be successful.| My Faber Security
[Microsoft Sentinel All-in-One](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/announcing-microsoft-sentinel-all-in-one-v2/ba-p/3800037) | Microsoft Sentinel All-in-One is aimed at helping customers and partners quickly set up a full-fledged Microsoft Sentinel environment that is ready to use by customers speeding up deployment and initial configuration tasks in few clicks, saving time and simplifying Microsoft Sentinel setup.| Blogs
[Microsoft Sentinel All-in-One - GitHub](https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One) | | GitHub
[Centrally manage multiple Microsoft Sentinel workspaces with workspace manager](https://learn.microsoft.com/en-us/azure/sentinel/workspace-manager) | This article takes you through provisioning and usage of workspace manager. Whether you're a global enterprise or a Managed Security Services Provider (MSSP), workspace manager helps you operate at scale efficiently. | Microsoft Learn
[Protecting MSSP intellectual property in Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/mssp-protect-intellectual-property) | This article describes the methods that managed security service providers (MSSPs) can use to protect intellectual property they've developed in Microsoft Sentinel, such as Microsoft Sentinel analytics rules, hunting queries, playbooks, and workbooks | Microsoft Learn
[Sentinel Migration Guides](https://docs.microsoft.com/en-us/azure/sentinel/migration)| These are detailed guides to migrate from ArcSight, QRadar and Splunk; migrate historical data, convert dashboards to workbooks and update SOC processes.| Microsoft Learn
[Splunk Migration](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/siem-migration-update-now-migrate-with-contextual-depth-in/ba-p/4241234) | The process of moving from Splunk to Microsoft Sentinel via the SIEM Migration experience has been enhanced with three key additions that help customers get more context aware translations of their detections from Splunk to Sentinel. These features let customers provide more contextual details about their Splunk environment & usage to the Microsoft Sentinel SIEM Migration translation engine so it can account for them when converting the detections from SPL to KQL.| Tech Community
[Azure Sentinel Tools](https://github.com/Azure/Azure-Sentinel/tree/master/Tools) | Microsoft Sentinel API integrations, tools and deployment templates that can enable you to easily: connect your solutions with Microsoft Sentinel, deploy in Microsoft Sentinel, migrate to Microsoft Sentinel, work easily and connect to different products in Microsoft Sentinel| GitHub
[Azure Sentinel Playbook](https://github.com/Azure/Azure-Sentinel/tree/master/Playbooks) | This repo contains sample security playbooks for security automation, orchestration and response (SOAR). Each folder contains a security playbook ARM template that uses Microsoft Sentinel trigger. | GitHub
[Introducing the next generation of SOC automation: Sentinel playbook generator](https://techcommunity.microsoft.com/blog/microsoftsentinelblog/introducing-the-next-generation-of-soc-automation-sentinel-playbook-generator/4494438) | Announces the Sentinel playbook generator to accelerate SOC automation and playbook creation in Microsoft Sentinel. | Tech Community
[Overview of Advanced Hunting](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/advanced-hunting-overview?view=o365-worldwide) | Advanced hunting is a query-based threat-hunting tool that lets you explore up to 30 days of raw data. |
[Microsoft Sentinel and Microsoft 365 Defender](https://github.com/Azure/Azure-Sentinel) | This repository contains out of the box detections, exploration queries, hunting queries, workbooks, playbooks and much more to help you get ramped up with Microsoft Sentinel and provide you security content to secure your environment and hunt for threats. The hunting queries also include Microsoft 365 Defender hunting queries for advanced hunting scenarios in both Microsoft 365 Defender and Microsoft Sentinel.| GitHub
[How to use Azure Sentinel for Incident Response Orchestration](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/how-to-use-azure-sentinel-for-incident-response-orchestration/ba-p/2242397) | Microsoft Tech Community Article
[Automate tasks management to protect your organization against threats](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/automate-tasks-management-to-protect-your-organization-against/ba-p/3884516) | While tasks can be added manually from within the Sentinel console, playbooks, and automation rules can be used to automatically create tasks based on certain conditions.  | Tech Community
[Connect your threat intelligence platform to Microsoft Sentinel with the upload indicators API](https://learn.microsoft.com/en-us/azure/sentinel/connect-threat-intelligence-upload-api) | This data connector uses the Sentinel upload indicators API to ingest threat intelligence indicators into Microsoft Sentinel. | Microsoft Learn
[Microsoft Sentinel Transformations Library](https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Transformations-Library)| This repository contains samples for multiple scenarios that are possible thanks to the new Log Analytics Custom Logs v2 and pipeline transformation features.| GitHub
[Microsoft Sentinel Triage Assistant (STAT)](https://github.com/briandelmsft/SentinelAutomationModules) | The Microsoft Sentinel Triage AssistanT (STAT) is a Logic Apps Custom Connector that calls on a library of Automation Modules that can be used from Incident based Microsoft Sentinel playbooks. This connector and modules simplify automation by moving complex automation tasks into these callable modules so they can be performed consistently and with ease from the Logic Apps Connector. | GitHub
[Bring your own Machine Learning (ML) into Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/bring-your-own-ml) | Machine Learning (ML) is one of the major underpinnings of Microsoft Sentinel, and one of the main attributes that set it apart. Microsoft Sentinel offers ML in several experiences: built-in to the Fusion correlation engine and Jupyter notebooks, and the newly available Build-Your-Own ML (BYO ML) platform | ,,,
[BYO-ML Github](https://github.com/Azure/Azure-Sentinel-BYOML) | Build-Your-Own Machine Learning(BYO ML) package is provided by Azure Sentinel team to help organizations build or bring your own ML to tackle security problems specifically for your business. This folder contains the BYO ML package including the first ML algorithm Azure Sentinel team shares. | ...
[Discover the power of UEBA anomalies in Microsoft Sentinel](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/discover-the-power-of-ueba-anomalies-in-microsoft-sentinel/ba-p/3576185) | Our mission in Microsoft Sentinel UEBA is to detect insider and unknown threats – so we surface those suspicious activities that won’t be detected by other platforms. Since we’re looking into and analyzing that grey area of activities - we’re able to provide insights on threats that might have been missed otherwise. | ...
[UEBA Reference](https://learn.microsoft.com/en-us/azure/sentinel/ueba-reference) | This reference article lists the input data sources for the User and Entity Behavior Analytics service in Microsoft Sentinel. It also describes the enrichments that UEBA adds to entities, providing needed context to alerts and incidents. | Azure docs
[Using Cribl Stream to ingest logs into Microsoft Sentinel](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/using-cribl-stream-to-ingest-logs-into-microsoft-sentinel/ba-p/4179790) |  Microsoft and Cribl are working to drive accelerated SIEM migrations for customers looking to modernize their security operations (SecOps) with Microsoft Sentinel. | Tech Community

# Training

Source | Description | Notes
:----- | :---------- | :----
[Microsoft Sentinel Black Belt](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/what-s-new-earn-your-microsoft-sentinel-black-belt-digital-badge/ba-p/3071558)| New for 2022, our Cloud Security Private Community Digital Badge program has introduced a new L5 Microsoft Sentinel Black Belt Digital Badge for you to earn and display proudly to show your prowess as a Microsoft recognized expert and contributor to the product.|...
[Sentinel Ninja](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/become-a-microsoft-sentinel-ninja-the-complete-level-400/ba-p/1246310)| October 2024: This Ninja updated - Ninja Training program — a structured and in-depth journey (level 400)  into the platform’s capabilities.| Tech Community
[The Art and Science of Threat Hunting](https://www.microsoft.com/security/blog/2022/09/08/part-1-the-art-and-science-of-threat-hunting/) | From Microsoft Security Experts and Microsoft Detection and Response Team (DART) | September 2022

# Sentinel Demo References

Source | Description | Notes
:----- | :-----  | :-----
[Microsoft 365 Defender - Demo Hero Environment]()| - M365 Defender (Protection, Detection, Alerts vs Incidents)<br>-Defender for Cloud (Alerts, Security Posture, Cloud Protection)<br>-Microsoft Sentinel for multiple data sources Analytic Rules (Scheduled, ML, Anomaly,  Fusion) <br>-Threat Vulnerability Management<br>-Integration with Microsoft Endpoint Management for patch and configuration  management<br>-Automatic remediations from M365 Defender<br>-Playbooks from Microsoft Sentinel | Read-Only environment
[Azure Sentinel To-Go (Part1)](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-to-go-part1-a-lab-w-prerecorded-data-amp-a-custom/ba-p/1260191)|A Lab w/ Prerecorded Data and a Custom Logs Pipe via ARM Templates|...
[Cost Worthy Azure Sentinel Demo](https://azurecloudai.blog/2020/09/01/steps-to-create-a-cost-worthy-azure-sentinel-demo-testing-environment/)| Steps to Create a Cost Worthy Azure Sentinel Demo/Testing Environment|...
[Microsoft Sentinel Training Lab](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/learning-with-the-microsoft-sentinel-training-lab/ba-p/2953403)| This solution ingests sample data into your Microsoft Sentinel workspace which will trigger incidents that allow you to explore Microsoft Sentinel features without Additional effort |...
[Integrate Azure Data Explorer for long-term log retention](https://learn.microsoft.com/en-us/azure/sentinel/store-logs-in-azure-data-explorer?tabs=adx-event-hub) | Storing logs in Azure Data Explorer reduces costs while retains your ability to query your data, and is especially useful as your data grows. | Microsoft Learn


