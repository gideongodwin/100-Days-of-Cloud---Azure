## Day 13: SSH into an Azure Virtual Machine

#### Task Details:
The Nautilus DevOps team is working on setting us secure SSH access for their virtual machines in Azure. One of the requirements is to add the SSH public key of the root user from the Azure client host (landing host) to the diet Azure VM's file. This ensures secure and password-less SSH access to the VM.

1. VM Detalla
The VM is named and is running in the win mglon.
You need to add the root user's SSH public key from the Azure client host to the file of the VM's root user.
The SSH public key of the root user on the Azure client host is located at
2. Public Key Addition
Copy the public key located at on the Azure client host to the file of the root user on
Ensure that the proper permissions for the folder and are set on the VM.
3. Verification:
After adding the public key, make sure that you are able to SSH into the cent VM from the Azure client host without needing a password
Important Notes:
Ensure that the VM is up and running before attempting to SSH.
You may need to adjust the firewall or security group rules for the VM to allow SSH access.

STEPS:
1. Sign in to the [Azure Portal](https://portal.azure.com/)

2. On the virtual machines dashboard, select the available vm `xfusion-vm`

