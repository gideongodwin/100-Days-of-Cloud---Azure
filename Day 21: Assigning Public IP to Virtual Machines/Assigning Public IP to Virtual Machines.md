## Day 21: Assigning Public IP to Virtual Machines

##Task Details
The Nautilus DevOps Team has received a new request from the Development Team to set up a new Azure Virtual Machine (VM). This VM will be used to host a new application that requires a stable public IP address. To ensure that the VM has a consistent public IP, a Static Public IP address needs to be associated with it. The VM will be named devops-vm, and the Static Public IP will be named devops-pip. This setup will help the Development Team to have a reliable and consistent access point for their application.
- Create an Azure VM named `devops-vm` using any available Ubuntu image, with the VM size `Standard_B1s`
- Generate an SSH public key on the `azure-client` host and associate it with the VM for SSH access
- Associate a Static Public IP address named `devops-pip` with this VM
- Ensure the VM is accessible via SSH using the generated public key

