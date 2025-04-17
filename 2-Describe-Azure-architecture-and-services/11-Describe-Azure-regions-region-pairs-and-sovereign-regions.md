# Describe Azure regions, region pairs, and sovereign regions

How the physical infrastructure is set up

## Regions
An area on the globe, containing at least one Azure datacenter.

## Availability zone
Physically separate datacenters within a region, containing at least one Azure datacenter with independent physical infrastructure (power, cooling, networking etc). 
The availability of one Availability zone shall not affect other Availability zones.
Not all regions support Availability zones.

Availability zones are primarily for VMs, managed disks, load balancers and SQL databases.

## Region Pairs
Some disasters are so big that Availability zones aren't enough. To provide even further recilience, Azure has Region pairs.
Most regions are paired with another region within the geography (Europe, Middle East, Asia).
Example: South-East Asia is paired with East Asia.
Region pairs must be at least 300 miles away from eachother.

## Sovereign regions
Instances of Azure that are isolated from the main instances of Azure. Typically used for compliance and legal purposes.
Example: China East, China North, US DoD Central.

Souce: https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/5-describe-azure-physical-infrastructure

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)