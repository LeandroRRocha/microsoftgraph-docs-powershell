---
Module Name: Microsoft.Graph.Beta.DirectoryObjects
Module Guid: d6208ea7-8014-4006-845b-dc429e3a52a4
Download Help Link: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.directoryobjects
Help Version: 1.0.0.0
Locale: en-US
---

# Microsoft.Graph.Beta.DirectoryObjects Module
## Description
Microsoft Graph PowerShell Cmdlets

## Microsoft.Graph.Beta.DirectoryObjects Cmdlets
### [Confirm-MgBetaDirectoryObjectMemberGroup](Confirm-MgBetaDirectoryObjectMemberGroup.md)
Check for membership in a specified list of group IDs, and return from that list those groups (identified by IDs) of which the specified user, group, service principal, organizational contact, device, or directory object is a member.
This function is transitive.
You can check up to a maximum of 20 groups per request.
This function supports all groups provisioned in Azure AD.
Because Microsoft 365 groups cannot contain other groups, membership in a Microsoft 365 group is always direct.

### [Confirm-MgBetaDirectoryObjectMemberObject](Confirm-MgBetaDirectoryObjectMemberObject.md)
Invoke action checkMemberObjects

### [Get-MgBetaDirectoryObject](Get-MgBetaDirectoryObject.md)
Retrieve the properties and relationships of a directoryObject object.

### [Get-MgBetaDirectoryObjectById](Get-MgBetaDirectoryObjectById.md)
Return the directory objects specified in a list of IDs.
Some common uses for this function are to:

### [Get-MgBetaDirectoryObjectCount](Get-MgBetaDirectoryObjectCount.md)
Get the number of the resource

### [Get-MgBetaDirectoryObjectDelta](Get-MgBetaDirectoryObjectDelta.md)
Invoke function delta

### [Get-MgBetaDirectoryObjectMemberGroup](Get-MgBetaDirectoryObjectMemberGroup.md)
Return all the group IDs for the groups that the specified user, group, service principal, organizational contact, device, or directory object is a member of.
This function is transitive.

### [Get-MgBetaDirectoryObjectMemberObject](Get-MgBetaDirectoryObjectMemberObject.md)
Invoke action getMemberObjects

### [Get-MgBetaDirectoryObjectUserOwnedObject](Get-MgBetaDirectoryObjectUserOwnedObject.md)
Retrieve a list of recently deleted application and group objects owned by the specified user.
This API returns up to 1,000 deleted objects owned by the user, sorted by ID, and doesn't support pagination.

### [New-MgBetaDirectoryObject](New-MgBetaDirectoryObject.md)
Add new entity to directoryObjects

### [Remove-MgBetaDirectoryObject](Remove-MgBetaDirectoryObject.md)
Delete a directory object, for example, a group, user, application, or service principal.

### [Test-MgBetaDirectoryObjectProperty](Test-MgBetaDirectoryObjectProperty.md)
Validate that a Microsoft 365 group's display name or mail nickname complies with naming policies.
Clients can use this API to determine whether a display name or mail nickname is valid before trying to **create** a Microsoft 365 group.
For validating properties of an existing group, use the validateProperties function for groups.
The following validations are performed for the display name and mail nickname properties: \n1.
Validate the prefix and suffix naming policy\n2.
Validate the custom banned words policy\n3.
Validate the mail nickname is unique This API returns with the first failure encountered.
If one or more properties fail multiple validations, only the property with the first validation failure is returned.
However, you can validate both the mail nickname and the display name and receive a collection of validation errors if you are only validating the prefix and suffix naming policy.

### [Update-MgBetaDirectoryObject](Update-MgBetaDirectoryObject.md)
Update entity in directoryObjects

