# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket Role Conigurations</h1>
<p>This tutorial will cover the post-installation configuration of the help desk ticketing system osTicket. I will be configuring various roles you would come accross at a typical Help Desk Role such as Departments, Teams, SLAs, Agents, Users, and more. </p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-  Create Roles
-  Create Departments
-  Create Teams
-  Create Agents
-  Create Users
-  Create SLA
-  Create Help Topics
   <h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel > Agents > Roles > Add New Role > Create "Head Admin"
</p>
  
<img width="962" alt="Screenshot 2024-12-18 at 2 08 17 PM" src="https://github.com/user-attachments/assets/a53da265-66c6-4798-83e9-b881c9849276" />
<img width="963" alt="Screenshot 2024-12-18 at 2 09 04 PM" src="https://github.com/user-attachments/assets/85927902-2efa-450c-b574-f09842e1ea41" />
<img width="962" alt="Screenshot 2024-12-18 at 2 11 09 PM" src="https://github.com/user-attachments/assets/aab7ee20-a80b-40ff-9558-5d0875237179" />
<img width="963" alt="Screenshot 2024-12-18 at 2 11 22 PM" src="https://github.com/user-attachments/assets/a0f33eaf-eef0-4e26-af2f-2672474a80e8" />
<img width="960" alt="Screenshot 2024-12-18 at 2 11 42 PM" src="https://github.com/user-attachments/assets/a23f630e-91d5-42e6-9cfb-9b8bcf934979" />


<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel > Agents > Departments > Add New Department > Name: "Sys. Admins"
</p>
<p>
<img width="960" alt="Screenshot 2024-12-18 at 2 12 56 PM" src="https://github.com/user-attachments/assets/18453148-c235-4dda-96b5-ac02a7ccf425" />
<img width="965" alt="Screenshot 2024-12-18 at 2 13 44 PM" src="https://github.com/user-attachments/assets/6a37e1ea-0841-4183-bb32-f9d367cf5bbf" />
<img width="962" alt="Screenshot 2024-12-18 at 2 14 11 PM" src="https://github.com/user-attachments/assets/40dc8073-1ef3-47f9-9500-b54c6593a3f9" />


  <h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel > Agents > Teams > Add New Team > Name: "Online Banking"
</p>
<p>
  <img width="962" alt="Screenshot 2024-12-18 at 2 14 47 PM" src="https://github.com/user-attachments/assets/6c0fdb6b-3fb3-4500-b74a-c739bfbd6eb4" />
<img width="960" alt="Screenshot 2024-12-18 at 2 15 44 PM" src="https://github.com/user-attachments/assets/d69b3a5e-9aef-40f3-94c4-045070193c1d" />



  <h3 align="center">Allow anyone to create tickets</h3>
<br />
<p>
  Admin Panel > Settings > User Settings > Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>

  <img width="961" alt="Screenshot 2024-12-18 at 2 16 03 PM" src="https://github.com/user-attachments/assets/0b1385cb-d4d4-4074-90a9-bae8207f22e4" />
<img width="961" alt="Screenshot 2024-12-18 at 2 16 46 PM" src="https://github.com/user-attachments/assets/1d804ac9-547c-43e8-87a4-4204db6d0922" />

<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel > Agents > Add New Agent >  Create the Users "Jane Doe" and "John Doe" (Dont lose the User and Password)
  Make sure to uncheck "Require password change at next login"
</p>
  
<img width="961" alt="Screenshot 2024-12-18 at 2 17 19 PM" src="https://github.com/user-attachments/assets/8448f8df-1cf7-4c1f-89d2-1b12586a267b" />
<img width="961" alt="Screenshot 2024-12-18 at 2 17 34 PM" src="https://github.com/user-attachments/assets/2839d230-502a-4218-bb5b-136031c157f7" />
<img width="961" alt="Screenshot 2024-12-18 at 2 19 03 PM" src="https://github.com/user-attachments/assets/78ea7e58-db10-46b6-afd8-6bbe3d9f47ac" />
<img width="651" alt="Screenshot 2024-12-18 at 2 20 51 PM" src="https://github.com/user-attachments/assets/bb35bfac-b8f1-489f-b167-066909867515" />

  <h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel > Users > Add New Role > Create Users "Karen" and "Ken". These will be the "customers" that will create tickets for the agents to work on.
