<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configured Roles (Admin Panel -> Agents -> Roles -> Supreme Admin)  
- Configured Departments (Admin Panel -> Agents -> Departments -> SysAdmins)
- Configured Agents (Admin Panel -> Agents -> Add New -> Jane, John) 
- Configured SLA (Admin Panel -> Manage -> SLA -> Sev-A, Sev-B, Sev-C) 
- Configured Help Topics (Admin Panel -> Manage -> Help Topics -> Business Critical Outage, etc.) 



<h2>Configuration Steps</h2>

<p>
<img width="465" height="707" alt="image" src="https://github.com/user-attachments/assets/06d048eb-7474-4a04-ab66-7ccbb1f68082" />
</p>
<p>

Creating the "Supreme Admin" role is critical because it defines the highest level of permissions for agents, allowing full control over the osTicket system, including configuration, ticket management, and user oversight. Roles determine what actions agents can perform, making this a cornerstone of access control.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting up departments like "SysAdmins" is essential for organizing agents into groups based on their expertise or responsibilities. Departments control ticket visibility and assignment, ensuring tickets are routed to the right team (e.g., SysAdmins vs. Networking), streamlining workflow.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating help topics like "Business Critical Outage" or "Password Reset" is key because they guide users when submitting tickets, categorizing issues for efficient routing and reporting. This improves ticket organization and helps agents address issues systematically.
</p>
<br />
