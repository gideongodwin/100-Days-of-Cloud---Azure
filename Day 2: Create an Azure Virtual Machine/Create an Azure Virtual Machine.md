## Day 2: Create an Azure Virtual Machine

#### Task Details:
The Nautilus DevOps team is planning to migrate a portion of their infrastructure to the Azure cloud incrementally. As part of this migration, you are tasked with creating an Azure Virtual Machine (VM).
The requirements are:
- Use the existing resource group.
-  The VM name must be xfusion-vm, it should be in West us region.
-  Use the Ubuntu 22.04 LTS image for the VM.
-  The VM size must be standard Bis.
-  Attach a default Network Security Group (NSG) that allows inbound SSH (port 22).
-  Attach a 30 GB storage disk of type Standard HDD.
-  The rest of the configurations should remain as default.

1. Sign in to the [Azure Portal](https://portal.azure.com/) using the provided credentials

2. Select the "Virtual Machines" from the Microsoft Azure portal dashboard

<img width="684" height="506" alt="1" src="https://github.com/user-attachments/assets/0793550c-c6a5-4129-b6e5-6c903bc83d2a" />

3. From the Virtual Machines dashboard, select Create, then choose Virtual machine

<img width="683" height="597" alt="2" src="https://github.com/user-attachments/assets/8164100d-1c26-4cac-9bcd-7c36bd3caffc" />

4. Select the default resource group, enter the VM name, and choose the region

<img width="681" height="595" alt="3" src="https://github.com/user-attachments/assets/cdf98ba7-3514-4d49-a571-7306e728cdc6" />

5. Select the image and size

<img width="683" height="602" alt="4" src="https://github.com/user-attachments/assets/a2c947ae-86d9-4f8a-b997-cfee2aa62524" />

6. Allow inbound traffic for SSH on port 22, then click Next: Disks >

<img width="683" height="402" alt="5" src="https://github.com/user-attachments/assets/59d52dd5-4ade-4a74-8d8f-db1035fdbb22" />

7. Select the disk size and type, then click on the review + create button

<img width="681" height="177" alt="6" src="https://github.com/user-attachments/assets/3b39acd1-e805-4fd5-9f93-72ab9a824ff8" />

8. Locate the newly created VM on the Virtual Machines dashboard.

<img width="681" height="603" alt="Screenshot 2026-01-16 115452" src="https://github.com/user-attachments/assets/e66690b3-d900-494e-b29f-817f37fd2dda" />