</p>
<p>
<img width="962" alt="Screenshot 2024-12-18 at 2 24 15 PM" src="https://github.com/user-attachments/assets/11a58139-0ab4-4b18-97f2-e05ac9bb4647" />
<img width="647" alt="Screenshot 2024-12-18 at 2 24 41 PM" src="https://github.com/user-attachments/assets/1c918a3c-8078-4808-8bfe-24e8396cc0a1" />

 

  <h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel > Manage > SLA - a Service-Level Agreement (SLA) is essentially an agreement between the Service Provider and a customer defining the minimum amount of service that needs to be provided.
</p>
<p>

  <img width="235" alt="Screenshot 2024-12-18 at 2 26 14 PM" src="https://github.com/user-attachments/assets/4b82d79f-50bd-4c58-8193-aae1e3735574" />
<img width="964" alt="Screenshot 2024-12-18 at 2 26 26 PM" src="https://github.com/user-attachments/assets/6350e733-1d8f-4914-a7b6-ea29b46a1bb6" />
 <p>
 Severity-A (1 hour, 24/7)
 </p>
<img width="960" alt="Screenshot 2024-12-18 at 2 28 37 PM" src="https://github.com/user-attachments/assets/004924cf-9d6b-4376-9ea4-a6711cbd6381" />
<p>
  Severity-B (4 hours, 24/7)
</p>
<img width="961" alt="Screenshot 2024-12-18 at 2 29 09 PM" src="https://github.com/user-attachments/assets/53864e8c-9b5c-477c-86ab-eb9836039c58" />
<p>
 Severity-C (8 hours, business hours)
 </p>
<img width="960" alt="Screenshot 2024-12-18 at 2 29 32 PM" src="https://github.com/user-attachments/assets/629ec901-5132-4e44-a1ee-8eff740d583b" />



  <h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel > Manage > Help Topics > Create New Help Topic
</p>
<p>
<img width="960" alt="Screenshot 2024-12-18 at 2 30 45 PM" src="https://github.com/user-attachments/assets/3e9603f2-fdc5-4f02-90e9-ada714839e99" />
<img width="962" alt="Screenshot 2024-12-18 at 2 31 15 PM" src="https://github.com/user-attachments/assets/9f14d04f-fec8-424c-9c30-0d32df1cfa8e" />
<p>
Name: "Business Critical Outage"
</p>
<img width="961" alt="Screenshot 2024-12-18 at 2 31 38 PM" src="https://github.com/user-attachments/assets/ba11779c-5d77-42b1-a0cc-c64b9cfc85e9" />
<p>
Name: "Personal Computer Issues"
</p>
<img width="961" alt="Screenshot 2024-12-18 at 2 32 02 PM" src="https://github.com/user-attachments/assets/78fff783-4e07-4f33-a973-2106fd24b8ac" />
<p>
Name: "Equipment Request"
</p>
<img width="961" alt="Screenshot 2024-12-18 at 2 32 27 PM" src="https://github.com/user-attachments/assets/a3ff7314-2b2c-402b-bde6-5c3646b01459" />
<p>
 Name: "Password Reset"
</p>
<img width="961" alt="Screenshot 2024-12-18 at 2 33 12 PM" src="https://github.com/user-attachments/assets/97d609f9-b4d8-497f-94aa-eba4c52de3de" />
<p>
Name: "Other"
</p>
<img width="960" alt="Screenshot 2024-12-18 at 2 33 37 PM" src="https://github.com/user-attachments/assets/42d7795d-ba5a-43d8-853c-a436fbbb9afd" />















  
