# Security Solution Area - Sentinel

![Sentinel](./Library/sentinel-logo.png)

[< Back to Crucible](./)

## Purpose

A Collection of resources for building Sentinel and SOC demos. For a view of other solution areas, please see the [Taxonomy](Taxonomy.md).

To contribute to the PartnerCrucible, see [Contributor's Guide](ContributorsGuide).

## Industry reports

Source | Description | Notes
:----- | :-----  | :-----
[Magic Quadrant for Security Information and Event Management](https://www.gartner.com/doc/reprints?id=1-2AHCXAHG&ct=220701&st=sb) | Gatner Magic Quadrant for SIEM | October 2022
[Microsoft named a Leader in the 2022 Gartner® Magic Quadrant™ for Security Information and Event Management](https://www.microsoft.com/en-us/security/blog/2022/10/13/microsoft-named-a-leader-in-the-2022-gartner-magic-quadrant-for-security-information-and-event-management/) | We’re delighted to announce that Microsoft is named a Leader in the 2022 Gartner® Magic QuadrantTM for Security Information and Event Management and is positioned highest on the measure of Ability to Execute axis.| Microsoft
[Forrester names Microsoft a Leader in Q4 2022 Security Analytics Platforms Wave report](https://www.microsoft.com/en-us/security/blog/2022/12/19/forrester-names-microsoft-a-leader-in-q4-2022-security-analytics-platforms-wave-report/) | Microsoft achieved the highest possible score in 17 different criteria, including partner ecosystem, innovation roadmap, product security, case management, and architecture. | Forrester Wave

## Sentinel Demo References

Source | Description | Notes
:----- | :-----  | :-----
[Microsoft Sentinel and Microsoft 365 Defender](https://github.com/Azure/Azure-Sentinel) | This repository contains out of the box detections, exploration queries, hunting queries, workbooks, playbooks and much more to help you get ramped up with Microsoft Sentinel and provide you security content to secure your environment and hunt for threats. The hunting queries also include Microsoft 365 Defender hunting queries for advanced hunting scenarios in both Microsoft 365 Defender and Microsoft Sentinel.| GitHub
[Microsoft 365 Defender - Demo Hero Environment]()| - M365 Defender (Protection, Detection, Alerts vs Incidents)<br>-Defender for Cloud (Alerts, Security Posture, Cloud Protection)<br>-Microsoft Sentinel for multiple data sources Analytic Rules (Scheduled, ML, Anomaly,  Fusion) <br>-Threat Vulnerability Management<br>-Integration with Microsoft Endpoint Management for patch and configuration  management<br>-Automatic remediations from M365 Defender<br>-Playbooks from Microsoft Sentinel | Read-Only environment
[Azure Sentinel To-Go (Part1)](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-to-go-part1-a-lab-w-prerecorded-data-amp-a-custom/ba-p/1260191)|A Lab w/ Prerecorded Data and a Custom Logs Pipe via ARM Templates|...
[Cost Worthy Azure Sentinel Demo](https://azurecloudai.blog/2020/09/01/steps-to-create-a-cost-worthy-azure-sentinel-demo-testing-environment/)| Steps to Create a Cost Worthy Azure Sentinel Demo/Testing Environment|...
[Azure Sentinel Playbook](https://github.com/Azure/Azure-Sentinel/tree/master/Playbooks) | This repo contains sample security playbooks for security automation, orchestration and response (SOAR). Each folder contains a security playbook ARM template that uses Microsoft Sentinel trigger. |
[Overview of Advanced Hunting](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/advanced-hunting-overview?view=o365-worldwide) | Advanced hunting is a query-based threat-hunting tool that lets you explore up to 30 days of raw data. |
[How to use Azure Sentinel for Incident Response Orchestration](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/how-to-use-azure-sentinel-for-incident-response-orchestration/ba-p/2242397) | Microsoft Tech Community Article
[Microsoft Sentinel Training Lab](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/learning-with-the-microsoft-sentinel-training-lab/ba-p/2953403)| This solution ingests sample data into your Microsoft Sentinel workspace which will trigger incidents that allow you to explore Microsoft Sentinel features without Additional effort |...
[Integrate Azure Data Explorer for long-term log retention](https://learn.microsoft.com/en-us/azure/sentinel/store-logs-in-azure-data-explorer?tabs=adx-event-hub) | Storing logs in Azure Data Explorer reduces costs while retains your ability to query your data, and is especially useful as your data grows. | Microsoft Learn

## Training

Source | Description | Notes
:----- | :---------- | :----
[Azure Sentinel Technical Playbook for MSSPs](http://aka.ms/azsentinelmssp)| How to deploy Azure Sentinel as a managed security services provider | March 2021
[Microsoft Sentinel for MSSPs](https://learn.microsoft.com/en-us/azure/sentinel/multiple-tenants-service-providers) | If you're a managed security service provider (MSSP) and you're using Azure Lighthouse to offer security operations center (SOC) services to your customers, you can manage your customers' Microsoft Sentinel resources directly from your own Azure tenant, without having to connect to the customer's tenant | Microsoft Learn
[Sentinel Migration Guides](https://docs.microsoft.com/en-us/azure/sentinel/migration)| These are detailed guides to migrate from ArcSight, QRadar and Splunk; migrate historical data, convert dashboards to workbooks and update SOC processes.|
[Microsoft Sentinel Black Belt](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/what-s-new-earn-your-microsoft-sentinel-black-belt-digital-badge/ba-p/3071558)| New for 2022, our Cloud Security Private Community Digital Badge program has introduced a new L5 Microsoft Sentinel Black Belt Digital Badge for you to earn and display proudly to show your prowess as a Microsoft recognized expert and contributor to the product.|...
[Sentinel Ninja](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/become-a-microsoft-sentinel-ninja-the-complete-level-400/ba-p/1246310)| Sentinel Ninja Training
[The Art and Science of Threat Hunting](https://www.microsoft.com/security/blog/2022/09/08/part-1-the-art-and-science-of-threat-hunting/) | From Microsoft Security Experts and Microsoft Detection and Response Team (DART) | September 2022

## Bring your own

Source | Description | Notes
:----- | :-----  | :-----
[Bring your own Machine Learning (ML) into Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/bring-your-own-ml) | Machine Learning (ML) is one of the major underpinnings of Microsoft Sentinel, and one of the main attributes that set it apart. Microsoft Sentinel offers ML in several experiences: built-in to the Fusion correlation engine and Jupyter notebooks, and the newly available Build-Your-Own ML (BYO ML) platform | ,,,
[BYO-ML Github](https://github.com/Azure/Azure-Sentinel-BYOML) | Build-Your-Own Machine Learning(BYO ML) package is provided by Azure Sentinel team to help organizations build or bring your own ML to tackle security problems specifically for your business. This folder contains the BYO ML package including the first ML algorithm Azure Sentinel team shares. | ...

## User and Entity Behaviour Analytics (UEBA)

Source | Description | Notes
:----- | :-----  | :-----
[Discover the power of UEBA anomalies in Microsoft Sentinel](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/discover-the-power-of-ueba-anomalies-in-microsoft-sentinel/ba-p/3576185) | Our mission in Microsoft Sentinel UEBA is to detect insider and unknown threats – so we surface those suspicious activities that won’t be detected by other platforms. Since we’re looking into and analyzing that grey area of activities - we’re able to provide insights on threats that might have been missed otherwise. | ...
[UEBA Reference](https://learn.microsoft.com/en-us/azure/sentinel/ueba-reference) | This reference article lists the input data sources for the User and Entity Behavior Analytics service in Microsoft Sentinel. It also describes the enrichments that UEBA adds to entities, providing needed context to alerts and incidents. | Azure docs

[< Back to Crucible](./)
