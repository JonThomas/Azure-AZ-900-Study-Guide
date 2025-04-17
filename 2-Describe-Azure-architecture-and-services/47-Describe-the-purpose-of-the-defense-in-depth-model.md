# Describe the purpose of the defense-in-depth model

A model with 7 layers. Each layer acts as function to protect the layer inside, so that if one layer is breached, a subsequent layer is already in place to prevent further exposure.

## The 7 layers:
1. Physical layer: First line of defence. Protects computing hardware using fences, locks and walls.
1. Identity and Access: Ensures that access to infrastructure is only granted to whats needed, and that sign-in events and changes are logged. Implemented using among other things: SSO and MFA.
1. Perimeter: Protects the network perimeter from neworks based attacks, using DDoS protection and Firewalls.
1. Network: Limiting network connectivity to prevent traversing of resources. Restrict inbound traffic, and limit outbound traffic.
1. Compute: Secure compute resources such as Virtual Machines, and add endpoint protection/ Defender for Servers.
1. Application: Ensure that apps are secure and free of vulnerabilities, without exposed secrets. Keyword: SSDLC.
1. Data: Often regulated by official laws and regulations. Access to data shall be restricted to the ones needing it.

![The 7 leyars of defence in depth](img/defense-depth.png)

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/8-describe-defense-depth

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)