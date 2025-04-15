# Compare compute types, including containers, virtual machines, and functions

"Compute types" (descibed here) include Containers, VMs and **functions**

"Hosting options" (described [later](24-Describe-application-hosting-options-including-web-apps-containers-and-virtual-machines.md)) include Containers, VMs and **WebApps**(!)

Virtual Machines are described under [Describe virtual machine options, including Azure virtual machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop](22-Describe-virtual-machine-options-including-Azure-virtual-machines-Azure-Virtual-Machine-Scale-Sets-availability-sets-and-Azure-Virtual-Desktop.md)

Containers are described under [Describe application hosting options, including web apps, containers, and virtual machines](24-Describe-application-hosting-options-including-web-apps-containers-and-virtual-machines.md)

## Azure Functions
* Code only runs when it triggers, typically by an event, REST-request or message.
* A function is typically used for handling work that can be completed within seconds or less.
* Functions are abstracted from the infrastructure
* Functions are automatically scaled based on demand.
* Statless (default) vs Durable/ Stateful functions.
   * Durable functions has a context that is passed to the function as a parameter that tracks prior activity.

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/6-functions

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)