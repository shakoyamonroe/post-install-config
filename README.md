<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation]
- https://youtu.be/mbckqBHjLxM?si=yv3RB5N2AQtB8iUI
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

### 2️⃣ Enable Email Fetching & SMTP
- Go to **Emails** → **Email Settings**.
- Enable **IMAP/POP Fetching**.
- Configure **SMTP Authentication** for sending emails.

### 3️⃣ Set Up User Roles and Permissions
- Navigate to **Agents** → **Roles**.
- Create roles such as **Support Agent, Manager, and Administrator**.
- Assign **permissions** based on responsibilities.

### 4️⃣ Configure Help Topics and Ticket Filters
- Go to **Manage** → **Help Topics**.
- Create categories such as **IT Support, HR Requests, Software Issues**.
- Set up **Ticket Filters** to route tickets accordingly.

### 5️⃣ Secure osTicket with Best Practices
- Rename `scp` directory for added security.
- Configure **file permissions** to restrict access.
- Regularly update **osTicket and server dependencies**.
