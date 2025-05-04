# Describe Azure Service Health

Azure Service Health helps you keep track of Azure resource, both your specifically deployed resources and the overall status of Azure. Azure service health does this by combining three different Azure services:
* Azure Status: Show the overall status of Azure globally. 
   * Publicly accessible, and does not require any setup from your side.
* Service Health: Shows the health of services and regions you are using. Provides links to support when services are impacted. To make the most of Service Health, you need to:
   * Set up Service Health Alerts to notify you of service issues, planned maintenance, or health advisories affecting your resources.
   * Configure these alerts via the Azure portal to ensure timely notifications.
* Resource Health: Shows the health of your resources. Alerts can be configured using Azure Monitor. To use Resource Health effectively, you need to:
   * Enable Azure Monitor and configure alerts for availability changes to your resources.
   * Use Resource Health insights to diagnose and resolve issues affecting specific resources.

Source: https://learn.microsoft.com/en-us/training/modules/describe-monitoring-tools-azure/3-describe-azure-service-health

⬅️ [Return to Describe Azure management and governance](README.md)

⬅️ [Return to Table of Contents](../README.md)