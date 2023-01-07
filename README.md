Add-Groups-from-1-user-to-another

This script adds all the AzureAD groups from one user to another. 

First Connect to your Azure tenant
The script is interactive. It gets all of the tenants users and presents them with their UPN and objectID. 
Choose the example. This is the user that has all the right groups already added.
Next choose the target user. The user to which all the same groups should be added to 

The script does not copy 'roles' on purpose

If a user has already been added to a certain group you will be notified. 
