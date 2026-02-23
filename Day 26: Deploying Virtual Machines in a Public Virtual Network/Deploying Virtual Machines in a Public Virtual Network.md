<img width="593" height="266" alt="Screenshot 2026-02-23 111833" src="https://github.com/user-attachments/assets/b7d63cb7-8f1b-499b-9469-04896e1ad4ef" /><img width="593" height="266" alt="Screenshot 2026-02-23 111833" src="https://github.com/user-attachments/assets/b7d63cb7-8f1b-499b-9469-04896e1ad4ef" />## Day 26: Deploying Virtual Machines in a Public Virtual Network

#### Task Details 
The Nautilus DevOps Team has received a request from the Networking Team to set up a new public-facing services. This VNet will host various resources that need to be accessible over the internet. As part of this setup, you need to ensure the VNet has public subnets with automatic public IP assignment for resources. Additionally, a new VM will be launched within this VNet to host public applications that require SSH access. This setup will enable the Networking Team to deploy and manage public-facing applications.
- Create a public VNet named `datacenter-pub-vnet`, and a subnet named `datacenter-pub-subnet` under the same, make sure public IP is being auto-assigned to resources under this subnet
- Further, create a VM named `datacenter-pub-vm` under this VNet. Make sure SSH `port 22` is open for this instance and accessible over the internet. Use the Azure portal to complete the task and ensure that SSH access is configured correctly.

#### STEPS
1. Sign in to the [Azure Portal](https://portal.azure.com/) 

2. Use the global search bar to search for “Virtual network.” From the results, select “Virtual network.”

<img width="593" height="266" alt="Screenshot 2026-02-23 111833" src="https://github.com/user-attachments/assets/ec81721c-2958-4ce1-b637-0cee8279311f" />
 
3. From the Virtual Network dashboard, click on create button
