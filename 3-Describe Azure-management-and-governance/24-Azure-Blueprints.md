# Azure Blueprints

> On July 11, 2026, Blueprints (Preview) will be deprecated, replaced by Template Specs and Deployment Stacks. [Source](https://learn.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-portal) 

* Azure Blueprints was created to provide you with an automated and easy-to-deploy solution to help set up Azure subscriptions inline with a governance strategy.
* Azure Blueprints allow you to implement governance as code.
* Azure Blueprints promises to give you the ability to compose, manage, and scale governance as code.

## What are Blueprints?
Blueprints are JSON files, composed of the following artifacts:
   * Azure Resource Manager templates - descibes the resources that will be created
   * Policy assignments - to enforce business rules
   * Resource groups - to hold created resources
   * Role assignments - 

These artifacts are embedded into a package, which can then be composed, versioned, and assigned to a management group containing multiple subscriptions, or assigned directly to a single subscription.

Microsoft provide sample Blueprints, that can be used for example to bring an empty environment to ISO27001 compliance.

## Blueprints vs ARM templates
* More about [ARM templates here](35-Describe-Azure-Resource-Manager-ARM-and-ARM-templates.md)
* Blueprints are stored within your Azure envionment, so they are protected using standard Azure functionality. (They don't need "another layer of management")
* Blueprints maintain a connection to the created resources (between blueprint definition and blueprint assignments). 
* Blueprints track and audit the deployments.
* Blueprints have better resource lock capabilities (see below)
* Existing ARM templates can be used in blueprints

## Blueprint locks
* Locks prevent resources created by a blueprint from being deleted
* The only way to change or remove a lock that was created by a blueprint is to alter or delete the blueprint itself.
* Blueprints can't add or change locks on resources not created by the blueprint.
* Three choices (compared to "normal" [resource locks](23-Describe-the-purpose-of-resource-locks.md), that only have two)
   * Don't Lock: No lock.
   * Read Only: Resource can't be changed or deleted (except tags on a resource group)
   * Do Not Delete: Resouce can be changed, but not deleted

## Deleting or changing a Blueprint
* Deleting a blueprint assignment removes any locks.
* Any resources are left unchanged.
* The same managed identity that that assigned the blueprint must be used to change it.

## Source:
* https://learn.microsoft.com/en-us/training/modules/intro-to-azure-blueprints/
* https://learn.microsoft.com/en-us/training/modules/intro-to-azure-blueprints/2-what-is-azure-blueprints
* Blueprint locks: https://learn.microsoft.com/en-us/azure/governance/blueprints/concepts/resource-locking

⬅️ [Return to Describe Azure management and governance](README.md)

⬅️ [Return to Table of Contents](../README.md)