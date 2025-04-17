# Describe the purpose of Microsoft Defender for Cloud

* Can assess, monitor and defend resoures in the cloud, on-prem and multi cloud.
* Functionality:
   * Tools for hardening resources
      * Assesses resources and provides a prioritized list of recommendations
   * Track security posture
      * Provides security alerts
   * Protect against cyber attacks
   * Streamline security management
* On-prem and multi cloud protection is handled by [Azure Arc](../3-Describe%20Azure-management-and-governance/33-Describe-the-purpose-of-Azure-Arc.md), by deploying a Log Analytics agent
* Aggregates results and scans from Defender for Servers

## Defending Azure-native resources
* Detects threats against PaaS services 
* Defender for cloud can automatically classify data in Azure SQL, and get assessments for potential vulnerabilities across Azure SQL and storage services
* Protects VMs by using just-in-time VM access, setting secure access policies on selected ports, for only authorized users, allowed source IP address ranges or IP addresses, and for a limited amount of time

## Defending on-prem/ hybrid resources
* Enabled by deploying Azure Arc and enabling Defender For Cloud enhanced secuity features.

## Defending resources on other clouds
* Requirement: Other cloud must be connected to the Azure subscription
* Cloud security posture management (CSPM) gives advice, also for resources on other clouds
* Defender for Containers defends Amazon EKS Linux clusters
* Defender for Servers defends Windows and Linux EC2 instances.

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/9-describe-microsoft-defender-for-cloud

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)