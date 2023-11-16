# azure-devops-pipeline
This repo is used for deploying Azure resources through Azure DevOps Pipeline

Prerequisites :
Create a resource group in Azure.
Create a Storage account in Azure.
Create a Container inside the storage account in Azure.

Variables :

- bkstrgrg ------------> The name of the backend storage account resource group
- bkstrg --------------> The name of the backend storage account
- bkcontainer ---------> The container name for the backend storage account
- bkstrgkey -----------> The access key for the storage account
- resourcegroup_name --> RG Name
- location ------------> Azure Region Name
- vnet_name -----------> VNET Name
- bastionhost_name ----> Bastion Host Name
