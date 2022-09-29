# Security Solution Area - Sentinel Demos

![Sentinel](./Library/sentinel-logo.png)

[< Back to Crucible](./)

## Purpose

A Collection of resources for building Sentinel and SOC demos. For a view of other solution areas, please see the [Taxonomy](Taxonomy.md). 

To contribute to the PartnerCrucible, see [Contributor's Guide](ContributorsGuide).

## Sentinel Demo References

Source | Description | Notes
:----- | :-----  | :-----
[Microsoft 365 Defender - Demo Hero Environment]()| - M365 Defender (Protection, Detection, Alerts vs Incidents)<br>-Defender for Cloud (Alerts, Security Posture, Cloud Protection)<br>-Microsoft Sentinel for multiple data sources Analytic Rules (Scheduled, ML, Anomaly,  Fusion) <br>-Threat Vulnerability Management<br>-Integration with Microsoft Endpoint Management for patch and configuration  anagement<br>-Automatic remediations from M365 Defender<br>-Playbooks from Microsoft Sentinel | Read-Only environment 
[Azure Sentinel To-Go (Part1)](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-to-go-part1-a-lab-w-prerecorded-data-amp-a-custom/ba-p/1260191)|A Lab w/ Prerecorded Data and a Custom Logs Pipe via ARM Templates|...
[Cost Worthy Azure Sentinel Demo](https://azurecloudai.blog/2020/09/01/steps-to-create-a-cost-worthy-azure-sentinel-demo-testing-environment/)| Steps to Create a Cost Worthy Azure Sentinel Demo/Testing Environment|...
[Azure Sentinel Playbook](https://github.com/Azure/Azure-Sentinel/tree/master/Playbooks) | This repo contains sample security playbooks for security automation, orchestration and response (SOAR). Each folder contains a security playbook ARM template that uses Microsoft Sentinel trigger. | 
[Overview of Advanced Hunting](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/advanced-hunting-overview?view=o365-worldwide) | Advanced hunting is a query-based threat-hunting tool that lets you explore up to 30 days of raw data. |
[How to use Azure Sentinel for Incident Response Orchestration](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/how-to-use-azure-sentinel-for-incident-response-orchestration/ba-p/2242397) | Microsoft Tech Community Article
[Microsoft Sentinel Training Lab](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/learning-with-the-microsoft-sentinel-training-lab/ba-p/2953403)| This solution ingests sample data into your Microsoft Sentinel workspace which will trigger incidents that allow you to explore Microsoft Sentinel features without Additional effort |...

## Bring your own ML
Source | Description | Notes
:----- | :-----  | :-----
[Bring your own Machine Learning (ML) into Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/bring-your-own-ml) | Machine Learning (ML) is one of the major underpinnings of Microsoft Sentinel, and one of the main attributes that set it apart. Microsoft Sentinel offers ML in several experiences: built-in to the Fusion correlation engine and Jupyter notebooks, and the newly available Build-Your-Own ML (BYO ML) platform | ,,,
[BYO-ML Github](https://github.com/Azure/Azure-Sentinel-BYOML) | Build-Your-Own Machine Learning(BYO ML) package is provided by Azure Sentinel team to help organizations build or bring your own ML to tackle security problems specifically for your business. This folder contains the BYO ML package including the first ML algorithm Azure Sentinel team shares. | ...

## User and Entity Behaviour Analytics (UEBA)
Source | Description | Notes
:----- | :-----  | :-----
[Discover the power of UEBA anomalies in Microsoft Sentinel](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/discover-the-power-of-ueba-anomalies-in-microsoft-sentinel/ba-p/3576185) | Our mission in Microsoft Sentinel UEBA is to detect insider and unknown threats – so we surface those suspicious activities that won’t be detected by other platforms. Since we’re looking into and analyzing that grey area of activities - we’re able to provide insights on threats that might have been missed otherwise. | ...
[UEAB Reference](https://learn.microsoft.com/en-us/azure/sentinel/ueba-reference) | This reference article lists the input data sources for the User and Entity Behavior Analytics service in Microsoft Sentinel. It also describes the enrichments that UEBA adds to entities, providing needed context to alerts and incidents. | Azure docs

[< Back to Crucible](./)
