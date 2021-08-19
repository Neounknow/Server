**How to sync. Azure AD with Window Server 2019**

1. Install Active Directory on Window Server
2. Promote as Domain controller
3. Login into Azure AD
4. Download & Install Azure Connected
5. During install will fill the user global admin from Azure AD and local admin for local AD

Note!
> Sync will be local to Azure only, not Azure to local.

**Setup Remote Desktop App with Window Server2019**
1. Run "Add Roles and Features Wizard"
2. Select Remote Desktop Services
3. Select Quick Start
4. Select Session-based if you needed to set session timeout.
5. Next until deploy.
6. Setup RD Licensing and added the license via Remote Desktop License.
7. Add RD Gateway, in case your domain is not public DNS
8. Applied Certificate for all
