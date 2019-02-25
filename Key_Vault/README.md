# Key Vault
ARM template for deployment Azure Key Vault with access policies configured for user/application and Run As Account

## Needed parameters:
* Azure AD Tenant ID where Key Vault will be deployed
* Object ID of user or application that needs access to Key Vault objects 
* Object ID of Azure Run As account that was created previously
