# Describe management groups

A management group logically groups subscriptions.
Governance conditions can be applied to management groups, and any policies are automatically applied to all subscriptions (and therefore resource groups and resources) within the management group.
Management groups can be nested, so it is possible to set up a hierarchy of management groups.

Important facts about management groups:
* 10,000 management groups can be supported in a single directory.
* A management group tree can support up to six levels of depth. This limit doesn't include the root level or the subscription level.
* Each management group and subscription can support only one parent.

Source: https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/6-describe-azure-management-infrastructure

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)