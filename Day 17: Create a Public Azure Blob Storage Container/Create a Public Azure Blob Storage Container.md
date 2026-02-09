<img width="680" height="594" alt="Screenshot 2026-02-09 130511" src="https://github.com/user-attachments/assets/46bb4021-9687-4826-aae5-01891b5a6536" />## Day 17: Create a Public Azure Blob Storage Container

#### Task Details:
As part of the data migration process, the Nautilus DevOps team is actively creating several storage containers on Azure. They plan to utilize public Blob containers to store the relevant data. Given the ongoing migration of other infrastructure to Azure, it is logical to consolidate data storage within the Azure environment as well.
- Create a new storage account named `devopsst21175` and a `public` Blob container named `devops-blob-1048` within the storage account. Make sure `anonymous read access for containers and blobs` is enabled

1. Sign in to the [Azure Portal](https://portal.azure.com/)
2. From the Azure portal dashboard, select Storage accounts
3. Click Create to create a new storage account

<img width="678" height="284" alt="Screenshot 2026-02-09 125953" src="https://github.com/user-attachments/assets/3f579d06-b81e-47d2-b4bf-5c666e0f41a5" />

4. On the Basics tab, select the existing Resource group, and then enter a name for the Storage account.

<img width="674" height="594" alt="Screenshot 2026-02-09 130142" src="https://github.com/user-attachments/assets/e19b49a2-9000-48bb-a311-c58acf9676c1" />

5. Select Review + create.
6. After the deployment is complete, select Go to resource
7. In the storage account, under Data storage, select Containers, and then select + Container
8. Select Add, and then enter a name for the container

<img width="680" height="594" alt="Screenshot 2026-02-09 130511" src="https://github.com/user-attachments/assets/cbf55c50-df45-4357-8e14-b1ccab25db6e" />

9. 

