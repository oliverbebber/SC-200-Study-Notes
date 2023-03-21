# SC-200: Microsoft Security Operations Analyst

This project is a work in progress while I study and take notes for the SC-200 Exam.

# Disclaimer

Do not rely on these notes to pass the exam. It's advised to use Microsoft's study guide for the exam: https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4Myp3


## Skills measured as of February 7, 2023

### Audience profile

The Microsoft security operations analyst collaborates with organizational stakeholders to secure information technology systems for the organization. Their goal is to reduce organizational risk by rapidly remediating active attacks in the environment, advising on improvements to threat protection practices, and referring violations of organizational policies to appropriate stakeholders. 

Responsibilities include threat management, monitoring, and response by using a variety of security solutions across their environment. The role primarily investigates, responds to, and hunts for threats using Microsoft Sentinel, Microsoft Defender for Cloud, Microsoft 365 Defender, and third-party security products. Since the security operations analyst consumes the operational output of these tools, they are also a critical stakeholder in the configuration and deployment of these technologies.

Candidates for this role should be familiar with attack vectors, cyberthreats, incident management, and Kusto Query Language (KQL). Candidates should also be familiar with Microsoft 365 and Azure services.

---

# Exam Objectives

## Mitigate threats using Microsoft 365 Defender (25–30%)

### Mitigate threats to the productivity environment by using Microsoft 365 Defender

- Investigate, respond, and remediate threats to Microsoft Teams, SharePoint, and OneDrive
- Investigate, respond, and remediate threats to email by using Microsoft Defender for Office 365
- Investigate and respond to alerts generated from Data Loss Prevention policies
- Investigate and respond to alerts generated from insider risk policies
- Identify, investigate, and remediate security risks by using Microsoft Defender for Cloud Apps
- Configure Microsoft Defender for Cloud Apps to generate alerts and reports to detect threats

### Mitigate endpoint threats by using Microsoft Defender for Endpoint

- Manage data retention, alert notification, and advanced features
- Recommend security baselines for devices
- Respond to incidents and alerts
- Manage automated investigations and remediations
- Assess and recommend endpoint configurations to reduce and remediate vulnerabilities by using the Microsoft's threat and vulnerability management solution
- Manage endpoint threat indicators

### Mitigate identity threats

- Identify and remediate security risks related to events for Microsoft Azure Active Directory (Azure AD), part of Microsoft Entra
- Identify and remediate security risks related to Azure AD Identity Protection events
- Identify and remediate security risks related to Azure AD Conditional Access events
- Identify and remediate security risks related to Active Directory Domain Services using Microsoft Defender for Identity

### Manage extended detection and response (XDR) in Microsoft 365 Defender

- Manage incidents across Microsoft 365 Defender products
- Manage investigation and remediation actions in the Action Center
- Perform threat hunting
- Identify and remediate security risks using Microsoft Secure Score
- Analyze threat analytics
- Configure and manage custom detections and alerts

## Mitigate threats using Microsoft Defender for Cloud (20–25%)

### Implement and maintain cloud security posture management and workload protection

- Plan and configure Microsoft Defender for Cloud settings, including selecting target subscriptions and workspaces
- Configure Microsoft Defender for Cloud roles
- Assess and recommend cloud workload protection
- Identify and remediate security risks using the Microsoft Defender for Cloud Secure Score
- Manage policies for regulatory compliance
- Review and remediate security recommendations

### Plan and implement the use of data connectors for ingestion of data sources in Microsoft Defender for Cloud

- Identify data sources to be ingested for Microsoft Defender for Cloud
- Configure automated onboarding for Azure resources
- Connect multi-cloud and on-premises resources
- Configure data collections

### Configure and respond to alerts and incidents in Microsoft Defender for Cloud

- Validate alert configuration
- Set up email notifications
- Create and manage alert suppression rules
- Design and configure workflow automation in Microsoft Defender for Cloud
- Remediate alerts and incidents by using Microsoft Defender for Cloud recommendations
- Manage security alerts and incidents
- Analyze Microsoft Defender for Cloud threat intelligence reports
- Manage user data discovered during an investigation

## Mitigate threats using Microsoft Sentinel (50–55%)

### Design and configure a Microsoft Sentinel workspace

- Plan a Microsoft Sentinel workspace
- Configure Microsoft Sentinel roles
- Design and configure Microsoft Sentinel data storage
- Implement and use Content hub, repositories, and community resources

### Plan and implement the use of data connectors for ingestion of data sources in Microsoft Sentinel

- Identify data sources to be ingested for Microsoft Sentinel
- Identify the prerequisites for a Microsoft Sentinel data connector
- Configure and use Microsoft Sentinel data connectors
- Configure Microsoft Sentinel data connectors by using Azure Policy
- Configure Microsoft Sentinel connectors for Microsoft 365 Defender and Microsoft Defender for Cloud
- Design and configure Syslog and CEF event collections
- Design and configure Windows Security event collections
- Configure custom threat intelligence connectors

### Manage Microsoft Sentinel analytics rules

- Design and configure analytics rules
- Activate Microsoft security analytics rules
- Configure built-in scheduled queries
- Configure custom scheduled queries
- Define incident creation logic
- Manage and use watchlists
- Manage and use threat indicators

### Perform data classification and normalization

- Classify and analyze data by using entities
- Create custom logs in Azure Log Analytics to store custom data
- Query Microsoft Sentinel data by using Advanced SIEM Information Model (ASIM) parsers
- Develop and manage ASIM parsers

### Configure Security Orchestration, Automation, and Response (SOAR) in Microsoft Sentinel

- Configure automation rules
- Create and configure Microsoft Sentinel playbooks
- Configure alerts and incidents to trigger automation
- Use automation to remediate threats
- Use automation to manage incidents

### Manage Microsoft Sentinel incidents

- Triage incidents in Microsoft Sentinel
- Investigate incidents in Microsoft Sentinel
- Respond to incidents in Microsoft Sentinel
- Investigate multi-workspace incidents
- Identify advanced threats with User and Entity Behavior Analytics (UEBA)

### Use Microsoft Sentinel workbooks to analyze and interpret data

- Activate and customize Microsoft Sentinel workbook templates
- Create custom workbook
- Configure advanced visualizations
- View and analyze Microsoft Sentinel data using workbooks
- Track incident metrics using the security operations efficiency workbook

### Hunt for threats using Microsoft Sentinel

- Create custom hunting queries
- Run hunting queries manually
- Monitor hunting queries by using Livestream
- Configure and use MSTICPy in notebooks
- Perform hunting by using notebooks
- Track query results with bookmarks
- Use hunting bookmarks for data investigations
- Convert a hunting query to an analytical rule
