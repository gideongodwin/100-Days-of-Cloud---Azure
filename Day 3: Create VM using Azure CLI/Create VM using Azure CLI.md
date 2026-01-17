The Nautilus DevOps team is in the process of migrating some of their workloads to Azure. One of the tasks involves creating a new Virtual Machine (VM) using the Azure CLI. The team does not have access to the Azure portal but can manage Azure resources via the azure-client host (the landing host for this lab).
1) Create a new Azure Virtual Machine named xfusion-vw using the Azure CLI.
2) Use the Ubuntu2204 Image and set the VM size to Standard_825
3) Make sure the admin username is set to azureuser and SSH keys are generated for secure access.
4) Use Standard LRS storage account, disk size must be 30GB and ensure the VM xfusion-vm is in the running state after creation.
