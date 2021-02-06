## [Azure Administration: Implement and Manage Storage](https://www.linkedin.com/learning/azure-administration-implement-and-manage-storage)

### Manage Storage Accounts
------

Looking at Azure replication within the secondary region, which option allows data to be read from the replica without Microsoft initiating a failover?

- [-]geo-redundant storage (GRS)
- [-] read-access geo-zone-redundant storage (RA-GZRS)
- [-] geo-zone-redundant storage (GZRS)
- [+] read-access geo-redundant storage (RA-GRS)

When you create a storage account using Azure AD authentication, which RBAC role should you assign to allow for read, write, and delete blob access?

- [-] Storage Blob Data Reader
- [-] Storage Blob Data Owner
- [-] Storage Blob Delegator
- [+] Storage Blob Data Contributor

Which access tier on your Azure Storage account is used for frequent object access, and is also the default tier?

- [-] the premium tier
- [-] the cool tier
- [-] the archive tier
- [+] the hot tier

What does Microsoft recommend you use for the Account Kind when creating a storage account?

- [-] FileStorage
- [-] BlockBlobStorage
- [-] Storage (general purpose v2)
- [+] StorageV2 (general purpose v2)

Which type of shared access signature, or SAS, is recommended when you need access to any of the storage services?

- [+] an Account SAS
- [-] a User SAS
- [-] a Service SAS
- [-] a Storage SAS

How often should you regenerate your Azure Storage account keys?

- [+] regularly
- [-] monthly
- [-] daily
- [-] weekly

### Manage Data in Azure Storage
------

In order to move data to Azure, using the Azure Data Box Disk, what must you do first?

- [-] Enable the export service.
- [-] Retrieve the BitLocker key.
- [-] Import data to blobs.
- [+] Prepare the disks.

When importing a job into Azure, what does Microsoft recommend using for the journal name?

- [+] the serial number drive
- [-] the source directory
- [-] the session ID
- [-] the BitLocker numerical password

Where will you retrieve the BitLocker keys when you open an export job?

- [-] in Locks
- [-] in Properties
- [+] in Encryption
- [-] in Tags

If you are working with Azure files, what is the only option for authentication?

- [-] the URL for the storage account
- [+] the shared access signature
- [-] the tenant ID
- [-] the AZCopy login

### Configure Azure Files
------

If you are creating an Azure file share and using GRS or GZRS, what must you do?

- [-] Mount the file share to your local systems.
- [-] Ensure you have over 5 tebibytes of storage.
- [-] Declare your variables.
- [+] Remove the parameter `EnableLargeFileShare`.

After you create an Azure file share using PowerShell, which command can you use to view the files in that file share?

- [-] New-AzStorageShare - Name $FileSharename - Context $ctx
- [-] New-AzStorageDirectory -ShareName $FileSharename -Path $Path -Context $ctx
- [-] Remove-AzStorageShare -Name $FileSharename -Context $ctx
- [+] Get-AzStorageShare -Context $ctx

Before you can register a server with the sync service, what must you create first?

- [-] the region
- [-] the cloud share
- [-] the sync service
- [+] the server

### Configure Azure Blob Storage
------

Which Azure Blob type is only used for VHDs?

- [-] a block blob
- [-] a queue blob
- [+] a page blob
- [-] an append blob

Which tier is only available at the blob level?

- [+] the archive tier
- [-] the hot tier
- [-] the premium tier
- [-] the cool tier