# Describe virtual networking, including the purpose of Azure virtual networks, Azure virtual subnets, peering, Azure DNS, Azure VPN Gateway, and ExpressRoute

## Virtual networking
Azure virtual networks and virtual subnets enable Azure resources, such as VMs, web apps, and databases, to communicate with each other, with users on the internet, and with your on-premises client computers. 

## Azure Virtual Networks
* Allows you to create multiple isolated virtual networks.
* An Azure Virtual Network is set up with a private IP address space, not accessible from the internet.
* The IP range can be divided into **subnets**, and allocated to a named subnet.
* Can communicate with Azure resources using
   * Virtual networks directly, to connect to resource types such as VMs, App Service Environments for Power Apps, Azure Kubernetes Service and Azure virtual machine scale sets.
   * Service endpoints, to connect to resource types such as Azure SQL databaser and storage accounts
* Can communicate with on-premise resources using
   * Point-to-site VPN: From a client computer (outside your organization) to your on-site or Azure resources via an **Azure VPN gateway**. Must be initiated by the client computer.
   * Site-to-site VPN: From on-premise device/ gateway to the Azure VPN gateway in a virtual network. This makes Azure resources appear as local resources.
   * Azure **ExpressRoute**: A dedicated private connection from you site to Azure, that doesn't travel over the internet.

## Azure subnets

## Peering
* Virtual networks can be linked using Peering.
* Two Virtual networks can be directly connected.
* Peering traffic uses the Microsoft backbone network.
* The virtual networks can be in different regions.

## Azure DNS
Used for name resolution.

## Azure VPN Gateway
* VPN = Virtual Private Network.
* A VPN uses an encrypted tunnel within another network, to connect two trusted networks using an untrusted network.
* The gateway is deployed in a subnet of the Virtual Network, and allows to connect on-premise datacenters, individual devices or other virtual networks to the Virtual Network (see )
* Only one gateway can be deployed to each virtual network.
* Authentication is done using a preshared key.
* The VPN Gateway must be set up specifying policy- or route- based VPN, determining which traffic needs encryptio:
   * 

## ExpressRoute


Virtual Network Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/8-virtual-network

⬅️ [Return to Describe Azure architecture and servies](README.md)

⬅️ [Return to Table of Contents](../README.md)