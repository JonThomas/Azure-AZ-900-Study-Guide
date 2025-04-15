# Describe application hosting options, including web apps, containers, and virtual machines

"Hosting options" (described here) include Containers, VMs and **WebApps**.

"Compute types" (descibed [earlier](21-Compare-compute-types-including-containers-virtual-machines-and-functions.md)) include Containers, VMs and **functions**(!)

## Web apps
<TODO>

## Containers
* Virtualizes the _operating system_ (where VMs virtalizes the hardware!)
* Allows deployment to an OS-independent container host
* Typically contains only one application
* More light weight, more portable, and better performance than VMs

### Azure Container Instances
* The easiest way to run a Docker container
* Optimized for running single containers or small groups of containers without orchestration
* Containers can be deployed and run without VMs or orchestrators.
* A Platform as a Service (PaaS) offering.

### Azure Container Apps
* Optimized for running several services
* Runs on top of Kubernetes, but doesn't provide direct access to Kubernetes.
* Similar to Azure Container Instances, but higher level and provides more services:
   * Load balancing
   * Scaling
   * Certificate support
   * Revisions, and environments

Comparing Container apps to other container options: https://learn.microsoft.com/en-us/azure/container-apps/compare-options

### Azure Kubernetes Service
AKS is a container orchestration service. It manages the lifecycle of containers, and helps manage large container fleets

## Virtual Machines
* Virtualizes the _hardware_, where containers virtalizes the operating system!
Virtual Machines are desribed under [Describe virtual machine options, including Azure virtual machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop](22-Describe-virtual-machine-options-including-Azure-virtual-machines-Azure-Virtual-Machine-Scale-Sets-availability-sets-and-Azure-Virtual-Desktop.md)

Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/5-containers

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)