## [Azure Administration: Deploy and Manage Compute Resources](https://www.linkedin.com/learning/azure-administration-deploy-and-manage-compute-resources) 


### Configure Virtual Machines for High Availability and Scalability
------

You, the Azure administrator, need to configure HA using Availability Sets. You need to move your existing virtual machines into an availability set but you are unable to do so. What is the most likely reason?

- [-] The availability set is located in a different region.
- [-] There should not be any reason why the stopped virtual machines can not be moved into the availability set.
- [-] There should not be any reason why the running virtual machines can not be moved into the availability set.
- [+] A virtual machine can only be added to an availability set during provisioning.

What is the minimum number of virtual machines that should be assigned to an availability set?

- [-] 1
- [-] 3
- [+] 2
- [-] 0

What is the scale set scaling policy?

- [-] Default
- [-] OldestVM
- [+] all of these answers
- [-] NewestVM

### Create and Configure Virtual Machines
------

You are unable to connect to the virtual machine in Azure. What does Microsoft recommend doing when this happens?

- [-] Move the virtual machine to another resource group.
- [+] Redeploy the virtual machine.
- [-] Stop and start the virtual machine.
- [-] Delete the virtual machine and recreate it.

Vikram is attempting to add a NIC to virtual machine but he is unable to do so. What could be the reason for this?

- [-] Virtual machines do not support NICs at all.
- [-] The virtual machine can only have one NIC associated with it.
- [+] The virtual machine does not support additional NICs.
- [-] The virtual machine is turned on.

A Spot Instance can save you money because your virtual machine is using unused Azure resource. What is the risk of using a Spot Instances?

- [-] The virtual machine can only be a small virtual machine with limited IOPs.
- [-] The virtual machine could be throttled when the Azure resources are required.
- [+] The virtual machine could be evicted without notice when the Azure resources are required.
- [-] There are no risks, Spot Instances are a great alternative to deploying a full virtual machine.

You need to verify the disk encryption on an Azure disk. What PowerShell cmdlet would you us?

- [+] Get-AZVMDiskEncryptionStatus
- [-] Show-AZDiskEncryptionStatus
- [-] Get-AZDiskEncryptionStatus
- [-] Get-AZVMDiskEncryption

You require support for HSM backed key, which pricing tier do you need to use?

- [+] Premium
- [-] Basic
- [-] Standard
- [-] Advanced

You need to retrieve a list of all the virtual machine sizes using PowerShell. What cmdlet do you use?

- [+] Get-AZVMSize
- [-] List-AZVMSize
- [-] List-AZVMSKU
- [-] Get-AZVMSku

After moving resources you must then perform what action?

- [+] Update tools and subscriptions associated with the moved resources as the resources will have new IDs.
- [-] Update the resource names associated with the moved resources as the resources will have new IDs.
- [-] Manually assign new resource Ids to the moved resources as resource ids are not generated automatically during a move.
- [-] Nothing, all resources will maintain all settings and IDs.

Which caching type is the default for C: drive?

- [-] None
- [-] WriteOnly Host Caching
- [-] ReadOnly Host Caching
- [+] Read Write Host Caching

### Automate Deployment and Configuration of Virtual Machines
------

The element "contentVerison" is used for what purpose?

- [-] the number of times the template has been deployed
- [+] versioning control
- [-] the number of times the template has been used
- [-] the version of the schema

How many elements are in a Azure template?

- [-] 5
- [+] 7
- [-] 3
- [-] 9

What must you be aware of when adding a password to the parameters file?

- [-] A simple password can be used.
- [+] It is displayed in clear text and is not a Microsoft best practice.
- [-] A complex password must be used.
- [-] It is in hidden text.

What are the required settings to generalize a virtual machine?

- [-] Enter System Out-of-Box Experience (OOBE) Shutdown
- [-] Enter System Out-of-Box Experience (OOBE) Generalize Reboot
- [-] Enter System Audit Mode Generalize Shutdown
- [+] Enter System Out-of-Box Experience (OOBE) Generalize Shutdown

You are adding a custom extension to a virtual machine. Where do you need to access the scripts from?

- [+] an Azure storage container
- [-] your local system
- [-] an Azure file share
- [-] your GitHub repo

Desired State Configuration prevents what?

- [+] server drift
- [-] applications from being uninstalled or deleted
- [-] servers from being deleted

### Create and Configure Containers
------

How many open ports are required when using a Public network for your container instance?

- [+] 1
- [-] None. Ports can be opened later.
- [-] 2
- [-] 5

You are trying to disable VM Scale Sets when creating a node pool in AKS. Why are you unable to disable the scale sets option?

- [+] VM Scale Sets are required for multiple node pools.
- [-] There is no option to disable VM Scale Sets.
- [-] VM Scale Sets are not required for multiple node pools.
- [-] All nodes, single or multiple, require VM Scale Sets.

### Create and Configure Web Apps
------

Cool down is _____.

- [-] The amount of time to wait before a scale operation to scale again.
- [-] The amount of data to reduce after a scale operation before scaling again.
- [-] The amount of data to reduce before a scale operation before scaling again.
- [+] The amount of time to wait after a scale operation before scaling again.

You need to add a custom domain to your Shared infrastructure tier D1 web app but you are unable to do so. What do you need to do to correct this problem spending the least amount of money?

- [-] Enable custom domains on the web app.
- [-] Move up to the Isolated category of pricing tiers.
- [+] Move up to a pricing tier that supports custom domains.

By default what type of access is allowed on web apps?

- [+] Anonymous. Authentication is not required.
- [-] Microsoft work or school authenticated users.
- [-] Azure Active Directory authenticated users.
- [-] Server active directory authenticated users.
