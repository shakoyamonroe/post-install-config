<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Administrative Settings
- Enable Email Fetching & SMTP
- Set Up User Roles and Permissions
- Configure Help Topics and Ticket Filters
- Secure osTicket with Best Practices


<h2>Configuration Steps</h2>

### 1️⃣ Configure Administrative Settings
- Navigate to **Admin Panel** → **Settings**.
- Update **Company Name, Default Timezone, and System Email**.
- Set up **Helpdesk Name and Email Preferences**.

  <img width="665" alt="Screenshot 2025-03-05 at 11 58 49 AM" src="https://github.com/user-attachments/assets/655d747c-2cd1-4778-9957-c12073dc7d4e" />


### 2️⃣ Set Up User Roles and Permissions
- Navigate to **Agents** → **Roles**.
- Create roles such as **Support Agent, Manager, and Administrator**.
- Assign **permissions** based on responsibilities.

  <img width="668" alt="Screenshot 2025-03-05 at 12 21 30 PM" src="https://github.com/user-attachments/assets/1c884b2c-d267-4801-93d0-90219b957150" />

  <img width="469" alt="Screenshot 2025-03-05 at 12 23 56 PM" src="https://github.com/user-attachments/assets/1b9bad18-2b07-4eeb-8893-c08b51d125cc" />

  <img width="408" alt="Screenshot 2025-03-05 at 12 24 11 PM" src="https://github.com/user-attachments/assets/62e35132-2b0d-44ee-9fe1-06436bfae5c2" />
  

###  Configure Help Topics and Ticket Filters
- Go to **Manage** → **Help Topics**.
- Create categories such as **IT Support, HR Requests, Software Issues**.
- Set up **Ticket Filters** to route tickets accordingly.

 <img width="683" alt="Screenshot 2025-03-05 at 12 35 28 PM" src="https://github.com/user-attachments/assets/31fd0f4f-23f3-4772-bbfd-300f0e609df9" />

 <img width="689" alt="Screenshot 2025-03-05 at 12 33 23 PM" src="https://github.com/user-attachments/assets/4d17db84-ac1f-46ef-84ab-478afdd31265" />


### 5️⃣ Secure osTicket with Best Practices
- Rename `scp` directory for added security.
- Configure **file permissions** to restrict access.
- Regularly update **osTicket and server dependencies**.
