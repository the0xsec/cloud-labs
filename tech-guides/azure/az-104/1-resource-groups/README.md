<p><a target="_blank" href="https://app.eraser.io/workspace/HWP4VkuWLwXtkhbP1iIZ" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

# Understand Azure Resource Groups
In this lab, you will read and learn about Azure Resource Groups.

Reference Documentation:

- [﻿Azure Resource Manager Overview](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview)  
- [﻿The 0x - AZ-104 Guide](https://publish.obsidian.md/ysac/Azure/AZ-104/AZ-104) 
---

## How to deploy Azure Resource Groups using Pulumi
In this lab, deploy the Azure Resource Group using Pulumi defined in `main.go` file. Login to the Azure portal and verify the deployment of the resource group and the storage account. Notice how the storage account is tied to the resource group called `the0xResourceGroup`.

## Goal
The goal is to see how the Storage Account is tied to the Resource Group and that various resources objects are grouped together in a logical manner and stored within a single subscription. In the diagram provided you can see we have a resource-group which consists of a VM and a Storage Account. These two resources are paired together.

## Cleanup
After you have verified the deployment, remove the resources by running `pulumi destroy` and then `pulumi stack rm dev` to remove the stack.


<!-- eraser-additional-content -->
## Diagrams
<!-- eraser-additional-files -->
<a href="/cloud-labs/azure/az-104/1-resource-groups/README-Azure Resource Groups-1.eraserdiagram" data-element-id="gFdLF6vwTYrvo3MCfJeOk"><img src="/.eraser/HWP4VkuWLwXtkhbP1iIZ___5TeIkEqzZuNt0Cv0uz03Dj9ejbv1___---diagram----2c52e08b05498598768b64dd9cae7a6b-Azure-Resource-Groups.png" alt="" data-element-id="gFdLF6vwTYrvo3MCfJeOk" /></a>
<!-- end-eraser-additional-files -->
<!-- end-eraser-additional-content -->
<!--- Eraser file: https://app.eraser.io/workspace/HWP4VkuWLwXtkhbP1iIZ --->