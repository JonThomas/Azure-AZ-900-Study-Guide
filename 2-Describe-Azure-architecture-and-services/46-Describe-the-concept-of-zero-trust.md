# Describe the concept of zero trust

* Verify Explicitly - meaning that for example all requests has to be verified explicitly in each application, api and service
* Use least privilege access - meaning for example that the user used to access a database from an application not necessarily needs access to the whole database. Maybe it only needs read permissions on a few tables?
* Assume breach - meaning that logs must be present to identify breach, and the logs must be monitored; All communication (also internally within the datacenter/ cloud) must be encrypted; No applications or API's can use frameworks or libraries with known vulnarabilities; Etc

## Security policies
All assets must be protected by policies: Implementing and enforcing security policies for all components is crucial. Microsoft includes [Conditional access](44-Describe-Microsoft-Entra-Conditional-Access.md) as the main policy engine: Based on various signals or conditions, Conditional Access can block or give limited access to resources. Source: https://learn.microsoft.com/en-us/azure/security/fundamentals/zero-trust.

![Zero Trust](img/zero-trust.png)

* Sorce: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/7-describe-zero-trust-model

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)