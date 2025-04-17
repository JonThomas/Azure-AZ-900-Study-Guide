# Describe external identities in Azure, including business-to-business (B2B) and business-to-customer (B2C)

* External identity: Person, device, service etc, outside of your organization.
* Internal Azure resources can be shared with external identities, by "bringing their own identities":
  * Corporate or government issued digital identities
  * Unmanaged social identities like Google or Facebook
* The external users identity providers manages their identity. Access to applications is managed with Microsoft Entra Id or Azure AD B2C

## B2B, using Entra Id:
* For collaboration (e.g. Teams) between partners, vendors, suppliers etc
* External identities are invited to your tenant, or they sign up using a selv service portal.
* Two types of B2B collaboration: 
  * "B2B collaboration users": typically represented in your directory as guest users.
  * "B2B direct connect": For shared Teams channels. B2B direct connect users aren't represented in your directory, but they're visible from within the Teams shared channel and can be monitored in Teams admin center reports.

## B2C, using Azure AD:
* For consumers of your published app
* Exernal identities are onboarded using sign-up and sign-in user flows/ custom policies, using Azure Ad B2C for identity and access management

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/4-external-identities

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)