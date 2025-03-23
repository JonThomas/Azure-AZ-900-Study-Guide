# Describe directory services in Azure, including Microsoft Entra ID and Microsoft Entra Domain Services

## Entra ID: Cloud based
* Provides
  * Authentication, including functionality such as self-service password reset, multifactor authentication, a custom list of banned passwords, and smart lockout services
  * Single Sign-on: SSO
  * Application management: Application Proxy, SaaS apps, the My Apps portal,
  * Device management, so that devices can be managed by Intune. Allows for device based [conditional access](44-Describe-Microsoft-Entra-Conditional-Access.md) policies. 
* "Microsoft can detect suspicious login attempts"

## Active Directory
* Based on premises, running on Windows server.
* "Microsoft doesn't monitor login attempts"

## Connecting AD with Entra ID
* Entra ID and Active Directory can be connected, to manage identities only in Entra ID.
  * Using Entra Connect.

## Entra Domain Services
* Use Entra Domain Services when lifting on-prem applications to the cloud, that requires AD (and doesn't support Entra ID)
* Provides managed domain services such as domain join, group policy, lightweight directory access protocol (LDAP), and Kerberos/NTLM authentication
* ~ similar to AD Domain Controller in the cloud(?)
* Created by adding a managed domain to Azure. Two Windows Server domain controllers aka "replicaset" are deployed to the managed domain (SaaS).
* Identities are typically one way synced from On-prem Ad, via Entra ID, into the managed domain / Entra Domain Services.

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/2-directory-services

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)