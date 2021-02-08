## [Azure Administration: Configure and Manage Virtual Networks](https://www.linkedin.com/learning/azure-administration-configure-and-manage-virtual-networks) 

### Implement and Manage Virtual Networking
------
By default, where is all traffic within a VNet routed?

- [-] between all subnets in a subscription
- [+] between all the subnets
- [-] between peered subnets
- [-] Traffic is not routed between subnets in a Vnet.

What does standard DDoS protection include?

- [-] adaptive tuning
- [-] telemetry
- [-] notifications
- [+] all of these answers

What is the cmdlet to create a subnet?

- [-] Add-AZVirtualnetworkSubnet
- [+] Add-AZVirtualnetworkSubnetConfig
- [-] New-AZVirtualnetworkSubnetConfig
- [-] New-AZVirtualnetworkSubnet

When must you add public IP addresses to a network interface?

- [-] during the creation of the network interface
- [+] after the network interface has been provisioned
- [-] A public IP cannot be assigned to a network interface without it first being associated with a virtual machine.
- [-] A public IP must be provisioned separately and then added to the network interface.

A dynamic public IP is assigned at what point during the provisioning of a virtual machine?

- [-] Azure virtual machines do not support dynamic public IPs
- [-] after the virtual machine has been provisioned
- [+] during the start up of a virtual machine

When creating a new virtual machine, what type is the default sku for a public IP?

- [+] basic
- [-] static
- [-] dynamic
- [-] standard

What is the cmdlet to create a network interface?

- [-] Create-AZNetworkInterface
- [+] New-AZNetworkInterface
- [-] New-AZNetworkInterfaceConfig
- [-] Create-AZNetworkInterfaceConfig

You are creating an Azure public IP address that will require an IPv6 address. What sku type must you select?

- [-] standard
- [-] All public IP SKUs support IPv6.
- [-] dynamic
- [+] basic

What happens to traffic if the next hop is set to none?

- [+] All traffic is dropped.
- [-] Traffic is routed to the default next hop.
- [-] Traffic is sent back to the originating host with an error of 238.
- [-] Traffic is routed to the Internet.

When setting up a route table, what type of virtual resource can the next hop be?

- [-] Virtual Network
- [-] Virtual Appliance
- [-] Virtual Network Gateway
- [+] all of these answers

What cmdlet would you use to create a route?

- [-] New-AZRouteConfig
- [-] Add-AZRoute
- [+] Add-AZRouteConfig
- [-] Set-AZRouteConfig

### Create Connectivity between Virtual Networks
------

You are connecting two virtual networks in Azure. The traffic must be encrypted during transit. What type of connection should you use?

- [-] Peered Network
- [+] VNet to VNet
- [-] Connected Network

To verify two networks have been peered in effective routes, what is the next hop type?

- [+] peered
- [-] none
- [-] the virtual network that is being peered to

What cmdlet would you use to peer to another network?

- [-] Add-AZVirtualNetworkPeer
- [-] New-AZVirtualNetworkPeer
- [+] Add-AZVirtualNetworkPeering
- [-] New-AZVirtualNetworkPeering

You are setting up a VNet connection and require multiple vnet gateways from a single on-premises connection. What do you need to enable for this functionality?

- [-] Active-passive mode
- [+] Active-active mode
- [-] Nothing--this functionality is enabled by default.
- [-] Passive-active mode

You need to connect two networks in different subscriptions using a VNet to VNet connection. How would you accomplish this?

- [-] Create a new VNet in the same subscription.
- [-] This scenario is not supported.
- [+] Create a VNet to VNet connection using PowerShell.
- [-] Create a VNet to VNet connection using the Portal.

### Configure Name Resolution
------

To avoid accidental removal of DNS records, what must you do if you "bring your own DNS" to Azure?

- [-] Turn on scavenging.
- [+] Turn off scavenging.
- [-] Nothing if you're in a "bring your own DNS" scenario.

Microsoft provides domain names for Azure DNS.

- [-] TRUE
- [+] FALSE

To create a Private DNS, what cmdlet do you need to include when creating a zone using PowerShell?

- [-] -Zone Private
- [+] -ZoneType Private
- [-] -ZoneType Public
- [-] -Type Private

### Create and Configure a Network Security Group
------

What are the default NSG rule(s)?

- [-] DenyAllInBound
- [-] AllowAzureLoadBalancerInBound
- [-] AllowVNetInBound
- [+] all of these answers

Security rules are processed in which order?

- [-] there is no priority
- [+] lowest to highest
- [-] highest to lowest
