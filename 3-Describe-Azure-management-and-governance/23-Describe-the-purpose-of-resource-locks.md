# Describe the purpose of resource locks

* A resource lock prevents resources from being accidentally deleted or changed.
* A resource lock can be applied to a resource, a resource group or a subscription.
* Two types of locks
   * Delete locks: Authorized users can still change the resource, but not delete it
   * ReadOnly locks: Authorized users can still read the resource, but not delete or update it

* Resources with a resource lock can be modified and deleted, but the resource lock always have to be removed first!

Source: https://learn.microsoft.com/en-us/training/modules/describe-features-tools-azure-for-governance-compliance/4-describe-purpose-resource-locks

⬅️ [Return to Describe Azure management and governance](README.md)

⬅️ [Return to Table of Contents](../README.md)