## [Planning for Azure Active Directory](https://www.linkedin.com/learning/planning-for-azure-active-directory)

### AD Connect Fundamentals
------
How many internal components comprise the AD Connect tool?

- [-] seven
- [+] three
- [-] two
- [-] four

What are the three deployment configurations that can be implemented in the deployment of AD Connect?

- [-] Regular, Concave, and Convex
- [-] Small, Medium, and Large
- [+] Simple, Converging, and Diverging
- [-] Low, Neutral, and High

Which AD Connect supporting tool should you use to create custom incoming or outgoing synchronization rules?

- [+] Synchronization Rules Editor
- [-] AD Connect Wizard
- [-] Synchronization Service Manager
- [-] Web Service Configuration Tool

What is the name of the attribute that maps Active Directory objects on-premises to their corresponding counterparts in Azure AD?

- [+] Source Anchor
- [-] Dip Anchor
- [-] Object Link
- [-] Hybrid Mapper

Which AD Connect supporting tool should you use to change settings that were configured during the initial installation?

- [+] AD Connect Wizard
- [-] Synchronization Service Manager
- [-] Web Service Configuration Tool
- [-] Synchronization Rules Editor

Which is a valid deployment configuration rule that corresponds to the relation between AD Connect and the Azure AD Tenant?

- [-] Each unique object should only synchronize to one Azure AD Tenant.
- [+] The ratio must be 1 is to 1.
- [-] The ratio should be > 1.
- [-] The ratio should be <1.

Which is a valid deployment configuration rule that corresponds to the relation between AD Forest Topology on-premises and the AD Connect tool?

- [-] The ratio should be <1.
- [-] The ratio should be > 1.
- [-] The ratio must be 1 is to 1.
- [+] Each unique object should only synchronize to one Azure AD Tenant.

Which AD Connect supporting tool should you use to perform a Metaverse Search?

- [-] Synchronization Rules Editor
- [-] Web Service Configuration Tool
- [+] Synchronization Service Manager
- [-] AD Connect Wizard

### Planning for Users and Devices
------

Which object filtering method is only used for testing and not in production environments?

- [-] Attribute-based filtering
- [+] Group-based filtering
- [-] Domain-based filtering
- [-] OU-based filtering

Which AD Connect feature should you enable to ensure self-service password reset credentials are consistent with the on-premises credentials?

- [-] Password Hash Synchronization
- [-] Passwords Reversal
- [-] Password Linking
- [+] Password Writeback

Which is a disadvantage of using AD FS Authentication as the sign-in method for users?

- [-] writeback capability
- [+] high infrastructure requirements
- [-] passwords stored in the cloud
- [-] seamless SSO

What is an advantage of using Pass-Through Authentication as the sign-in method for users?

- [-] high infrastructure requirements
- [-] federated SSO
- [+] passwords stored on-premises
- [-] passwords stored in the cloud

What is an advantage of using Password Hash Synchronization as the sign-in method for users?

- [+] low dependency on-premises
- [-] writeback capability
- [-] passwords stored on-premises
- [-] federated SSO

What is the primary source of authority for managing Synchronized Users?

- [-] Azure AD
- [+] Windows Server
- [-] System Center
- [-] Microsoft Intune

Which device management strategy is convenient for managing devices of Synchronized Users?

- [+] Hybrid Azure AD Join
- [-] Windows Server Domain Join
- [-] Azure AD Join
- [-] Device Registration

### Preparing the Environment
------

What outbound ports must be open for AD Connect to communicate and send synchronization data to Azure AD?

- [+] 80 and 443
- [-] 445
- [-] 1433
- [-] 389 and 636

Which prerequisite is needed to initialize the first synchronization in AD Connect?

- [-] an Azure AD license
- [-] a domain administrator account
- [-] a verified domain
- [+] a global administrator account

What should you do to ensure your local Active Directory domain maps successfully with the verified domain in Azure AD?

- [-] Verify the Azure AD domain in Windows Server.
- [-] Add a Schema Prefix to it.
- [+] Add a UPN suffix for it.
- [-] Verify the local domain in Azure AD.

What can you do to ensure low latency of synchronization during the installation of AD Connect?

- [-] Install AD Connect on the domain controller.
- [-] Install AD Connect in the perimeter network.
- [+] Install AD Connect and its database on the same server.
- [-] Install AD Connect in Express mode.

### Deploying AD Connect
------

What should you implement to ensure business continuity in case an AD Connect server fails?

- [-] Configure high availability.
- [-] Implement clustering.
- [-] Implement load balancing.
- [+] Implement Staging mode.

Which initial installation mode should you choose to enable Pass-Through Authentication for users in AD Connect?

- [-] AD Connect Reconfiguration Wizard
- [-] Express mode
- [-] PTA mode
- [+] Custom mode

What should you do to ensure AD Connect Health also monitors your domain controllers?

- [-] Enable agentless DC monitoring in Azure.
- [-] Enable DC Monitoring mode in AD Connect.
- [-] Install AD Connect on the domain controller.
- [+] Install the agent on the DCs.
