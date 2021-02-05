## [Planning a Microsoft Cloud Solution](https://www.linkedin.com/learning/planning-a-microsoft-cloud-solution-2)

------
### What Is the Cloud?
------
What are some common considerations when moving to a cloud environment?

- [-] the current on-premises infrastructure
- [-] current supported workloads
- [-] the costs
- [+] all of these answers

------
### The Foundation
------

Resources in a resource group should share the same _____.

- [-] type of resources i.e. only virtual machines
- [-] nothing, since resources should have different management lifecycles
- [+] lifecycle

What are tags in a Resource Group used for?

- [+] to organize your resources
- [-] to schedule resources for deletion
- [-] to name your resources

How many IP address are used in an Azure subnet?

- [-] 3
- [-] 2
- [-] 4
- [+] 5

Microsoft recommends using what type of storage for virtual machines?

- [+] Premium SSD
- [-] Basic
- [-] Standard SSD
- [-] Standard HDD

The Azure Storage Explorer application must be _____.

- [-] purchased as a separate Azure service
- [+] downloaded and installed locally
- [-] run in the Azure portal

------
### Azure Virtual Machines
------

What type of VPN Gateways support remote users?

- [-] site-to-site
- [+] point-to-site
- [-] ExpressRoute

Availability Sets provide what kind of functionality?

- [-] They connect to on-premises.
- [+] They ensure virtual machines resources are isolated from each other.
- [-] They back up the virtual machines.

D drive on the virtual machine is used for?

- [+] temporary storage
- [-] backup files
- [-] user data

How many data disks can be added to your Azure virtual machine?

- [+] Only as many as the virtual machine supports.
- [-] Only 1 disk.
- [-] As many as you want.

Replication is _____.

- [-] not necessary or available
- [-] a full backup solution
- [+] not a backup

------
### Azure Active Directory
------

Which choices are available as a multifactor authentication method?

- [-] Something you have
- [-] Something you know
- [-] Something you are
- [+] all of these answers

he Azure AD Connect Tool includes what services?

- [-] Sync Services
- [-] AD FS
- [-] Health Services
- [+] all of these answers

------
### Azure Backup and Disaster Recovery
------

When using LRS (locally redundant storage) how many copies are stored within the same region?

- [-] 2
- [-] 9
- [+] 3
- [-] 6

Virtual machine backups must be _____.

- [+] in the same region as the Recovery Services Vault
- [-] in any region outside of a Recovery Services Vault
- [-] in any region parallel to a Recovery Services Vault

------
### Exam Questions
------

1. What is the cloud?
- [-] Amazon data centers only
- [-] Attempted incorrect option
- [-] Microsoft datacenters only unicorns and fairy dust
- [+] servers in someone else's datacenter

2. In the IaaS model, what are you responsible for managing?

- [-] data and applications
- [+] virtual machines, data, and applications
- [-] building including security, heating, and cooling

3. What are some common services in Azure?

- [-] Backup and Site Recovery
- [-] Azure SQL Database
- [-] Azure virtual machines
- [+] All of the above

4. The Azure Dashboard is _____.

- [+] customizable
- [-] limited to the types of customizations
- [-] static

5. The Azure File Service uses which SMB version?

- [-] 2
- [-] 1
- [+] 3

6. What is the benefit of a virtualized environment?

- [-] quick and easy setup
- [-] scalability
- [-] manageability
- [+] all of these answers

7. Virtual machine considerations include?

- [-] right sizing the virtual machine
- [-] costs
- [-] egress charges
- [+] all of these answers

8. A virtual machine must be assigned to an availability set at what time?

- [+] When the virtual machine is being created.
- [-] After the virtual machine has been created.
- [-] At any time.

9. Azure supports what type of virtual disk format?

- [-] VMDK
- [-] OVA
- [+] VHD
- [-] VHDX

10. Adding a data disk is initially created where?

- [+] In the virtual machine blade.
- [-] Directly in the virtual machine.
- [-] Data disks are not required or recommended.

11. Stopping the virtual machine from the portal does what?

- [+] Deallocates the virtual machine and stops incurring charges.
- [-] Stops the virtual machine but continues to incur costs.
- [-] It does nothing, the virtual machine will continue to run and incur costs.

12. According to Gartner, a password reset by the IT help desk costs on average?

- [-] 125
- [-] 25
- [-] 10
- [+] 70

13. In Azure Active Directory to assign a user a specific administrative role you would choose which directory role?

- [-] The directory role
- [+] Limited Administrator
- [-] User
- [-] Global Administrator

14. The Microsoft provided traffic manager does what?

- [+] Automates traffic flow to available regions.
- [-] Redirects traffic to other countries in the case of a failure.
- [-] Microsoft does not provide a traffic manager.

15. The default storage replication type for a Recovery Services vault is?

- [-] Zone redundant storage (ZRS)
- [-] Locally-redundant storage (LRS)
- [+] Geo-redundant storage (GRS)
- [-] Read Access Geo-redundant storage (RA-GA)
