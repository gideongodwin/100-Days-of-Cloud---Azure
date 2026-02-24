## Day 27 Deploying Virtual Machines in a Private Virtual Network

#### Task Details 
The Nautilus DevOps team is expanding their Azure infrastructure and requires the setup of a private Virtual Network (VNet) along with a subnet. This VNet and subnet configuration will ensure that resources deployed within them remain isolated from external networks and can only communicate within the VNet. Additionally, the team needs to provision a Virtual Machine (VM) under the newly created private VNet. 
This VM should be accessible over SSH from within the VNet only, allowing for secure communication and resource management within the Azure environment. The name of the VNet must be `nautilus-priv-vnet`
- Create a subnet named nautilus-`priv-subnet` under the same. Further, create a Virtual Machine named `nautilus-priv-vm` under this VNet
- Additionally, create a Network Security Group (NSG) named `nautilus-priv-nsg` and ensure that the NSG rules for the VM allow access only from within the VNet's CIDR block
- Ensure all resources are created in the `Central US` region

#### STEPS
1. Sign in to the [Azure Portal](https://portal.azure.com/) 
2. Use the global search bar to search for “Virtual network.” From the results, select “Virtual network.”
3. From the Virtual Network dashboard, click on create button

<img width="578" height="232" alt="Screenshot 2026-02-24 094524" src="https://github.com/user-attachments/assets/f332f62d-726e-46c3-96fe-93bef0af0d91" />

4. On the Basics tab of the Create virtual network page, enter the VM name and select the appropriate region.

<img width="605" height="492" alt="Screenshot 2026-02-24 094615" src="https://github.com/user-attachments/assets/65d20b5f-102b-4fd3-a28f-df4f85166dc1" />

5. 



