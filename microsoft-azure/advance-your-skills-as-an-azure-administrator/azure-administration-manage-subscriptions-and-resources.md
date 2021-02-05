## [Azure Administration: Manage Subscriptions and Resources](https://www.linkedin.com/learning/azure-administration-manage-subscriptions-and-resources)

------
### Manage Azure Subscriptions
------

What role allows for privilege at the root scope?

- [-] Contributor
- [-] Reader
- [-] Owner
- [+] User Access Administrator

What are removed when a subscription moves to another Azure AD Tenant?

- [-] Virtual machines
- [-] Disks
- [+] RBAC Assignments
- [-] Websites

Abid is attempting to apply a tag to a resource but is unable to do so. What is the minimum role that is required to apply tags?

- [-] User Role
- [-] Operator Role
- [+] Contributor Role
- [-] Reader Role

Rachel, who has been assigned the contributor role, is trying to create a new Resource Group in the West US and is unable to do so. What could be preventing this?

- [+] A policy restricting creation of Resource Groups in the West US has been applied at the Subscription level.
- [-] Rachel does not have the permissions to create Resource Groups.
- [-] A policy has been applied to Rachel that prevents her from creating Resource Groups in the subscription.
- [-] A policy has been applied to Rachel that prevents her from creating Resource Groups in the West US.

An initiative definition is _____.

- [+] a grouping of policy definitions
- [-] a grouping of assignment definitions
- [-] a grouping of parameters definitions
- [-] sa subset of policy assignments

------
### Analyze Resource Utilization and Consumption
------

What log would you access to determine who created a virtual machine on a specific day and time?

- [-] Azure system logs
- [-] Diagnostic logs
- [-] Application logs
- [+] Activity logs

What is the default TimeGrain?

- [-] PT15M
- [-] PT5M
- [-] PT10M
- [+] PT1M

What is the PowerShell command to add the DSC module?

- [-] Set-DscResource -ModuleName PsDesiredStateConfiguration
- [-] Import-DscResource PsDesiredStateConfiguration
- [+] Import-DscResource -ModuleName PsDesiredStateConfiguration
- [-] Get-DscResource -ModuleName PsDesiredStateConfiguration

What are the three components of an alert?

- [-] criteria, action, user
- [-] resource ID, target, action
- [-] source, criteria, action
- [+] target, criteria, action

Flavio needs to review the metrics from an Azure virtual machine. He is unable to view the logs from 100 days ago. Why?

- [-] Flavio does not have the appropriate permission to view metrics.
- [+] Metric history is kept 93 days.
- [-] Metric history is kept for 95 days.
- [-] Metrics are not retained for Azure virtual machines.

Low or under-utilized virtual machines must meet which default rules?

- [-] CPU utilization is less than 5% and network usage is less than 7 MB for 14 days.
- [-] CPU utilization is less than 10% and network usage is less than 7 MB for four days.
- [+] CPU utilization is less than 5% and network usage is less than 7 MB for four days.
- [-] CPU utilization is less than 5% and network usage is less than 5 MB for four days.

ABC company has lost access to all of its Azure resources halfway through the billing period. Why?

- [+] ABC company reached its spending limit on its credit subscription for the billing period.
- [-] The network admin forgot to pay the bill.
- [-] The credit card associated with the Pay As You Go subscription expired.

------
### Manage Resource Groups
------

What PowerShell cmdlet is used to create a Policy Assignment?

- [-] Set-AzureRMPolicyAssignment
- [+] New-AzureRMPolicyAssignment
- [-] Get-AzureRMPolicyAssignment
- [-] New-PolicyAssignment

Shiva, who belongs to the Azure contributor role, is unable to apply locks to resources. What permissions does Shiva need to apply locks?

- [-] Microsoft.Authorization/locks/*
- [-] Microsoft.Authorization/*
- [-] Owner role
- [+] all of these answers

What PowerShell cmdlet is used to create a new tag?

- [+] New-AzureRMTag
- [-] Set-AzureRMTag
- [-] New-AzureTag
- [-] Set-AzureTag

Joelle is testing a resource move and receives a code of 204. What does this mean?

- [-] The validation request was not accepted.
- [-] The move was unsuccessfully validated.
- [+] The move was successfully validated.
- [-] The validation request was accepted.

When moving resources to another resource group using PowerShell, what is required?

- [-] Resource Name
- [-] Subscription ID
- [+] Resource ID
- [-] Subscription name

Amelia wants to delete a Resource Group using PowerShell. What cmdlet does she need to use?

- [+] Remove-AzureRMResourceGroup
- [-] Delete-AzureRMResourceGroup
- [-] Remove-AzureResourceGroup
- [-] Delete-AzureResourceGroup