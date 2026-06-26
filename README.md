# post-install-config
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

-Configure Roles (for grouping permissions) Admin Panel -> Agents -> Roles
-Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking) Admin Panel -> Agents -> Departments
- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
- Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
-Configure Agents (workers)
Admin Panel -> Agents -> Add New
Configure Users (customers)
Agent Panel -> Users -> Add New
Configure SLA
Admin Panel -> Manage -> SLA


<h2>Configuration Steps</h2>

<p>
<img <img width="1185" height="1296" alt="image" src="https://github.com/user-attachments/assets/3c81f845-054a-4015-8940-b626432033fe" />

</p>
<p>
Creating system admins to assign people to it later on.
</p>
<br />

<p>
<img <img width="868" height="943" alt="image" src="https://github.com/user-attachments/assets/babf8190-0df7-4d01-bf95-3d812f671d9e" />
/>
</p>
<p>
Allowing anyone to create tickets withiut being registered.
</p>
<br />

<p>
<img <img width="879" height="910" alt="image" src="https://github.com/user-attachments/assets/74f6c2ca-008b-48f5-b5b7-879e349e776c" />
/>
</p>
<p>
Created SLA's of different severaties all active.
</p>
<br />
