## Day 6: Create a Subnet in Azure Virtual Network

#### Task Details:
The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the Azure cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition.
- Create a Virtual Network (VNet) named `devops-vnet` and one subnet named `devops-subnet` within the VNet in the `East US` region. Make sure the IPv4 address range is `10.0.0.0/16`

1. Sign in to the [Azure Portal](https://portal.azure.com/)

2. Use the global search bar to search for “Virtual network.” From the results, select “Virtual network.”

<img width="993" height="879" alt="537295630-42c4d35f-59e5-42b6-aae1-a36298715809" src="https://github.com/user-attachments/assets/d4db0812-6180-496b-a96b-8eb62375aec5" />

3. From the Virtual Network dashboard, click on create button

<img width="957" height="875" alt="537295738-ae06d70b-3cd2-4400-9dc7-39d15429cd81" src="https://github.com/user-attachments/assets/929b0727-5bc7-4736-9b86-324b2454833e" />

4.On the Basics tab of the Create virtual network page, enter the VM name and select the appropriate region.

<img width="679" height="600" alt="Screenshot 2026-01-19 141124" src="https://github.com/user-attachments/assets/091b9b36-5a4d-49a3-82c4-68b1aec6ef74" />

5. On the IP address tab, click Next, update the default subnet name to devops-subnet, and then select Save

<img width="678" height="602" alt="Screenshot 2026-01-19 141458" src="https://github.com/user-attachments/assets/d67555b3-977a-4767-b542-f3bf8464f10f" />

6. Then, select Create to complete the process

<img width="683" height="599" alt="Screenshot 2026-01-19 141555" src="https://github.com/user-attachments/assets/aba691cc-2981-4aa6-b3ea-5e075523d1a2" />

