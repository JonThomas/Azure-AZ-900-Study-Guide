# Describe the concept of zero trust

Protect all assets with central policy

* Verify Explicitly - meaning that for example all requests has to be verified explicitly in each application, api and service
* Use least privilege access - meaning for example that the user used to access a database from an application not necessarily needs access to the whole database. Maybe it only needs read permissions on a few tables?
* Assume breach - meaning that logs must be present to identify breach, and the logs must be monitored; All communication (also internally within the datacenter/ cloud) must be encrypted; No applications or API's can use frameworks or libraries with known vulnarabilities; Etc

![Zero Trust](img/zero-trust.png)

* Sorce: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/7-describe-zero-trust-model

[Return to Describe Azure architecture and servies](README.md)

[Return to Table of Contents](../README.md)