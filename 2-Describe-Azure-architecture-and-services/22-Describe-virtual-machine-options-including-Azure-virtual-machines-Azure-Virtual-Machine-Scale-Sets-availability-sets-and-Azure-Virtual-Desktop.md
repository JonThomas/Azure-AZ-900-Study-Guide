# Describe virtual machine options, including Azure virtual machines, Azure Virtual Machine Scale Sets, availability sets, and Azure Virtual Desktop

## Virtual machine
Provides a computer in the cloud: Infrastructure as a Service (IaaS)
Good choice when you need
* total control of the operating system
* ability to run custom software
* use custom hosting options

## Virtual Machine Scale Sets
Allows you to manage identical load-balanced VMs a group.
* The number of VMs can automatically change in response to demand, or based on a schedule
* Automatically uses a load balancer to balance the load between the VMs

## Virtual Machine Availability Sets
Improves availablility of a VM by staggering updates between the sets, and requiring the sets to have different power and network connectivity.
VMs in are grouped in two ways:
* Update domain: VMs in a the same update domain can be booted at the same time. The VMs in the second domain is rebooted 30 minutes after VMs in the first domain.
   * Tries to improve availability by isolating OS updates/ reboots between the domains
* Fault domain: Groups VMs by common power and network switch
   *  Tries to improve availability by isolating power and network issues between the domains

## Azure Virtual Desktop
Gives you a Windows machine in the cloud.
Login with [Entra Id](41-Describe-directory-services-in-Azure-including-Microsoft-Entra-ID-and-Microsoft-Entra-Domain-Services.md)
~ UDI setup
Data and applications are separate from the local hardware, so you can have complete control on what can be copied locally
Concurrent users on the same VM/ "multi session" is possible using Windows 10/ 11 Enterprise multi session.

Sources: 
* https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/2-virtual-machines
* https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/4-virtual-desktop

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)