Managed identities: https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview
- Enables azure resources to talk to each other, without passwords or keys.
- A Managed identity is a service principal behind the scenes
- Create a managed identity in Azure manually or through IaC. Assign it to your resource (eg a function) and its dependenies (eg a storage container)
- Configure the function to use DefaultAzureCredentials, with the client id from the service principal.
- Debug locally: End users must have same permissions as the managed identity.

User assigned managed identity or System assigned managed identity?
Managed identities vs EntraId identity?
