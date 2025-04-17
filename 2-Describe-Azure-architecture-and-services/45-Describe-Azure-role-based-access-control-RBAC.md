# Describe Azure role-based access control (RBAC)

* Use RBAC to implement least privilege principle for Azure services that support it (Application security must be handled by the application)
* Azure provides built-in roles that describe common access rules for cloud resources
* You can also define your own roles. 
* Each role has an associated set of access permissions that relate to that role. 
* When you assign individuals or groups to one or more roles, they receive all the associated access permissions.
* Roles are applied to resources through scopes. Scopes include:
  * A management group (a collection of multiple subscriptions).
  * A single subscription.
  * A resource group.
  * A single resource.
* RBAC is hierarchical, so if you have the Owner role at a subscription level, you automatically have Owner access to all resource grups and resources in that subscription.
* Acure Resource Manager enforces the RBAC rules.

The figure below shows examples of roles on the top, scopes down on the left, and user groups that need access to resources in the middle. Two sets of permissions are explained below: 
* People in the Observers group are assigned to the Reader role on the Management group level (a collection of multiple subscriptions), which gives Reader access to all resources on and below management gruoup.
* Automated processes might have many roles, but the roles are assigned on a resource-by-resource basis.
![Roles are applied to resources through scopes](img/role-based-access-scope.png)

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/6-role-based-access-control

⬅️ [Return to Describe Azure architecture and services](README.md)

⬅️ [Return to Table of Contents](../README.md)