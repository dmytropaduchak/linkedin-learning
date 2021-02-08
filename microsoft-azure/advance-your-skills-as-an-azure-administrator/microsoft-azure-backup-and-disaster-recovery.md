## [Microsoft Azure: Backup and Disaster Recovery](https://www.linkedin.com/learning/microsoft-azure-backup-and-disaster-recovery)

### Disaster Recovery Overview

By default Microsoft provides how many copies of your Azure SQL Database?

- [-] 2
- [+] 3
- [-] 4
- [-] 1

The Microsoft Virtual machine SLA states you must have how many machines in an availability set to guarantee the 99.95% SLA?

- [-] 1
- [-] 3
- [+] 2
- [-] 4

### Azure Backup Solutions

For large amounts of data that need be protected but can not be uploaded, what should you use?

- [-] Azure Backup Service
- [+] Azure Import/Export Service
- [-] Microsoft Hard Drive Swap
- [-] Azure Delivery Service

The Azure Recovery Service Vault defaults to what type of storage replication type?

- [-] read-access geo-redundant storage
- [+] geo-redundant storage
- [-] locally-redundant storage
- [-] zone-redundant storage

A recovery services vault will not be available to use if it is located in _____.

- [+] a different region
- [-] an area that is not encrypted
- [-] a different data center

What is the minimum client operating system that Azure Backup Supports?

- [-] Windows 8.1 64 Bit
- [-] Windows 10
- [-] Windows XP
- [+] Windows 7 64 Bit

What does the Azure Backup Server require?

- [-] the server to be domain joined
- [-] .Net 3.5 Framework
- [-] Server 2016
- [+] all of these answers

Local storage on the Azure Backup Server is required _____.

- [-] to keep the license active
- [-] for the Azure Backup Server installation
- [+] to keep a local copy of the backup

Which agent would be used if the system to be protected is in a workgroup?

- [-] protection agent
- [+] attach agent
- [-] install agent
- [-] download agent

The two types of protection groups that can be created are:

- [-] Application Server and Cloud Server
- [-] File Server and Data Server
- [-] Windows 10 clients and Window 7 clients
- [+] Servers and Clients

When should you create a replica manually?

- [-] If you are going to transfer at a specified date and time.
- [+] If you are transferring data using removable media.
- [-] If you are transferring across the network.

How long can a SQL Azure Database be retained when using LongTerm Backups?

- [-] 15 years
- [-] 5 years
- [-] 1 year
- [+] 10 years

What is the maximum retention for Azure File Shares?

- [+] 120 days
- [-] 180 days
- [-] 60 days
- [-] 30 days

What can not be changed, once backups are in the Recovery Services Vault?

- [+] storage redundancy type
- [-] storage size
- [-] backup recover plans

### Azure Restore Solutions

If you need to customize a restored Azure virtual machine you would need to use what tool?

- [-] The Portal
- [-] Visual Studio
- [+] PowerShell

What is not supported when you restore files or folders from an Azure virtual machine backup?

- [-] you can not restore files or folders from an Azure machine backup
- [+] encrypted disks
- [-] all disks

What is the default amount of time a folder will be mounted for:

- [-] 12 hours
- [-] 3 hours
- [+] 6 hours
- [-] 1 hour

What is the minimum OS that Azure Site Recovery can be installed on?

- [-] Server 2008 R2
- [-] Server 2008
- [+] Server 2012 R2
- [-] Server 2012

How long is the vault credential valid for?

- [+] 2 days
- [-] 3 days
- [-] It never expires
- [-] 24 hours

A Point In Time Restore in the Standard or Premium tier of SQL has a maximum retention of how long?

- [+] 35 days
- [-] 7 days
- [-] 21 days
- [-] 14 days

### Azure Site Recovery

Azure Site Recovery can replicate a physical server to Azure. The replicated server can fail back to _____.

- [-] another physical server
- [+] a virtual machine
- [-] the same physical server

In preparation for an ASR implementation in Azure, what do you need to create?

- [-] a storage account
- [-] a recovery services vault
- [-] a virtual network
- [+] all of the above

How long can it take for the Hyper-V servers to be found after the Hyper-V servers have been added?

- [+] 15-30 minutes
- [-] 30-60 minutes
- [-] 6 hours
- [-] immediately

Copy frequency of 15 minutes will be changed to how many minutes when the 15 minute option is deprecated?

- [-] 30 seconds
- [-] 1 minute
- [+] 5 minutes
- [-] 10 minutes

What is needed to add a script to recovery plan action?

- [-] nothing is needed
- [+] an automation account
- [-] scripts are not supported in recovery plans

After a successful test failover you will need to _____.

- [-] do nothing, since no action is required
- [+] run the cleanup test failover
- [-] delete the resources manually

A planned failover is initiated when _____.

- [-] the protected machine fails unexpectedly
- [+] the protected machine is known to be available
- [-] no difference exists between the failover options

After a failback, what is the final step in the process?

- [-] Delete resources manually.
- [+] Commit the failback.
- [-] Clean up resources.
- [-] Nothing is required.

When replicating a virtual machine, what state should the virtual machine be in?

- [-] stop state
- [-] unallocated state
- [+] running state
- [-] paused state
